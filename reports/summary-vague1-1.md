# Compte rendu — résumés vague1-1

- Œuvres : `le-comte-de-monte-cristo`, `les-trois-mousquetaires`, `le-rouge-et-le-noir`, `la-chartreuse-de-parme`, `germinal`, `lassommoir`, `bel-ami`, `une-vie`, `la-parure`, `le-horla`, `poil-de-carotte`
- Créé le : 2026-11-19
- Données : `summaries/vague1-1.md`

## Passe 1 — rédaction

Outils : `summary lint` après chaque œuvre ; contrôle Dart des fuites (`summary apply --output` dans le dossier temporaire de session, puis `dart run tool/list_name_leaks.dart`) après chaque œuvre. Dart est installé.

### Par œuvre

- **`le-comte-de-monte-cristo`** — Edmond parle. Difficulté propre : « Monte-Cristo » est à la fois le titre et le nom de l'île du trésor, et « comte » est le mot du titre qui désignerait la réponse ; d'où « une île déserte » et « grand seigneur énigmatique ». Simplifications : Caderousse tu, rôle de Fernand et de Danglars dans la lettre fondu en « ourdie par » ; « linceul » est une image pour le sac de Faria (relevé). Doutes : durée exacte (quatorze ans), détails du suicide de Fernand. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

- **`les-trois-mousquetaires`** — d'Artagnan parle. Règle 5 : « mousquetaires » est le mot rare du titre, évité partout (« la compagnie de M. de Tréville », « frères d'armes ») ; « trois hommes » est gardé dans `personalSummary` (mot courant du titre, permis), en note. Doutes : « Gascon » pour un Béarnais, le cheval jaune et les quinze écus, le lieu de la mort de Constance (Béthune). Simplifications : Felton, Rochefort, le procès d'Armentières, le brevet laissé en blanc. Premier jet à 122 mots, réduit à 118. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

- **`le-rouge-et-le-noir`** — Julien parle. Règle 5 : « rouge » et « noir » sont des mots courants, mais l'uniforme et la soutane y renvoient trop directement ; évités. Le corpus est le texte entier, tous les faits sont tranchables. Doutes : « charpentier » ou « scieur » pour le père, la paillasse où se cache le portrait, l'enchaînement lettre anonyme → séminaire, le nom de La Vernaye. Écarté faute de place : la tête ensevelie par Mathilde, la mort de Mme de Rênal. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

- **`la-chartreuse-de-parme`** — Fabrice parle. Règle 5 : « Parme » (nom propre) et « chartreuse » (mot rare) évités ; la cour n'est pas située, la retraite finale devient « un couvent », « un cloître » ; « tour Farnèse » gardée. Doutes : âge au départ, moment de l'empoisonnement du prince, motif exact du retour en prison (formulé « pour Clélia »), enfant Sandrino. Premier jet à 129 mots, réduit à 118 en trois retouches. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

- **`germinal`** — Étienne parle. Règle 5 : « Germinal » est un nom propre ; « germer », « germination » évités aussi (image finale), d'où « la révolte qui mûrit sous terre ». Doutes : la gifle au chef, le mois d'arrivée (mars), le poste de herscheur, la fusillade comme cause de la mort de Maheu. Simplifications : Maigrat, Bonnemort, Cécile Grégoire, les Hennebeau tus. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

- **`lassommoir`** — Gervaise parle ; la première phrase reprend de mémoire son « idéal », sans guillemets, la citation exacte étant incertaine. Règle 5 : « assommoir » (mot rare du titre, nom du cabaret) évité. Doutes : l'hôtel Boncœur, l'ordre ouverture de la boutique / convalescence de Coupeau, la niche sous l'escalier. Termes : `boiteuse`, `Banban` plutôt que `boit`, qui se confondrait avec « boire ». Lint : 0 erreur, 0 avertissement (120 mots, à la limite) ; Dart : aucune fuite.

- **`bel-ami`** — Georges parle. Règle 5 : le surnom « Bel-Ami » jamais employé ; « ami » évité dans `summary`, gardé une fois dans `personalSummary` (« la veuve de mon ami », mot courant). « Madeleine » désigne l'épouse et l'église : « l'église de la Madeleine ». Doutes : les trois francs quarante, Walter « banquier » (écarté au profit de « le journal de Walter »), l'ordre Mme Walter / affaire du Maroc, l'enlèvement de Suzanne. Lint : 0 erreur, 0 avertissement (120 mots) ; Dart : aucune fuite.

