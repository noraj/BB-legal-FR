# Bug Bounty légal en FRANCE

> Quelques conseils autour des obligations légales, fiscales et juridiques pour la pratique du Bug Bounty en France

:warning: Les conseils mentionnés ici sont simplement des travaux de collecte d'information sur le sujet et n'ont en aucun cas une valeur juridique, leur exactitude n'est pas garantie et ne sauraient en aucun cas impliquer ma responsabilité. Nul n'est censé ignorer la loi, renseignez-vous et vérifiez tout ce qui est écrit ici.

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

Commençons par jeter un oeil à la [FAQ de YesWeHack](https://www.yeswehack.com/fr/entreprises/aide-faq/) :

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

Bon là c'est un peu fouilli mais on comprend vite qu'on va devoir créer une entreprise, déclarer et payer des impôts et qu'il y a des histoires de seuils et de TVA.

Maintenant, regardons-les [CGU de Yogosha](https://yogosha.com/fr/conditions-generales-dutilisation/)

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

Bon là c'est clairement comme le dernier paragraphe de la FAQ de YesWeHack: "Vous avez des devoirs/obligations, maintenant débrouiller vous !". Normalement à ce stade vous êtes confus,vous n'avez pas compris grand-chose, vous ne savez toujours pas ce que vous devez ou pouvez faire et vous n'avez pas plus de réponses qu'au départ, mais plutôt des questions supplémentaires.

Vous êtes tenté de vous dire "Bon ! Ca à l'air compliqué et rébarbatif tout cas, il y a peut être moyen de passer à côté". Et bien non les plateformes déclarent tout et si vous n'êtes pas dans les clous il y aura bientôt une grosse différence entre les informations que les autorités fiscales auront reçues et ce que vous aurez (ou pas) déclaré.

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
En pratique, il y a cependant une tolérance **officieuse** si le revenu est ponctuel et faible (seuil non défini) donc par exemple si vous gagnez 1 fois 500€ dans l'année pas besoin de créer une entreprise mais dès que vous dépasserez quelques milliers d'euros
ou mènerez cette activité de manière récurrente il vous faudra créer une entreprise.
Comme vous ne pourrez pas rattacher de manière rétro-active des revenus à votre entreprise, il faut prévoir sa création à l'avance si vous prévoyez de pratiquer la chasse aux bugs.

En résumé:

- Vous trouvez **1** bug qui représente un faible montant 1 fois dans l'année: pas besoin d'entreprise
- Dans tous les autres cas **une création d'entreprise est nécessaire**, si vous vous lancez sérieusement dans le Bug Bounty vous trouverez forcément plus d'un bug par an

Ref.

- [impots.gouv.fr - Revenus exceptionnels][13]
- [economie.gouv.fr - Quelles modalités d'imposition pour les revenus exceptionnels ?][14]
- [service-public.fr - Impôt sur les revenus exceptionnels : quelles sont les règles ?][15]

## Création d'une entreprise

Entrepreneur individuel, Micro-entrepreneur/auto-entrepreneur, EIRL, SARL, EURL, SAS, SASU

### Créer une entreprise seul

> Il existe 3 possibilités d'exercer Pour exercer une une activité en nom personnel soumise à l'impôt sur le revenu vous avez le choix entre trois statuts différents :
>
> - le statut de l'entrepreneur individuel (**EI**) ;
> - le statut du **micro-entrepreneur** ;
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

Les 3 status sont des entreprises individuelles en nom propre où l'identité de l'entreprise correspond à celle de son dirigeant (le nom de l'entreprise comportera votre nom),
et elle ne peut être constitué que d'une seule personne physique (vous, pas d'associés ou de salariés).
La micro-entreprise est une entreprise individuelle qui bénéficie d'un régime simplifié.
L'entreprise individuelle n'a donc aucun intérêt pour le bug bounty et la micro-entreprise est le status le plus utilisé par les hunters car très simple.
Le gros défaut de la micro-entreprise reste la responsabilité, le dirigeant est indéfiniment responsable des dettes de son entreprise sur ses biens propres.
L'Entrepreneur Individuel à Responsabilité Limitée (EIRL) permet à l’entrepreneur de protéger ses biens personnels, en créant un patrimoine affecté à son activité professionnelle distinct de son patrimoine privé. C'est une entreprise individuelle qui peut aussi profiter du régime simplifié de la micro-entreprise.
L'autre différence avec l'EIRL c'est que le dirigeant peut opter pour l'IS (impôt sur les sociétés) au lieu de l'IR (impôt sur le revenu) et donc potentiellement bénéficier de déduction de rémunération dans les comptes de l'entreprise.
Légèrement plus compliqué l'EIRL semble plus intéressante que la micro-entreprise pour limiter sa responsabilité.

Il existe deux autre status d'entreprise unipersonnelle (1 seule personne) mais non individuelle (pas en votre nom propre) :

- La société par actions simplifiées unipersonnelle (**SASU**)
- L’entreprise unipersonnelle à responsabilité limitée (**EURL**)

La SASU est un cas particulier de SAS, elle va être beaucoup plus complexe que les entreprises individuelles et son principal avantage est de pouvoir émettre
des actions, pour faire du bug bounty cela ne va pas du tout nous intéresser.
L'EURL est un cas particulier de SARL, là aussi beaucoup plus complexe et génère d'avantage d'obligations juridique et comptables, l'intérêt se en cas de dépassement des plafonds
de revenus des entreprises individuelles (nous verrons ce point par la suite).

Ref.

- [guichet-entreprises.fr - Les formes juridiques de l’entreprise][16]
- [lecoindesentrepreneurs.fr - Les différents statuts juridiques possibles pour les entreprises][17]

### Créer une entreprise à plusieurs

Il existe de nombreux autres status d'entreprises qui requièrent au minimum 2 associés : SA, SARL, SNC, certaines SEL, etc.

Ces status d'entreprise ne nous intéressent pas dans le cadre du bug bounty.

### Conclusion

Les 3 status qui vont intéressés les hunters Français sont donc la micro-entreprise, l'EIRL et plus rarement l'EURL.
Nous avons déjà expliqué l'intérêt de l'EIRL par rapport à la micro-entreprise au niveau de la responsabilité.
Ce qui fera pencher entre l'EIRL (ou micro-entreprise) et l'EURL sera lié au régime fiscal, notamment du plafond de revenus.

## Les régimes fiscaux des entreprises individuelles

> L'entrepreneur individuel peut choisir entre 3 régimes d'imposition, en fonction du montant de son chiffre d'affaires : le [régime de la micro-entreprise][7], le [régime réel simplifié][8] et le [régime réel normal][9].

Pour des bénéfices non commerciaux (BNC) :

- régime micro entreprise : 0 à 72 600 €
- régime réel simplifié : 70 600 à 238 000 €
- régime réel normal : 238k€ et +
- régime de la déclaration contrôlée : 70 000 € et +

Ici l'on comprend bien que l'on pourra ne bénéficier du régime de micro-entreprise
qu'en dessous de ce palier de revenus.
Au dessus de ~70k€ il faudra passer soit à une EIRL au régime réel ou de déclaration contrôlée,
soit à une EURL au régime de l’impôt sur les sociétés (IS) ou au régime des
sociétés de personnes (dans le cadre d'une personne morale) [[20][20]][[21][21]].

Point de vue personnel : je pense opter pour l'EIRL afin de conserver un status simple tout en limitant mes responsabilités, et en partant du régime micro entreprise
qui est le plus simple et passer au régime réel simplifié si jamais j'ai le chance de dépasser le plafond de revenus.

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

## Les démarches

La page [Création d'entreprise : les démarches à effectuer][25] nous donne un
aperçu haut niveau des démarches à entreprendre pour la création de son entreprise :

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

A la création de votre entreprise vous recevrez notamment les courriers postaux
suivants:

- Une lettre de la _DGFIP_ (Direction Général des FInances Publiques), plus précisément du _Service des Impôts des Entreprises_ rappelant les démarches à suivre en terme de déclaration d'impôt ainsi qu'un _memento fiscal_ concernant votre activité et vos obligations fiscales (type d'impôt (BNC, TVA, CFE) et régime d'imposition)
- Un _Certificat d'inscription au Répertoire des Entreprises et des Établissements_ (SIRENE) envoyé par l'_INSEE_ contenant la description de la personne et de l'établissement où vous trouverez tous les numéros utils
- Une _Notification d'affiliation_ à la sécurité sociale (CPAM) envoyé par l'_URSSAF_
- Potentiellement une lettre du _Greffe du tribunal de commerce_ en cas de non conformité de votre dossier

### [Draft] Durant la vie de l'entreprise

TODO

### [Draft] Cessation d'activité

TODO

## TVA

> La TVA est une taxe collectée par les entreprises et reversée à l’Etat. L'entreprise collecte la TVA sur le montant de ses ventes, c'est la TVA collectée. En contrepartie, elle peut déduire de la TVA payer sur ses propres achats auprès de ses fournisseurs, c'est la TVA déductible. L'entreprise versera à l'État la différence entre la TVA collectée et la TVA déductible.

Une entreprise individuelle peut être exonérée de TVA en optant pour le **régime de la franchise de TVA** et il n'y a donc pas besoin de facturer de TVA.
Par contre vous ne pouvez pas non plus récupérer celle sur vos achats.

Les conditions pour pouvoir bénéficier de la franchise en base de TVA:

- chiffre d’affaires hors taxes au cours de l’année civile précédente < 33 200 €
- indiquer sur vos factures la mention suivante : `TVA non applicable, art. 293 B du CGI`

Une marge est accordée dans le dépassement des seuils.
La franchise reste applicable pendant l’année au cours de laquelle a lieu le dépassement si le chiffre d'affaires < 35 200 €.

> Si vous dépassez ces seuils, la TVA s’appliquera à compter du premier jour du mois au cours duquel les seuils ont été dépassés. Cela peut être embêtant quand vous avez déjà émis des factures pour le mois !

Avec le **régime réel simplifié de TVA** il faut payer des acomptes de TVA et établir une déclaration annuelle de TVA. Si le montant de la taxe est supérieur à 15 000 €, il faut déposer une déclaration de TVA mensuellement à compter de l’exercice suivant.

En récapitulatif:

- régime de la franchise de TVA (pas de TVA) : CA < 33 200€
- régime réel simplifié de TVA : 33 200 à 238 000€
- régime normal de TVA : + 238 000€

Ref.

- [captaincontrat.com - EIRL et TVA : fonctionnement de la taxe sur la valeur ajoutée en entreprise individuelle à responsabilité limitée][29]
- [impots.gouv.fr - En tant que micro-entrepreneur, puis-je être redevable de la TVA ?][30]

## [Draft] CFE

Le CFE de Paris est 16,52% =>, mais il y a un paquet de ville avec des taux aux alentours de 7%. Eg à ANGLEFORT (01350) le taux est de 4% en 2018.

https://www.data.gouv.fr/fr/datasets/impots-locaux/

## [Draft] divers

assurance, compte bancaire, etc.
espace pro impots

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