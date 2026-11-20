# Compte rendu — résumés vague3-3

- Œuvres : `le-tour-du-monde-en-quatre-vingts-jours`, `vingt-mille-lieues-sous-les-mers`, `voyage-au-centre-de-la-terre`, `lile-mysterieuse`, `cinq-semaines-en-ballon`, `les-enfants-du-capitaine-grant`, `michel-strogoff`, `de-la-terre-a-la-lune`, `un-capitaine-de-quinze-ans`, `robur-le-conquerant`
- Créé le : 2026-11-20
- Données : `summaries/vague3-3.md`

## Passe 1 — rédaction

Dart disponible (`/opt/flutter/bin/dart`) : contrôle des fuites lancé après chaque œuvre.

### `le-tour-du-monde-en-quatre-vingts-jours`

- Voix : Phileas Fogg, le héros, sur un ton bref et maîtrisé.
- Titre : le nombre de jours est tu (« dans un délai fixé », « tour du globe ») : joint à « tour du monde », il reconstituerait le titre. Le résumé perd un peu en précision, assumé.
- Doutes principaux : lieu de la première rencontre avec Fix (Suez, je crois) ; vol de la Banque d'Angleterre (écrit « une banque ») ; c'est Aouda qui propose le mariage (non écrit, formulation neutre). Simplification : l'attaque des Sioux sans l'enlèvement de Passepartout.

### `vingt-mille-lieues-sous-les-mers`

- Voix : le professeur Aronnax, narrateur ; il finit sans savoir si Nemo a survécu.
- Doutes : année (signalement en 1866, départ de la frégate en 1867 je crois) ; graphies « Abraham-Lincoln », « Maelstrom/Maëlstrom », « Lofoden » ; lieu des poulpes géants ; nationalité du navire coulé (je ne m'en souviens pas, « navire de guerre »).
- Simplifications : quatre épisodes tus (île Crespo, Papous, pêcheur de perles, tunnel arabe).

### `voyage-au-centre-de-la-terre`

- Voix : Axel, narrateur, plus craintif que son oncle.
- Doutes : Axel est-il fiancé dès le début (Graüben pupille du professeur, amour d'abord secret, je crois) ; « alchimiste islandais » pour Saknussemm ; moyen de faire sauter le roc (fulmicoton, je crois).
- Simplifications : la séparation d'Axel n'est que dans « Mon histoire » ; tempête, berger géant et boussole tus.

### `lile-mysterieuse`

- Voix : « nous », les cinq colons (pas de narrateur unique).
- Croisement des romans : Nemo et le Nautilus sont légitimes ici (dénouement du roman) ; Ayrton et le Duncan aussi, mais je n'ai nommé ni Glenarvan ni Robert Grant, dont je ne suis pas sûr du rôle dans la venue du Duncan.
- Doutes : graphie « Harbert » ; nom « Granite-House » ; « nordistes » ; le rocher où se réfugient les colons après l'éruption.
- Simplifications : Top, Jup, le *Speedy* et la quinine tus.

### `cinq-semaines-en-ballon`

- Voix : le docteur Fergusson.
- Titre : la durée n'est jamais écrite ; « ballon » est gardé (mot courant, permis).
- Doutes : lieu et espèce des oiseaux qui crèvent l'enveloppe, moment où Joe saute (près du lac Tchad, je crois) ; lieu du sauvetage du missionnaire ; manière de passer le Sénégal (enveloppe gonflée d'air chaud, peut-être en partie brûlée).

### `les-enfants-du-capitaine-grant`

- Titre : « Grant » n'apparaît nulle part ; le père est désigné par périphrase. C'est la contrainte la plus lourde du lot : les enfants ne peuvent pas porter leur nom de famille.
- Voix : Robert, le fils.
- Doutes : nom de l'îlot final (Tabor ou Maria-Theresa) ; année 1864 ; Paganel et le *Scotia* ; Ayrton = Ben Joyce (je le crois sûr).

### `michel-strogoff`

- Titre : héros éponyme. Ni le prénom ni le nom ; la mère est « Marfa ». Le nom d'emprunt Nicolas Korpanoff est employé une fois, comme nom de voyage, le reste en périphrase (« un capitaine de ses courriers », « le courrier ») : l'appeler Korpanoff partout aurait été trompeur.
- Voix : le courrier lui-même.
- Doutes : « lame rougie » (sabre chauffé à blanc, je crois) ; lieu du reniement de la mère (Omsk, je crois). Les journalistes et le radeau de l'Angara sont tus.

### `de-la-terre-a-la-lune`

- Voix : Barbicane, dont la dernière phrase est dite depuis le projectile (il ignore ce que voit le télescope).
- Titre : « la Lune » gardé seul (mot courant), jamais joint à « la Terre ».
- Doutes : graphie « Stone's Hill » ; dernier message (Long's Peak, Belfast) et cause de la déviation, que je crois ne pas mêler au bolide de la suite ; dernière réplique de Maston.

