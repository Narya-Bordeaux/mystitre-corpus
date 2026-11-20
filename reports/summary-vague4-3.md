# Compte rendu — résumés vague4-3

- Œuvres : `la-veritable-histoire-dah-q`, `la-chair-comme-tapis-de-priere`, `zhuangzi`, `le-pavillon-aux-pivoines`, `notes-de-chevet`, `la-sente-etroite-du-bout-du-monde`, `les-suicides-damour-a-sonezaki`, `je-suis-un-chat`, `rashomon`, `kojiki`
- Créé le : 2026-11-20
- Données : `summaries/vague4-3.md`

## Passe 1 — rédaction

### Mise en route

- Branche `claude/summary-vague4-3-draft` créée depuis `claude/gracious-archimedes-fj4bg2` ; `summary init` sans refus pour les dix œuvres.
- Deux œuvres sans texte dans le corpus : `les-suicides-damour-a-sonezaki` et `kojiki` ; trois avec deux pages choisies seulement (`la-chair-comme-tapis-de-priere`, `zhuangzi`, `le-pavillon-aux-pivoines`).
- Lot entièrement asiatique (chinois et japonais) : les termes des faits sont donnés en caractères (traditionnels, avec la variante simplifiée quand elle diffère), ce qui rend ma graphie moins sûre que pour une langue européenne.
- Contrôle des fuites : Dart est présent ; `list_name_leaks.dart` lancé après chaque œuvre sur le catalogue simulé.

### `la-veritable-histoire-dah-q`

