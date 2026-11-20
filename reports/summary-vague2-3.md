# Compte rendu — résumés vague2-3

- Œuvres : `electre`, `micromegas`, `voyages-de-gulliver`, `mahabharata`, `shahnameh`, `le-neveu-de-rameau`, `jacques-le-fataliste`, `recherche-du-temps-perdu`, `freres-karamazov`, `lidiot`
- Créé le : 2026-11-19
- Données : `summaries/vague2-3.md`

## Passe 1 — rédaction

Outils : `summary lint` après chaque œuvre ; fuites contrôlées avec
`summary apply --output` (dossier temporaire) puis
`dart run tool/list_name_leaks.dart` (Dart présent).

### `electre`

- Qui parle : la fille d'Agamemnon, jamais nommée (périphrase dans `summary`).
- Doutes principaux : la proposition faite à Chrysothémis ne viserait
  qu'Égisthe ; la reconnaissance par l'anneau, non écrite ; la pièce
  s'achèverait avant la mort d'Égisthe (écrit « pousse Égisthe dans le palais
  pour l'abattre », sans affirmer sa mort).
- Termes donnés sous les graphies de Leconte de Lisle (Orestès, Klytaimnèstra,
  Aigisthos, Khrysothémis) et sous les graphies françaises.
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `micromegas`

- Qui parle : le géant de Sirius, dont le nom est le titre et qui n'a pas
  d'autre nom : périphrases (« un jeune géant », « le Sirien »).
- Doutes principaux : « banni de la cour pour huit cents ans » (chiffre et
  « cour » plutôt que planète) ; le muphti juge-t-il le livre « hérétique » ou
  seulement « suspect » ; l'ordre baleine puis navire.
- Difficulté : premier jet à 131 mots, réduit à 116 en retirant la
  comparaison des sens entre les deux géants. Je n'avais pas assez choisi
  avant d'écrire.
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `voyages-de-gulliver`

- Qui parle : le voyageur. Nommé « Lemuel » (prénom seul) dans `summary`,
  « Gulliver » étant un nom propre du titre.
- Doutes principaux : la formule de la « vermine » attribuée au roi de
  Brobdingnag (simplifiée en « les Européens ») ; le renvoi par l'assemblée
  des Houyhnhnms ; le retour auprès des chevaux, peut-être hors des pages du
  corpus (seul le chapitre 12 du dernier voyage y figure).
- Simplification : le troisième voyage réduit à Laputa et Lagado.
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `mahabharata`

- Aucun texte dans le corpus : rien ne se vérifiera. Je n'ai écrit que la
  trame la plus connue, sans épisode douteux.
- Qui parle : Arjuna (découragement entre les armées, enseignement de
  Krishna), plutôt que Yudhishthira.
- Règle 5 : « Bharata », nom propre du titre, évité ; Vyasa, nom de l'auteur
  et personnage de l'épopée, non nommé.
- Désaccord avec la fiche : ses `firstSentences` et `lastSentences` me
  semblent forgées (aucune traduction connue de moi) ; signalé en note,
  hors du champ de cette passe.
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `shahnameh`

- Qui parle : le poète, sans se nommer ; aucun personnage ne traverse
  l'épopée, et le corpus s'achève sur sa voix.
- Règle 5 : « Livre des Rois » est un titre accepté ; « rois » reste permis,
  mais j'ai évité « livre des rois » ou « histoire des rois ».
- Doutes principaux : les graphies de Mohl (Keïoumors, Zohak, Feridoun,
  Roustem…), données en variantes ; la phrase sur l'édifice de vers que ni le
  vent ni la pluie n'abattront, peut-être ailleurs que dans les pages de fin.
- Ambiguïté corrigée : « Après sa mort » (Rostam ou Esfandiyar) devenu
  « Après la mort de Rostam ».
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `le-neveu-de-rameau`

- Qui parle : le neveu (« Lui »), le plus vivant des deux interlocuteurs.
- Règle 5 : ni le neveu ni l'oncle ne sont nommés (« Rameau » est un nom
  propre du titre) ; je ne crois pas que le texte donne au neveu un autre nom
  que « Lui ». « Neveu » employé une fois, sans le nom de l'oncle.
