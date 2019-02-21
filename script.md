# Agilité et développeurs - La guerre est déclarée ?

## Petit sondage
- Qui est développeur ?
- Qui a envie de travailler sur un projet agile ?
- Qui travaille sur un projet en mode agile ?
- Qui est satisfait du produit qu'il livre ? (qualité du code, satisfaction des utilisateurs, ...)

## Constat : rejet de l'agilité
Même si travailler en mode agile reste attractif pour la plupart des développeurs, on constate actuellement une sorte de rejet du mouvement.
On ne voit plus de développeurs dans les conférences agiles, et on ne voit plus d'agilistes aux conférences de développeurs.
Certains développeurs ne veulent même plus entendre parler d'agilité.
On peut donc se demander pourquoi une telle scission ?

### Traumatisme
En discutant avec un certain nombre de développeurs, on constate qu'ils ont vécu l'agilité sur leur projet comme un traumatisme. Ils ne veulent surtout plus jamais travailler dans de telles conditions. Ces signaux sont assez inquiétants et font se poser pas mal de questions sur les éventuelles dérives qui ont pu avoir lieu.

### programming motherfuckers
On peut également observer de tels mouvements de développeurs, qui peuvent être mal accueillis car ils renforcent les stéréotypes des dev pas intéressés par autre chose que le code.

### programming motherfuckers
Mais quand on regarde un peu plus, on commence à avoir quelques pistes d'explication...

### Why ?
On a émis plusieurs hypothèses :
- En fait, l'agilité est tellement rentré dans les mœurs que ce n'est plus un sujet de discussion. Tous les projets fonctionnent en mode agile et tout va bien dans le monde des bisounours. => on n'en parle plus, point.
- L'agilité, c'est du bullshit marketing => c'est n'importe quoi, ça part dans tous les sens. On ne veut plus en entendre parler
- L'agilité, c'est plein de process, de réunions, ... on n'a plus le temps de bosser => c'est lourdingue
- L'agilité, c'est une volonté de la direction. Avec notre taille de boîte, on passe à de l'agilité "at scale" => c'est une question politique qui ne nous concerne pas

## Perversion de l'agilité
Première constatation, l'agilité a été pervertie au fil du temps.

### Perversion de l'Agilité
Uncle Bob a très bien décrit ce phénomène dans un de ses articles d'août 2018.
A l'origine, l'agilité a été créée par des programmeurs, qui avaient à coeur de faire un travail de qualité.
Et puis, peut-être par réaction d'auto-défense parce qu'ils sentaient que leur utilité était remise en question, les managers se sont emparés de l'agilité et en ont exclus les développeurs : c'est de la gestion de projets, non ?
Typiquement, dans les conférences sur l'agilité, qui voyons-nous ? Il n'y a plus ni développeurs ni entrepreneurs. Seul reste le middle management qui semble chercher à justifier sa place en s'emparant de ces méthodes.

### Historique
Refaisons un peu l'histoire de tout ça.
L'agilité a donc été créée par des programmeurs, pour des programmeurs et des utilisateurs heureux (RAD, DSDM, XP, Manifeste)
Puis on a vu l'apparition de Scrum, qui proposait un cadre bien défini, des règles et des process.
Les histoires de projets réussis grâce à l'agilité ont donné envie à de plus en plus de personnes de s'y mettre, sans pour autant en comprendre les valeurs intrinsèques.
Avec la popularisation de Scrum, on a pu observer une monétisation de l'agilité, via des formations, des certifications, des audits de maturité agile, du passage à l'échelle, ... Tout ça sans prendre en compte le coeur même de l'agilité, à savoir les personnes qui font le travail.

### Perversion
L'agilité est entrée dans les moeurs. Mais comme toutes les choses qui deviennent populaires, elles perdent peu à peu de leur essence.
On met de l'agilité à toutes les sauces, pour justifier tout et son contraire.
Le projet est en retard ? C'est sûrement la faute de l'agilité. Ces développeurs n'en font qu'à leur tête.
Des bugs ? Rhalala ces méthodes de hippies sont vraiment pas fiables.
Le client est satisfait ? A par contre, là c'est grâce au chef de projet.

