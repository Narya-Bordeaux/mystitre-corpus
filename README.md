# Corpus Mystitre

Textes libres de droits des œuvres du jeu [Mystitre](https://github.com/Narya-Bordeaux/mystitre),
téléchargés sur Wikisource et nettoyés. Ils servent de source unique aux citations
du jeu (extraits d'ouverture et de clôture) : aucune citation n'est écrite de mémoire.

Ce dépôt ne contient que des données. Le moteur qui les produit est dans le dépôt
`mystitre` (`scripts/corpus_cli.py`, spécification `docs/corpus_extraction.md`).

## Organisation

| Fichier | Contenu |
|---|---|
| `sources/<id>.json` | Fiche de source : pages Wikisource et révisions figées, empreinte du texte nettoyé, bornes du corps du texte, origine du texte |
| `texts/<id>.json` | Texte nettoyé complet, paragraphes numérotés (`p00001`…) — **référence** |
| `texts/<id>.md` | Même texte, lisible dans GitHub, régénéré depuis le JSON |

`<id>` est l'identifiant de l'œuvre dans le catalogue du jeu (`assets/data/books.json`).

## Origine du texte (`textOrigin`)

| `kind` | Sens |
|---|---|
| `frenchOriginal` | Texte original français, libre de droits |
| `publicDomainTranslation` | Traduction française libre de droits (traducteur mort depuis plus de 70 ans), avec traducteur, année et année de décès |
| `foreignOriginal` | Original dans une autre langue : les citations en sont traduites |

## Garanties

- Chaque page est lue à une **révision figée** : un nouveau téléchargement redonne le même texte.
- L'**empreinte** (`cleanTextSha256`) le vérifie : `fetch` échoue si le texte nettoyé diffère.
- Chaque **borne** du corps du texte mémorise le début de son paragraphe : si un nettoyage
  ultérieur décale les numéros, `check` le signale et `relocate-bounds` les retrouve.

## Utilisation

Depuis le dépôt `mystitre`, avec ce dépôt cloné à côté (`../mystitre-corpus`) :

```bash
python scripts/corpus_cli.py status
```

```bash
python scripts/corpus_cli.py check
```