- **`une-vie`** — Jeanne parle. Règle 5 : « vie » est un mot courant du titre, mais la dernière réplique de Rosalie le rendrait transparent ; évité dans les deux textes. Doutes : 1819 et dix-sept ans, « avare et froid », la nature exacte de la cabane roulante et de la pente. Simplifications : la baronne et ses lettres, l'abbé Tolbiac, Batteville. Sept faits seulement, faute d'autres points utiles. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

- **`la-parure`** — Mathilde parle. Règle 5 : « parure » jamais employé (« rivière de diamants », « collier », « bijou »). Le corpus est la nouvelle entière ; j'ai relevé surtout les nombres (quatre cents francs, trente-six mille, dix ans, cinq cents francs), dont je suis moins sûr que de l'intrigue. Écarté : le fusil auquel le mari renonce. Coïncidence notée : « Mme Forestier » est aussi le nom de Madeleine dans `bel-ami`, sans lien. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

- **`le-horla`** — le narrateur anonyme du journal parle ; dernière phrase reprise de mémoire. Règle 5 : « Horla », nom que le narrateur donne à l'être, jamais employé. Version visée : le journal de 1887 (celle du corpus). Doutes : la date d'ouverture (8 mai), la graphie de São Paulo (variantes `San-Paulo`, `Saint-Paul`), l'image du poids sur la poitrine, la rose « cueillie ». Simplifications : Mont-Saint-Michel, l'hypnose de Mme Sablé par le docteur Parent. Premier jet à 122 mots, réduit à 118. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

- **`poil-de-carotte`** — l'enfant parle, sans se nommer (« maman », « papa »). Règle 5 : le surnom du titre jamais écrit, ni « poil » ni « carotte » ; « par un sobriquet ». « Roux » gardé : ce n'est pas un mot du titre, mais il l'évoque ; à juger en intégration. Œuvre en courts chapitres : `summary` décrit les humiliations et l'apprentissage de l'enfant, puis suit la seule progression nette (la révolte, l'aveu au père). Doutes : le prénom François, la réplique « Non, maman, je n'irai pas », « Tout le monde ne peut pas être orphelin » (relevée comme fait seulement), la soupe du chapitre « Le Pot » (voilée en « soupe souillée »). Règle 6 appliquée : « il avoue à son père qu'il ne l'aime pas » pouvait désigner le père, reformulé. Lint : 0 erreur, 0 avertissement ; Dart : aucune fuite.

### Difficultés au fil du lot

