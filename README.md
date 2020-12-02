# Bug Bounty légal en FRANCE

> Quelques conseils autour des obligations légales, fiscales et juridique pour la pratique du Bug Bounty en France

:warning: Les conseils mentionnés ici sont simplement des travaux de collecte d'information sur le sujet et n'ont en aucun cas une valeur juridique, leur exactitude n'est pas garantie et ne sauraient en aucun cas impliquer ma responsabilité. Nul n'est censé ignoré la loi, renseignez vous et vérifiez tout ce qui est écrit ici.

## TL;DR FAQ

> Débusquons ensemble les pré-jugés incorrects

- _Je peux faire du Bug Bounty sans créer d'entreprise._
  + **Faux**
- _Je suis pentester, je peux faire du Bug Bounty sans prévenir mon employeur._
  + **Faux**
- _Je peux faire du Bug Bounty sans payer d'impôts._
  + **Faux**
- _Une simple déclaration comme revenues exceptionnels liés à une activite non professionelle suffit._
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

