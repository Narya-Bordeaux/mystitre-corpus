# L'Iliade (Homère) — compte rendu

- **Source retenue** : traduction française libre de droits de Leconte de Lisle (Lemerre), chants I à XXIV de fr.wikisource (`Iliade/Rhapsodie I` … `XXIV`), enregistrés un à un. Traducteur mort en 1894 (page « Auteur:Leconte de Lisle » lue par le moteur). Original grec. Date d'édition non indiquée sur Wikisource : aucune année de traduction enregistrée (corrigée à la main dans `sources/iliade.json` après un premier enregistrement où elle avait été donnée de mémoire).
- **Pourquoi pas « Texte entier »** : la page « Iliade (trad. Leconte de Lisle)/Texte entier » s'arrête au chant IX (vérifié par `peek`). Les 24 chants ont donc été pris séparément, sans l'« Avertissement » de l'éditeur.
- **Complétude** : début du chant I (« Chante, Déesse… ») et fin du chant XXIV (funérailles d'Hektôr) comparés au grec (el.wikisource, Ιλιάς/Ω, dernier vers « les funérailles d'Hektôr dompteur de chevaux ») : concordent.
- **Exclu du corps** : intertitres « RHAPSODIE I. »… « XXIV. ». Corps p00002 → p01898.
- **Extraits** : ouverture 360 caractères (2 phrases), clôture 371 caractères (3 phrases).
- **Points à noter** : graphies grécisantes (Akhilleus, Hektôr, Pèlèiade), conservées. Titre « Iliade » absent des extraits, pas de masque. Précédente citation : texte d'attente, rien à comparer. Contrôles en code 0.
- **Incident** : une erreur 429 de Wikisource pendant `register` (fiche cependant créée, `fetch` relancé avec succès).
- **Hésitation** : la consigne dit de ne jamais donner l'année de mémoire, mais `--translation-year` est demandé à l'enregistrement ; j'ai dû le corriger après coup. Le moteur pourrait accepter `register` sans année.