### Petit rappel : le Manifeste
Nous avons rencontré un certain nombre de scrum masters qui n'avaient jamais lu le manifeste agile.
Dans le doute, nous vous faisons donc une petite piqûre de rappel !

### Perversion : abandon des développeurs
Encore un fois, Uncle Bob tape assez justement (toujours dans le même article) en critiquant les dérives du mouvement agile.
Avec toutes ces conférences, certifications et autres, il y a eu un abandon des programmeurs et des valeurs de l'eXtreme programming.
On ne se concentre plus que sur la gestion de projets, et plus du tout sur la manière dont les projets sont effectivement réalisés techniquement au quotidien.

## Excellence technique
L'agilité repose avant tout sur une excellence technique. C'est d'ailleurs un des principes du manifeste : "Une attention continue à l'excellence technique et à un bon design renforce l'agilité."

### Quote Uncle Bob
Encore une fois, le constat est assez accablant.

### Excellence technique
Il y a une différence entre être agile et faire agile.
Si vous dites "On est agile dans l'équipe ! On fait de la revue de code, de l'intégration continue, parfois quelques tests, et des estimations collectives", malheureusement, mon brave, c'est un package.
On ne peut pas juste prendre les pratiques qui nous arrangent :
"Alors je prendrais la revue de code, mais pas le binômage (non mais, je ne vais pas payer deux personnes pour faire le boulot d'un seul quand même).
Je prendrais aussi un peu de tests unitaires, mais pas trop, c'est pas bon pour la ligne des plannings, ça fait grossir les temps de développement. Mais les trucs comme TDD, BDD, j'y comprends rien, j'en veux pas. C'est pour les hippies hipsters.
Bon, l'intégration continue, c'est devenu la norme quand même, je vais pas y couper.
Et pour faire plaisir aux développeurs, on va ajouter un peu d'estimations collectives, ils auront l'impression d'avoir leur mot à dire comme ça.
Par contre, le rythme soutenable, c'est bien joli votre idée de bisounours, mais on a un business à faire tourner quand même ! "

La base de l'agilité repose sur une bonne conception, un code évolutif et simple. Les auteurs du manifeste n'ont peut-être pas assez insisté sur ce point ou ça leur paraissait tellement évident qu'ils ne l'ont pas rendu suffisamment explicite.

### Extreme programming
Les pratiques de l'extreme programming sont toutes conditionnées entre elles. On ne peut pas prendre une seule pratique sans tirer le reste de la pelote.
Et pourtant, ce n'est pas ce qu'on peut observer sur la plupart des projets agiles ?
Qui parmi vous met en place au moins une de ces pratiques ?
Deux ? Trois ? Toutes ?
En passant, vous constaterez que les deux points centraux sont les tests et le binômage, pratiques les plus considérées comme de la "perte de temps".
C'est de la perte de temps, et en plus, on ne voit pas ce que ça apporte dans les indicateurs du projet

## Gestion par les indicateurs
La popularisation de scrum, et de sa liste d'indicateurs comme les burndown, burnup, le management visuel associé aux méthodes agiles ont permis aux managers de renforcer leur gestion par les indicateurs ("Wahou ! Top bien ! Plein de nouveaux KPIs pour tracker le travail des autres !")

### Transparence
Les indicateurs biaisent la relation au travail. Les outils supposés apporter de la transparence se retournent contre leurs auteurs.
"Pourquoi est-ce que le burndown n'avance pas ?", "Pourquoi est ce que tu n'as pas diminué ton reste à faire ?", "Machin a fait plus de tâches que toi lors du dernier sprint. Tu n'es pas vraiment impliqué dans ton travail..."
On observe des dérives assez malsaines :
- par exemple, les développeurs ne vont prendre que les petites tâches pour montrer qu'ils avancent vite. Et les tâches complexes qui prennent du temps ne sont jamais faites.
- certains scrum masters sont objectivés sur le burndown. Il faut donc à tout prix qu'il soit le plus rectiligne possible, quitte à tricher
- on ne veut surtout pas de rouge dans les "mood boards". Tout va bien dans l'équipe et tout le monde est heureux.

