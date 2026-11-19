# Compte rendu — résumés lot-test

- Œuvres : `guerre-et-paix`, `crime-et-chatiment`, `antigone`, `au-bord-de-leau`
- Créé le : 2026-11-19
- Données : `summaries/lot-test.md`

Session d'essai, antérieure au gabarit de compte rendu : ce fichier rassemble
après coup les remarques écrites à quatre endroits provisoires (hésitations de
la passe 1, section de tête du fichier de session, deux rapports de vérification).

## Passe 1 — rédaction

Hésitations relevées pendant les sessions `/summary-draft`, à reprendre dans la
consigne (`mystitre/.claude/skills/summary-draft/SKILL.md`) ou la spécification
(`mystitre/docs/summary_rewrite.md`).

### Session `lot-test` (2026-11-19)

Œuvres : `guerre-et-paix`, `crime-et-chatiment`, `antigone`, `au-bord-de-leau`.

#### Hésitations sur la consigne

1. **Personnage dont le nom est le titre** (*Antigone*). La règle 4 interdit le
   titre dans les deux textes et interdit « le héros » dans `personalSummary`.
   La consigne ne dit pas comment faire parler ce personnage. Choix fait : la
   première personne seule, sans nom ; dans le `summary`, « leur sœur », « la
   jeune femme ».
2. **Corpus partiel.** Le corpus ne couvre souvent que le début et la fin de
   l'œuvre (tome 1 et épilogue pour *Guerre et Paix*, I/1 et épilogue pour
   *Crime et Châtiment*, prologue et chapitres 1 et 100 pour *Au bord de
   l'eau*). Faut-il relever en priorité les faits que ces pages peuvent
   confirmer, ou ceux dont on est le moins sûr, même s'ils tombent hors du
   corpus ? Choix fait : un mélange, et les faits hors corpus sont signalés
   dans les notes.
3. **Commentaires du gabarit.** La consigne ne dit pas s'il faut garder les
   commentaires `<!-- … -->` sous `### summary` et `### personalSummary`.
   Choix fait : ils sont remplacés par les textes.
4. **Graphies des traductions anciennes.** Quand la graphie du corpus est
   incertaine (« Raskolnikoff » ou « Raskolnikov », « Lizaveta » ou
   « Élisabeth »), la colonne « Termes » donne plusieurs variantes. La consigne
   pourrait dire si c'est la pratique attendue.
5. **Où noter ces retours.** La consigne ne prévoit pas d'endroit pour les
   hésitations sur la consigne elle-même : d'où ce fichier.

#### Doutes reportés après coup dans les notes de la session

Doutes apparus pendant la rédaction mais oubliés dans les « Notes » de
`summaries/lot-test.md`, puis ajoutés à la demande de la relectrice ou du
relecteur. Les textes n'ont pas été corrigés : la phrase ambiguë reste en
l'état, la session sert à tester la procédure.

- **Guerre et Paix**
  - Phrase ambiguë dans le `summary` : « Fiancée à André, la jeune Natacha
    Rostova se laisse séduire par Anatole Kouraguine et rompt avec lui » ;
    « lui » peut désigner André ou Anatole. Laissée en l'état.
- **Crime et Châtiment**
  - La « mansarde » du `personalSummary` est une image de mémoire, pas un fait
    relevé.
  - La lecture de l'Évangile par Sonia (résurrection de Lazare) se trouve au
    milieu du roman, hors du corpus ; seul l'Évangile de l'épilogue peut être
    confirmé.
- **Antigone**
  - J'ai d'abord pensé à « la fille aînée d'Œdipe », puis j'y ai renoncé faute
    d'être sûr qu'elle soit l'aînée.
- **Au bord de l'eau**
  - « Des ministres jaloux » simplifie : il s'agit de Gao Qiu, Tong Guan, Cai
    Jing et Yang Jian, et la répartition de leurs rôles dans l'empoisonnement
    est incertaine.
  - « Une crypte » et « cent huit esprits stellaires » sont des
    approximations : une stèle sous laquelle s'ouvre une fosse, et des étoiles
    démoniaques (天罡, 地煞).
  - « Petit greffier de district » traduit 押司 ; l'équivalence française n'est
    pas sûre.

## Passe 2 — vérification

### Vérification Sonnet

