# [Le projet Phoenix : un roman sur l'informatique, le DevOps et la réussite de votre entreprise](https://www.goodreads.com/book/show/17255186-the-phoenix-project)

  

- [À propos de l'histoire](#à-propos-de-l'histoire)

- [À propos de DevOps](#about-devops)

- [Les trois voies](#les-trois-voies)

- [Les quatre types de travail](#les-quatre-types-de-travail)

  

_Le projet Phoenix_ montre comment un conflit fondamental et chronique entre le développement et les opérations informatiques prédit l'échec de l'ensemble de l'organisation informatique.

## À propos de l'histoire

### Définition du changement

Un « changement » est toute activité physique, logique ou virtuelle concernant les applications, les bases de données, les systèmes d'exploitation, les réseaux ou le matériel qui pourrait avoir un impact sur les services fournis.

### Goulots d'étranglement

Les travaux ne devraient pas être libérés en fonction de la disponibilité de la première station. Au lieu de cela, il doit être basé sur le rythme avec lequel la ressource goulet d’étranglement peut consommer le travail.

Sur la _Théorie des Contraintes_, toute amélioration apportée _partout en dehors du goulot d'étranglement_ est une illusion. Toute amélioration apportée après le goulot d'étranglement est inutile, car elle restera toujours affamée, attendant le travail du goulot d'étranglement. Et toute amélioration apportée avant le goulot d’étranglement entraîne simplement une accumulation de stocks supplémentaires au niveau du goulot d’étranglement.

### Indispensable people

Peut-être qu’une partie d’entre eux est réticente à partager les connaissances qu’ils possèdent. Ils se sont donc rendus pratiquement impossibles à remplacer.

Les personnes indispensables travaillent comme des contraintes pour l'entreprise. Chaque fois que vous laissez ces personnes réparer quelque chose que personne d’autre ne peut reproduire, ces personnes deviennent plus intelligentes et le système tout entier devient plus stupide.

Une solution possible est d'isoler ces profils et de disposer d'un pool de personnes pour travailler sur les mêmes problématiques et être les seuls à accéder à l'indispensable avec l'encadrement des managers.

> Ce n'est pas le capital initial qui vous tue, ce sont les opérations et la maintenance en aval.

### Le but

Dans la plupart des usines, il existe un très petit nombre de ressources, qu'il s'agisse d'hommes, de machines ou de matériaux, qui dictent le rendement de l'ensemble du système. Nous appelons cela la contrainte ou le goulot d'étranglement.

Étapes de mise au point :

1. **Identifiez la contrainte.** Toute amélioration non apportée à la contrainte n'est qu'une illusion.

2. **Exploitez la contrainte.** Assurez vous que la contrainte ne permet pas de perdre du temps. Jamais. Il ne devrait jamais attendre quoi que ce soit sur une autre ressource.

3. **Subordonnez la contrainte.** Dans la _Théorie des contraintes_, ceci est généralement implémenté par le Drum-Buffer-Rope. Le Boy Scout le plus lent de la troupe dicte en fait le rythme de marche de l'ensemble du groupe. Vous déplacez donc le garçon le plus lent en tête de la file pour éviter que les enfants n'aillent trop loin. Dans une usine, vous devez libérer du travail en fonction du rythme auquel il pourrait être consommé par le goulot d'étranglement. L'utilisation d'un tableau _Kanban_ pour publier le travail et contrôler les _travaux en cours_ pour le développement et les opérations informatiques peut être utile.

### Résultats

Il est plus important de pouvoir supprimer le travail inutile du système que de pouvoir y consacrer davantage de travail. Vous devez savoir ce qui compte pour la réalisation des objectifs commerciaux.

**Ce qui compte, ce sont les résultats, pas le processus, ni les contrôles ni le travail que vous effectuez.**

### Dynamique d'équipe

Une grande équipe ne signifie pas qu’elle compte les personnes les plus intelligentes. Ce qui a rendu ces équipes formidables, c’est que tout le monde se faisait confiance. Le livre _Cinq dysfonctionnements d'une équipe_ montre que pour avoir une confiance mutuelle, il faut être vulnérable.

L'informatique n'est pas seulement un département. L'informatique est une compétence que nous devons acquérir en tant qu'entreprise dans son ensemble. Les gens doivent se regrouper en grandes équipes où tous peuvent se faire confiance pour réussir.

### Travaux imprévus

Être toujours en train de se bousculer, de devoir prendre des raccourcis, ce qui conduit à des applications fragiles en production qui aboutissent à des travaux plus imprévus et à la lutte contre les incendies sont la conséquence du non-remboursement de la _dette technique_.

La _dette technique_ vient du fait de prendre des raccourcis, ce qui peut avoir du sens à court terme. Mais comme la dette financière, les coûts des intérêts composés augmentent avec le temps. Si une organisation ne rembourse pas sa dette technique, chaque calorie de l’organisation peut être dépensée simplement en payant des intérêts, sous la forme de travaux imprévus.

Les travaux non planifiés coûtent très cher, car les travaux non planifiés se font au détriment des travaux planifiés.

La dette technique garantira que le seul travail effectué sera un travail imprévu.

Le travail imprévu a un autre effet secondaire. Lorsque vous passez tout votre temps à lutter contre les incendies, il vous reste peu de temps ou d'énergie pour la planification. Lorsque vous réagissez, vous n'avez pas assez de temps pour effectuer le dur travail mental consistant à déterminer si vous pouvez accepter un nouveau travail.

Les dirigeants doivent dire _non_. Les entreprises ne peuvent pas se permettre de laisser leurs équipes de direction prendre les commandes. Les dirigeants sont payés pour réfléchir, pas seulement pour agir.

### Priorisation

Mieux prioriser ne résoudra pas le problème. Il faut penser aux contraintes. L’objectif est d’augmenter le débit de l’ensemble du système, et pas seulement d’augmenter le nombre de tâches effectuées.

Dans le cas de priorités concurrentes, vous gèlez le reste, pas de multitâche autorisé à moins de maîtriser toutes vos contraintes et d'être réellement capable de paralléliser.

### Capacité et demande

Rassembler les conditions préalables dont vous avez besoin avant de pouvoir terminer le travail vous permet d'établir une liste de ressources. Une nomenclature ainsi que la liste des centres de travail requis et l'itinéraire, ainsi que les bons de travail et les ressources, vous pourrez enfin comprendre quelle est votre capacité et votre demande. Cela vous permettra enfin de savoir si vous pouvez accepter de nouveaux travaux et ensuite de pouvoir réellement planifier les travaux.

### Résilience

La troisième voie consiste à garantir que nous mettons continuellement des tensions dans le système, afin de renforcer continuellement les habitudes et d'améliorer quelque chose. L'ingénierie de la résilience nous apprend qu'il suffit d'injecter régulièrement des fautes dans le système, en les effectuant fréquemment, pour les rendre moins douloureuses.

### Amélioration déclarée

Ce que vous améliorez n’a presque pas d’importance, du moment que vous améliorez quelque chose. Pourquoi? Parce que si vous ne vous améliorez pas, l’entropie garantit que votre état se détériore, ce qui garantit qu’il n’y a aucun chemin vers zéro erreur, zéro accident du travail et zéro perte.

Un _kata_ est une répétition qui crée des habitudes, et ce sont les habitudes qui permettent la maîtrise. Qu'il s'agisse d'entraînement sportif, d'apprentissage d'un instrument de musique ou de formation dans les Forces Spéciales, rien n'est plus à maîtriser que la pratique et les exercices. Si vous souhaitez créer une véritable culture d’amélioration, vous devez créer ces habitudes.

### Transferts de temps

La gestion des transferts est tout aussi importante que la limitation de la libération du travail. Un élément essentiel de la Deuxième Voie consiste à rendre visibles les temps d'attente, afin que vous sachiez quand votre travail passe des jours dans la file d'attente de quelqu'un, ou pire, si le travail a reculé parce qu'il n'a pas les pièces nécessaires ou nécessite une reprise.

### Erreur de portée

> Ce type est comme le responsable qualité qui demande à son groupe d'écrire des millions de nouveaux tests pour un produit que nous ne livrons même plus, puis de déposer des millions de rapports de bogues pour des fonctionnalités qui n'existent plus.

Tout ce qui n’a pas pour but d’aider l’entreprise à survivre n’est tout simplement que des détails techniques sans importance.

### Tableau Kanban

Un tableau Kanban est l’un des principaux moyens utilisés par les usines de fabrication pour planifier et gérer le travail dans le système. Il rend visible la demande et les en-cours et est utilisé pour signaler les stations en amont et en aval.

Vous pouvez prendre en compte les demandes de service les plus fréquentes, documenter exactement les étapes et les ressources qui peuvent les exécuter, et chronométrer la durée de chaque opération.

Fournir aux cadres et aux travailleurs les outils dont ils ont besoin pour faire leur travail est l'une de nos principales responsabilités.

### Gérer les transferts

Le temps d'attente est le « pourcentage de temps occupé » divisé par le « pourcentage de temps inactif ». Si une ressource est occupée à cinquante pour cent, elle est alors inactive à cinquante pour cent. Le temps d'attente est de cinquante pour cent divisé par pour cent, soit une unité de temps. Disons que c'est une heure. Ainsi, en moyenne, notre tâche attendrait dans la file d'attente pendant une heure avant d'être exécutée.

Si une ressource est occupée à quatre-vingt-dix pour cent, le temps d'attente est de « quatre-vingt-dix pour cent divisé par dix pour cent », soit neuf heures. Une tâche attendrait dans la file d'attente neuf fois plus longtemps que si la ressource était inactive à cinquante pour cent.

    TEMPS D'ATTENTE = %BUSY / %IDLE

    TEMPS D'ATTENTE

    100 ┤                             ■

     90 ┤                             ■

     80 ┤                             ■

     70 ┤                             ■

     60 ┤                             ■

     50 ┤                             ■

     40 ┤                            ■

     30 ┤                           ■  

     20 ┤                         ■■  

     10 ┤                     ■■■■

        ┤■■■■■■■■■■■■■■■■■■■■■

        └──┬──┬──┬──┬──┬──┬──┬──┬──┬──┬── % DE RESSOURCES OCCUPÉES

      0    10 20 30 40 50 60 70 80 90 100

Créer et prioriser le travail au sein d’un département est difficile. La gestion du travail entre les départements doit être au moins dix fois plus difficile.

Tout le monde a besoin de temps libre, ou de temps libre. Si personne n’a de temps libre, WIP reste bloqué dans le système. Ou plus précisément, coincé dans les files d’attente, en train d’attendre.

Parfois, certaines tâches ressemblent à une tâche effectuée par une seule personne, mais ce n'est pas le cas. Parfois, ils impliquent plusieurs étapes avec plusieurs transferts entre plusieurs personnes. Si ces personnes sont toujours occupées, les tâches resteront indéfiniment bloquées dans les files d’attente.

### La première voie

Il s’agit d’une pensée systémique, confirmant toujours que c’est l’organisation dans son ensemble qui atteint son objectif, et non seulement une partie de celle-ci.

* Sommes-nous compétitifs ?

* Comprendre les besoins et les désirs des clients : savons-nous quoi construire ?

* Portefeuille de produits : Avons-nous les bons produits ?

* Efficacité de la R&D : peut-on la construire efficacement ?

* Délai de mise sur le marché : Pouvons-nous l'expédier suffisamment tôt pour avoir une importance ?

* Pipeline de ventes : pouvons-nous convertir les produits en prospects intéressés ?

* Sommes-nous efficaces ?

* Livraison à temps aux clients : les clients obtiennent-ils ce que nous leur avons promis ?

* Fidélisation de la clientèle : gagnons-nous ou perdons-nous des clients ?

* Précision des prévisions de ventes : pouvons-nous en tenir compte dans notre processus de planification des ventes ?

Vous devez quitter le domaine de l'informatique pour découvrir dans quels domaines l'entreprise s'appuie sur l'informatique pour atteindre ses objectifs. Vous devez identifier les domaines dans lesquels vous avez sous-estimé l'informatique, les domaines dans lesquels certaines parties des processus et de la technologie que vous gérez compromettent activement la réalisation des objectifs commerciaux. Et deuxièmement, lorsque l'informatique est peut-être trop vaste et que vous vous concentrez sur les problèmes qui apportent peu de valeur à l'entreprise.

### La deuxième voie

Créez des boucles de rétroaction constantes depuis les opérations informatiques vers le développement, en concevant la qualité du produit dès les premières étapes. Pour ce faire, vous pouvez disposer de versions de neuf mois. Vous avez besoin d’un feedback beaucoup plus rapide. Vous devez réduire la taille de vos lots.

Idéalement, le flux de travail ne devrait aller que dans une seule direction : vers l’avant. Lorsque le travail recule, cela s'appelle du _déchet_.

Une conséquence inévitable des longs cycles de publication est que vous n'atteindrez jamais les objectifs de taux de rendement interne, une fois pris en compte le coût de la main-d'œuvre.

### _Merci_ temps

Le temps de cycle nécessaire pour répondre à la demande des clients. Si une opération dans le flux de travail prend plus de temps que le temps takt, vous ne serez pas en mesure de répondre à la demande des clients.

### Infrastructure automatisée

Tant que le code n’est pas en production, aucune valeur n’est réellement générée. Afin de réduire le temps de changement et de permettre un cycle de déploiement plus rapide, vous devez automatiser le processus de création et de déploiement, en reconnaissant que l'infrastructure peut être traitée comme du code. Cela permet de créer une procédure de création et de déploiement d’environnement en une seule étape. Ceci a été défini par les livres _Continuous Delivery_ et _Lean Startup_.

Vous devez tout mettre en contrôle de version. Pas seulement le code, mais tout ce qui est nécessaire pour créer l'environnement. Ensuite, vous devez automatiser l’ensemble du processus de création d’environnement. Vous avez besoin d'un pipeline de déploiement dans lequel vous pouvez créer des environnements de test et de production, puis y déployer du code, entièrement à la demande. C'est ainsi que vous réduisez vos temps de configuration et éliminez les erreurs, afin que vous puissiez enfin correspondre au rythme de changement auquel le développement fixe le tempo.

Éliminez les humains du secteur du déploiement.

Si vous ne parvenez pas à surpasser vos concurrents en matière d'expérimentation et de rapidité de commercialisation et en termes d'agilité, vous êtes coulé. Les fonctionnalités sont toujours un pari. Si vous avez de la chance, dix pour cent obtiendront les avantages souhaités. Ainsi, plus vite vous pourrez commercialiser et tester ces fonctionnalités, mieux vous vous porterez. Par ailleurs, vous remboursez également l'entreprise plus rapidement pour l'utilisation du capital, ce qui signifie que l'entreprise commence également à gagner de l'argent plus rapidement.

Un grand nombre de déploiements par jour vous permet de corriger les bugs plus rapidement, d'obtenir des améliorations de performances plus rapidement, d'évoluer si nécessaire et d'exécuter des tests A/B dès que possible.

### Intervalle de sprint

En réduisant l'intervalle de sprint, vous réduisez votre horizon de planification pour prendre et exécuter des décisions plus fréquemment, au lieu de vous en tenir à un plan élaboré il y a près d'un mois.

### DevOps

Une super-tribu qui va au-delà du développement, des opérations ou de la sécurité. Il s'agit de la gestion des produits, du développement, des opérations informatiques et même de la sécurité de l'information qui travaillent ensemble et se soutiennent mutuellement.

## À propos du DevOps

### Pourquoi?

Une mise sur le marché plus rapide des fonctionnalités, une satisfaction client, une part de marché, une productivité et un bonheur des employés accrus, tout en permettant aux organisations de gagner sur le marché. La technologie est devenue le processus dominant de création de valeur et un moyen de plus en plus important d’acquisition de clients.

Les entreprises les plus performantes déploient des fonctionnalités plus rapidement, tout en offrant des niveaux de fiabilité, de stabilité et de sécurité de premier ordre, leur permettant de surpasser leurs concurrents sur le marché. Fournir ces niveaux élevés de fiabilité _exige_ en fait que des modifications soient apportées fréquemment.

Les entreprises les plus performantes ont également des performances organisationnelles nettement meilleures : elles sont deux fois plus susceptibles de dépasser leurs objectifs de rentabilité, de part de marché et de productivité, et certains indices suggèrent qu’elles ont également de bien meilleures performances sur les marchés des capitaux.

Tout le monde valorise les exigences non fonctionnelles (par exemple, qualité, évolutivité, facilité de gestion, sécurité, opérabilité) autant que les fonctionnalités. Pourquoi? Parce que les exigences non fonctionnelles sont tout aussi importantes pour atteindre les objectifs commerciaux.

Nous avons une culture de collaboration et de confiance élevée, où chacun est responsable de la qualité de son travail. Au lieu des processus d'approbation et de conformité, caractéristiques d'une culture de gestion de commandement et de contrôle à faible confiance, nous nous appuyons sur l'examen par les pairs pour garantir que chacun a confiance dans la qualité de son code.

En outre, il existe une culture fondée sur des hypothèses, qui exige que chacun soit un scientifique, ne prenant aucune hypothèse pour acquise et ne faisant rien sans mesurer. Pourquoi? Parce que nous savons que notre temps est précieux. Nous ne passons pas des années à créer des fonctionnalités dont nos clients ne veulent pas réellement, à déployer du code qui ne fonctionne pas ou à réparer quelque chose qui n'est pas réellement le problème. Ces facteurs contribuent à notre capacité à proposer sur le marché des fonctionnalités intéressantes qui ravissent nos clients et aident notre organisation à gagner.

### D'où ça vient ?

DevOps est le résultat de l'application des principes Lean à la chaîne de valeur informatique. Ces principes s'appuient sur plus d'un siècle de saines pratiques de gestion.

## Les trois façons

### La première voie

Il s'agit du flux de travail de gauche à droite, du développement aux opérations informatiques jusqu'au client. Afin de maximiser les flux, nous avons besoin de petites tailles de lots et d'intervalles de travail, de ne jamais transmettre de défauts aux centres de travail en aval et d'optimiser constamment les objectifs globaux.

Les pratiques comprennent : la construction, l'intégration et le déploiement continus, la création d'environnements à la demande, la limitation des travaux en cours et la création de systèmes et d'organisations sûrs et modifiables en toute sécurité.

### La deuxième voie

Il s'agit d'un flux constant de retours rapides de droite à gauche à toutes les étapes de la chaîne de valeur, en l'amplifiant pour garantir que nous pouvons éviter que les problèmes ne se reproduisent ou permettre une détection et une récupération plus rapides. Ce faisant, nous créons de la qualité à la source, en créant ou en intégrant les connaissances là où nous en avons besoin.

Ces pratiques incluent : « l'arrêt de la chaîne de production » lorsque nos builds et nos tests échouent, privilégiant l'amélioration du travail quotidien par rapport au travail quotidien ; créer des suites de tests automatisés rapides pour garantir que le code est toujours potentiellement déployable, créant des objectifs partagés et des difficultés partagées entre le développement et les opérations informatiques ; et créer une télémétrie de production omniprésente afin que chacun puisse voir si le code et les environnements fonctionnent comme prévu et si les objectifs du client sont atteints.

### La troisième voie

Il s'agit de créer une culture qui favorise deux choses : l'expérimentation continue, qui nécessite de prendre des risques et d'apprendre des succès et des échecs, et de comprendre que la répétition et la pratique sont la condition préalable à la maîtrise.

L’expérimentation et la prise de risques nous permettent d’améliorer sans cesse notre système de travail.

Les pratiques incluent : Créer une culture d'innovation et de prise de risque (par opposition à la peur ou à la prise d'ordres inconsidérée) et de confiance élevée (par opposition à une faible confiance, au commandement et au contrôle), en allouant au moins vingt pour cent du développement et de l'informatique. Les opérations vers des exigences non fonctionnelles et le renforcement constant du fait que les améliorations sont encouragées et célébrées.

## Les quatre types de travaux

* **Projets d'affaires**. Il s’agit d’initiatives commerciales, dont la plupart des projets de développement englobent.

* **Projets informatiques internes**. Projets d'infrastructure ou d'opérations informatiques que des projets d'entreprise pourraient créer, ainsi que des projets d'amélioration générés en interne. Souvent, ceux-ci ne font l’objet d’un suivi centralisé nulle part, mais résident plutôt chez les responsables du budget. Cela crée un problème lorsque les opérations informatiques constituent un goulot d'étranglement, car il n'existe pas de moyen simple de savoir quelle grande partie de la capacité est déjà affectée aux projets internes.

* **Changements**. Générés à partir des deux types de travaux précédents et sont généralement suivis dans un système de billetterie.

* **Travail de mot ou de récupération non planifié**. Incidents et problèmes opérationnels. Cela se fait toujours au détriment des autres engagements professionnels prévus.