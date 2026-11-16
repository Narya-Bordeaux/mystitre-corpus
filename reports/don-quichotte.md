# Don Quichotte — compte rendu /corpus-book

- **Œuvre** : Don Quichotte (Cervantès, 1605/1615), langue d'origine espagnole.
- **Texte retenu** : traduction française de Louis Viardot, libre de droits (décès 1883, lu sur « Auteur:Louis Viardot » par le moteur), fr.wikisource. Édition décrite d'après la page de titre de l'œuvre : « dessins de Gustave Doré, M DCCC LXII ». Les pages de chapitres sont titrées « LIVRE I. — CHAPITRE I. », sans mention d'édition propre : on ne peut pas affirmer qu'elles reproduisent exactement l'édition de 1862.
- **Téléchargement limité (consigne de l'utilisateur)** : la page « Texte entier » ne couvre que la première partie (elle s'arrête à l'épitaphe de Dulcinée) ; le téléchargement des 128 pages a été bloqué par des erreurs 429 de Wikimedia (limite par adresse de sortie, probablement partagée par la vague de sessions). Sur instruction, seules deux pages ont été enregistrées : Première partie/Chapitre I et Deuxième partie/Chapitre LXXIV.
- **Traduction** : traduction libre complète au sens de l'œuvre, mais la comparaison d'intégrité de la section 2.3 (peek avec l'original espagnol) n'a pu être faite que sommairement : es.wikisource n'a pas l'œuvre complète. Début et fin du texte français concordent avec l'œuvre.
- **Corps du texte** : p00003 → p00024. Exclus : titres et intitulés de chapitres ; prologue de l'auteur non téléchargé.
- **Extraits** : ouverture 451 caractères (2 phrases), clôture 552 caractères (2 phrases). Masque : « Quichotte » (clôture, « mon véritable Don [TITRE] »).
- **Points douteux** : le découpage isole « ( — Vale. ) » » comme dernière phrase (ponctuation inhabituelle, non corrigé à la main). La clôture n'est pas la mort du héros mais l'adieu de Cid Hamet à sa plume, vraie fin du livre (conforme à l'audit : « finit sur la plume de Cide Hamete et un Vale »).
- **Écart avec l'ancienne citation** : l'ancienne ouverture (« Dans un village de la Manche… vivait… un gentilhomme ») ne venait pas de ce texte ; l'ancienne clôture « Il rendit l'esprit. » est remplacée.
- **Hésitations** : retenir ou non le prologue ; édition exacte des pages de chapitres.
- **Contrôles** : format_book_json --check, check_decoys, flutter test test/data/, tests unitaires du moteur : tous en code 0.
