# Pantagruel — compte rendu

- **Œuvre** : *Pantagruel* (Rabelais), fiche `pantagruel`.
- **Édition** : Les Œuvres de François Rabelais (Éditions Marty-Laveaux), page « Pantagruel » de fr.wikisource ; texte original en orthographe ancienne, complet. Pages figées : « Prologue de l'Auteur » et chapitre 34 (œuvre longue, deux bouts). L'édition Clouzot est écartée pour la même raison que pour *Gargantua* (abrégée).
- **Corps du texte** : p00002 (prologue de l'auteur) → p00006 (fin de la conclusion du livre, chap. XXXIIII). Exclus : intertitres et la formule finale d'édition « Fin des Cronicques de Pantagruel… » (p00007), qui est une mention de fin et donnerait le titre.
- **Corrections déclarées** (2) :
  - p00002 : « ſ » → « s » sur les ~1 000 premiers caractères (jusqu'à « à ſes enfans »), et lettrine absente : « resillvstres » → « Tresillustres ». Remplacement ample, signalé.
  - p00006 : « ſ » → « s » sur le paragraphe entier.
  Seule la graphie du « ſ » est modernisée. Le texte non cité de p00002 et p00004 garde ses « ſ ».
  La raison de la première correction avait d'abord été écrite « lettrine B » par erreur de mon script ; je l'ai corrigée à la main dans `sources/pantagruel.json` (« lettrine T »), faute de commande pour la modifier. Aucun texte n'a été touché.
- **Extraits** : ouverture 517 caractères (1 phrase), clôture 489 caractères (3 phrases, finit sur « par un partuys. »).
- **Écart avec l'audit** : l'audit demandait de vérifier la clôture « Car c'est la fin de ce présent livre… » ; la fin du livre est bien la conclusion du chapitre XXXIIII, que j'ai reprise.
- **Points douteux** : le masque `pantagruel` est déclaré mais « pantagruelistes » (dérivé) reste visible dans la clôture, et le test de fuites l'accepte. Si on juge que le dérivé révèle le titre, il faudra retirer la dernière phrase. La lettrine T et la graphie « Tresillustres » sont à relire. L'ouverture est une seule phrase longue.
