# Compte rendu — résumés vague1-2

- Œuvres : `notre-dame-de-paris`, `le-dernier-jour-dun-condamne`, `lhomme-qui-rit`, `les-travailleurs-de-la-mer`, `quatrevingt-treize`, `ruy-blas`, `hernani`, `lucrece-borgia`, `han-dislande`, `bug-jargal`, `rene-chateaubriand`
- Créé le : 2026-11-19
- Données : `summaries/vague1-2.md`

## Passe 1 — rédaction

Rédaction de mémoire, une œuvre après l'autre, dans l'ordre donné. Contrôle des
fuites par `summary apply --output` (fichier dans le dossier temporaire de la
session) puis `dart run tool/list_name_leaks.dart` après chaque œuvre : Dart est
disponible.

### Par œuvre

#### `notre-dame-de-paris`

- Qui parle : Quasimodo (l'ancien texte faisait parler Esmeralda). Il traverse
  tout le dénouement, jusqu'au charnier, ce qui permet de raconter la fin à la
  première personne.
- Titre : « Notre-Dame » et « Paris » sont deux noms propres du titre, évités
  tous les deux (« la cathédrale », pas de ville nommée).
- Doutes principaux : le lieu de la danse du 6 janvier (place de Grève, non
  écrit) ; le détail de la mort de Frollo (gouttière, balustrade), réduit à
  « du haut des tours ».
- Simplifications : la recluse (mère d'Esmeralda), Gringoire et l'assaut des
  truands sont omis.
- 7 faits, 116 mots : premier jet à 119 mots, réduit en retirant un complément
  de lieu inutile ; la date d'ouverture n'est pas relevée car elle est déjà dans
  la première phrase de la fiche.
- Lint : 0 erreur, 0 avertissement. Dart : aucune fuite.

#### `le-dernier-jour-dun-condamne`

- Qui parle : le condamné, dans la voix de son journal.
- Titre : mots courants (« dernier », « jour », « condamné ») ; « condamné à
  mort » gardé une fois dans le `summary`, la suite « dernier jour » évitée ;
  dans `personalSummary`, « la loi va me couper la tête » plutôt que « je suis
  condamné à mort », qui reprend la première phrase de l'œuvre.
- Doutes principaux : l'ordre des étapes du jour de l'exécution (rejet du
  pourvoi, transfert à la Conciergerie, visite de Marie, Hôtel de Ville) ; le
  mot « friauche », de mémoire. Le lieu de la visite de Marie n'est pas écrit.
- Simplifications : la préface, la chanson d'argot, la mère, la femme et le
  prêtre omis.
- 7 faits, 116 mots. Lint : 0 erreur, 0 avertissement. Dart : aucune fuite.

#### `lhomme-qui-rit`

- Qui parle : Gwynplaine.
- Titre : « rire » employé (il est le cœur de l'histoire, mot courant), jamais
  la formule « l'homme qui rit », surnom de scène du personnage.
- Doutes principaux : Portland et Weymouth (non écrits, « une côte anglaise ») ;
  la confession dans une gourde plutôt qu'une bouteille ; le nom du navire de
  l'exil (*Vograat*) ; Dea mourant dans les bras de Gwynplaine.
- Simplifications : Josiane, lord David, Barkilphedro, Hardquanonne, la prison
  de Southwark omis — l'intrigue de cour est réduite à la révélation et au
  discours.
- Premier jet à 125 mots (erreur du lint) : réduit à 119 en resserrant trois
  compléments. 6 faits. Lint : 0 erreur. Dart : aucune fuite.

#### `les-travailleurs-de-la-mer`

- Qui parle : Gilliatt.
- Doutes principaux : le plan de Clubin (les Hanois visés, les Douvres
  atteintes par erreur ; l'argent de Rantaine) ; qui écrit le nom dans la neige
  à Noël ; le lien de parenté entre Déruchette et Lethierry (« nièce », absent
  de la fiche).
- Simplifications : la mort de Clubin dans la grotte, l'argent rendu, le Bû de
  la Rue, le nom du rocher final et du navire omis.
- 7 faits, 105 mots. Lint : 0 erreur, 0 avertissement. Dart : aucune fuite.

#### `quatrevingt-treize`

- Qui parle : Gauvain, qui s'arrête avant son exécution.
- Titre : le titre est un nombre (titre accepté « 93 »). J'ai évité « 1793 »,
  qui le contient et le désignerait à coup sûr ; la période est dite par « sous
  la Terreur ». **Point à trancher** : l'ancien `summary` commençait par « En
  1793 », et un essai sur un catalogue simulé (« En 1793 » ajouté) montre que
  `list_name_leaks.dart` ne le relève pas. La règle des mots isolés ne prévoit
  pas le cas d'un titre numérique contenu dans une date.
- Doutes principaux : « petit-neveu » (ou grand-neveu ?) ; le lieu de la
  fusillade de la mère (Herbe-en-Pail, non écrit) ; le nom de la corvette
  (*Claymore*, non écrit) ; la manière dont Lantenac s'échappe.
- Simplifications : la caronade, la scène Robespierre-Danton-Marat, Radoub, les
  noms des enfants omis.
- 7 faits, 115 mots. Lint : 0 erreur, 0 avertissement. Dart : aucune fuite.

#### `ruy-blas`

- Qui parle : le valet, sans se nommer ; dans le `summary`, « son propre
  laquais », « le faux don César », « le valet ».
- **Désaccord avec la fiche** : `importantPassages` dit que le héros
  « empoisonne » Salluste avant de boire lui-même le poison. Ma mémoire : il le
  tue (à l'épée), et lui seul boit le poison. Écrit « tue son maître », sans
  arme ; relevé en fait. Si la passe 2 confirme, la fiche est à corriger à
  l'intégration.
- Doutes principaux : la date (fin du XVIIe siècle, non chiffrée) ; le sort de
  don César (corsaires, Afrique) ; le titre de duc d'Olmedo (non écrit).
- Simplifications : le quatrième acte (retour de don César par la cheminée,
  duel de Guritan) omis.
- 7 faits, 116 mots. Lint : 0 erreur, 1 avertissement gardé (« j'aime » : amour
  du personnage pour la reine). Dart : aucune fuite.

#### `hernani`

- Qui parle : le proscrit, sans se nommer (son nom de bandit est le titre).
- Choix : son vrai nom, Jean d'Aragon, est écrit à sa place (révélation du
  quatrième acte) : il n'est pas proche du titre. « Honneur castillan » (titre
  accepté) non employé.
- Doutes principaux : le grief (le père du roi a fait mourir son père) ; 1519
  et Saragosse ; le détail du pacte du cor (alliance contre le roi, non écrite) ;
  Aix-la-Chapelle (non écrit).
- Premier jet à 121 mots (erreur du lint), réduit à 118 ; « j'aime » remplacé
  par « mon cœur est à » pour lever l'avertissement plutôt que le justifier.
- 7 faits. Lint : 0 erreur, 0 avertissement. Dart : aucune fuite.

#### `lucrece-borgia`

- Qui parle : la duchesse, sans se nommer (son nom est le titre) ; Gennaro
  ignore tout jusqu'à la dernière réplique, sa voix aurait manqué le cœur du
  drame.
- Titre : « Lucrèce », « Borgia », « Lucrezia » évités ; l'épisode « Borgia »
  devenu « Orgia » est dit sans le nom (« mutile le nom de la duchesse […] pour
  en faire une injure »).
- Doutes principaux : le palais Barbarigo ; la scène du poison au deuxième acte
  (qui verse, choix imposé par le duc) ; le souper chez la princesse Negroni ;
  la mort de Gennaro, non montrée je crois, donc non écrite.
- Premier jet à 128 mots (erreur du lint) : deux reprises pour descendre à 119.
  C'est l'œuvre où la compression a le plus coûté (épisode du nom, double
  poison, banquet).
- 7 faits. Lint : 0 erreur, 0 avertissement. Dart : aucune fuite.

#### `han-dislande`

- Qui parle : Ordener.
- Titre : « Han » et « Islande » évités ; « un brigand légendaire ».
- **Œuvre la moins sûre du lot** : mes souvenirs du milieu de l'intrigue sont
  flous. Formulations volontairement larges sur ce qui sauve Ordener (« les
  intrigues sont dévoilées »), sur la cassette (il part la reprendre, sans dire
  qu'il l'obtient) et sur l'incendie (sans lieu).
- Doutes principaux : titre de Schumacker (grand chancelier ?) ; le rôle
  d'Ordener au procès ; la mort de Musdœmon (pendu par son frère le bourreau ?,
  non écrit) ; le brigand s'est-il livré lui-même ?
- Fin tirée en partie de la dernière phrase de la fiche (Schumacker meurt en
  1699) : c'est un appui sur la fiche, pas sur ma mémoire.
- 7 faits, 115 mots. Lint : 0 erreur, 0 avertissement. Dart : aucune fuite.

#### `bug-jargal`

- Qui parle : Léopold d'Auverney, le soir au camp, puis au passé — la situation
  même de l'œuvre (un récit fait à des officiers).
- Titre : « Bug » et « Jargal » évités ; « Pierrot », son nom d'esclave, est
  employé (il n'est pas proche du titre).
- Doutes principaux : la date du mariage de Léopold et Marie (le jour même de
  l'insurrection ? « devait épouser » gardé, vrai au début du récit) ; la scène
  du chant nocturne ; le royaume de Kakongo ; le rôle d'Habibrah auprès de
  Biassou.
- Simplifications : la note finale (mort de Léopold, de Thadée et du chien, le
  commissaire) omise, comme la lutte au bord du gouffre.
- 7 faits, 115 mots. Lint : 0 erreur, 0 avertissement. Dart : aucune fuite.

#### `rene-chateaubriand`

- Qui parle : le narrateur, sans se nommer ; il s'arrête à sa confidence aux
  deux vieillards.
- Titre et auteur : « René », « François » et « Chateaubriand » évités ; le
  héros est « un jeune Français mélancolique ». **L'ancien `summary` écrivait
  « René »** (fuite du titre dans la fiche actuelle).
- Doutes principaux : la lettre d'Europe qui provoque la confidence et celle
  qui annonce la mort d'Amélie (non écrites) ; l'itinéraire des voyages ; la
  formule de l'aveu sous le drap mortuaire.
- Fin : un premier état s'arrêtait au reproche du père Souël (vraie fin du
  récit) ; j'ai ajouté la mort dans le massacre des Natchez, tirée de la
  dernière phrase de la fiche, puisque la consigne veut une fin révélée. Cela a
  fait passer le texte à 121-122 mots, ramené à 118 en trois reprises.
- 7 faits. Corpus : une seule page, « René », qui est l'œuvre entière (courte) :
  tous les faits devraient se trancher. Lint : 0 erreur, 0 avertissement.
  Dart : aucune fuite.

### Bilan du lot

| Œuvre | `summary` | `personalSummary` | Faits | Voix |
|---|---|---|---|---|
| `notre-dame-de-paris` | 116 | 89 | 7 | Quasimodo |
| `le-dernier-jour-dun-condamne` | 116 | 74 | 7 | le condamné |
| `lhomme-qui-rit` | 119 | 85 | 6 | Gwynplaine |
| `les-travailleurs-de-la-mer` | 105 | 84 | 7 | Gilliatt |
| `quatrevingt-treize` | 115 | 81 | 7 | Gauvain |
| `ruy-blas` | 116 | 80 | 7 | le valet (sans nom) |
| `hernani` | 118 | 91 | 7 | le proscrit (sans nom) |
| `lucrece-borgia` | 119 | 77 | 7 | la duchesse (sans nom) |
| `han-dislande` | 115 | 72 | 7 | Ordener |
| `bug-jargal` | 115 | 78 | 7 | Léopold d'Auverney |
| `rene-chateaubriand` | 118 | 79 | 7 | le narrateur (sans nom) |

`summary lint` final : 0 erreur, 1 avertissement gardé (`ruy-blas`, « j'aime »
au sens de l'amour du personnage). Dart (`list_name_leaks.dart` sur le
catalogue simulé des 11 fiches) : aucune fuite.

Points à trancher à l'intégration :

1. `quatrevingt-treize` : l'année « 1793 » contient le titre numérique (« 93 »)
   et n'est pas relevée par le contrôle Dart (essai fait). Je l'ai évitée ;
   décider si c'est la règle, et si le scanner doit la connaître.
2. `ruy-blas` : `importantPassages` dit que le héros empoisonne Salluste ; ma
   mémoire dit qu'il le tue (à l'épée). Fait relevé ; corriger la fiche si la
   passe 2 tranche dans ce sens.
3. `rene-chateaubriand` : l'ancien `summary` nomme « René » (fuite) ; le
   nouveau le remplace de toute façon.
4. `han-dislande` : œuvre la moins sûre du lot, formulations larges ; une
   relecture humaine du milieu de l'intrigue serait utile si la passe 2 trouve
   beaucoup de faits hors zone (le corpus n'a que le premier chapitre et la
   conclusion).

### Difficultés au fil du lot

- Pas de fatigue ressentie ni d'envie d'abréger : les notes des dernières œuvres
  (`han-dislande`, `bug-jargal`, `rene-chateaubriand`) sont aussi longues que
  celles des premières, et portent plus de doutes — par nature (souvenirs plus
  minces de *Han d'Islande* et *Bug-Jargal*), pas par relâchement. Je ne peux
  pas exclure un effet de longueur que je ne percevrais pas : 11 œuvres, c'est
  près de trois sessions ordinaires.
- Un seul auteur pour dix œuvres sur onze : pas de confusion ressentie, mais
  une vigilance particulière entre les deux drames espagnols (*Hernani*, *Ruy
  Blas* : deux « don », un roi d'Espagne, un poison final) et entre les deux
  fins par noyade (*L'Homme qui rit*, *Les Travailleurs de la mer*).
- Longueur : quatre premiers jets dépassaient 120 mots (`lhomme-qui-rit` 125,
  `hernani` 121, `lucrece-borgia` 128, `rene-chateaubriand` 121-122). Ce n'est
  pas du remplissage mais l'effet du plan imposé (situation, nœud, deux ou trois
  événements, dénouement, personnages nommés) sur des intrigues très chargées.
  Tous les textes finaux sont entre 105 et 119 mots : toujours dans le haut de
  la fourchette, comme le signalait le bilan de `lot-essai-10`.
- Faits : 6 ou 7 par œuvre, choisis sans chercher à atteindre 8 ; j'ai écarté
  ceux que la première ou la dernière phrase de la fiche confirme déjà
  (date d'ouverture de *Notre-Dame*, « cinq semaines », « quatre heures »).
- Outil : le fichier de session étant réécrit par mes propres scripts entre
  deux éditions, l'outil d'édition a refusé une écriture (« modifié depuis la
  lecture ») ; j'ai continué avec un petit script de remplissage dans mon
  dossier temporaire. Aucun effet sur le contenu. Chaque contrôle Dart prend
  environ une minute.

### Retours sur la consigne

- **Titre numérique** : la règle des mots isolés ne dit rien d'un titre qui est
  un nombre ou une date (« Quatrevingt-treize », « 93 »). J'ai traité l'année
  « 1793 » comme un nom propre du titre (évitée). À préciser.
- **Personnage-titre** : cinq œuvres sur onze ont pour titre le nom du héros
  (*Ruy Blas*, *Hernani*, *Lucrèce Borgia*, *Han d'Islande*, *René*), plus
  *Bug-Jargal* (nom africain de Pierrot). La règle « personnages nommés » et la
  périphrase obligatoire tirent en sens inverse : le `summary` devient moins
  lisible (« le proscrit », « le valet »), et le personnage principal est le
  seul à ne pas être nommé. Quand le personnage a un autre nom sans rapport avec
  le titre (Jean d'Aragon, Pierrot, « le faux don César »), je l'ai employé ;
  à confirmer comme pratique.
- **Fin révélée et longueur** : pour une œuvre dont la vraie fin est un
  épilogue ajouté (*René* : la mort des trois amis ; *Bug-Jargal* : la note
  finale), j'ai révélé l'épilogue pour *René* (une phrase de l'œuvre) et pas
  pour *Bug-Jargal* (un chapitre à part, hors du récit principal). Règle
  possible : la fin du récit principal suffit.
- **Taille du lot** : 11 œuvres d'un même auteur se sont bien passées, mais la
  consigne dit « trois ou quatre » ; si la taille compte pour la qualité, ce
  lot sert de point de comparaison avec `lot-essai-10`.

## Passe 2 — vérification

Chaque œuvre est vérifiée dans l'ordre du fichier, fait par fait, contre les pages enregistrées. Le corpus est partiel pour neuf œuvres sur onze (extraits d'ouverture et de clôture) : la plupart des « hors zone » tiennent à cette limite et non à une contradiction du texte.

### Bilan

| Œuvre | Faits | Confirmés | Hors zone | Corrigés |
|---|---|---|---|---|
| `notre-dame-de-paris` | 7 | 7 | 0 | 0 |
| `le-dernier-jour-dun-condamne` | 7 | 1 | 6 | 0 |
| `lhomme-qui-rit` | 8 | 3 | 5 | 0 |
| `les-travailleurs-de-la-mer` | 8 | 3 | 5 | 0 |
| `quatrevingt-treize` | 8 | 5 | 3 | 0 |
| `ruy-blas` | 8 | 5 | 2 | 1 |
| `hernani` | 7 | 6 | 1 | 0 |
| `lucrece-borgia` | 7 | 7 | 0 | 0 |
| `han-dislande` | 8 | 3 | 5 | 0 |
| `bug-jargal` | 7 | 1 | 6 | 0 |
| `rene-chateaubriand` | 7 | 7 | 0 | 0 |
| **Total** | **82** | **48** | **33** | **1** |

Les faits « Notes » (doutes) sont vérifiés sur une ligne « Vérification : … » sous chaque puce concernée.

### Corrections

- `ruy-blas`, fait ajouté « Le valet révèle sa condition à la reine avant de tuer Salluste » (statut corrigé, `p00507` à `p00512` puis `p00533`) : l'aveu précède le meurtre. Le fait « Le valet tue Salluste de sa main » est scindé et confirmé (`p00534`, épée de Salluste).
- `ruy-blas`, `summary` : « Le valet tue son maître, révèle sa condition et s'empoisonne » devient « Le valet révèle sa condition, tue son maître et s'empoisonne » (`p00507` à `p00534`).
- `ruy-blas`, `personalSummary` : « Pour la sauver, j'ai tué mon maître, j'ai avoué à la reine qui j'étais et j'ai bu le poison. » devient « Pour la sauver, j'ai avoué à la reine qui j'étais, j'ai tué mon maître et j'ai bu le poison. » (mêmes paragraphes).

### Points à trancher

1. **Fiche `ruy-blas`** (`importantPassages`) : elle dit que le héros « empoisonne » celui qui l'utilisait puis révèle son identité. Le texte dit le contraire : aveu (`p00512`), meurtre à l'épée (`p00534`), poison bu seul (`p00584`). À corriger à l'intégration.
2. **Notes « non écrit » erronées** : trois doutes affirmaient que le texte ne disait pas une chose qu'il dit. `ruy-blas` : « duc d'Olmedo » (`p00504`). `lucrece-borgia` : « princesse Negroni » (`p00313`) et « vin de Syracuse » (`p00523`). Les notes sont corrigées par une ligne « Vérification » ; à relire.
3. **`bug-jargal`** : la note supposait Marie morte à « Fort-Dauphin » ; le texte dit « fort Galifet », puis « premier incendie du Cap » (`p00042`). Doute contredit, note corrigée, résumé inchangé.
4. **`quatrevingt-treize`** : le point de la passe 1 (« 1793 » contient le titre numérique) reste ouvert, comme signalé.
5. **Hors zone à relire humainement** : `le-dernier-jour-dun-condamne` (6 faits sur 7, corpus = chapitres I et XLIX), `bug-jargal` (6 sur 7, corpus = chapitre I et note finale), `han-dislande` (5 sur 8, cœur de l'intrigue absent). Dans `hernani`, l'élection « près du tombeau de Charlemagne » n'est pas dans le corpus : hors zone, non corrigé.
6. **Appuis faibles** : `hernani`, « Ruy Gomez refuse de livrer le proscrit » repose sur `p00293` seul (protection de la fuite) ; `notre-dame-de-paris`, « squelette de Quasimodo » : l'identité des deux squelettes est implicite (difformité, robe blanche, `p00405`, `p03716`). `rene-chateaubriand` : le reproche de Souël emploie « présomptueux » (`p00120`), non « orgueil » ; le résumé dit « orgueil », sens conservé, à arbitrer.
7. **Fait dans `lhomme-qui-rit`** : « Dea meurt dans mes bras » n'est pas écrit (Gwynplaine lui baise les mains, `p00397`) ; détail hors zone, non corrigé.

### Contrôles

- `summary lint vague1-2 --checked` : 0 erreur, 1 avertissement gardé (`ruy-blas`, « j'aime » : amour du personnage pour la reine).
- `summary apply vague1-2 --output` (catalogue simulé, 11 fiches) puis `dart run tool/list_name_leaks.dart` : « Aucune fuite de titre ou d'auteur ». Dart répond (avec un avertissement de Flutter « running as root », sans effet).
- `summary mark vague1-2 checked` : lancé après l'écriture de ce compte rendu.

### Incidents

- Une écriture du script d'application (`ruy-blas`) a été refusée sur une chaîne de recherche inexacte : rien n'a été écrit, la chaîne a été corrigée, puis l'application a réussi.
- La session a redémarré en cours de travail, pendant `ruy-blas` (sixième œuvre) ; la reprise s'est faite sur les données sauvegardées par œuvre. Les données de vérification étaient sauvegardées par œuvre ; la reprise s'est faite sans perte, et le fichier de session est relu par le lint après application.
- Une recherche par termes (`summary find`) tronque à quatre occurrences par terme : pour `lucrece-borgia`, une première recherche sur l'acte III avait été mal filtrée et faussement conclu « absent » ; la vérification a été reprise par lecture directe des paragraphes. Les conclusions retenues sont celles de la lecture directe.

### Difficultés au fil du lot

- La fin du lot n'a pas été plus facile à traiter : les mêmes gestes (lecture ciblée, puis confirmation par paragraphe) ont été tenus de bout en bout. Mais j'ai trouvé plus de dérives dans les dernières œuvres : des doutes affirmaient « non écrit » pour des éléments que le texte donne, comme `ruy-blas` et `lucrece-borgia`. C'est un signal sur la passe 1, plus que sur la vérification.
- Les corpus partiels (`le-dernier-jour-dun-condamne`, `bug-jargal`, `han-dislande`) demandent beaucoup de lectures pour un petit nombre de faits confirmés. Je n'ai pas pu confirmer les faits du cœur de ces intrigues.

### Retours sur la consigne

- **Corpus partiel** : la consigne donne « hors zone » pour un fait introuvable, sans dire ce qu'on fait d'une œuvre dont la moitié n'est pas enregistrée. J'ai utilisé l'appui « absent des pages enregistrées » et précisé dans la cellule ce qui manque (chapitre, acte). Une règle explicite serait utile.
- **Fait à deux affirmations** : la scission en deux lignes a servi sept fois (dont une pour ajouter le fait corrigé). Le tableau reste lisible.
- **Doutes qui se contredisent** : j'ai corrigé la note, pas le résumé, quand le texte contredit seulement le doute (`bug-jargal`, `ruy-blas` : Olmedo). La consigne le permet ; je le signale par cohérence.

## Intégration

Décisions de la session principale (pas de relecture humaine) :

- `ruy-blas` : correction de la passe 2 retenue (aveu, puis meurtre, puis poison). L'erreur de la fiche (`importantPassages`) est hors du périmètre des résumés : signalée dans `docs/todo.md` de `mystitre`.
- `quatrevingt-treize` : « 1793 » évité, gardé ainsi (nombre du titre traité comme un nom propre).
- `le-dernier-jour-dun-condamne`, `bug-jargal`, `han-dislande` : faits hors zone gardés (corpus partiel).
- `lhomme-qui-rit` : « Dea meurt dans mes bras » gardé (hors zone, conforme à l'œuvre).
