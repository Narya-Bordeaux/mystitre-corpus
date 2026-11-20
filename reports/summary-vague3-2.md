# Compte rendu — résumés vague3-2

- Œuvres : `splendeurs-et-miseres-des-courtisanes`, `le-lys-dans-la-vallee`, `orgueil-et-prejuges`, `jane-eyre`, `les-liaisons-dangereuses`, `frankenstein`, `dracula`, `le-portrait-de-dorian-gray`, `jekyll-et-hyde`, `le-proces`
- Créé le : 2026-11-20
- Données : `summaries/vague3-2.md`

## Passe 1 — rédaction

### `splendeurs-et-miseres-des-courtisanes`

- Qui parle : Lucien, dans sa cellule, juste avant son suicide (le seul moment où il peut dire tout son parcours sans sortir de son histoire).
- Doutes principaux : l'ordre exact entre la mort d'Esther et l'arrivée de l'héritage de Gobseck (formulation large gardée) ; le destinataire de la dernière lettre de Lucien ; le titre exact « chef de la police de sûreté ».
- Simplifications : Corentin, Peyrade, Lydie, Asie, Europe, Calvi, le couvent d'Esther et le juge Camusot sont tus pour tenir 115 mots. L'œuvre est foisonnante (quatre parties) : c'est la plus difficile à faire tenir en six phrases.


### `le-lys-dans-la-vallee`