- Qui parle : le héros, avec sa logique de « vainqueur » ; il ne raconte pas sa mort, seulement le cercle mal tracé.
- Règle 5 : le nom du héros est le titre ; périphrase (« un journalier sans terre ni toit ») et aucun nom dans « Mon histoire ».
- Doutes principaux : la mention explicite de « 1911 » (je me souviens d'une date en ère Xuantong) ; la nature exacte de la punition après l'épisode de Wu Ma (« puni », large) ; l'ordre nonne puis Wu Ma.
- Simplifications : Wang le Barbu, Petit D et le « Faux Diable étranger » tus ; séjour en ville et recel tus.
- Premier jet à 127 mots, ramené à 119 par des resserrements de formule, sans retirer d'événement.
- Lint sans erreur ; aucune fuite.


### `la-chair-comme-tapis-de-priere`

- Qui parle : Weiyangsheng, après sa conversion (d'où « je payais mes propres dettes »).
- Règle 5 : « tapis de chair » reconstitue un titre accepté ; « tapis » n'est pas employé, et la scène du dialogue initial avec le moine reste allusive.
- Doutes principaux : la graphie de Yanfang et le métier de Quan Laoshi ; les modalités de la vengeance (domestique chez le beau-père, fuite de Yuxiang) ; le suicide de Yuxiang par pendaison, que l'ancien résumé ne mentionnait pas ; la castration finale, écrite « se mutile » ; le nom religieux Wanshi.
- Simplifications : les autres conquêtes (trois femmes d'une même famille) et le beau-père (« Porte de fer » dans mon souvenir) sont tus.
- Œuvre érotique : j'ai gardé la greffe d'un organe de chien, sobrement, parce qu'elle est le ressort central et la marque de l'œuvre.
- Lint sans erreur (105 et 83 mots) ; aucune fuite.

### `zhuangzi`

- Œuvre sans intrigue : contenu (fables les plus connues), organisation (trois ensembles de chapitres), thèmes, puis le dernier chapitre en guise de « fin ».
- Qui parle : la voix du maître, sans se nommer, qui reprend à la première personne les anecdotes où il est lui-même acteur (papillon, tortue, mort de sa femme).
- Règle 5 : titre et auteur portent le nom du maître ; « un maître », « le maître » partout.
- Doutes principaux : le nombre exact de chapitres (« une trentaine ») ; l'identité de l'oiseau qui se moque de Peng (« tourterelle ») ; l'épisode de la tortue et le roi de Chu ; le contenu exact de la revue finale.
- Seuls le début (Kun, Peng, cigale) et la revue des écoles tombent dans les deux pages du corpus ; les autres faits sont choisis parce que j'en suis moins sûr, ils resteront sans doute hors zone.
- Lint sans erreur (117 et 82 mots) ; aucune fuite.

### `le-pavillon-aux-pivoines`

- Qui parle : Du Liniang, qui traverse le rêve, la mort et le retour à la vie.
- Règle 5 : « pavillon » et « pivoines » ensemble reconstitueraient le titre ; je n'emploie aucun des deux, seulement « le jardin ».
- Doutes principaux : le prunier de la tombe ; la cachette du portrait ; l'ordre de la fin (visite de Liu à Du Bao, coups, proclamation, arbitrage impérial) ; la nature exacte de la décision de l'empereur.
- Le prologue (`標目`) et la dernière scène (`圓駕`) sont dans le corpus : les noms, le titre de premier lauréat et l'arbitrage impérial devraient s'y vérifier.
- Simplifications : précepteur Chen Zuiliang, servante Chunxiang, religieuse du sanctuaire et guerre contre les Jin tus.
- Lint sans erreur (114 et 68 mots) ; aucune fuite.

### `notes-de-chevet`

- Œuvre sans intrigue : ouverture sur les saisons, trois sortes de notes (listes, réflexions, souvenirs de cour), un épisode emblématique (la neige du mont Xianglu), la postface.
- Qui parle : la narratrice, dame d'honneur. Cas limite : sa dernière phrase évoque le papier reçu et ce qu'elle y a écrit ; c'est son geste dans l'histoire (la postface le raconte), non un mot qui désigne l'œuvre. À juger en passe 2.
- Règle 5 : ni « chevet » ni « oreiller » dans les textes ; « notes » est un mot courant du titre, employé seul.
- Doutes principaux : le nom « Teishi », que le texte ne donne peut-être pas (il dit sans doute « Sa Majesté ») ; qui relève le store ; qui offre le papier dans la postface ; l'heure de l'hiver.
- Le summary tient juste à 120 mots.
- Lint sans erreur ; aucune fuite.

### `la-sente-etroite-du-bout-du-monde`

- Journal de voyage : je l'ai traité comme un récit (départ, étapes, fin), avec les poèmes les plus célèbres comme événements.
- Qui parle : le poète voyageur, qui reprend l'ouverture et le dernier poème.
- Règle 5 : « la sente étroite », « le chemin étroit » évités ; ni le nom de l'auteur ni son nom de plume.
- Doutes principaux : le lieu où Sora le quitte (Yamanaka dans mon souvenir, écrit « en chemin ») ; l'année écrite ou non dans le texte ; la cession de la cabane ; le jeu de mots final sur la palourde.
- Choix : « haïkus », anachronique mais clair pour le joueur.
- Lint sans erreur (107 et 77 mots) ; aucune fuite.

### `les-suicides-damour-a-sonezaki`

- Aucun texte dans le corpus : tout est de mémoire ; les huit faits portent sur ce dont je suis le moins sûr et resteront hors zone. Termes japonais donnés au jugé.
- Qui parle : Tokubei, pendant la marche de la dernière nuit.
- Règle 5 : « Sonezaki » évité (« le bois d'un sanctuaire ») ; « suicide » non employé.
- Désaccord avec l'ancien résumé : « commerce d'huile » pour l'oncle de Tokubei ; dans mon souvenir l'oncle vend de la sauce de soja et c'est Kuheiji le marchand d'huile. Relevé comme fait.
- Doutes principaux : la dot reçue par la belle-mère ; l'accusation de faux sceau ; l'ordre des gestes dans la scène du pied ; l'arbre et l'arme de la mort.
- Lint sans erreur (111 et 68 mots) ; aucune fuite.

### `je-suis-un-chat`

- Qui parle : le chat narrateur. Je n'écris pas sa phrase d'ouverture, qui est le titre ; il commence par l'absence de nom, et se désigne par « mon espèce ».
- Règle 5 : « chat » (mot courant du titre) employé à la troisième personne dans `summary` seulement.
- Doutes principaux : l'adoption « par hasard » ; la thèse de Kangetsu et ses billes de verre ; la part des Kaneda dans le harcèlement par les collégiens ; l'origine de la bière.
- Simplifications : Tōfū, Dokusen, Sampei, la chatte Mikeko et le chat Kuro tus ; le sort de la fille Kaneda tu.
- Lint sans erreur (114 et 73 mots) ; aucune fuite.

### `rashomon`

- Qui parle : le domestique ; il s'arrête au vol, sans raconter sa disparition.
- Règle 5 : le titre est le nom de la porte ; « une grande porte en ruine », « la porte ».
- Doutes principaux : les fléaux exacts qui ravagent la capitale ; le moment où il tire le sabre ; la formule de l'argument de la vieille ; la fin (deux versions dans mon souvenir : « disparaît dans la nuit » vaut pour les deux).
- Règle 6 appliquée : un « lui pardonnerait » pouvait désigner la vieille ou le domestique ; reformulé en « comprendrait qu'on la dépouille à son tour ».
- Nouvelle courte et texte entier dans le corpus : tous les faits devraient être vérifiables.
- Lint sans erreur (117 et 69 mots) ; aucune fuite.

### `kojiki`

- Aucun texte dans le corpus : tout est de mémoire ; faits hors zone attendus. Termes dans la graphie phonétique de l'original, au jugé (`八俣遠呂智`, `邇邇藝`…).
- Qui parle : le compilateur, dans la voix de sa préface (ordre impérial, Hieda no Are, peine à noter la langue en caractères chinois), sans se nommer ; aucun personnage ne traverse les trois livres.
- Règle 5 : ni le titre ni le compilateur ; « choses anciennes » et « faits anciens » évités (titres acceptés).
- Doutes principaux : qui donne l'ordre (Tenmu, puis Genmei ; « l'impératrice » = Genmei) ; le lien de parenté Ninigi–Amaterasu et Ninigi–Jinmu ; la dernière souveraine (Suiko). Par prudence, je n'ai pas qualifié Susanoo de « dieu de la tempête ».
- Simplifications : Ōkuninushi, le lièvre d'Inaba, la cession du pays, Yamato Takeru tus.
- Lint sans erreur (118 et 84 mots) ; aucune fuite.

### Bilan du lot

- `summary lint vague4-3` : 0 erreur, 0 avertissement. `list_name_leaks.dart` : aucune fuite de titre ou d'auteur, sur les dix œuvres.
- Toutes les œuvres ont 8 faits : le lot est loin de mes œuvres les mieux connues, et j'ai préféré relever le maximum de points incertains plutôt que d'en laisser dans les seules notes.
- Les summary sont tous entre 105 et 120 mots ; seul le premier (Ah Q) a dépassé au premier jet (127 mots) et a été resserré sans perte d'événement.

### Difficultés au fil du lot

- Je n'ai pas senti la fin du lot plus difficile : le *Kojiki* a demandé autant de soin que le premier, et plus de notes. La difficulté tient plutôt à la nature du lot qu'à sa longueur.
- La vraie difficulté est la graphie des termes : caractères traditionnels ou simplifiés pour le chinois, graphie classique ou moderne pour le japonais (`曾良`/`曽良`, `蝉`/`蟬`, `甕`/`瓶`), noms divins écrits phonétiquement dans le *Kojiki*. J'ai donné des variantes, mais certains termes risquent de manquer par simple différence de caractère, sans que le fait soit faux.
- Ma mémoire est inégale : sûre pour *Rashōmon*, *Je suis un chat*, Ah Q et le voyage vers le Nord ; plus fragile pour *La Chair comme tapis de prière* (vengeance, mort de l'épouse) et la pièce de Chikamatsu, sans texte dans le corpus.

### Retours sur la consigne

- Titre identique au nom d'un lieu (*Rashōmon*) ou d'un maître qui est aussi l'auteur (Zhuangzi) : la règle 5 couvre ces cas ; périphrase « la porte », « le maître ».
- Titres acceptés formés de mots courants (« Le Tapis de chair », « Chronique des faits anciens », « Le Chemin étroit… ») : j'ai appliqué la limite « ne pas reconstituer un titre » aussi aux titres acceptés, ce que la consigne dit pour les mots isolés mais pas explicitement pour la reconstitution. Il serait utile de l'écrire.
- Œuvre dont la phrase d'ouverture est le titre (*Je suis un chat*) : « Mon histoire » ne peut pas la reprendre ; le chat commence par la phrase suivante. Cas non prévu, choix simple.
- Œuvre sans personnage continu (*Kojiki*, *Notes de chevet*) : la voix de la préface ou de la postface (le compilateur, la dame d'honneur) permet de garder le test « dit dans son histoire » ; mais ces voix évoquent leur propre écriture (« j'ai mis par écrit », « sur le papier »). J'ai jugé que c'est un geste vécu, non un mot qui désigne l'œuvre ; la consigne pourrait trancher ce cas.
- Termes en langue originale : une indication sur la graphie attendue (celle de l'édition Wikisource) aiderait ; à défaut, je donne les deux.

## Passe 2 — vérification

### Bilan

| Œuvre | Confirmés | Hors zone | Corrigés |
|---|---|---|---|
| `la-veritable-histoire-dah-q` | 8 | 0 | 0 |
| `la-chair-comme-tapis-de-priere` | 6 | 1 | 1 |
| `zhuangzi` | 3 | 5 | 0 |
| `le-pavillon-aux-pivoines` | 7 | 1 | 0 |
| `notes-de-chevet` | 6 | 2 | 0 |
| `la-sente-etroite-du-bout-du-monde` | 7 | 0 | 1 |
| `les-suicides-damour-a-sonezaki` | 0 | 8 | 0 |
| `je-suis-un-chat` | 8 | 0 | 0 |
| `rashomon` | 7 | 0 | 1 |
| `kojiki` | 0 | 8 | 0 |
| **Total** | **52** | **25** | **3** |

Les huit faits de *Les Suicides d'amour à Sonezaki* et du *Kojiki* sont hors zone faute de source : aucune fiche `sources/<id>.json` dans le corpus.

### Corrections

- `la-chair-comme-tapis-de-priere`, fait 8 : « reçoit le nom de Wanshi » devient « se donne le nom de Wanshi » (p00010 : 自取法名).
- `la-sente-etroite-du-bout-du-monde`, fait 7 : « Le voyage s'achève à Ōgaki » devient « Le voyage atteint Ōgaki, où ses amis le rejoignent » (p00171 à p00172 : le texte repart pour Ise).
- `rashomon`, fait 8 : « Il disparaît dans la nuit » devient « Il s'élance sous la pluie vers la ville pour voler » (p00039) ; le résumé dit désormais « court voler en ville sous la pluie ».
- `rashomon`, résumé : « sabre au clair » devient « puis tire son sabre » (p00027 : le sabre sort après que le domestique a repoussé la vieille). « Convaincu, » est retiré pour rester sous 120 mots.

### Points à trancher

- *Ah Q* : la non-participation au pillage et la perte d'embauche générale ne sont pas attestées ; le texte dit seulement l'interdiction d'entrer chez les Zhao et de réclamer le salaire (p00128, p00130).
- *La Chair comme tapis de prière* : « lettré austère » (le père de Yuxiang est appelé 鐵扉道人, « un Taoïste ») ; « marchand » pour Quan Laoshi ; la pendaison de Yuxiang (absente des deux pages).
- *Zhuangzi* : « une trentaine de chapitres » ; « tourterelle » comme traduction de 鷽.
- *Notes de chevet* : le sujet du store (le causatif porte sur le treillis, pas sur le store) ; le nom « Teishi » n'apparaît que dans une glose éditoriale 〈定子〉 ; le « petit matin » d'hiver n'est pas dans la phrase d'ouverture ; pas de postface dans le texte, et le don de papier (p00437) est au milieu de l'œuvre, sans donateur nommé dans les pages lues ; le nombre « quelque trois cents ».
- *La Sente étroite* : l'année 1689 n'apparaît que dans la notice éditoriale (p00004) ; l'ordre Kisakata puis Kanazawa n'a pas été relevé.
- *Je suis un chat* : la cause du harcèlement (les Kaneda « le font harceler ») ; la bière « laissée par les invités ».
- *Les Suicides d'amour à Sonezaki* et *Kojiki* : rien n'a pu être vérifié. Le désaccord avec l'ancien résumé (commerce d'huile) reste ouvert ; les doutes sur le *Kojiki* aussi.

### Contrôles

- `summary lint vague4-3 --checked` : 0 erreur, 0 avertissement (après la correction de longueur de *Rashōmon*, 120 mots).
- `summary apply vague4-3 --output` : catalogue simulé écrit dans le dossier temporaire ; 10 fiches changées.
- `dart run tool/list_name_leaks.dart --catalogue=…` : « Aucune fuite de titre ou d'auteur. » (le contrôle s'est exécuté avec le Dart de l'environnement, sans avertissement d'absence).
- `summary mark vague4-3 checked` : lancé après l'écriture de cette section.

### Difficultés au fil du lot

Oui, la fin du lot m'a paru plus difficile. Les derniers livres (*Notes de chevet*, *Je suis un chat*, *Rashōmon*) ont demandé plus de lectures de passages, et une formule de la rédaction (le sabre) n'a été corrigée qu'à la relecture de la fin. Le contexte chargé a pu disperser mon attention : deux œuvres sans source ont aussi été traitées comme telles sans les tenir pour vérifiées. Je signale ce risque plutôt que de le taire.

### Retours sur la consigne

- Cas non prévu : œuvre sans fiche dans `sources/` (*Les Suicides d'amour à Sonezaki*, *Kojiki*). La consigne ne dit pas quoi écrire ; j'ai noté « aucune source dans le corpus » et « hors zone », sans parler de corrections possibles. Une règle explicite serait utile.
- Gloses et notices éditoriales (Wikisource) : un nom ou une date peut ne figurer que dans la notice ou une glose. Je les ai traitées comme hors du texte de l'œuvre et je l'ai dit au cas par cas. La consigne pourrait trancher.
- Variantes graphiques : 鎗斃 pour 槍斃 et 學鳩 pour 鷽 ont été acceptées comme confirmations. La consigne l'admet pour les noms ; elle pourrait le préciser pour les mots courants.
- Limite de 120 mots : une correction peut la dépasser. J'ai dû retirer un mot ailleurs ; une règle d'équilibre le dirait.
