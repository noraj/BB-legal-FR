# Bug Bounty légal en FRANCE

> Quelques conseils autour des obligations légales, fiscales et juridique pour la pratique du Bug Bounty en France

:warning: Les conseils mentionnés ici sont simplement des travaux de collecte d'information sur le sujet et n'ont en aucun cas une valeur juridique, leur exactitude n'est pas garantie et ne sauraient en aucun cas impliquer ma responsabilité. Nul n'est censé ignorer la loi, renseignez vous et vérifiez tout ce qui est écrit ici.

## TL;DR FAQ

> Débusquons ensemble les pré-jugés incorrects

- _Je peux faire du Bug Bounty sans créer d'entreprise._
  + **Faux**
- _Je suis pentester, je peux faire du Bug Bounty sans prévenir mon employeur._
  + **Faux**
- _Je peux faire du Bug Bounty sans déclarer ce que je gagne._
  + **Faux**
- _Une simple déclaration comme revenus exceptionnels liés à une activite non professionelle suffit._
  + **Faux**

## Etude préliminaire

Commençons par jeter un oeil à la [FAQ de YesWeHack](https://www.yeswehack.com/fr/entreprises/aide-faq/) :

> ## Quelles sont les obligations légales, fiscales et sociales d’un hunter ?
>
> Si son activité auprès de la plateforme ou de plusieurs plateformes est professionnelle (exercice régulier et lucratif), le Hunter doit disposer d’un statut légal pour son activité, qui peut s’exercer de manière individuelle (Autoentrepreneur) ou en société (EURL, SARL). A défaut d’inscription à un régime juridique adéquat, le Hunter risque d’être poursuivi pour dissimulation d’activité.
>
> Le Hunter doit se rapprocher des autorités administratives compétentes (URSSAF, administration fiscale) afin de connaitre les obligations relatives à son activité et procéder à son inscription et aux diverses formalités administratives. Pour plus d’information, voir le site de l’URSSAF rubrique « Indépendant » : https://www.urssaf.fr/portail/home/independant.html
>
> Au-delà d’un certain niveau de revenu tiré de son activité sur la plateforme ou de plusieurs plateformes, le Hunter pourra être assujetti à la TVA et en conséquence devra facturer, collecter et reverser à l’administration fiscale la TVA afférente à chaque opération. L’administration fiscale applique une franchise de TVA suivant le Chiffre d’affaires annuel du Hunter (33.200 euros Franchise en base applicable en 2019).
>
> Dès lors qu’il est assujetti, le Hunter doit obligatoirement émettre une facture conforme à la réglementation fiscale notamment en y mentionnant son N° de TVA. Le N° de TVA est par principe attribué automatiquement au moment où le hunter adopte un statut professionnel.
>
> Les mentions légales obligatoires sur la facture sont prévues à l’article 441-3 du code de commerce et aux articles article 242 nonies et 242 nonies A du code général des impôts – annexe 2.
>
> De plus, toute source de revenu doit faire l’objet d’une déclaration fiscale au titre de l’impôt sur le revenu et le cas échéant, au titre de l’impôt sur les sociétés en fonction du statut légal adopté.
>
> Afin de connaitre ses obligations, le Hunter devra se rapprocher de son centre des impôts pour connaitre les formalités applicables à sa situation et au statut qu’il aura choisi.

Bon là c'est un peu fouilli mais on comprend vite qu'on va devoir créer une entreprise, déclarer et payer des impôts et qu'il y a des histoires de seuils et de TVA.

Maintenant regardons les [CGU de Yogosha](https://yogosha.com/fr/conditions-generales-dutilisation/)

> ## 3.1 Création et utilisation du Compte Utilisateur
>
> Le Chercheur s’engage à fournir, lors de la création et de l’utilisation de son Compte Utilisateur, son numéro de TVA s’il y est assujetti et s’il est résident fiscal en France ou intra-communautaire ainsi qu’une attestation de résidence fiscale ou, à défaut, une déclaration sur l’honneur attestant du lieu de son domicile fiscal. Dans le cas où le chercheur serait domicilié ou établi en dehors de l’UE, il s’engage à fournir une preuve de son activité professionnelle indépendante et déclaré aux autorités fiscales de sa résidence fiscale.
>
> Pour les besoins des cotisations sociales des chercheurs domiciliés en France, il sera demandé au Chercheur de fournir à Yogosha, chaque semestre, une attestation de vigilance ou d’auto-entrepreneur délivrée par l’URSSAF.

Ici ca parle TVA, activité professionnelle, autorités fiscales, auto-entrepreneur, URSSAF.

Continuons :

> 5.1.1 Respect de la réglementation applicable en matière comptable, fiscale et sociale
>
> Le Chercheur s’engage à accéder et utiliser la Plateforme dans le strict respect de la réglementation applicable en matière comptable, fiscale et sociale, notamment s’agissant des obligations d’immatriculation et de déclaration auprès de l’administration fiscale et les organismes de sécurité sociale dont il dépend.

Bon là c'est clairement comme le dernier paragraphe de la FAQ de YesWeHack: "Vous avez des devoirs/obligations, maintenant débrouiller vous !". Normalement à ce stade vous êtes confus,vous n'avez pas compris grand chose, vous ne savez toujours pas ce que vous devez ou pouvez faire et vous n'avez pas plus de réponses qu'au départ mais plutôt des questions supplémentaires.

Vous êtes tenté de vous dire "Bon ! Ca à l'air compliqué et rébarbatif tout ca, il y a peut être moyen de passer à côté". Et bien non les plateformes déclarent tout et si vous n'êtes pas dans les clous il y aura bientôt une grosse différence entre les informations que les autorités fiscales auront reçu et ce que vous aurez (ou pas) déclaré.

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

**Faux**, c'est une activité exercée à titre indépendant, dans un but lucratif. Il va falloir créer une entreprise, nous reviendrons sur les differents types d'entreprise possibles par la suite.

Ref.

- [travail-emploi.gouv.fr - Les sanctions liées au travail illégal - Le travail dissimulé][1]
- [legifrance.gouv.fr - article L. 613-4 du code de la sécurité sociale][2]

### _Je suis pentester, je peux faire du Bug Bounty sans prévenir mon employeur._

**Faux**, le Bug Bounty peut facilement être catégorisé comme une activité concurrente au Pentest, c'est en tout cas le même secteur d'activité, et les deux activités peuvent partager les mêmes clients.

La loyauté empêche d'exercer une 2ème activité professionnelle si elle est considérée comme concurrente. Elle est imposée par le code civil et le code pénal et souvent rappelée dans une clause spécifique du contrat de travail.

Il existe souvent dans les contrats de travail une clause d'exclusivité qui interdit au salarié d'exercer une activité professionnelle complémentaire qu'elle soit concurrente ou non. Mais dans la quasi totalité des cas cette clause est nulle et non applicable car les conditions suivantes ne sont pas respecter :

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

**Faux**, à partir du moment où vous résidez en France ou que votre domicil fiscal est en France vous devez déclarer vos revenus peu importe le montant. Cela ne veut pas forcément dire que vous allez devori payer des impôts.

Ref.

- [economie.gouv.fr - Impôt sur le revenu : quelles sont vos obligations déclaratives ?][10]
- [impots.gouv.fr - Obligations déclaratives][11]
- [service-public.fr - Impôt sur le revenu : déclaration de revenus annuelle][12]

### _Une simple déclaration comme revenus exceptionnels liés à une activite non professionelle suffit._

**Faux**, en aucun cas une activitée à but lucratif ne rentre dans les cas prévus pour les revenus exceptionnels même si c'est ponctuel ou représente de petits montants.

Ref.

- [impots.gouv.fr - Revenus exceptionnels][13]
- [economie.gouv.fr - Quelles modalités d'imposition pour les revenus exceptionnels ?][14]
- [service-public.fr - Impôt sur les revenus exceptionnels : quelles sont les règles ?][15]

[13]:https://www.impots.gouv.fr/portail/particulier/revenus-exceptionnels
[14]:https://www.economie.gouv.fr/particuliers/impot-revenus-exceptionnels
[15]:https://www.service-public.fr/particuliers/vosdroits/F3178

## [Draft] Création d'une entreprise

Entrepreneur individuel, Micro-entrepreneur/auto-entrepreneur, EIRL, SARL, EURL, SAS, SASU

- https://www.impots.gouv.fr/portail/professionnel/exercice-dune-activite-en-nom-personnel
- https://www.impots.gouv.fr/portail/avantages-et-inconvenients-des-entreprises-individuelles
- https://www.lecoindesentrepreneurs.fr/les-statuts-d-entreprises/
- https://www.economie.gouv.fr/entreprises/creation-entreprise-demarches
- https://www.guichet-entreprises.fr/fr/creation-dentreprise/les-prealables-a-la-creation-dentreprise/les-formes-juridiques-de-lentreprise/

## [Draft] L'entrepreneur individuel

> L'entrepreneur individuel peut choisir entre 3 régimes d'imposition, en fonction du montant de son chiffre d'affaires : le [régime de la micro-entreprise][7], le [régime réel simplifié][8] et le [régime réel normal][9].

Pour du BNC :

- Régime micro entreprise : 0 à 72 600 €
- régime réel simplifié : 72 600 à 238 000 €
- régime réel normal : 238k€ et +

Guichet entreprise (https://www.guichet-entreprises.fr/) vs l'URSSAF

## [Draft] BIC, BNC, etc.

https://www.economie.gouv.fr/entreprises/impot-sur-revenu-bic-bnc
https://www.economie.gouv.fr/entreprises/micro-entreprise-auto-entreprise

## [Draft] TVA

33k

## [Draft] CFE

Le CFE de Paris est 16,52% => mais il y a un paquet de ville avec des taux aux alentours de 7%. Eg à ANGLEFORT (01350) le taux est de 4% en 2018.

https://www.data.gouv.fr/fr/datasets/impots-locaux/

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