Ces indicateurs étaient supposés apporter de la transparence et permettre de lancer des alertes au plus tôt pour rectifier le tir. Ils ont été déviés de leur raison d'être pour servir d'indicateurs sur la performance des personnes et sont même utilisés comme moyen de mesurer l'atteinte des objectifs définis lors des entretiens annuels.

## Un outil imposé
Avec tous ces nouveaux indicateurs, les managers trouvent que l'agilité, c'est vraiment quelque chose de bien, qu'il faut absolument mettre en place.

### client
En plus, maintenant que les clients en ont entendu parler, c'est ce qu'ils veulent, c'est ce qui est à la mode. Donc on est obligé de passer en mode agile.

### outil imposé
En plus, l'agilité, c'est vraiment chouette !
- On va pouvoir changer les priorités n'importe quand (comment ça, on n'a pas le droit de le faire pendant le sprint ? Vous êtes agiles, non ?)
- On va pouvoir ne pas faire de specs ni vraiment définir notre besoin. Ça doit tenir sur un post-it, non ?
- On va faire un max de fonctionnalités qui vont rapporter de l'argent. La qualité, on verra plus tard. On livre vite vite un max de trucs pour faire de l'argent / faire plaisir aux actionnaires et avoir notre prime
- On va faire des reportings détaillés parce que personne ne comprends plus rien à ce qui est fait. (c'est pas ce qu'on appelle la transparence de l'équipe ?)
- On ne va surtout pas mettre un utilisateur au sein des équipes et laisser les développeurs leur parler directement. On sait jamais ce qu'ils vont dire ces ours asociaux. En plus, chez nous, on a plein de chefs de projet à recycler => hop ! proxy proxy proxy PO, nickel
- Pour montrer qu'on est jeune et dynamique, on va coller plein de post-its aux murs, qui ne bougeront jamais ou finiront par tomber de vieillesse
- On va utiliser des supers outils comme Jira, et tant pis si ça ne convient pas à l'équipe, elle s'adaptera. Jira c'est cool, c'est pro, ça fait des beaux rapports d'avancement.

### Transformation agile
OK, donc Vous faites des daily scrums qui se rapprochent plus du reporting envers le management, vous faites des itérations, vous avez un scrum master certifié, ancien chef de projet, qui protège l'équipe en leur épargnant les tâches douloureuses d'auto-organisation en assignant les tâches aux développeurs, avec un PO qui en fait est un ancien chef de projet fonctionnel, donc qui n'a jamais pratiqué le métier du client, qui n'utilisera jamais de sa vie le produit développé et qui en fait est juste un passe plats entre le client et l'équipe de développement...  Je pense que ce n'est pas tout à fait l'esprit ...

## Un monde de bisounours ?
L'agilité a également tendance à être présentée comme une méthode de bisounours. Tout le monde est content et fait ce qui lui plaît.

### Idéalisation
On constate une sorte d'idéalisation de l'image d'une équipe agile, avec des personnes soudées, motivées, solidaires, avec des managers à l'écoute, compréhensifs, empathiques, des clients accessibles et disponibles, ...
Cette idéalisation se heurte souvent violemment à la réalité de certaines entreprises et les dégâts peuvent être importants sur le point humain.

### Les rétrospectives
Cette idéalisation d'un monde parfait se retrouve également dans la manière dont sont réalisées les rétrospectives.
On ne parle pas des sujets qui fâchent (encore moins si le client participe à la rétro, quitte à en faire une "interne" pour laver son linge sale en famille, et une autre avec le client).
Trop souvent, les rétros aboutissent à une liste d'actions beaucoup trop ambitieuse, et on se retrouve à ne pas réaliser la moitié des choses à faire, et les points réalisés sont en général les actions marginales sans grand impact (il ne faudrait pas modifier l'ordre établi non plus).
A quoi servent ces rétrospectives ? Est-ce que l'équipe améliore ses pratiques ? Est-ce que le travail réalisé s'en trouve amélioré ?

