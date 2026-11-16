# Notre-Dame de Paris — compte rendu

- **Œuvre** : Victor Hugo, *Notre-Dame de Paris* (1831), texte français original, libre de droits.
- **Édition retenue** : Wikisource, page « Notre-Dame de Paris/Texte entier » — « Œuvres complètes de Victor Hugo, Imprimerie nationale, Roman, tome II » (index djvu indiqué par la page, texte validé). Choisie car complète, validée, en une seule page.
- **Exclu du corps du texte** : page de titre, justification du tirage, préface de l'auteur (Ἀνάγκη, février 1831), note de l'édition définitive (1832) ; en fin : notes de l'édition, reliquat, scénario, manuscrit, notes de l'éditeur, revue de la critique, illustration. Corps : p00048 → p03748 (10 010 phrases).
- **Ouverture** : 317 caractères, 2 phrases (« Il y a aujourd'hui trois cent quarante-huit ans… » / « Ce n'est cependant pas un jour… 1482. »).
- **Clôture** : 385 caractères, 4 phrases, finissant sur « il tomba en poussière. »
- **Contrôles** : verify sans erreur ; format_book_json, check_decoys, tests corpus (55) et `flutter test test/data/` : code 0.
- **Points douteux** : découpage correct ; « parisiens » est en minuscule dans l'édition (fidèle à la source, l'ancienne citation avait une majuscule). Pas de masque de titre nécessaire.
- **Écart avec l'ancienne citation / l'audit** : l'ancienne clôture (« Ainsi périt l'archidiacre et ainsi périt la bohémienne. ») était une phrase du chapitre précédent ; l'audit visait déjà la fin de « Mariage de Quasimodo » (« …il tomba en poussière »), désormais retenue. L'ouverture est inchangée sur le fond (deuxième phrase ajoutée).
- **Hésitations** : l'édition ne dit rien de plus que l'index djvu ; je n'ai pas complété éditeur/date de mémoire. Le corps exclut la préface de l'auteur (paratexte), conformément à la règle.
