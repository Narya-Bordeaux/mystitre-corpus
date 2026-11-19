# Remarques — vérification de la session `lot-test` (passe 2)

Fichier hors dépôt. Livrable poussé : `mystitre-corpus`, branche `claude/sleepy-archimedes-u69uu1`, commit « Résumés lot-test : vérification ».

## Bilan par œuvre

| Œuvre | Confirmés | Hors zone | Corrigés |
|---|---|---|---|
| Guerre et Paix | 6 | 2 | 0 |
| Crime et châtiment | 4 | 3 | 0 |
| Antigone | 7 | 0 | 0 |
| Au bord de l'eau | 7 | 0 | 0 |

Aucune correction : le corpus ne contredit aucun fait.

## Guerre et Paix
- Hors zone : mort d'André de sa blessure de Borodino, veillé par Natacha. Le corpus (tome 1 + épilogue) n'atteste que sa mort et le désespoir de Natacha (p03145) ; Borodino n'a qu'une allusion sans rapport (p03118).
- Hors zone : Pierre prisonnier qui marche avec Karataïev. L'épilogue évoque seulement « плен, Платон Каратаев » (p03364).
- « Pieds nus » (`personalSummary`) reste hors zone.

## Crime et châtiment
- Hors zone : meurtre de Lizaveta (seule « Élisabeth » apparaît, p00025 ; la sœur p00049-p00050), Porphyre Petrovitch, prostitution de Sonia.
- Huit ans confirmés (p00067, p00090, p00094). Graphie du corpus : « Aléna Ivanovna », « Raskolnikoff ».

## Antigone
- Œuvre entière dans le corpus (traduction Leconte de Lisle : « Kréôn », « Haimôn », « divinateur »). Tous les faits retrouvés.
- « Mon oncle » confirmé : Créon dit « née de ma sœur » (p00104).

## Au bord de l'eau
- Corpus : ouverture + chapitre 100. 108 étoiles attestées en 36 et 72 (p00009) et « 百八 » (p00051).
- Les quatre ministres (Cai Jing, Tong Guan, Gao Qiu, Yang Jian) trament l'empoisonnement (p00054, p00060) ; Song Jiang empoisonne aussi Li Kui (p00066) ; Wu Yong et Hua Rong se pendent sur sa tombe (p00074-p00076). Empereur du chapitre 1 : Renzong (p00016).
- « Une crypte » : approximation de la fosse sous la stèle (p00037-p00039), non contredite.

## Points à trancher
- Aucun fait introuvable dans une œuvre entière.

## Retours sur la consigne
- Pas de règle pour un fait composé dont une moitié seulement est attestée : choix « hors zone » avec l'appui de la partie attestée. À préciser (scinder le fait à la rédaction ?).
- Pas d'indication sur où consigner l'issue des « Doutes » de la passe 1 : résumée dans la section « Retours sur la consigne » du fichier de session.
- Pas d'indication sur un fait confirmé par une graphie du corpus différente de celle du `summary` : noté confirmé, sans correction.

## Déroulé et incidents
- Premier `which dart` sans résultat alors que Dart est installé (`/opt/flutter/bin/dart`) ; contrôle des fuites fait après le push : « Aucune fuite de titre ou d'auteur ». Fichier poussé inchangé.
- `lint --checked` : 0 erreur, 0 avertissement ; `mark lot-test checked` : code 0.
- Rien poussé dans `mystitre`, aucune pull request.