### Coaching personnel
Parfois, on s'approche de méthodes de coaching personnel.
On traite de sujet hyper personnels qui ne devraient pas être abordés dans un contexte professionnel ou en tout cas, pas en réunion devant toute l'équipe.
On peut essayer de changer la façon dont les gens travaillent, mais pas la façon dont les gens sont.
Lead, don't tell : montrer par l'exemple, pas de comportement prescriptif

### Energizers
Une autre dérive de l'agilité qu'on peut observer, c'est l'utilisation à outrance d'energizers ou de gamification extrême de toutes les réunions.
Leur utilité peut se comprendre dans certaines conditions (pour faire passer certains messages ou concepts par exemple), mais pas systématiquement, pas de manière obligatoire, pas en mettant les personnes dans des conditions qu'ils considèrent inconfortables ou dégradantes. Le bizutage est interdit, pourquoi vouloir continuer ce genre de comportement en entreprise ?
De plus, l'utilisation de jeux, même si cela permet de faire passer facilement des messages, accentue l'image décrédibilisante des développeurs qui seraient des éternels enfants, que l'on peut amadouer avec des nerfs, des bonbons ou des tables de ping-pong.

## Non universalité
Même si l'agilité est désormais quelque chose de très populaire, sachez que ce n'est pas quelque chose d'universel.

### Transparence et communication
L'agilité implique une transparence et une surexposition du travail au quotidien.
Cela implique de travailler en équipe, de communiquer en permanence, d'accepter la revue de son code par une autre personne,
d'accepter de revenir sur des choses déjà faites, de remettre en question sa manière de travailler...
Tout le monde n'est pas forcément à l'aise avec ces pratiques.
Que faire des personnes qui n'arrivent pas à travailler dans ces conditions ?
Faut-il les pousser à rentrer dans le moule, les mettre en permanence en dehors de leur zone de confort ?
Faut-il les exclure des équipes ?

### Support à l'innovation
Même si ces méthodes sont à la mode, elles ne sont pas forcément bonnes pour tous et dans tous les contextes.
A l'origine, l'agilité était mise en place comme support à l'innovation. Ce n'est pas très étonnant que ce soient les startups qui aient
commencé à l'utiliser de manière intensive. Leurs besoins de tester le produit le plus vite possible, de corrections, de changement de cap étaient essentiels à leur survie.
Ce qu'on constate aujourd'hui, c'est que les avantages de l'agilité ne sont plus mis en oeuvre à bon escient.
On ne prend plus le temps nécessaire à la réflexion pour innover. Ce qui a été perçu de l'agilité, c'est le time to market.
On va réduire les coûts et les durées de développement. On est dans l'urgence permanente de livrer des nouvelles fonctionnalités.
Vous devez entendre souvent des développeurs demander à "souffler" un peu ? Pas étonnant.
Cette course permanente pour vider le backlog peut être épuisante à terme, et ce n'est absolument pas ce qui est préconisé par l'agilité.

## Inventez votre propre méthode
Mais nous avons une bonne nouvelle ! Votre équipe n'est peut-être pas agile, mais si son mode de fonctionnement lui convient,
si elle résout les problèmes qui la concernent et s'améliore au fil du temps, si ses membres se sentent bien, c'est une équipe avec laquelle il fait bon travailler !