Fichier hors dépôt. Livrable poussé : `mystitre-corpus`, branche `claude/sleepy-archimedes-u69uu1`, commit « Résumés lot-test : vérification ».

### Bilan par œuvre

| Œuvre | Confirmés | Hors zone | Corrigés |
|---|---|---|---|
| Guerre et Paix | 6 | 2 | 0 |
| Crime et châtiment | 4 | 3 | 0 |
| Antigone | 7 | 0 | 0 |
| Au bord de l'eau | 7 | 0 | 0 |

Aucune correction : le corpus ne contredit aucun fait.

### Guerre et Paix
- Hors zone : mort d'André de sa blessure de Borodino, veillé par Natacha. Le corpus (tome 1 + épilogue) n'atteste que sa mort et le désespoir de Natacha (p03145) ; Borodino n'a qu'une allusion sans rapport (p03118).
- Hors zone : Pierre prisonnier qui marche avec Karataïev. L'épilogue évoque seulement « плен, Платон Каратаев » (p03364).
- « Pieds nus » (`personalSummary`) reste hors zone.

### Crime et châtiment
- Hors zone : meurtre de Lizaveta (seule « Élisabeth » apparaît, p00025 ; la sœur p00049-p00050), Porphyre Petrovitch, prostitution de Sonia.
- Huit ans confirmés (p00067, p00090, p00094). Graphie du corpus : « Aléna Ivanovna », « Raskolnikoff ».

### Antigone
- Œuvre entière dans le corpus (traduction Leconte de Lisle : « Kréôn », « Haimôn », « divinateur »). Tous les faits retrouvés.
- « Mon oncle » confirmé : Créon dit « née de ma sœur » (p00104).

### Au bord de l'eau
- Corpus : ouverture + chapitre 100. 108 étoiles attestées en 36 et 72 (p00009) et « 百八 » (p00051).
- Les quatre ministres (Cai Jing, Tong Guan, Gao Qiu, Yang Jian) trament l'empoisonnement (p00054, p00060) ; Song Jiang empoisonne aussi Li Kui (p00066) ; Wu Yong et Hua Rong se pendent sur sa tombe (p00074-p00076). Empereur du chapitre 1 : Renzong (p00016).
- « Une crypte » : approximation de la fosse sous la stèle (p00037-p00039), non contredite.

### Points à trancher
- Aucun fait introuvable dans une œuvre entière.

### Retours sur la consigne
- Pas de règle pour un fait composé dont une moitié seulement est attestée : choix « hors zone » avec l'appui de la partie attestée. À préciser (scinder le fait à la rédaction ?).
- Pas d'indication sur où consigner l'issue des « Doutes » de la passe 1 : résumée dans la section « Retours sur la consigne » du fichier de session.
- Pas d'indication sur un fait confirmé par une graphie du corpus différente de celle du `summary` : noté confirmé, sans correction.

### Déroulé et incidents
- Premier `which dart` sans résultat alors que Dart est installé (`/opt/flutter/bin/dart`) ; contrôle des fuites fait après le push : « Aucune fuite de titre ou d'auteur ». Fichier poussé inchangé.
- `lint --checked` : 0 erreur, 0 avertissement ; `mark lot-test checked` : code 0.
- Rien poussé dans `mystitre`, aucune pull request.

#### Retours écrits en tête du fichier de session (Sonnet, puis Haiku)

- Vérification : la consigne ne dit pas quel statut donner à un fait composé dont une seule moitié est attestée (« Pierre est fait prisonnier et marche avec Karataïev » : captivité et nom évoqués en passant, p03364, mais pas la marche). J'ai choisi `hors zone`, en citant dans l'appui ce qui est attesté ; une règle explicite serait utile (scinder le fait en deux lignes à la rédaction ?).
- Vérification : les « Doutes » de la section Notes de la passe 1 ne sont pas des faits du tableau ; la consigne ne dit pas où consigner leur issue. Je ne les ai pas ajoutés au tableau (aucune contradiction) et je les résume ici : Antigone, « mon oncle » confirmé (Créon dit « née de ma sœur », p00104) ; Au bord de l'eau, les quatre ministres Cai Jing, Tong Guan, Gao Qiu et Yang Jian trament l'empoisonnement (p00054, p00060) et l'empereur du premier chapitre est Renzong (p00016) ; Crime et châtiment, huit ans confirmés (p00067). Guerre et Paix : « pieds nus » et « mort d'André à Borodino » restent hors zone.
- Vérification : le tableau demande des termes dans la graphie du corpus, mais le `summary` garde la graphie usuelle (« Aliona », « Hémon ») : un fait confirmé par une variante (« Aléna », « Haimôn ») est noté confirmé, sans correction ; la consigne gagnerait à le dire.
- Vérification : la consigne ne dit pas quoi faire d'un fichier déjà à l'étape « vérifiée » (cas de `lot-test` : une seconde passe, sur la même branche). J'ai contrôlé chaque statut sans rien changer de ce qui était juste, et ajouté les faits repérés dans le `personalSummary` (« pieds nus »). Une règle sur la seconde passe serait utile.