- Qui parle : Félix, qui a lu la dernière lettre d'Henriette (sa situation au moment où il écrit à Natalie).
- Doutes principaux : le prénom (Henriette, nom d'élection, et Blanche, prénom de baptême, à ma mémoire) ; la cause exacte du dépérissement d'Henriette ; le bal de Tours. Le corpus contient le texte entier : tout est vérifiable.
- Choix : « lys » permis mais non employé ; Madeleine et la lettre-conseil retirées.

### `orgueil-et-prejuges`

- Qui parle : Elizabeth, jusqu'à ses fiançailles.
- Doutes principaux : peu ; le rang d'Elizabeth (deuxième) et le mot « tolerable » tombent sans doute hors des deux chapitres du corpus ; « arrangeant leur mariage » reste large sur le rôle financier de Darcy.
- Simplifications : Pemberley, Lady Catherine, Charlotte Lucas et la demande de Collins sont tus. Termes en anglais (corpus en anglais).

### `jane-eyre`

- Qui parle : l'héroïne, narratrice de sa vie, sans son adresse au lecteur (interdite).
- Choix : titre = nom de l'héroïne, donc ni prénom ni nom ; « une petite orpheline », « la jeune femme ». L'héritage de l'oncle est tu dans `summary` (son nom ferait fuir le titre) et suggéré par « libre et riche ».
- Doutes : « sous les combles » (étage exact où Bertha est enfermée) ; la cause de la mort d'Helen ; les circonstances exactes de la cécité de Rochester.

### `les-liaisons-dangereuses`

- Qui parle : Valmont, mourant, quand il confie les lettres à Danceny.
- Doutes : ordre entre la chute de Cécile et celle de Tourvel ; « retourne au couvent » (postulante ?) ; qui informe Danceny. Le dénouement est dans la lettre 175, dans le corpus.
- Correction de premier jet (règle 6) : « Elle m'a refusé la récompense » pouvait désigner Tourvel ou Merteuil, et « la quitte » pouvait désigner Cécile ; reformulés.

### `frankenstein`

- Qui parle : Victor, mourant sur le navire de Walton (la créature ignore sa mort jusqu'à la toute fin).
- Doutes : graphie des prénoms dans la traduction Saladin de 1821 (variantes données) ; « étrangle » pour Clerval et Élisabeth ; « fragments de cadavres ».
- Choix : le nom de famille de Victor (le titre) n'apparaît jamais ; la famille De Lacey est tue, alors qu'elle occupe tout le récit de la créature (118 mots, au bord de la fourchette).

### `dracula`

- Qui parle : Jonathan (auteur de la note finale), avec « nous » pour le groupe.
- Choix : titre = nom du comte, jamais écrit ; Renfield, Whitby, les trois femmes retirés.
- Doutes : « clerc de notaire » pour « solicitor » (il vient peut-être d'être reçu solicitor) ; le moment exact de la destruction (juste avant le coucher du soleil, à ma mémoire). Termes en anglais.

### `le-portrait-de-dorian-gray`

- Qui parle : le jeune homme, le dernier soir, au moment de prendre le couteau.
- Choix : prénom et nom du titre jamais écrits (« un jeune homme », « son modèle ») ; « portrait » employé une fois, permis.
- Doutes : la durée (dix-huit ans, à ma mémoire : écrit « des années ») ; le même couteau pour Basil et pour la toile ; la graphie Sibyl/Sibylle dans la traduction Jaloux.
- Premier jet à 124 mots, réduit à 119 : j'ai mal choisi ce que je taisais avant d'écrire ; c'est le seul dépassement du lot.

### `jekyll-et-hyde`

- Qui parle : le médecin, au moment où il achève sa confession (dernier chapitre, dans le corpus).
- Choix difficile : le titre contient les deux noms de famille. J'emploie les prénoms, Henry et Edward, comme la règle le permet ; mais le texte n'appelle presque jamais l'autre « Edward », si bien que la désignation paraît artificielle. À trancher à l'intégration (une périphrase seule, « son protégé », « l'inconnu », est l'alternative).
- Utterson est « l'avocat » dans la traduction du corpus ; l'ancien résumé disait « notaire » (désaccord avec la fiche, noté).
- Doutes : la fillette piétinée, l'empoisonnement d'Edward, le mot « cabinet ».

### `le-proces`

- Qui parle : K., en suivant les deux messieurs vers la carrière ; il ne dit pas sa mort.
- Doutes : l'âge à l'arrestation (trente ans, à ma mémoire ; la veille des trente et un ans à la fin, plus sûr) ; ce que Titorelli dit exactement des acquittements. Termes en allemand.
- Premier jet à 122 mots, réduit à 118.
- L'ancien résumé écrit « Joseph » ; j'écris « Josef », graphie allemande et de la fiche.

### Contrôles

- `summary lint vague3-2` : 0 erreur, 0 avertissement sur les dix œuvres.
- Fuites (`summary apply` vers un fichier temporaire, puis `dart run tool/list_name_leaks.dart`) : aucune fuite de titre ou d'auteur. Contrôle lancé après la 2e, la 4e, la 8e et la 10e œuvre. Dart est présent.

### Difficultés au fil du lot

- Je n'ai pas senti la fin du lot plus difficile en elle-même. Les deux dépassements de la fourchette (Dorian Gray, Procès, 124 et 122 mots) tombent pourtant en fin de lot : signe possible d'une attention moins tenue au choix préalable de ce que je tais. Je les ai corrigés en retirant des mots, non des faits. J'ai essayé de garder les notes aussi détaillées pour les dernières œuvres que pour les premières.
- Les œuvres les plus difficiles n'étaient pas les dernières mais celles dont le titre est le nom des personnages (Jane Eyre, Dracula, Dorian Gray, Jekyll et Hyde, Frankenstein) : cinq dans ce lot, ce qui oblige à des périphrases constantes dans `summary`. *Splendeurs et misères* est la plus dure à faire tenir en six phrases (quatre parties, nombreux personnages).
- Lot bien dimensionné pour moi à dix œuvres ; ces romans très connus se rédigent avec assurance, les doutes portent surtout sur les graphies des traductions anciennes (Saladin, Jaloux) et les détails de dénouement.

### Retours sur la consigne

- Titre composé de deux noms (*Jekyll et Hyde*) : la règle « prénom permis » fonctionne, mais donne un prénom que le texte n'emploie presque pas (« Edward »). La consigne pourrait dire si l'on préfère alors un prénom peu usité ou une périphrase.
- Faits : la consigne veut des faits tirés des deux textes ; j'ai d'abord relevé pour *Splendeurs* un surnom (« la Torpille ») absent de mes textes, puis je l'ai remplacé. Un rappel au moment du tableau aiderait.
- Les noms d'une autre œuvre identiques à un mot du titre d'ici (« Jane » Bennet dans *Orgueil et Préjugés*, alors que *Jane Eyre* est dans le même lot) : la règle « titres des autres œuvres libres » s'applique, et l'outil de fuites ne signale rien ; je l'ai gardé.

## Passe 2 — vérification

### Bilan (faits par œuvre)

| Œuvre | Corpus enregistré | Faits | Confirmés | Hors zone | Corrigés |
|---|---|---|---|---|---|
| `splendeurs-et-miseres-des-courtisanes` | Première et Quatrième parties (Deuxième et Troisième absentes) | 12 | 10 | 2 | 0 |
| `le-lys-dans-la-vallee` | texte entier | 9 | 9 | 0 | 0 |
| `orgueil-et-prejuges` | chapitre 1 et dernier chapitre | 8 | 4 | 4 | 0 |
| `jane-eyre` | chapitre 1 et dernier chapitre | 13 | 6 | 7 | 0 |
| `les-liaisons-dangereuses` | lettre 1 et lettre 175 | 8 | 4 | 4 | 0 |
| `frankenstein` | lettres de Walton et fin du récit de Victor | 9 | 5 | 4 | 0 |
| `dracula` | chapitre 1 et chapitre 27 | 8 | 5 | 3 | 0 |
| `le-portrait-de-dorian-gray` | chapitre 1 et chapitre 20 | 8 | 6 | 2 | 0 |
| `jekyll-et-hyde` | chapitre I et chapitre X | 9 | 6 | 3 | 0 |
| `le-proces` | chapitre 1 et chapitre 10 | 9 | 6 | 3 | 0 |
| **Total** | | **93** | **61** | **32** | **0** |

Les faits « hors zone » se répartissent entre des noms propres absents des pages enregistrées (Huld, Titorelli, Bertha, Justine, Ingolstadt, Westenra…), des scènes absentes (le duel de Valmont, la révélation de l’église, la découverte du corps de Hyde…) et des précisions sur lesquelles le texte se tait. Aucun fait n’est contredit : aucune correction de texte n’est donc faite.

Les scindages (un fait qui affirmait deux choses) ont porté le nombre de lignes de 8 à 13 pour *Jane Eyre* et de 8 à 12 pour *Splendeurs* ; les tableaux des autres œuvres ont aussi reçu une ligne scindée. Le résumé n'a pas changé : seul le tableau de faits est plus fin.

### Corrections

Aucune. Aucun fait du tableau ni aucun doute des notes n’est contredit par le texte du corpus : les fragments non attestés restent « hors zone » et le texte est conservé.

### Points à trancher

1. *Splendeurs* : le titre « chef de la police de sûreté » pour Collin est hors zone. Le texte atteste la négociation avec la justice et une place dans la police (p01934 ; « ses fonctions pendant environ quinze ans », p02018). Les parties 2 et 3 ne sont pas au corpus : la décision doit venir de la relecture, avec ou sans le titre.
2. *Splendeurs* : l’ignorance d’Esther face à son héritage (« sans savoir ») est hors zone. Le texte atteste la fortune (près de deux millions, p01549) et son empoisonnement (p01908).
3. *Dracula* : la visite de Jonathan pour vendre une demeure à Londres est hors zone. Carfax est attestée comme maison du comte (p00055), pas comme bien mis en vente.
4. *Frankenstein* : le texte dit « assassiné » pour la victime qui est « aimable et sans appui » (p00067), et « étranglé » pour l’innocent endormi (p00067). Le résumé écrit « étrangle son ami Clerval » : l’étranglement de Clerval n’est pas attesté. Texte conservé ; à trancher (« tue » serait exact).
5. *Jane Eyre* : la parenté « sa tante » (Mrs Reed) n’est pas dite dans les pages (hors zone). Le texte garde « sa tante ». Le nom « Thornfield » est absent des pages.
6. *Le Procès* : Huld (avocat), Titorelli (peintre) et « fondé de pouvoir » sont absents des pages. Le résumé reste « un avocat », « un peintre », sans nom : rien à corriger, mais la relecture peut vouloir les noms.
7. *Jekyll et Hyde* : le prénom « Edward » est attesté (p00040 et suivants), mais le texte emploie surtout le nom de famille. Le choix du prénom reste celui de la rédaction (règle du titre), à juger à la relecture.

### Contrôles

- `summary lint vague3-2 --checked` : 0 erreur, 0 avertissement (dix œuvres).
- `summary lint vague3-2` (sans `--checked`, étape « rédigée ») : 6 erreurs, toutes « plus de 8 faits ». C’est la conséquence attendue des scindages de la passe 2, qui sont permis en vérification. Voir « Retours sur la consigne ».
- Fuites (titre et auteur) : `summary apply vague3-2 --output <scratchpad>/vague3-2-catalogue.json` (10 fiches simulées), puis `dart run tool/list_name_leaks.dart --catalogue=<scratchpad>/vague3-2-catalogue.json` : « Aucune fuite de titre ou d'auteur ». Code de sortie 0. Dart est présent (`/opt/flutter/bin/dart`) ; la commande a affiché un avertissement Flutter sur l’exécution en root, sans effet sur le résultat.
- `summary mark vague3-2 checked` : lancé après la rédaction de ce compte rendu (voir la réponse finale pour le code de sortie).

### Incidents

- Deux faux positifs de recherche par sous-chaîne, corrigés avant d’écrire les statuts : « Huld » correspondait à « Schuld » (dans *Le Procès*), « aunt » à « haunt » (dans *Jane Eyre*). Le statut « hors zone » de Huld et la mention d’une tante non attestée s’appuient sur la recherche corrigée (mot entier).
- Dans *Dracula*, un identifiant de paragraphe déduit du numéro de ligne était décalé (le coup de couteau de Morris est en p00099, non en p00102). Les appuis ont été repris avec un script de localisation par paragraphe.
- `summary corpus` n’existe pas : la commande du corpus est `corpus_cli.py show`. Sans conséquence sur les données.
- Les textes du corpus ont été copiés hors dépôt, dans le dossier temporaire de la session, pour être parcourus par `grep`. Rien n’a été modifié dans `mystitre`.

### Difficultés au fil du lot

- Je n’ai pas constaté de baisse d’attention vers la fin du lot. Le dernier point difficile a été la vérification de *Jekyll et Hyde* et de *Le Procès*, où j’ai dû distinguer ce que le texte dit de ce que la rédaction croyait savoir (par exemple « Edward empoisonné », absent). Le faux positif « Schuld » a été relevé à ce moment-là, et la recherche a été reprise en mot entier.
- Les œuvres dont le corpus ne garde que des chapitres d’ouverture et de fin (*Jane Eyre*, *Orgueil*, *Dracula*, *Jekyll*, *Le Procès*) ont exigé plus de recherches par terme que le texte entier du *Lys*. Plus de la moitié des faits « hors zone » vient de ces œuvres.
- La difficulté principale du lot tient au corpus, non à la fatigue : 32 faits hors zone sur 93 signifient qu’une partie de la vérification ne peut pas aboutir avant l’intégration.

### Retours sur la consigne

- Le scindage est nécessaire pour un fait qui affirme deux choses : *Splendeurs* (fortune / héritage ignoré), *Orgueil* (Wickham / grade), *Jane Eyre* (Rivers / cousins). La règle fonctionne sans ambiguïté.
- La limite de 8 faits à la rédaction est contrôlée par `lint` à l’étape « rédigée », alors que la passe 2 peut la dépasser en scindant. Ce conflit produit 6 erreurs sur `lint` sans `--checked`, après la passe 2. Proposition : limiter le contrôle de la limite à la rédaction, ou l’exempter une fois l’étape « vérifiée » atteinte.
- « Hors zone » recouvre deux cas très différents : un terme absent d’un chapitre enregistré, et une affirmation qu’aucune partie du corpus ne peut trancher. La consigne gagnerait à distinguer « absent des pages enregistrées » (œuvre partielle) et « absent du texte complet — à trancher » (œuvre entière), pour que l’intégration sache ce qui reste ouvert.
- Les doubts des « Notes » sont à traiter comme des faits ; j’ai ajouté une ligne « Vérification : … » par doute, avec le paragraphe, conformément à la règle 6.