## Pragmatisme
Vous avez le droit de picorer les bonnes pratiques qui vous sont utiles dans votre contexte. Mais ayez conscience que vous être en phase de transformation et d'amélioration continue.
L'agilité n'est pas un but à atteindre, mais juste une façon de marcher dans la direction dans laquelle l'équipe souhaite aller.
L'agilité, ce ne sont pas des tampons de certifications à collectionner comme des cartes Panini.
L'agilité n'est pas non plus un buzzword à ajouter à vos descriptions d'offres d'emploi, à côté du babyfoot et des pizzas. C'est un réel état d'esprit d'entreprise et des valeurs qui impliquent pas mal de choses en contrepartie.
Et vous savez quoi ? Il n'y a pas que les développeurs qui commencent à rejeter cette chimère qu'est devenue l'agilité. Beaucoup d'agilistes, de coachs, ne se reconnaissent plus dans les messages qui sont désormais passés. Certains n'osent d'ailleurs même plus parler d'agilité...

## Artisanat
Tout n'est pas perdu ! Nous avons le pouvoir de changer les choses :-)
Vous êtes les créateurs de valeur de l'entreprise, vous êtes les artisans qui façonnent les produits ! Ne laissez pas les managers vous dicter les outils à utiliser pour bien faire votre travail !
Lorsqu'un artisan intervient chez vous, est-ce que vous lui imposez quels outils il doit utiliser ? Si il vient accompagné d'un apprenti, est-ce que vous lui refusez sa présence (parce que bon, il va le ralentir et y'a pas besoin de deux personnes pour faire ce boulot quand même).
Pourquoi est ce qu'on n'accepte pas ce genre de comportement dans nos métiers ? Pourquoi le binômage est-il tant décrié par les managers ? Pourquoi est ce que les développeurs expérimentés sont considérés comme des personnes immatures qui n'ont pas réussi à évoluer en chef de projet, des éternels ados ? Pourquoi une telle infantilisation ?

Vous êtes responsables de vos outils et de vos méthodes de travail. L'agilité, c'est dans l'équipe de développement qu'elle née, pas suite à des décisions de managers et de directeurs.
Vous allez devoir maintenir demain le code que vous produisez aujourd'hui. Alors pourquoi vous mettre des bâtons dans les roues tous seuls ? Pourquoi ne pas mettre la priorité sur la qualité, le partage des connaissances au sein de l'équipe, la facilité de relecture du code, la compréhension du métier, ... ?
En acceptant de faire du code de mauvaise qualité, dans des conditions "agiles", c'est la santé de votre projet, de l'équipe que vous mettez en péril. Et vous risquez de mettre la votre en péril également (nous en avons fait l'amère expérience, mais c'est un autre sujet ^^ )
Commencez petit, testez des choses, voyez si ça vous convient, itérez, progressez, ... N'ayez pas peur de tenter de nouvelles approches. Au pire, vous risquez d'apprendre quelque chose ;-)
Si vous êtes ici, c'est que vous avez à coeur de vous améliorer, d'apprendre de nouvelles choses, ... Et si ces pratiques de développement vous font peur, vous pouvez également les tester dans un environnement "safe", au cours de coding dojo par exemple.
<Moment pub>Et n'hésitez pas à venir discuter avec d'autres développeurs dans les meetups Software Crafters</Moment Pub>.
L'agilité, ce n'est pas appliquer à la lettre toutes les pratiques et les cérémonies de tel ou tel framework. L'agilité s'appelle ainsi car son but est de s'adapter aux équipes, d'évoluer au fil du temps.

## Agile != A.G.I.L.E
Vous pouvez tout à fait être agiles dans votre travail quotidien, sans pour autant être estampillés ou certifiés A.G.I.L.E.
L'agilité, c'est un état d'esprit, des valeurs, une envie de travail bien fait et utile à l'utilisateur final.
Pas la peine de chercher un nouveau nom pour rebaptiser la volonté de faire du travail de qualité, dans un environnement bienveillant pour produire des logiciels utiles aux utilisateurs. Soyez juste agiles :-)
