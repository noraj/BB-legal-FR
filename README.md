# Bug Bounty légal en FRANCE

> Quelques conseils autour des obligations légales, fiscales et juridiques pour la pratique du Bug Bounty en France

:warning: Les conseils mentionnés ici sont simplement des travaux de collecte d'informations sur le sujet et n'ont en aucun cas une valeur juridique, leur exactitude n'est pas garantie et ne sauraient en aucun cas impliquer ma responsabilité. Nul n'est censé ignorer la loi, renseignez-vous et vérifiez tout ce qui est écrit ici. D’ailleurs, les seuils et barèmes sont susceptibles d'être révisés tous les ans.

## TL;DR FAQ

> Débusquons ensemble les préjugés incorrects

- _Je peux faire du Bug Bounty sans créer d'entreprise._
  + **Faux**
- _Je suis pentester, je peux faire du Bug Bounty sans prévenir mon employeur._
  + **Faux**
- _Je peux faire du Bug Bounty sans déclarer ce que je gagne._
  + **Faux**
- _Une simple déclaration comme revenus exceptionnels liés à une activité non professionnelle suffit._
  + **Faux**

## Étude préliminaire

Commençons par jeter un œil à la [FAQ de YesWeHack](https://www.yeswehack.com/fr/entreprises/aide-faq/) (lient mort, il y a tout de même une [page facturation](https://helpcenter.yeswehack.io/billing-information) dans leur base de connaissances) :

> ## Quelles sont les obligations légales, fiscales et sociales d’un hunter ?
>
> Si son activité auprès de la plateforme ou de plusieurs plateformes est professionnelle (exercice régulier et lucratif), le Hunter doit disposer d’un statut légal pour son activité, qui peut s’exercer de manière individuelle (Autoentrepreneur) ou en société (EURL, SARL). À défaut d’inscription à un régime juridique adéquat, le Hunter risque d’être poursuivi pour dissimulation d’activité.
>
> Le Hunter doit se rapprocher des autorités administratives compétentes (URSSAF, administration fiscale) afin de connaître les obligations relatives à son activité et procéder à son inscription et aux diverses formalités administratives. Pour plus d’information, voir le site de l’URSSAF rubrique « Indépendant » : https://www.urssaf.fr/portail/home/independant.html
>
> Au-delà d’un certain niveau de revenu tiré de son activité sur la plateforme ou de plusieurs plateformes, le Hunter pourra être assujetti à la TVA et en conséquence devra facturer, collecter et reverser à l’administration fiscale la TVA afférente à chaque opération. L’administration fiscale applique une franchise de TVA suivant le Chiffre d’affaires annuel du Hunter (33.200 euros franchise en base applicable en 2019).
>
> Dès lors qu’il est assujetti, le Hunter doit obligatoirement émettre une facture conforme à la réglementation fiscale notamment en y mentionnant son N° de TVA. Le N° de TVA est par principe attribué automatiquement au moment où le hunter adopte un statut professionnel.
>
> Les mentions légales obligatoires sur la facture sont prévues à l’article 441-3 du code de commerce et aux articles article 242 nonies et 242 nonies A du code général des impôts – annexe 2.
>
> De plus, toute source de revenus doit faire l’objet d’une déclaration fiscale au titre de l’impôt sur le revenu et le cas échéant, au titre de l’impôt sur les sociétés en fonction du statut légal adopté.
>
> Afin de connaître ses obligations, le Hunter devra se rapprocher de son centre des impôts pour connaître les formalités applicables à sa situation et au statut qu’il aura choisi.

Bon là c'est un peu fouillis, mais on comprend vite qu'on va devoir créer une entreprise, déclarer et payer des impôts et qu'il y a des histoires de seuils et de TVA.

Maintenant, regardons-les [CGU de Yogosha](https://yogosha.com/fr/conditions-generales-dutilisation/) (lien mort, il y a maintenant des [CGV](https://26653563.fs1.hubspotusercontent-eu1.net/hubfs/26653563/Legal%20documents%20available%20on%20Yogosha%20website/%5BFran%C3%A7ais%5D%20CGV%20Yogosha%20Plateforme%20V3.1_2023.pdf)) :

> ## 3.1 Création et utilisation du Compte Utilisateur
>
> Le Chercheur s’engage à fournir, lors de la création et de l’utilisation de son Compte Utilisateur, son numéro de TVA s’il y est assujetti et s’il est résident fiscal en France ou intracommunautaire ainsi qu’une attestation de résidence fiscale ou à défaut, une déclaration sur l’honneur attestant du lieu de son domicile fiscal. Dans le cas où le chercheur serait domicilié ou établi en dehors de l’UE, il s’engage à fournir une preuve de son activité professionnelle indépendante et déclarée aux autorités fiscales de sa résidence fiscale.
>
> Pour les besoins des cotisations sociales des chercheurs domiciliés en France, il sera demandé au Chercheur de fournir à Yogosha, chaque semestre, une attestation de vigilance ou d’auto-entrepreneur délivrée par l’URSSAF.

Ici ça parle TVA, activité professionnelle, autorités fiscales, auto-entrepreneur, URSSAF.

Continuons :

> 5.1.1 Respect de la réglementation applicable en matière comptable, fiscale et sociale
>
> Le Chercheur s’engage à accéder et utiliser la Plateforme dans le strict respect de la réglementation applicable en matière comptable, fiscale et sociale, notamment s’agissant des obligations d’immatriculation et de déclaration auprès de l’administration fiscale et les organismes de sécurité sociale dont il dépend.

Bon là c'est clairement comme le dernier paragraphe de la FAQ de YesWeHack: "Vous avez des devoirs/obligations, maintenant débrouillez vous !". Normalement à ce stade vous êtes confus, vous n'avez pas compris grand-chose, vous ne savez toujours pas ce que vous devez ou pouvez faire et vous n'avez pas plus de réponses qu'au départ, mais plutôt des questions supplémentaires.

Vous êtes tenté de vous dire "Bon ! Ça a l'air compliqué et rébarbatif tout ça, il y a peut-être moyen de passer à côté". Et bien non les plateformes déclarent tout et si vous n'êtes pas dans les clous, il y aura bientôt une grosse différence entre les informations que les autorités fiscales auront reçues et ce que vous aurez (ou pas) déclaré.

> ## 7.3 Responsabilités administratives et fiscales de Yogosha concernant les chercheurs dont la résidence fiscale est en France
>
> Yogosha s’astreint aux obligations suivantes (article 242 bis du CGI) s’agissant des chercheurs résidant en France :
>
> - informer les chercheurs, à l’occasion de chaque transaction réalisée avec le Client, des obligations fiscales et sociales leur incombant ;
> - mettre à leur disposition un lien électronique vers les sites des administrations (DGFIP et URSSAF) permettant de se conformer à ces obligations :
> - sur http://www.impots.gouv.fr, concernant les obligations fiscales, lien ci-dessous https://www.impots.gouv.fr/portail/node/10841
> - sur http://www.securite-sociale.fr, concernant les obligations sociales, lien ci-dessous :http://www.securite-sociale.fr/Vos-droits-et-demarches-dans-le-cadre-des-activites-economiques-entre-particuliers-Article-87
>
> La Plateforme s’engage à fournir aux Chercheurs dont la résidence fiscale est située en France, en janvier de chaque année, un document récapitulant le montant brut des transactions dont elles ont connaissance et qu’ils ont perçu, par leur intermédiaire, au cours de l’année précédente.
>
> Yogosha s’engage chaque année, avant le 15 mars, à faire certifier par un tiers indépendant le respect, au titre de l’année précédente, de ces obligations et communiquer ce certificat à l’administration fiscale par voie électronique.

## FAQ détaillée

### _Je peux faire du Bug Bounty sans créer d'entreprise._

**Faux**, c'est une activité exercée à titre indépendant, dans un but lucratif. Il va falloir créer une entreprise, nous reviendrons sur les différents types d'entreprises possibles par la suite.

Ref.

- [travail-emploi.gouv.fr - Les sanctions liées au travail illégal - Le travail dissimulé][1]
- [legifrance.gouv.fr - article L. 613-4 du code de la sécurité sociale][2]

### _Je suis pentester, je peux faire du Bug Bounty sans prévenir mon employeur._

**Faux**, le Bug Bounty peut facilement être catégorisé comme une activité concurrente au Pentest, c'est en tout cas le même secteur d'activité, et les deux activités peuvent partager les mêmes clients.

La loyauté empêche d'exercer une 2e activité professionnelle si elle est considérée comme concurrente. Elle est imposée par le code civil et le code pénal et souvent rappelé dans une clause spécifique du contrat de travail.

Il existe souvent dans les contrats de travail une clause d'exclusivité qui interdit au salarié d'exercer une activité professionnelle complémentaire qu'elle soit concurrente ou non. Mais dans la quasi-totalité des cas, cette clause est nulle et non applicable, car les conditions suivantes ne sont pas respectées :

- les raisons de son insertion dans le contrat de travail ou l'avenant doivent être motivées
- le périmètre de l'exclusivité de l'activité du salarié doit être précisément délimité
- la clause doit être indispensable à la protection des intérêts légitimes de l'entreprise
- la clause doit être justifiée par la nature des fonctions du salarié
- la clause doit être proportionnée au but recherché, ce qui est rappelé dans quatre arrêts du 11 juillet 2000 et par l'article L.1121-1 du Code du travail

Donc vous pouvez créer une entreprise sans l'accord de votre employeur si l'activité exercée est non concurrente, que vous n'avez pas les mêmes clients et que vous ne nuisez pas aux intérêts de votre employeur, ce qui n'est pas le cas entre Bug Bounty et Pentest.

Ref.

- [legifrance.gouv.fr - article 1104 du Code civil][3]
- [legifrance.gouv.fr - article L1222-1 du Code du travail][4]
- [legalplace.fr - L'obligation de loyauté du salarié][5]
- [captaincontrat.com - Qu'est-ce que la clause d'exclusivité dans le contrat de travail ?][6]

### _Je peux faire du Bug Bounty sans déclarer ce que je gagne._

**Faux**, à partir du moment où vous résidez en France ou que votre domicile fiscal est en France vous devez déclarer vos revenus, peu importe le montant. Cela ne veut pas forcément dire que vous allez devoir payer des impôts.

Ref.

- [economie.gouv.fr - Impôt sur le revenu : quelles sont vos obligations déclaratives ?][10]
- [impots.gouv.fr - Obligations déclaratives][11]
- [service-public.fr - Impôt sur le revenu : déclaration de revenus annuelle][12]

### _Une simple déclaration comme revenus exceptionnels liés à une activité non professionnelle suffit._

**Faux**, en aucun cas une activité à but lucratif ne rentre dans les cas prévus pour les revenus exceptionnels.
En pratique, il y a cependant une tolérance **officieuse** si le revenu est ponctuel et faible (seuil non défini) donc par exemple si vous gagnez une fois 500€ dans l'année pas besoin de créer une entreprise mais dès que vous dépasserez quelques milliers d'euros
ou mènerez cette activité de manière récurrente il vous faudra créer une entreprise.
Comme vous ne pourrez pas rattacher de manière rétroactive des revenus à votre entreprise, il faut prévoir sa création à l'avance si vous prévoyez de pratiquer la chasse aux bugs.

En résumé:

- Vous trouvez **1** bug qui représente un faible montant 1 fois dans l'année: pas besoin d'entreprise
- Dans tous les autres cas **une création d'entreprise est nécessaire**, si vous vous lancez sérieusement dans le Bug Bounty vous trouverez forcément plus d'un bug par an

Ref.

- [impots.gouv.fr - Revenus exceptionnels][13]
- [economie.gouv.fr - Quelles modalités d'imposition pour les revenus exceptionnels ?][14]
- [service-public.fr - Impôt sur les revenus exceptionnels : quelles sont les règles ?][15]

## Création d'une entreprise

Entrepreneur individuel, Micro-entrepreneur/auto-entrepreneur, ~~EIRL~~, SARL, EURL, SAS, SASU

### Créer une entreprise seul

<details>
  <summary>Périmé 2021 - EIRL</summary>
> Il existe 3 possibilités d'exercer Pour exercer une une activité en nom personnel soumise à l'impôt sur le revenu vous avez le choix entre trois statuts différents :
>
> - le statut de l'entrepreneur individuel (**EI**) ;
> - ~~le statut du **micro-entrepreneur** ;~~
> - le statut de l'Entrepreneur Individuel à Responsabilité Limitée (**EIRL**).
>
> Etre entrepreneur individuel ou en votre nom personnel signifie que vous êtes personnellement responsable sur votre patrimoine des dettes résultant de votre activité professionnelle.
>
> L'EIRL vous permet toutefois de limiter votre responsabilité par l'enregistrement d'une déclaration d’affectation d'une partie de votre patrimoine (DAP) à votre activité professionnelle.
>
> Les principaux avantages de l'activité exercée en nom personnel résident dans la facilité de création et la souplesse de gestion.

Ref.

- [impots.gouv.fr - Exercice d'une activité en nom personnel][18] (voir le tableau comparatif des 3 status)
- [impots.gouv.fr - Avantages et inconvénients des entreprises individuelles][19]

Les 2 status sont des entreprises individuelles en nom propre où l'identité de l'entreprise correspond à celle de son dirigeant (le nom de l'entreprise comportera votre nom),
et elle ne peut être constituée que d'une seule personne physique (vous, pas d'associés ou de salariés).
La micro-entreprise est un un régime spécial de l'entreprise individuelle qui bénéficie d'un régime simplifié.
Le gros défaut de la micro-entreprise reste la responsabilité, le dirigeant est indéfiniment responsable des dettes de son entreprise sur ses biens propres.
L'Entrepreneur Individuel à Responsabilité Limitée (EIRL) permet à l’entrepreneur de protéger ses biens personnels, en créant un patrimoine affecté à son activité professionnelle distinct de son patrimoine privé. C'est une entreprise individuelle qui peut aussi profiter du régime simplifié de la micro-entreprise.
L'autre différence avec l'EIRL c'est que le dirigeant peut opter pour l'IS (impôt sur les sociétés) au lieu de l'IR (impôt sur le revenu) et donc potentiellement bénéficier de déduction de rémunération dans les comptes de l'entreprise.
Légèrement plus compliqué l'EIRL semble plus intéressante que la micro-entreprise pour limiter sa responsabilité.
</details>

> La [loi n°2022-172 du 14 février 2022 en faveur de l'activité professionnelle indépendante](https://www.legifrance.gouv.fr/dossierlegislatif/JORFDOLE000044125588/) modifie le statut de l’entrepreneur individuel afin de renforcer sa protection et de simplifier le transfert de son patrimoine professionnel. Elle crée un statut unique d’entrepreneur individuel, garantissant automatiquement la protection de son patrimoine personnel et supprime la possibilité de créer une EIRL à compter du 15 février 2022. Ce nouveau statut prévoit également la possibilité, pour tout entrepreneur individuel, d’opter pour l’assujettissement à l’impôt sur les sociétés.

En gros, le status d'Entrepreneur Individuel à Responsabilité Limitée (**EIRL**) est supprimé et le status d'entrepreneur individuel (**EI**) par défaut devient l'ancien status d'EIRL.

> Ce nouveau statut est plus protecteur : sauf option contraire, l’ensemble du patrimoine personnel de l’entrepreneur indépendant devient par défaut insaisissable par ses créanciers professionnels. Ainsi, les biens utiles à l'exercice de l'activité professionnelle seront transférés du patrimoine privé de l’entrepreneur au patrimoine professionnel. La séparation des patrimoines s’effectuera automatiquement, sans démarche administrative ou information des créanciers.

Ref.

- [impots.gouv.fr - Qu’est-ce que le statut unique d’entrepreneur individuel ?][38]

Il existe deux autre status d'entreprise unipersonnelle (1 seule personne) mais non individuelle (pas en votre nom propre) :

- La société par actions simplifiées unipersonnelle (**SASU**)
- L’entreprise unipersonnelle à responsabilité limitée (**EURL**)

La SASU est un cas particulier de SAS, elle va être beaucoup plus complexe que les entreprises individuelles et son principal avantage est de pouvoir émettre
des actions, pour faire du bug bounty cela ne va pas du tout nous intéresser.
L'EURL est un cas particulier de SARL, là aussi beaucoup plus complexe et génère davantage d'obligations juridiques et comptables, l'intérêt se trouve en cas de dépassement des plafonds
de revenus des entreprises individuelles (nous verrons ce point par la suite).

Ref.

- [guichet-entreprises.fr - Les formes juridiques de l’entreprise][16]
- [lecoindesentrepreneurs.fr - Les différents statuts juridiques possibles pour les entreprises][17]

### Créer une entreprise à plusieurs

Il existe de nombreux autres statuts d'entreprises qui requièrent au minimum 2 associés : SA, SARL, SNC, certaines SEL, etc.

Ces statuts d'entreprise ne nous intéressent pas dans le cadre du bug bounty.

### Conclusion

Les 2 statuts qui vont intéressés les hunters français sont donc l'EI et plus rarement l'EURL.
Ce qui fera pencher entre l'EI et l'EURL sera lié au régime fiscal, notamment du plafond de revenus.

## Les régimes fiscaux des entreprises individuelles

> L'entrepreneur individuel peut choisir entre 3 régimes d'imposition, en fonction du montant de son chiffre d'affaires : le [régime de la micro-entreprise][7], le [régime réel simplifié][8] et le [régime réel normal][9].

Pour des bénéfices non commerciaux (BNC) :

- régime micro entreprise : 0 à 72 600 €
- régime réel simplifié : 70 600 à 238 000 €
- régime réel normal : 238k€ et +
- régime de la déclaration contrôlée : 70 000 € et +

Ici l'on comprend bien que l'on pourra ne bénéficier du régime de micro-entreprise
qu'en dessous de ce palier de revenus.
Au dessus de ~70k€ il faudra passer soit au régime réel ou de déclaration contrôlée,
soit à une EURL au régime de l’impôt sur les sociétés (IS) ou au régime des
sociétés de personnes (dans le cadre d'une personne morale) [[20][20]][[21][21]].

## Types de bénéfices : BIC, BNC, etc.

> Les bénéfices industriels et commerciaux (**BIC**), les bénéfices non commerciaux (**BNC**) sont des revenus qui sont soumis à l’impôt sur le revenu.

Exemple :

- BIC : commerces, artisans, industries, restaurants, prestation de service commerciaux, etc.
- BNC : professions libérales, officiers, etc.

Le bug bounty hunting est classifiable comme profession libérale (les indépendants
qui exercent un art ou une science) au même titre que les développeurs, consultants,
experts, etc. donc nos bénéfices seront 100% en BNC.

Ref.

- [economie.gouv.fr - Impôt sur le revenu : BIC, BNC, comment ça marche ?][22]
- [shine.fr - Êtes-vous en BIC ou en BNC ? Le guide pour tout savoir][23]

## Impôts

Bon clairement malgré le baratin sur les status simplifiés, ca reste compliqué.

En tant qu'entrepreneur individuel, il y a un choix à faire parmis deux options :

- **IR** : [impôt sur le revenu][39]
- **IS** : [impôt sur les sociétés][40]

> L’imposition à l’IR se traduit par une imposition directe des bénéfices au nom de l’entrepreneur ou au nom de chaque associé en cas d’exercice en société.
>
> A contrario, le choix de l’IS fait supporter l’imposition des bénéfices sur l’entreprise directement. L’entrepreneur ou les associés sont quant à eux imposés personnellement sur les rémunérations et les dividendes qu’ils perçoivent.

Lorsque l’entreprise est soumise à l’impôt sur le revenu, l’imposition s’applique directement au niveau de l’entrepreneur. L’entreprise ne subit aucune imposition fiscale. Les bénéfices réalisés par l’intermédiaire de l’entreprise sont imposés dans la catégorie dont relève l’activité exercée : ici BNC.
Le choix de l’imposition à l’IR permet, pour les activités réduites, de profiter des régimes d’imposition ultra-simplifiés : micro-BNC ou statut auto-entrepreneur.

Lorsque l’entreprise est soumise à l’IS, l’imposition des bénéfices est appliquée directement au nom de l’entreprise. L’IS est calculé au taux normal mais un taux réduit de 15% sur les 38 120 premiers euros de bénéfices est possible sous conditions. Dans cette configuration, l’entrepreneur n'est imposable personnellement à l’IR que sur les rémunérations et les dividendes qu’il perçoit.

Dans notre cas de figure l'IR est plus simple et l'IS apporte de la complexité sans en tirer d'intérêt.

Ref.

- [lecoindesentrepreneurs - IR ou IS ? Le choix du régime fiscal de l’entreprise][41]

> Pour les revenus des indépendants (ici de bénéfices non commerciaux BNC, l'administration fiscale prélève directement le montant de l'impôt correspondant aux revenus professionnels sur la base de la dernière situation fiscale connue. Ce prélèvement prend la forme d'acomptes mensuels prélevés le 15 de chaque mois, sauf en cas d'option pour un prélèvement trimestriel.
>
> Chaque année, la déclaration de revenus reste nécessaire pour déterminer le taux de prélèvement à la source applicable à compter du mois de septembre de l'année (et jusqu'en août de l'année suivante) et le montant définitif de l'impôt sur le revenu de l'année précédente. Si les prélèvements ont été supérieurs à l'impôt dû, l'excédent sera remboursé par virement à l'été. Dans le cas contraire, le solde sera à payer par prélèvement sur le compte bancaire mentionné dans la déclaration de revenus.

En gros chaque année vous déclarerez les revenus de votre entreprise individuelle lors de votre déclaration de l'impôt sur le revenu et vous payerez l'impôt dû l'année suivante sous forme de mensualité avec une régulation en fin d'année.

Ref.

- [economie.gouv.fr - Le prelèvement à la source des indépendants : mode d'emploi](https://www.economie.gouv.fr/entreprises/prelevement-source-independants-micro-entrepreneurs-auto-entrepreneur)

> Le VFL (versement forfaitaire libératoire) est une option de paiement de l’impôt sur le revenu auprès de l’URSSAF, qui collecte l’impôt pour le compte de la direction générale des Finances publiques (DGFiP) sur une périodicité mensuelle ou trimestrielle.
>
> Ce dispositif consiste à effectuer des versements, communs avec ceux des cotisations sociales, tout au long de l’année, au fur et à mesure des encaissements. Cette modalité de paiement libère le micro‑entrepreneur du versement de l’impôt sur le revenu au titre des résultats de son activité auprès de la DGFiP et ne donne pas lieu à une régularisation l'année suivante.

Ref.

- [economie.gouv.fr - Comment fonctionne le versement libératoire de l’impôt sur le revenu ?][42]

En gros, ça permet de payer l'IR au fur et à mesure sur l'année en cours, et l'IR est collecté par l'URSSAF en même temps que les cotisations sociales (pas de prélèvement à la source). Cependant, il ne faut pas dépasser un certain seuil de revenu.

> Le versement forfaitaire libératoire est une option est ouverte uniquement aux micro-entrepreneurs dont le revenu fiscal de référence de l'année N-2 (RFR) n'excède pas un certain seuil pour une part de quotient familial.

Cela correspondait à un revenu de 27 519 €k, or comme nous avons déjà un salaire à côté il y a déjà de fortes chances qu'à lui seul notre salaire dépasse ce seuil, il nous sera alors impossible d'obter pour le VFL.

Pour l'IR au régime déclaratif spécial BNC, le chiffre d'affaires de l'année doit figurer sur la déclaration des revenus n°2042C-PRO (déclaration complémentaire des revenus des professions non salariées), selon les dates de déclaration de l'IR.

Dans le [formulaire n°2042 C pro][43], on devrait principalement remplir le champ `5HQ`. Ne pas remplir `5HY` car nous payons déjà les cotisatiosn sociales sur le site de l'URSSAF.

Il existe un [espace professionnel](https://cfspro-idp.impots.gouv.fr/) sur le site des impôt qui sera nécessaire pour payer la CFE. On peut être exonéré la 1ere année.

Ref.

- [impots.gouv.fr - dois-je payer une cotisation foncière des entreprises (CFE) et créer un espace professionnel sécurisé ?][44]

## Les démarches

La page [Création d'entreprise : les démarches à effectuer][25] nous donne un
aperçu au niveau des démarches à entreprendre pour la création de son entreprise :

- Choisir le statut juridique de votre entreprise (abordé plus haut ici)
- Les conséquences fiscales du choix du statut juridique de votre entreprise (abordé plus haut ici)
- Les déclarations et immatriculations
- Les centres de formalités des entreprises (CFE) : dans notre cas l'Urssaf
- L'attribution des numéros d'identification : [SIREN, SIRET, APE, TVA][26]
- Les démarches supplémentaires, non prises en charge par les CFE :
  - La domiciliation de votre entreprise
  - Le choix du nom de votre entreprise
  - Vos besoins d'assurance
  - L'ouverture d'un compte bancaire

Il est possible de faire toutes les démarches de création d'entreprise en
ligne :
- sur le [Guichet entreprise][24] pour tout type d'entreprise
- sur l'[URSSAF portail auto-entrepreneur][27] uniquement pour l'entreprise individuelle avec régime de micro-entrepreneur a.k.a. auto-entrepreneur

Une page intéressante est aussi [Tout savoir sur la micro-entreprise][28] qui reprend :

- les étapes de création (Créer sa micro-entreprise)
- l'imposition (Payer ses impôts)
- les cotisations (Payer ses cotisations sociales)
- les aides (Obtenir des aides financières)

## Les courriers

### Création de l'entreprise

À la création de votre entreprise, vous recevrez notamment les courriers postaux
suivants:

- Une lettre de la _DGFIP_ (Direction Général des FInances Publiques), plus précisément du _Service des Impôts des Entreprises_ rappelant les démarches à suivre en termes de déclaration d'impôt ainsi qu'un _memento fiscal_ concernant votre activité et vos obligations fiscales (type d'impôt (BNC, TVA, CFE) et régime d'imposition)
- Un _Certificat d'inscription au Répertoire des Entreprises et des Établissements_ (SIRENE) envoyé par l'_INSEE_ contenant la description de la personne et de l'établissement où vous trouverez tous les numéros utils
- Une _Notification d'affiliation_ à la sécurité sociale (CPAM) envoyé par l'_URSSAF_
- Potentiellement une lettre du _Greffe du tribunal de commerce_ en cas de non conformité de votre dossier

### [Draft] Durant la vie de l'entreprise

TODO

### [Draft] Cessation d'activité

TODO

## TVA

> La TVA est une taxe collectée par les entreprises et reversée à l’Etat. L'entreprise collecte la TVA sur le montant de ses ventes, c'est la TVA collectée. En contrepartie, elle peut déduire de la TVA payée sur ses propres achats auprès de ses fournisseurs, c'est la TVA déductible. L'entreprise versera à l'État la différence entre la TVA collectée et la TVA déductible.

Une entreprise individuelle peut être exonérée de TVA en optant pour le **régime de la franchise de TVA** et il n'y a donc pas besoin de facturer de TVA.
Par contre vous ne pouvez pas non plus récupérer celle sur vos achats.

Les conditions pour pouvoir bénéficier de la franchise en base de TVA:

- chiffre d’affaires hors taxes au cours de l’année civile précédente < 34 400 €
- indiquer sur vos factures la mention suivante : `TVA non applicable, art. 293 B du CGI`

Une marge est accordée dans le dépassement des seuils.
La franchise reste applicable pendant l’année au cours de laquelle a lieu le dépassement si le chiffre d'affaires < 36 500 €.

> Si vous dépassez ces seuils, la TVA s’appliquera à compter du premier jour du mois au cours duquel les seuils ont été dépassés. Cela peut être embêtant quand vous avez déjà émis des factures pour le mois !

Avec le **régime réel simplifié de TVA** il faut payer des acomptes de TVA et établir une déclaration annuelle de TVA. Si le montant de la taxe est supérieur à 15 000 €, il faut déposer une déclaration de TVA mensuellement à compter de l’exercice suivant.

En récapitulatif :

- régime de la franchise de TVA (pas de TVA) : CA < 34 400€
- régime réel simplifié de TVA : 34 400 à 238 000€
- régime normal de TVA : + 238 000€

Ref.

- [captaincontrat.com - EIRL et TVA : fonctionnement de la taxe sur la valeur ajoutée en entreprise individuelle à responsabilité limitée][29]
- [impots.gouv.fr - En tant que micro-entrepreneur, puis-je être redevable de la TVA ?][30]

## Compte bancaire

Pour une auto-entreprise ayant un chiffre d'affaires supérieur à 10 000€ un
compte bancaire dédié à l'auto-entreprise est obligatoire (séparé du compte
courant personnel).
Il doit être utilisé uniquement pour l’ensemble des transactions financières
liées à l'activité de l'entreprise :

- dépôt des recettes
- dépenses effectuées dans le cadre de l'activité
- paiement de vos charges (CFE, TVA, cotisations sociales, etc.)
- prélèvement de votre rémunération

Il n'est pas obligatoire d'ouvrir un compte professionnel, un compte
courant en son nom suffit (différent du votre).

> Il faut aussi savoir que les banques ont le droit de refuser l’ouverture du compte d’un client sans se justifier, de même qu’elles peuvent clôturer un compte bancaire arbitrairement avec un préavis d’un mois minimum.
>
> De fait, de nombreuses banques ont commencé à refuser tout simplement l’ouverture d’un compte dédié aux transactions d’un auto-entrepreneur. S’il est possible d’ouvrir un compte sans préciser quelle sera son utilité, rien n’empêche la banque de clôturer ensuite le compte lorsqu’elle aura réalisé à quelles fins il est utilisé. Le but est simple : forcer les auto-entrepreneurs à souscrire à un compte bancaire professionnel, dernier recours pour respecter la législation.

Il existe beaucoup de banques qui acceptent les auto-entrepreneurs avec des
offres allant de 5 à 20€ / mois, mais si vous cherchez des offres gratuites ça
se complique. Il y a actuellement 3 banques où vous pouvez avoir un compte
gratuit acceptant les auto-entrepreneurs, mais il y a cependant quelques limitations.

- **AXA Banque Pro**
  - Les plus
    - IBAN Français
    - dépôt espèce et chèques
    - CB Visa Classic
    - virements et prélèvements SEPA illimités
    - terminal de paiement par carte (25€ sans frais mensuel)
  - Les moins
    - 900 € / trimestre de dépense par carte obligatoire pour avoir la CB gratuite sinon pénalité de 4€
    - Si vous ne prenez pas la CB des frais de tenue de compte s'appliquent
- **N26 Business (Standard)**
  - Les plus
    - Cashback de 0,1 %
    - CB Virtuelle (0€) ou Mastercard (10€ frais de livraison)
    - virements et prélèvements SEPA illimités
    - paiements en devises étrangères gratuits
    - Liste des transactions téléchargeable en CSV et PDF
  - Les moins
    - ~~IBAN Allemand~~ [[49][49], [50][50]]
    - 3 retraits CB en DAB sans frais par mois
    - Frais sur les dépôts en cas de solde excédant 50 000€ (0,5%)
    - Non cumulable avec un compte N26 personnel
- **Bourso Business**
  - Les plus
    - CB Virtuelle (0€) ou Mastercard (9€/mois si pas d'utilisation, gratuite sinon)
    - Paiements & retraits en euros gratuits et illimités
  - Les moins
    - Nécessite l'ouverture d'un compte BoursoBank personnel
    - Pas d'outil de gestion comptable
    - Pas de dépot d'espèces

Ref.

- [legifrance.gouv.fr - Article L133-6-8-4 du Code de la sécurité sociale][31]
- [legifrance.gouv.fr - Article L613-10 du Code de la sécurité sociale][32]
- [legifrance.gouv.fr - Article 39 du la loi PACTE (LOI n° 2019-486 du 22 mai 2019 relative à la croissance et la transformation des entreprises)][33]
- [portail-autoentrepreneur.fr - Compte bancaire des auto-entrepreneurs : que dit la loi ?][34]
- [capitaine-banque.com - Auto-entrepreneur : un compte bancaire pro est-il obligatoire ?][35]
- [service-public.fr - Comptabilité du micro-entrepreneur (régime micro-social)][36]
- [independant.io - Les Meilleurs Comptes Bancaires Auto-Entrepreneur Gratuits en 2021][37]

## Dénomination sociale, nom commercial et marque d'entreprise

En tant qu'auto-entrepreneur, la **dénomination sociale** de l'entreprise est obligatoirement lié au nom de famille de l'entrepreneur, seuls les cas suivants sont possibles :

- NOM (obligatoire, nom a minima)
- Prénom NOM (optionnel, le prénom peut être ajouté)
- Prénom NOM EIRL (la mention EIRL peut être ajoutée dans le cadre d'une EIRL)

> Dans le cadre de la création d'une entreprise individuelle (EI) ou d'une micro-entreprise, la dénomination sociale correspond obligatoirement à votre nom de famille, qui peut s'accompagner de votre prénom. Pourquoi ? Car l'identité juridique de l'entreprise individuelle est indissociable et strictement limitée à celle de son créateur : l'entrepreneur individuel.

Si l'on souhaite avoir un site internet et/ou une identité propre, il peut être préférable d'ajouter un **nom commercial** à l'entreprise.

> Le nom commercial permet d'identifier votre société et tout particulièrement l'exercice de son activité sur l'ensemble des documents commerciaux que vous produisez : factures, papier à en-tête, mais aussi cartes de visite. Il peut être similaire à la dénomination sociale comme s'en distinguer afin de mieux décrire, auprès de vos clients, votre offre de service.
>
> Le choix d'un nom commercial, bien que facultatif, doit être déclaré lors de l'[immatriculation au registre du commerce et des sociétés (RSC)](https://www.economie.gouv.fr/entreprises/registre-commerce-societes-rcs).

Cela peut être fait à la création de l'entreprise ou être ajouté / modifié a posteriori. Et cette formalité doit être déclarée au CFE (centre de formalités des entreprises, comprendre l'URSSAF) / RCS.

Évidement le nom commercial doit légalement ne pas être identique, ressemblant ou similaire à celui d'un concurrent. On peut consulter les dénominations sociales et noms commerciaux enregistrés sur le site [infogreffe.fr](https://www.infogreffe.fr/recherche-siret-entreprise/chercher-siret-entreprise.html).

Le nom commercial apporte une protection limitée (voir l'article portail-autoentrepreneur.fr).

Pour aller plus loin, il est possible de déposer une **marque d’entreprise** auprès de l'INPI (Institut National de la Propriété Industrielle) afin de bénéficier d'une protection renforcée. La [base de l'INPI](https://data.inpi.fr/) est consultable dans le but de vérifier si une marque similaire est déjà déposée.

Ref.

- [economie.gouv.fr - Pourquoi et comment changer le nom de votre entreprise ?][47]
- [portail-autoentrepreneur.fr - Peut-on utiliser un nom commercial en auto-entreprise ?][48]

## Vie privée

En tant qu'auto-entrepreneur BNC, il y a de fortes chances que votre siège social soit votre domicile personnel. Afin de protéger sa vie privée et sa sécurité, il est judicieux de limiter l'accès de ses données à caractère personnel dans la base SIRENE, afin que, par exemple, votre adresse ne soit pas publique.

Afin de bénéficier de la protection, il s'agit d'une simple case à cocher dans le formulaire de création d'entreprise ou de changement d'adresse.

Une fois la protection activée, les sites [infogreffe.fr](https://www.infogreffe.fr/) ou [societe.com](https://www.societe.com/) ne renverront plus rien du tout quand l'on cherchera le SIREN ou SIRET de l'entreprise, comme si celle-ci n'existait pas.

En cherchant le SIREN ou SIRET sur [numero-siret.com](https://www.numero-siret.com/search-k.php) seuls les SIREN ou SIRET seront affichés et plus le nom ou l'adresse. Le site [sirene.fr](https://www.sirene.fr/sirene/public/recherche) affichera la commune, l'APE, la catégorie juridique mais toutes les informations personnelles seront masquées. Cela permet toutefois de confirmer que l'entreprise existe. De même, [avis-situation-sirene.insee.fr](https://avis-situation-sirene.insee.fr/) permet de vérifier que l'entreprise existe : si celle-ci est protégée, il faudra s'authentifier avec FranceConnect afin de consulter les informations (seul vous pourrez les voir), sinon si elle n'est pas protégée, les informations seront disponibles directement.

Enfin, pour modifier le statut de diffusion au répertoire SIRENE sans avoir à déclarer une modification de l'entreprise au CFE, il est possible de faire la démarche sur [statut-diffusion-sirene.insee.fr](https://statut-diffusion-sirene.insee.fr/) en s'authentifiant avec FranceConnect.

## Paiements internationaux et conversion de devises

Vidéo :

[![](https://img.youtube.com/vi/xJiHpMvNP3I/mqdefault.jpg)](https://www.youtube.com/watch?v=xJiHpMvNP3I)

## [Draft] CFE

La Cotisation foncière des entreprises (CFE) est redevable chaque année, dans
le cadre d'une entreprise individuelle pour du Bu Bounty notre local de travail
est notre domicile. La CFE sera basée sur celui-ci.

À noter : les entreprises redevables de la cotisation minimum réalisant un chiffre d'affaires ou de recettes inférieur ou égal à 5 000 € sont exonérées de CFE (art. 1649 D I-1° du CGI).

Ref.

- [impots.gouv.fr - Impôts locaux : CET (CFE et CVAE) et TF][45]
- [entreprendre.service-public.fr - Cotisation foncière des entreprises (CFE)][46]

Le CFE de Paris est 16,52% =>, mais il y a un paquet de villes avec des taux aux alentours de 7%. Eg à ANGLEFORT (01350) le taux est de 4% en 2018.

https://www.data.gouv.fr/fr/datasets/impots-locaux/

## [Draft] divers

- assurance, etc.
- Tax form : pas W-8BEN (individu) mais [W-8BEN-E](https://www.irs.gov/pub/irs-pdf/iw8bene.pdf) (entreprise)

[1]:https://travail-emploi.gouv.fr/droit-du-travail/lutte-contre-le-travail-illegal-10802/article/les-sanctions-liees-au-travail-illegal
[2]:https://www.legifrance.gouv.fr/codes/id/LEGIARTI000038602150/2019-07-01/
[3]:https://www.legifrance.gouv.fr/codes/id/LEGIARTI000032040772/2016-10-01/
[4]:https://www.legifrance.gouv.fr/codes/id/LEGIARTI000006900858/2008-05-01/
[5]:https://www.legalplace.fr/guides/obligation-loyaute/
[6]:https://www.captaincontrat.com/articles-droit-social/clause-exclusivite-contrat-travail
[7]:https://www.economie.gouv.fr/entreprises/regime-micro-entrepreneur-auto-entrepreneur
[8]:https://www.economie.gouv.fr/entreprises/regime-reel-simplifie
[9]:https://www.economie.gouv.fr/entreprises/regime-reel-normal-imposition
[10]:https://www.economie.gouv.fr/particuliers/impot-revenu-obligations-declaratives
[11]:https://www.impots.gouv.fr/portail/particulier/obligations-declaratives
[12]:https://www.service-public.fr/particuliers/vosdroits/F358
[13]:https://www.impots.gouv.fr/portail/particulier/revenus-exceptionnels
[14]:https://www.economie.gouv.fr/particuliers/impot-revenus-exceptionnels
[15]:https://www.service-public.fr/particuliers/vosdroits/F3178
[16]:https://www.guichet-entreprises.fr/fr/creation-dentreprise/les-prealables-a-la-creation-dentreprise/les-formes-juridiques-de-lentreprise/
[17]:https://www.lecoindesentrepreneurs.fr/les-statuts-d-entreprises/
[18]:https://www.impots.gouv.fr/portail/professionnel/exercice-dune-activite-en-nom-personnel
[19]:https://www.impots.gouv.fr/portail/avantages-et-inconvenients-des-entreprises-individuelles
[20]:https://www.lecoindesentrepreneurs.fr/regime-fiscal-eurl/
[21]:https://www.lecoindesentrepreneurs.fr/statut-fiscal-et-social-associe-unique-eurl/
[22]:https://www.economie.gouv.fr/entreprises/impot-sur-revenu-bic-bnc
[23]:https://www.shine.fr/blog/bic-bnc/
[24]:https://www.guichet-entreprises.fr/
[25]:https://www.economie.gouv.fr/entreprises/creation-entreprise-demarches
[26]:https://www.economie.gouv.fr/entreprises/numeros-identification-entreprise
[27]:https://www.autoentrepreneur.urssaf.fr/portail/accueil.html
[28]:https://www.economie.gouv.fr/entreprises/micro-entreprise-auto-entreprise
[29]:https://www.captaincontrat.com/articles-gestion-entreprise/eirl-tva
[30]:https://www.impots.gouv.fr/portail/professionnel/questions/en-tant-que-micro-entrepreneur-puis-je-etre-redevable-de-la-tva
[31]:https://www.legifrance.gouv.fr/codes/id/LEGIARTI000033613485/2016-12-11
[32]:https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000038586837/
[33]:https://www.legifrance.gouv.fr/jorf/article_jo/JORFARTI000038496184?r=yo7D3WuhWy
[34]:https://www.portail-autoentrepreneur.fr/academie/creation-auto-entreprise/compte-bancaire
[35]:https://www.capitaine-banque.com/actualite-banque/auto-entrepreneur-compte-bancaire-pro-obligatoire/
[36]:https://www.service-public.fr/professionnels-entreprises/vosdroits/F23266
[37]:https://independant.io/meilleurs-comptes-bancaires-auto-entrepreneur-gratuits/
[38]:https://www.impots.gouv.fr/professionnel/questions/quest-ce-que-le-statut-unique-dentrepreneur-individuel
[39]:https://www.economie.gouv.fr/particuliers/tranches-imposition-impot-revenu
[40]:https://www.economie.gouv.fr/entreprises/impot-societes-IS
[41]:https://www.lecoindesentrepreneurs.fr/ir-ou-is-regime-fiscal/
[42]:https://www.economie.gouv.fr/entreprises/micro-entreprise-auto-entreprise-versement-liberatoire-impot-revenu
[43]:https://www.impots.gouv.fr/formulaire/2042/declaration-des-revenus
[44]:https://www.impots.gouv.fr/professionnel/questions/je-suis-micro-entrepreneur-dois-je-payer-une-cotisation-fonciere-des
[45]:https://www.impots.gouv.fr/professionnel/cet-cfe-et-cvae
[46]:https://entreprendre.service-public.fr/vosdroits/F23547
[47]:https://www.economie.gouv.fr/entreprises/changer-nom-denomination-sociale-entreprise
[48]:https://www.portail-autoentrepreneur.fr/academie/creation-auto-entreprise/nom-commercial
[49]:https://n26.com/fr-fr/iban-france
[50]:https://n26.com/fr-fr/blog/l-iban-francais-debarque-chez-n26