### `un-capitaine-de-quinze-ans`

- Voix : Dick Sand.
- Titre : l'âge du héros n'est pas dit ; « capitaine » n'apparaît que pour Hull.
- Doutes : Harris prétend-il la Bolivie ou le Pérou ; détail du sabotage ; qui tue qui à la fin (Dingo tue Negoro, Dick tue Harris, je crois : c'est ce que dit « Mon histoire », relevé en fait). Les Noirs sont nommés « Noirs américains, hommes libres », pour que l'esclavage qui suit se comprenne.

### `robur-le-conquerant`

- Titre : héros éponyme sans autre nom connu de moi : « un ingénieur inconnu », puis « l'ingénieur ». « Conquérant » et « conquête » évités.
- Voix : l'ingénieur.
- Doutes : île de l'évasion (île X ou Chatham) ; ordre de l'itinéraire ; le Go-Ahead « explose » ou « crève ».
- Correction en cours de route : « leur valet Frycollin » était ambigu (valet de Prudent seul, je crois) ; reformulé en « le valet Frycollin ».

### Bilan des contrôles

- `summary lint vague3-3` : 0 erreur, 0 avertissement (10 œuvres ; 7 faits pour la première, 8 pour les autres).
- `summary apply --output` puis `dart run tool/list_name_leaks.dart` : « Aucune fuite de titre ou d'auteur », après chaque œuvre et sur le lot entier.

### Croisement des romans

Lot d'un seul auteur : chaque fiche n'emploie que ses propres personnages. Deux liens réels entre romans, et seulement ceux-là : Nemo et le Nautilus dans *L'Île mystérieuse* (dénouement du roman) ; Ayrton, abandonné sur l'îlot de Tabor à la fin des *Enfants du capitaine Grant*, recueilli dans *L'Île mystérieuse*, où revient aussi le Duncan. Je n'ai nommé ni Glenarvan ni Robert dans *L'Île mystérieuse*, faute d'être sûr de leur rôle dans la venue du Duncan. « Michel » (Ardan, *De la Terre à la Lune*) est un prénom du titre d'un autre roman du lot : permis.

### Difficultés au fil du lot

- Je n'ai pas senti de baisse d'attention vers la fin : les trois dernières fiches (*De la Terre à la Lune*, *Un capitaine de quinze ans*, *Robur*) ont autant de notes que les premières, et c'est sur la dernière que j'ai repris une ambiguïté. Les romans de ce lot sont connus et à intrigue nette, ce qui aide.
- La difficulté principale a été le titre : quatre titres sur dix gênent le résumé. Deux héros éponymes (*Michel Strogoff*, *Robur*), un nom de famille interdit à toute la famille (*Grant*), et trois titres faits de mots courants dont la réunion reconstitue le titre (durée du tour du monde, durée du vol en ballon, âge du jeune capitaine). La précision du résumé en souffre un peu, assumé.
- Mémoire : la mienne est plus sûre sur les grandes lignes que sur les noms secondaires et l'ordre des épisodes du milieu ; les notes le disent œuvre par œuvre. Le corpus n'a que le premier et le dernier chapitre de chaque roman : beaucoup de faits du milieu resteront hors zone.

### Retours sur la consigne

- **Héros éponyme avec un nom d'emprunt** (*Michel Strogoff* / Nicolas Korpanoff) : la consigne dit d'employer l'autre nom. Ici, c'est un nom de voyage, pas son nom : l'appeler Korpanoff partout serait trompeur. Choix : une mention comme nom d'emprunt, périphrase ailleurs. Une précision pourrait l'écrire.
- **Nom propre du titre porté par une famille** (*Grant*) : la règle impose de taire le nom de tous ses membres. Appliquée sans peine (prénoms, « le naufragé », « mon père »), mais la consigne ne cite pas ce cas.
- **Nombre ou durée dans le titre** (quatre-vingts jours, cinq semaines, quinze ans) : ni nom propre ni tout à fait « mot courant ». Je les ai traités comme des mots courants dont la réunion avec le reste reconstituerait le titre, donc tus. Une ligne sur les nombres dans les titres aiderait.
- La fiche du catalogue est restée d'un faible appui pour ce lot : descriptions anonymes, sans nom. Aucun désaccord relevé avec ma mémoire ; les anciens résumés sont plus courts mais compatibles. (Une première version de la note de *Cinq semaines en ballon* attribuait à tort à la fiche une enveloppe « brûlée » : la fiche n'en dit rien, note corrigée.)

## Passe 2 — vérification

<!-- Bilan (tableau confirmés / hors zone / corrigés par œuvre), corrections, points à trancher, contrôles et incidents, difficultés au fil du lot, retours sur la consigne. -->