- Œuvre sans intrigue : rencontre, grands sujets, séparation.
- Doutes principaux : l'ordre des sujets ; le motif exact de l'expulsion de
  chez Bertin.
- Désaccord avec la fiche : le lieu de la conversation serait le café de la
  Régence, non un « jardin public ».
- Premier jet à 122 mots, réduit à 118.
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `jacques-le-fataliste`

- Qui parle : le valet. « Jacques » étant un nom propre du titre et le valet
  n'ayant pas d'autre nom : périphrases ; « fataliste » aussi évité.
  L'ancien `summary` nommait Jacques (fuite).
- Doutes principaux : Fontenoy, le nom de l'auberge (Grand-Cerf), les
  circonstances de l'arrestation du valet, l'ordre de la fin (duel, fins
  proposées par l'éditeur).
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `recherche-du-temps-perdu`

- Qui parle : le narrateur, sans prénom (celui qu'il reçoit dans les volumes
  tardifs est aussi celui de l'auteur).
- Règle 5 : « temps » employé, « temps perdu » et « temps retrouvé » évités.
- Choix : sept volumes en 115 mots, réduits au fil narrateur, Swann et
  Odette, Gilberte, Balbec, Guermantes et Charlus, Albertine, la révélation
  finale.
- Doutes principaux : thé ou tilleul pour la madeleine ; matinée chez la
  princesse plutôt que la duchesse de Guermantes ; la mort d'Albertine (hors
  zone).
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `freres-karamazov`

- Qui parle : Aliocha, que le narrateur présente comme son personnage
  principal et qui seul peut dire la scène finale de la pierre.
- Règle 5 : « Karamazov » évité ; prénoms et patronyme seulement. L'ancien
  `summary` le nommait (fuite).
- Doutes principaux : la forme exacte de « tout est permis » ; la nature de
  l'argent disputé (héritage de la mère de Dmitri) ; la peine de Dmitri,
  écrite « bagne » sans durée.
- Ambiguïté corrigée : « inspiré par sa maxime » devenu « par la maxime
  d'Ivan ».
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### `lidiot`

- Qui parle : le prince ; « Mychkine » est un nom sans rapport avec le titre,
  employé dans `summary`.
- Règle 5 : « idiot » évité partout, même pour la rechute finale : seul, il
  reconstituerait le titre entier.
- Doutes principaux : graphies de Derély (« Muichkine », « Nastasie ») ;
  « renonce à Aglaé », simplification de la confrontation des deux femmes ;
  le retour en Suisse chez Schneider, relevé comme fait mais non écrit.
- `summary` à 120 mots, limite haute atteinte.
- Lint : zéro erreur, zéro avertissement ; aucune fuite.

### Difficultés au fil du lot

- Je n'ai pas senti de baisse de soin vers la fin : les deux Dostoïevski,
  derniers du lot, ont reçu autant de notes et de faits que les premières
  œuvres (8 faits chacun), et deux ambiguïtés ont été corrigées sur le moment
  (`shahnameh`, `freres-karamazov`). La difficulté était plutôt dans la
  matière : les œuvres-fleuves (`mahabharata`, `shahnameh`,
  `recherche-du-temps-perdu`) demandent de beaucoup taire, et le choix de ce
  qu'on tait y pèse plus que la rédaction.
- Longueur : deux premiers jets trop longs (`micromegas` 131 mots,
  `le-neveu-de-rameau` 122), corrigés par retrait d'un épisode ou de
  quelques mots ; `lidiot` tient juste à 120. La consigne de choisir avant
  d'écrire est juste ; je ne l'ai pas toujours assez appliquée au premier jet.
- Une dizaine d'œuvres reste une taille confortable pour ce lot.

### Retours sur la consigne

- `mahabharata` n'a aucun texte au corpus : les faits relevés ne pourront
  être ni confirmés ni contredits à la passe 2. J'en ai relevé 8 quand même
  (la consigne exige 3 au moins) ; il faudrait dire ce que la passe 2 en fait
  (« hors zone » pour tous, sans doute). Sa fiche a aussi des
  `firstSentences` et `lastSentences` qui me paraissent forgées.
- Mot courant du titre qui, seul, est le titre entier (« idiot » pour
  *L'Idiot*) : la règle le permet en principe mais interdit de reconstituer
  le titre ; j'ai jugé qu'« idiot » seul le reconstitue et l'ai évité. Cas à
  préciser dans la consigne, comme *Micromégas* où le héros n'a que le nom du
  titre (périphrase, conformément à la règle).
- Titre accepté composé de mots courants (« Livre des Rois ») : j'ai gardé
  « rois » mais évité l'expression entière, conformément à la règle.
- Nom de l'auteur porté par un personnage (Vyasa dans le *Mahabharata*) : la
  consigne prévoit le lieu qui porte le nom de l'auteur, pas le personnage ;
  j'ai appliqué la même prudence.
- Prénom de l'auteur donné au narrateur (*À la recherche du temps perdu*) :
  évité, par la même règle.
- Deux anciens `summary` nommaient un nom propre du titre (Jacques,
  Karamazov) ; ils disparaîtront avec l'intégration.

## Passe 2 — vérification

### Bilan

| Œuvre | Faits | Confirmés | Hors zone | Corrigés | Texte au corpus |
|---|---|---|---|---|---|
| `electre` | 7 | 7 | 0 | 0 | une page (texte entier) |
| `micromegas` | 9 | 8 | 0 | 1 | 7 chapitres choisis |
| `voyages-de-gulliver` | 9 | 3 | 6 | 0 | 3 chapitres choisis (ch. 1-2 de Lilliput, ch. 12 du dernier voyage) |
| `mahabharata` | 8 | 0 | 8 | 0 | aucun |
| `shahnameh` | 7 | 1 | 6 | 0 | 2 pages (invocation, dédicace) |
| `le-neveu-de-rameau` | 8 | 7 | 0 | 1 | une page (texte entier) |
| `jacques-le-fataliste` | 8 | 8 | 0 | 0 | une page (texte entier) |
| `recherche-du-temps-perdu` | 7 | 6 | 1 | 0 | 2 pages (Combray seulement ; Le Temps retrouvé III) |
| `freres-karamazov` | 8 | 1 | 6 | 1 | 2 pages (livre I ch. I ; épilogue III) |
| `lidiot` | 8 | 4 | 4 | 0 | 2 pages (I ch. 1 ; IV ch. 12) |
| **Total** | **79** | **45** | **31** | **3** | |

Les « Vérification » des Notes couvrent chaque doute de la passe 1. Aucun doute n'est resté sans issue.

### Corrections

1. `micromegas`, paragraphe p00018 : « Arrivés sur la Terre, ils la croient d'abord inhabitée » devient « Arrivés sur la Terre, le Saturnien la croit d'abord inhabitée ». Le texte dit que le nain conclut à une Terre sans habitants, et que le Sirien le contredit.
2. `le-neveu-de-rameau`, paragraphe p00004 : « Un soir, au café de la Régence » devient « Un après-midi, au café de la Régence ». Le texte dit « Une après-dînée j'étais là » ; « souper ce soir » (p00487) est un projet.
3. `freres-karamazov`, paragraphe p00056 : « Dmitri est pourtant condamné au bagne » devient « Dmitri est pourtant condamné à l'exil ». Aliocha dit « один пойдет в ссылку » (l'un des deux frères ira en exil). Le mot « bagne » n'apparaît pas dans les pages.

### Points à trancher

- `le-neveu-de-rameau` : la scène de chasse à table (p00661-p00671) ne nomme pas la maison. Le lien avec Bertin (« le fou de Bertin », p00655) est fort, mais inféré. Le fait est marqué « confirmé » avec cette réserve dans l'appui.
- `micromegas` : « ils croient que l'univers a été fait pour eux » généralise une thèse portée par un seul docteur (p00040). Non contredit, laissé tel quel.
- `freres-karamazov` : la correction « exil » suit le texte des pages enregistrées. Si la relecture préfère « bagne » (peine de katorga, de mémoire), elle sort de ce que le corpus permet de vérifier.
- `lidiot` : « la plus jeune fille » (Aglaé) n'est pas écrit ; le texte dit « sa sœur cadette » (p00096). Non contredit.
- `mahabharata` : les `firstSentences` et `lastSentences` de la fiche semblent forgées (rédaction). Non vérifiables sans texte. À signaler à la relecture du catalogue.
- Corpus, `shahnameh` : le compte rendu du corpus donne la source comme « declared », qui n'est pas un site Wikisource. Anomalie de données à corriger dans `mystitre-corpus`, hors de cette passe.

### Contrôles

- `summary lint vague2-3 --checked` : 0 erreur, 0 avertissement (après les corrections et les deux lignes ajoutées).
- Fuites : `summary apply vague2-3 --output` (catalogue simulé, 10 fiches, hors du dépôt) puis `dart run tool/list_name_leaks.dart --catalogue=…` : « Aucune fuite de titre ou d'auteur. » Ce contrôle a été refait après les dernières modifications.
- `summary mark vague2-3 checked` : lancé après l'écriture de ce compte rendu.

### Incidents

- Le script de mise à jour a oublié les faits de `recherche-du-temps-perdu` au premier passage. `summary lint --checked` a signalé 7 faits « encore à vérifier » ; ils ont été renseignés et le lint est repassé à 0.
- Deux faits ont été ajoutés au tableau pour tracer une correction qui n'y figurait pas : « Les géants croient la Terre inhabitée d'abord » (micromegas) et « La conversation a lieu l'après-midi, non le soir » (rameau).
- Le clone du dépôt `mystitre-corpus` s'est fait sans encombre (shallow, quelques secondes).

### Difficultés au fil du lot

- La fin du lot a été plus pénible que le début. Les derniers faits ont été relevés avec un contexte déjà chargé, et l'oubli de `recherche-du-temps-perdu` dans le script en est le signe : j'ai dû vérifier mon propre tableau plutôt que de m'y fier.
- La matière est inégale. `mahabharata` n'a aucun texte, `shahnameh` deux pages, `freres-karamazov` et `lidiot` des pages choisies : pour ces quatre œuvres, la plupart des faits restent hors zone, et c'est la consigne qui décide, pas le texte.
- Les textes russes, traduits par des graphies variées, demandent de chercher en racines. Pour `freres-karamazov`, la racine « Зосим » n'a rien donné : l'absence n'a été tenue pour un « hors zone » qu'après la recherche des variantes.

### Retours sur la consigne

- Œuvre sans aucun texte (`mahabharata`) : la consigne ne prévoit que « hors zone, absent du texte complet ». Pour un corpus vide, j'ai écrit « hors zone, appui : aucun texte au corpus ». Une catégorie dédiée serait plus claire.
- Fait attesté seulement en partie (`le-neveu-de-rameau`, `lidiot`) : la consigne n'a pas de statut pour « partiellement attesté ». J'ai choisi « confirmé » avec la réserve écrite dans l'appui, et je signale le choix.
- Mot traduit plus précisément qu'en français (`freres-karamazov`, « ссылка » contre « bagne ») : la consigne ne dit pas si c'est une contradiction. J'ai corrigé, car le texte fait foi ; la relecture peut trancher autrement.
- Un fait relevé dans la passe 1 comme doute et contredit par le texte, mais absent du tableau, n'a pas de procédure claire : j'ai ajouté une ligne au tableau pour garder la trace.

## Intégration

Décisions de la session principale (pas de relecture humaine) :

- Corrections retenues : `micromegas` (le Saturnien croit la Terre inhabitée), `le-neveu-de-rameau` (« un après-midi »).
- Correction écartée : `freres-karamazov`, « bagne » rétabli (voir les notes de l'œuvre).
- `mahabharata` : aucun texte au corpus ; résumés gardés. Ses `firstSentences` et `lastSentences` paraissent forgées : signalé dans `docs/todo.md` de `mystitre`.
- `shahnameh` : la source « declared » est une source déclarée par l'utilisateur (v1.20.15), pas une anomalie.
- `le-neveu-de-rameau` (Bertin), `micromegas`, `lidiot` : points non contredits, gardés.
