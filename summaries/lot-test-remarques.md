# Remarques — vérification de la session lot-test (passe 2, Haiku)

Date : 2026-11-19
Branche de travail : `claude/lot-test-check-haiku` (dépôt `mystitre-corpus`, commit `9a246a5`)
Fichier vérifié : `summaries/lot-test.md`

## 1. État de départ

- Le fichier n'était pas à l'étape « rédigée » comme annoncé : il était déjà à l'étape « vérifiée ».
- La branche `claude/sleepy-archimedes-u69uu1` contenait déjà un commit « Résumés lot-test : vérification » (`418fad0`).
- J'ai donc fait une seconde vérification indépendante, à partir du texte du corpus.
- `origin/claude/sleepy-archimedes-u69uu1` n'existait pas comme référence distante après un clone superficiel : j'ai créé la branche de travail à partir de `FETCH_HEAD`.

## 2. Résultats par œuvre

### guerre-et-paix — 6 confirmés, 3 hors zone, 0 corrigé
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

### crime-et-chatiment — 4 confirmés, 3 hors zone, 0 corrigé
- Confirmés :
  - Raskolnikov, ancien étudiant pauvre (p00003, p00018) ;
  - Aliona Ivanovna, usurière, graphie du corpus « Aléna » (p00032) ;
  - condamnation à huit ans de bagne (p00065, p00067) ;
  - Sonia suit Raskolnikov en Sibérie (p00081) et l'Évangile de l'épilogue (p00095).
- Hors zone :
  - meurtre de Lizaveta (la sœur n'apparaît que comme « Élisabeth », p00025) ;
  - Porphyre Petrovitch (absent) ;
  - prostitution de Sonia (absente ; l'épilogue ne dit pas comment elle vit).

### antigone — 7 confirmés, 0 hors zone, 0 corrigé
- Créon interdit d'ensevelir Polynice (p00016, p00048).
- Ismène refuse d'aider sa sœur (p00021-p00027).
- Poussière sur le corps, découverte par un garde (p00063, p00065).
- Lois non écrites (p00102).
- Hémon est le fiancé d'Antigone (p00150, p00168, p00300).
- Tirésias avertit Créon (divinateur, p00246-p00270).
- Antigone se pend (p00300), Hémon se tue (p00293-p00295), Eurydice se frappe (p00312).

### au-bord-de-leau — 7 confirmés, 0 hors zone, 0 corrigé
- Hong Xin libère les esprits, envoyé contre une épidémie (p00016, p00019, p00037-p00039).
- 36 étoiles célestes + 72 étoiles terrestres = 108 (p00009) ; « 一百單八 » n'apparaît pas littéralement.
- Repaire des marais du mont Liang (p00011, p00066).
- Song Jiang chef (p00044, p00066, p00087).
- Amnistie et guerre contre Fang La (p00043, p00076, p00081).
- Song Jiang empoisonné par un vin envoyé par la cour (p00063, p00066).
- Li Kui, Wu Yong et Hua Rong meurent après Song Jiang (p00068, p00075).

## 3. Modifications apportées au fichier `summaries/lot-test.md`

- Ajout au tableau de guerre-et-paix : « Pierre marche pieds nus pendant la retraite », hors zone (`босиком` absent ; `босой` ne désigne que le pied de Touchine, p01938).
- Remplacement de la note « Doute » sur les pieds nus par une note « Vérification ».
- Ajout dans les notes d'antigone :
  - « mon oncle » confirmé (Créon dit « née de ma sœur », p00104) ;
  - la seconde poussière est attestée (p00096), le résumé n'en retient qu'une, ce qui ne contredit rien ;
  - la parenté de Créon avec Jocaste (précision de la passe 1) n'est pas dans les pages enregistrées (Jocaste n'y est pas nommée, p00025).
- Ajout dans « Retours sur la consigne » d'une note « Vérification » sur la seconde passe.
- Aucune correction de texte : aucun fait n'est contredit par le corpus.

## 4. Contrôles

- `summary lint lot-test --checked` : 0 erreur, 0 avertissement.
- `summary mark lot-test checked` : code 0 ; l'étape reste « vérifiée ».
- Contrôle des fuites : Dart disponible (`/opt/flutter/bin/dart`). `list_name_leaks.dart` renvoie « Aucune fuite de titre ou d'auteur ».
- Le catalogue temporaire de contrôle est écrit dans le scratchpad, non dans `/tmp`.

## 5. Points à trancher à la relecture

1. Garder ou retirer « marché pieds nus » du `personalSummary` de *Guerre et Paix*.
2. Lizaveta, Porphyre et la prostitution de Sonia restent hors zone : à confirmer avec le texte complet, ou à retirer du résumé.
3. Les phrases des résumés qui ne figurent pas au tableau (par exemple « emmurée vivante » dans *Antigone*) n'ont pas été vérifiées une à une ; aucun passage lu ne les contredit.
4. Le fait « Le corpus ne contient pas Créon frère de Jocaste » est une précision de la passe 1 non vérifiable dans les pages enregistrées : à trancher.

## 6. Retours sur la consigne `summary-check`

- Une seconde passe sur un fichier déjà à l'étape « vérifiée » n'est pas prévue. Il faudrait une règle (refaire, compléter, ou refuser).
- La consigne demande un chemin `/tmp` pour le catalogue simulé ; j'ai utilisé le scratchpad, selon la politique de session.
- Un fait composé dont une seule moitié est attestée (« Pierre est fait prisonnier et marche avec Karataïev ») : la consigne ne dit pas s'il faut le scinder. J'ai choisi « hors zone ».
- Les « Doutes » de la passe 1 n'ont pas de section prévue pour leur issue : la consigne devrait dire où les consigner.
- Un terme confirmé par une variante (« Aléna », « Haimôn ») : la consigne devrait dire si la graphie du résumé doit être corrigée ou seulement notée.

## 7. Choix faits pendant le travail

- Message de commit : la ligne `Co-Authored-By` demandée par les consignes de session a été omise, car elle nomme le modèle et les consignes interdisent un identifiant de modèle dans un commit poussé. La ligne `Claude-Session` est présente.
- Aucune PR créée ; aucun push dans `mystitre` ni sur `claude/sleepy-archimedes-u69uu1`.
