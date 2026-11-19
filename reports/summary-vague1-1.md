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

<!-- Bilan (tableau confirmés / hors zone / corrigés par œuvre), corrections, points à trancher, contrôles et incidents, difficultés au fil du lot, retours sur la consigne. -->