### Seconde vérification Haiku

Partie du fichier déjà vérifié par Sonnet (non à l'aveugle) : complète, ne
remplace pas.

Date : 2026-11-19
Branche de travail : `claude/lot-test-check-haiku` (dépôt `mystitre-corpus`, commit `9a246a5`)
Fichier vérifié : `summaries/lot-test.md`

### 1. État de départ

- Le fichier n'était pas à l'étape « rédigée » comme annoncé : il était déjà à l'étape « vérifiée ».
- La branche `claude/sleepy-archimedes-u69uu1` contenait déjà un commit « Résumés lot-test : vérification » (`418fad0`).
- J'ai donc fait une seconde vérification indépendante, à partir du texte du corpus.
- `origin/claude/sleepy-archimedes-u69uu1` n'existait pas comme référence distante après un clone superficiel : j'ai créé la branche de travail à partir de `FETCH_HEAD`.

### 2. Résultats par œuvre

#### guerre-et-paix — 6 confirmés, 3 hors zone, 0 corrigé
- Confirmés :
  - salon d'Anna Pavlovna à Saint-Pétersbourg en 1805 (p00004, p00015, p00044) ;
  - André blessé à Austerlitz (p03035-p03037) ;
  - Pierre fils illégitime et héritier (p00055, p02183) ;
  - Pierre épouse Hélène (p02266-p02273) ;
  - épilogue : Pierre marié à Natacha (p03144) ;
  - épilogue : Nicolas marié à Marie (p03206).
- Hors zone :
  - mort d'André à Borodino (seule allusion à Borodino en p03118) ;
  - captivité de Pierre avec Platon Karataïev (p03364 ne fait qu'évoquer « плен, Платон Каратаев ») ;
  - « marche pieds nus » (ligne ajoutée au tableau).

#### crime-et-chatiment — 4 confirmés, 3 hors zone, 0 corrigé
- Confirmés :
  - Raskolnikov, ancien étudiant pauvre (p00003, p00018) ;
  - Aliona Ivanovna, usurière, graphie du corpus « Aléna » (p00032) ;
  - condamnation à huit ans de bagne (p00065, p00067) ;
  - Sonia suit Raskolnikov en Sibérie (p00081) et l'Évangile de l'épilogue (p00095).
- Hors zone :
  - meurtre de Lizaveta (la sœur n'apparaît que comme « Élisabeth », p00025) ;
  - Porphyre Petrovitch (absent) ;
  - prostitution de Sonia (absente ; l'épilogue ne dit pas comment elle vit).

#### antigone — 7 confirmés, 0 hors zone, 0 corrigé
- Créon interdit d'ensevelir Polynice (p00016, p00048).
- Ismène refuse d'aider sa sœur (p00021-p00027).
- Poussière sur le corps, découverte par un garde (p00063, p00065).
- Lois non écrites (p00102).
- Hémon est le fiancé d'Antigone (p00150, p00168, p00300).
- Tirésias avertit Créon (divinateur, p00246-p00270).
- Antigone se pend (p00300), Hémon se tue (p00293-p00295), Eurydice se frappe (p00312).

#### au-bord-de-leau — 7 confirmés, 0 hors zone, 0 corrigé
- Hong Xin libère les esprits, envoyé contre une épidémie (p00016, p00019, p00037-p00039).
- 36 étoiles célestes + 72 étoiles terrestres = 108 (p00009) ; « 一百單八 » n'apparaît pas littéralement.
- Repaire des marais du mont Liang (p00011, p00066).
- Song Jiang chef (p00044, p00066, p00087).
- Amnistie et guerre contre Fang La (p00043, p00076, p00081).
- Song Jiang empoisonné par un vin envoyé par la cour (p00063, p00066).
- Li Kui, Wu Yong et Hua Rong meurent après Song Jiang (p00068, p00075).

### 3. Modifications apportées au fichier `summaries/lot-test.md`

- Ajout au tableau de guerre-et-paix : « Pierre marche pieds nus pendant la retraite », hors zone (`босиком` absent ; `босой` ne désigne que le pied de Touchine, p01938).
- Remplacement de la note « Doute » sur les pieds nus par une note « Vérification ».
- Ajout dans les notes d'antigone :
  - « mon oncle » confirmé (Créon dit « née de ma sœur », p00104) ;
  - la seconde poussière est attestée (p00096), le résumé n'en retient qu'une, ce qui ne contredit rien ;
  - la parenté de Créon avec Jocaste (précision de la passe 1) n'est pas dans les pages enregistrées (Jocaste n'y est pas nommée, p00025).
- Ajout dans « Retours sur la consigne » d'une note « Vérification » sur la seconde passe.
- Aucune correction de texte : aucun fait n'est contredit par le corpus.

### 4. Contrôles

- `summary lint lot-test --checked` : 0 erreur, 0 avertissement.
- `summary mark lot-test checked` : code 0 ; l'étape reste « vérifiée ».
- Contrôle des fuites : Dart disponible (`/opt/flutter/bin/dart`). `list_name_leaks.dart` renvoie « Aucune fuite de titre ou d'auteur ».
- Le catalogue temporaire de contrôle est écrit dans le scratchpad, non dans `/tmp`.

### 5. Points à trancher à la relecture

1. Garder ou retirer « marché pieds nus » du `personalSummary` de *Guerre et Paix*.
2. Lizaveta, Porphyre et la prostitution de Sonia restent hors zone : à confirmer avec le texte complet, ou à retirer du résumé.
3. Les phrases des résumés qui ne figurent pas au tableau (par exemple « emmurée vivante » dans *Antigone*) n'ont pas été vérifiées une à une ; aucun passage lu ne les contredit.
4. Le fait « Le corpus ne contient pas Créon frère de Jocaste » est une précision de la passe 1 non vérifiable dans les pages enregistrées : à trancher.

### 6. Retours sur la consigne `summary-check`

- Une seconde passe sur un fichier déjà à l'étape « vérifiée » n'est pas prévue. Il faudrait une règle (refaire, compléter, ou refuser).
- La consigne demande un chemin `/tmp` pour le catalogue simulé ; j'ai utilisé le scratchpad, selon la politique de session.
- Un fait composé dont une seule moitié est attestée (« Pierre est fait prisonnier et marche avec Karataïev ») : la consigne ne dit pas s'il faut le scinder. J'ai choisi « hors zone ».
- Les « Doutes » de la passe 1 n'ont pas de section prévue pour leur issue : la consigne devrait dire où les consigner.
- Un terme confirmé par une variante (« Aléna », « Haimôn ») : la consigne devrait dire si la graphie du résumé doit être corrigée ou seulement notée.

### 7. Choix faits pendant le travail

- Message de commit : la ligne `Co-Authored-By` demandée par les consignes de session a été omise, car elle nomme le modèle et les consignes interdisent un identifiant de modèle dans un commit poussé. La ligne `Claude-Session` est présente.
- Aucune PR créée ; aucun push dans `mystitre` ni sur `claude/sleepy-archimedes-u69uu1`.

## Intégration

Décisions de la session principale (pas de relecture humaine) :

- *Guerre et Paix* : « marché pieds nus » gardé dans le `personalSummary`
  (hors zone ; Pierre marche bien pieds nus, les pieds blessés, pendant la
  retraite). « Rompt avec lui » (ambigu) devient « rompt ses fiançailles ».
- *Crime et Châtiment* : Lizaveta, Porphyre et la prostitution de Sonia gardés
  (hors zone, éléments très connus de l'œuvre).
- *Antigone* : « emmurée vivante » et la parenté Créon–Jocaste gardés (non
  contredits).
- Retours sur la consigne repris dans `/summary-draft`, `/summary-check` et
  `docs/summary_rewrite.md` (v1.21.2 de `mystitre`).
