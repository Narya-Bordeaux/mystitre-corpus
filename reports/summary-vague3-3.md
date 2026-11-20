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

Corpus : deux pages par œuvre (début et fin de la fiche), donc « pages choisies » pour les dix. Un fait absent des pages reste hors zone ; seules les contradictions produisent une correction.

### Bilan

| Œuvre | Confirmés | Hors zone | Corrigés |
|---|---|---|---|
| le-tour-du-monde-en-quatre-vingts-jours | 5 | 2 | 0 |
| vingt-mille-lieues-sous-les-mers | 5 | 4 | 0 |
| voyage-au-centre-de-la-terre | 6 | 2 | 0 |
| lile-mysterieuse | 8 | 2 | 0 |
| cinq-semaines-en-ballon | 4 | 5 | 0 |
| les-enfants-du-capitaine-grant | 5 | 4 | 0 |
| michel-strogoff | 6 | 1 | 1 |
| de-la-terre-a-la-lune | 6 | 3 | 0 |
| un-capitaine-de-quinze-ans | 2 | 6 | 1 |
| robur-le-conquerant | 6 | 2 | 2 |
| **Total** | **53** | **31** | **4** |

Plusieurs faits affirmant deux choses ont été scindés (par exemple « Nemo meurt » confirmé, « dans une caverne » hors zone).

### Corrections

1. *Robur* — fait « Le dirigeable de l'Institut… » : le texte dit « aérostat » et « ballon » (p00067, p00070). Résumé : « dirigeable Go-Ahead » → « ballon Go-Ahead ».
2. *Robur* — fait « …de l'explosion du Go-Ahead » : le gaz trop dilaté fait crever l'enveloppe, le ballon tombe (p00128), et les hommes de Robur font passer Prudent et Evans sur l'Albatros (p00132). Pas d'explosion du ballon. Résumé : « de l'explosion du ballon » → « de la chute de leur ballon ».
3. *Michel Strogoff* — fait « a les yeux brûlés par une lame rougie » : le texte dit qu'il « n'était pas, n'avait jamais été aveugle » (p00089). Fait réécrit en « est condamné à avoir les yeux brûlés… ». Le résumé disait déjà « condamné » : aucun texte modifié.
4. *Un capitaine de quinze ans* — fait ajouté (règle 5), « livrés aux marchands d'esclaves d'Angola » : Angola absent ; les cinq hommes sont vendus à Madagascar (p00082), le convoi va à Emboma, à l'embouchure du Congo (p00069). Résumé : « d'Angola » retiré.
5. Notes, *Le Tour du monde* : « la veille du jour qu'il croit perdu » → la question est posée « ce soir-là même » (p00062), le soir de la victoire.
6. Notes, *Voyage au centre* : « pupille » → le texte dit « sa filleule Graüben » (p00031).
7. Notes, *Les Enfants du capitaine Grant* : « Grant n'apparaît nulle part » est faux : « Harry Grant » (p00068, p00076) et « Mary Grant » figurent dans les pages. Le résumé n'emploie pas ce nom, donc la contrainte du titre tient.

Les corrections ne font entrer aucun nom propre du titre ni de l'auteur (« ballon », « chute », « marchands d'esclaves »).

### Points à trancher

- *Michel Strogoff* : le résumé dit « natif d'Omsk ». Les pages montrent la maison familiale des Strogoff à Omsk (p00140), mais pas la naissance. Choix possible : « dont la famille vit à Omsk ».
- *Un capitaine* : le retrait de « d'Angola » laisse « marchands d'esclaves » sans lieu. Le texte ne donne que Madagascar et Emboma : à préciser ou non.
- *Robur* : « ballon » remplace « dirigeable », d'après le texte. La relecture peut préférer « aérostat ».
- Énoncés hors zone gardés faute de contradiction : « Nemo… dans une caverne » (*L'Île mystérieuse*), « navire de guerre » (*Vingt mille lieues*), « fiancé à Graüben » dès le départ (attesté seulement au retour, p00041), « Nicolas Korpanoff » (nom d'emprunt absent des pages, *Michel Strogoff*).

### Contrôles

- `summary lint vague3-3 --checked` : 0 erreur, 0 avertissement. Aucun statut « à vérifier » ne reste (les seules occurrences de la chaîne sont les titres « Faits à vérifier »).
- `summary apply vague3-3 --output` (catalogue simulé dans le dossier temporaire) : 10 fiches, puis `dart run tool/list_name_leaks.dart` : « Aucune fuite de titre ou d'auteur ».
- `summary mark vague3-3 checked` : lancé après l'écriture de cette section.

### Incidents

- Dart s'exécute ici en root : Flutter l'a signalé, sans effet sur le résultat du contrôle.
- Aucune modification du dépôt `mystitre`.

### Difficultés au fil du lot

- Le corpus ne donne que le début et la fin de chaque roman : plus de la moitié des faits ne peuvent pas être confirmés, ce qui allège la vérification mais la rend moins probante.
- Les deux dernières fiches (*Un capitaine de quinze ans*, *Robur*) ont demandé plus de relectures de passages. C'est là qu'est apparue la correction « Angola », lors du recoupement des doutes de la note (Emboma, Madagascar) et non à la première lecture du tableau. Je ne sens pas de baisse d'attention, mais cette fin de lot a été la plus coûteuse en relectures.
- Les doutes de la passe 1 étaient souvent justes sur le fond et faux sur les détails (« pupille », « Grant absent », « explosion »).

### Retours sur la consigne

- Cas non prévu : un fait « corrigé » où le résumé est déjà juste (« yeux brûlés »). J'ai réécrit la ligne du fait et laissé le texte inchangé.
- Fait à deux termes dont un seul est contredit ou attesté (« Dingo tue Negoro » : la mort de Dingo est attestée, pas la cause) : classé hors zone, avec la précision dans l'appui.
- Vérifications des notes : une ligne « Vérification : … » par doute, groupée en fin de notes, avant « Anciens textes ».
- Règle 5 : appliquée pour l'Angola.
- Ambiguïté : une graphie différente (« Go a head », « Loffoden », « Maelstrom ») est confirmée, alors qu'un mot différent (« dirigeable » pour « aérostat ») est corrigé. Choix retenu : corriger le mot quand le texte en emploie un autre à plusieurs reprises.