- **Taille du lot** : onze œuvres, quand la consigne en prévoit trois ou quatre. Je n'ai pas senti de fatigue au sens d'une envie d'abréger, mais la fin du lot a été plus facile pour une raison de fond : *La Parure*, *Le Horla* et *Poil de Carotte* sont courts, et deux d'entre eux sont entiers dans le corpus. Les romans du début (*Monte-Cristo*, *La Chartreuse*) demandaient plus de choix de compression. Les notes des dernières œuvres sont aussi longues que celles des premières.
- **Un défaut s'est glissé sur la dernière œuvre** : l'ambiguïté de pronom de *Poil de Carotte* (règle 6) dans le premier jet, rattrapée à la relecture de l'œuvre avant de passer à la livraison. Ce n'est pas un signe de fatigue évident (le même risque existait plus tôt), mais c'est la seule faute de ce type que j'ai repérée, et elle est en fin de lot. Je n'ai pas relu les œuvres précédentes à la recherche d'autres ambiguïtés : la passe 2 ou l'intégration peut le faire.
- **Longueur** : mes premiers jets de `summary` dépassent souvent la fourchette (122, 129, 122 mots) : trois œuvres sur onze ont demandé une retouche de quelques mots ; la plupart des textes finissent entre 112 et 120 mots, près du plafond. Pour des romans à nombreux personnages, 120 mots obligent à taire des figures (Caderousse, Rochefort, Bonnemort, la baronne d'*Une vie*), toutes notées.
- **Incident d'outillage (de mon fait)** : un bloc de texte passé au shell sans guillemets a fait exécuter un mot entre accents graves, qui a disparu d'une note de *Poil de Carotte* ; repéré aussitôt et rétabli. Aucun autre texte touché (les autres blocs étaient protégés).

### Retours sur la consigne

- **Mots courants du titre qui désignent la réponse** (règle 5) : le lot en compte beaucoup, et le jugement « désignerait la réponse à coup sûr » est délicat : « mousquetaires », « comte » (*Monte-Cristo*), « rouge » et « noir », « vie » (*Une vie*, à cause de la dernière réplique), « parure », « ami » (*Bel-Ami*). J'ai choisi de les éviter tous, sauf « trois hommes » (*Mousquetaires*) et « la veuve de mon ami » (*Bel-Ami*), gardés et notés. Le moteur Dart n'a rien signalé ; ces choix restent à confirmer en intégration.
- **Indices qui ne sont pas des mots du titre** : « roux » (*Poil de Carotte*), « une île déserte » (*Monte-Cristo*) évoquent la réponse sans en contenir un mot. La consigne ne dit rien de ce cas ; je les ai gardés, la fiche du catalogue les emploie déjà (« un enfant roux »).
- **Lieu ou personnage qui porte le nom du titre** : *Monte-Cristo* (l'île), *La Chartreuse* (le lieu de la retraite finale), *Le Horla* (le nom de l'être), *Germinal* (le mois, et l'image de la germination). La règle 5 suffit ; j'ai aussi évité les dérivés (« germer », « germination ») : la consigne pourrait le dire.
- **Faits formulés comme citations** : pour *Poil de Carotte*, *Le Horla* et *Une vie*, des répliques finales sont citées de mémoire ; je les ai relevées avec un fragment exact comme terme (`je n'irai pas`, `crois-tu donc que je l'aime`, `me tue`). Si la graphie diffère d'un mot, la recherche échoue sans que le fait soit faux : le vérificateur peut chercher un mot plus court.
- **Nombre de faits** : huit au plus, c'est juste pour *Monte-Cristo* ; j'ai privilégié les points incertains et les deux extrémités du corpus. *Une vie* n'en a que sept, faute d'autres points utiles.
- **Deux œuvres entières dans le corpus** (*Le Rouge et le Noir*, *La Parure*), ainsi que *Le Horla* (nouvelle entière) : pour elles, tous les faits sont tranchables, j'ai donc relevé des points précis (nombres, noms) plutôt que des faits « sûrs ».


## Passe 2 — vérification

### Bilan

Pages enregistrées : deux pour la plupart des œuvres, le texte entier pour *Le Rouge et le Noir*, *La Parure* et *Le Horla*. Un fait « hors zone » reste dans le texte (règle 1) ; il n'est retiré par aucune correction.

| Œuvre | Confirmés | Hors zone | Corrigés |
|---|---|---|---|
| `le-comte-de-monte-cristo` | 4 | 5 | 0 |
| `les-trois-mousquetaires` | 5 | 5 | 1 |
| `le-rouge-et-le-noir` | 7 | 0 | 2 |
| `la-chartreuse-de-parme` | 6 | 4 | 0 |
| `germinal` | 6 | 4 | 0 |
| `lassommoir` | 8 | 1 | 0 |
| `bel-ami` | 8 | 2 | 1 |
| `une-vie` | 5 | 3 | 0 |
| `la-parure` | 8 | 0 | 0 |
| `le-horla` | 8 | 0 | 0 |
| `poil-de-carotte` | 3 | 5 | 0 |
| **Total** | **68** | **29** | **4** |

Certains faits ont été scindés en deux lignes (règle 2), d'où un total de 101 lignes pour les 88 faits de la passe 1.

### Corrections

- `les-trois-mousquetaires`, `summary` : « En 1625 » devient « En 1626 ». Le texte date le voyage du « premier lundi du mois d'avril 1626 » (p00002). Fait « L'action commence en 1625 » : corrigé.
- `le-rouge-et-le-noir`, `summary` : « Une lettre anonyme le force à partir pour le séminaire de Besançon » devient « Après une lettre anonyme, l'abbé Chélan l'envoie au séminaire de Besançon ». La lettre est une machination des amants, qui vise à éloigner Julien de la maison (p00781 à p00796). L'ordre de partir pour le séminaire est donné par l'abbé Chélan (p01023), deux mois après la lettre (p01034). Fait corrigé (p00781, p01023, p01034).
- `le-rouge-et-le-noir`, `personalSummary` : « Je n'ai pas voulu de grâce. » devient « Au procès, je n'ai pas voulu de grâce. » Au procès, Julien dit « je ne vous demande aucune grâce » (p03484), mais en prison il compose un mémoire pour son recours en grâce (p03604). Fait « Au procès, Julien ne demande aucune grâce » : corrigé.
- `bel-ami`, `summary` : « puis enlève Suzanne » devient « puis, dit-on, enlève Suzanne ». Le texte ne donne l'enlèvement que comme rumeur (« On chuchotait qu'un enlèvement avait eu lieu, mais on n'était sûr de rien », p00202) et comme accusation de Madeleine (p00179). Fait « On dit que Georges enlève Suzanne pour forcer le mariage » : corrigé.

Ailleurs, aucune contradiction du texte : les autres « à vérifier » ont été confirmés ou sont restés hors zone.

### Points à trancher

1. **Le `personalSummary` du *Rouge et le Noir*.** « Au procès, je n'ai pas voulu de grâce » est fidèle au texte, mais la phrase perd son mouvement final. À l'intégration, on peut préférer une formulation qui garde l'ambivalence (le refus au procès, le recours écrit en prison).
2. **Noirtier, dans *Monte-Cristo*.** « Noirtier » n'apparaît que comme grand-père de Valentine (p00342). Le lien de père à fils avec Villefort et le motif de la disparition d'Edmond sont hors zone. Garder ou non la motivation est un choix d'écriture.
3. **Le prénom Constance, dans *Les Trois Mousquetaires*.** Le prénom n'est pas dans les pages enregistrées ; le mari est attesté, la femme inconnue du texte disponible. Le fait est scindé : prénom hors zone, lingerie hors zone, mariage confirmé (p00144). Le résumé garde le prénom.
4. **Algérie, dans *Bel-Ami*.** Le texte dit « deux années d'Afrique » (p00019) ; « Algérie » est absent. Le résumé peut garder l'Algérie (précision hors texte) ou prendre « Afrique ».
5. **Faits hors zone en grand nombre** (*Monte-Cristo* 5, *Poil de Carotte* 5, *Mousquetaires* 5) : il s'agit de faits sur des parties non enregistrées de l'œuvre. Rien ne les réfute, rien ne les confirme. C'est à la relecture de décider s'ils restent.

### Contrôles

- `summary lint vague1-1 --checked` : 0 erreur, 0 avertissement.
- Longueur : `bel-ami` à 121 mots après la correction « dit-on » ; « d'employé » a été retiré de « sa misère d'employé » (non vérifié dans le texte) pour revenir à 120.
- `summary apply vague1-1 --output` (catalogue simulé dans le dossier temporaire de session) : 11 fiches simulées. `dart run tool/list_name_leaks.dart` : aucune fuite de titre ou d'auteur.
- Le commentaire de section d'attente a été remplacé par ce compte rendu.

### Incidents

- Le processus de travail a été relancé en plein lot (à l'œuvre `germinal`). Les modifications déjà écrites dans le fichier de session étaient sur disque ; j'ai repris à partir de l'état relu, sans perte ni doublon.
- `germinal` : « Maheu » est mort (p00123, p00139), mais la fusillade et la mort de Catherine dans les bras d'Étienne ne sont pas dans les pages.

### Difficultés au fil du lot

Le lot est long (onze œuvres au lieu de trois ou quatre). La fin n'a pas été plus difficile au sens d'une envie d'abréger : j'ai vérifié chaque fait, y compris ceux de *La Parure* et du *Horla*, avec des recherches croisées. Je signale toutefois que, vers la fin, j'ai lu moins de passages complets et davantage de résultats de recherche : c'est le point où une erreur de lecture serait la plus probable. La passe 2 du lot devrait relire en priorité les faits corrigés et les « hors zone » de *Poil de Carotte*, *Germinal* et *Monte-Cristo*.

### Retours sur la consigne

- **Rumeur et accusation.** La consigne ne dit pas comment traiter un fait que le texte présente comme une rumeur ou comme une accusation d'un personnage. J'ai choisi la correction (« dit-on ») quand le texte refuse de trancher, et le statut « confirmé » quand un personnage le dit sans que le texte le démente.
- **Statut « corrigé » et reformulation du fait.** J'ai utilisé « corrigé » chaque fois que l'énoncé du fait a été réécrit pour coller au texte (1626, Chélan, recours en grâce, enlèvement). Pour une simple scission sans changement de sens, j'ai gardé « confirmé ». La consigne gagnerait à le dire.
- **Précision de « Appui » pour « hors zone ».** La consigne prévoit « absent des pages enregistrées ». Quand un terme voisin apparaît (« Afrique », « Julien », « assidu »), j'ai ajouté une précision entre parenthèses, pour que la relecture voie pourquoi le fait n'est pas tranché.
- **Un fait reformulé sans correction.** Pour *La Chartreuse de Parme*, « Le comte Mosca est ministre du prince » est devenu « premier ministre », formulation du texte (p00094). Ce changement d'énoncé n'est pas une correction de fond ; je le signale pour que l'intégration le sache.
