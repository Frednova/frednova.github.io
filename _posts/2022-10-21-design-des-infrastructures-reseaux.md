---
title: Design des infrastructures réseaux
date: 2022-10-21 8:30:00 +0100
categories: [cesi, cours, 1ère année, MICSI]
tags: [infrastructures, reseaux, rosselle, grand oral]
---

#### Intervenant Grégory Rosselle, notes de Frédéric Prince

Comprendre les stratégies d'entreprise, les parties financières, faire le lien entre le métier et la technique. Etre capable de se projeter à long terme.

On peut parler d'urbanisation des SI, avec des pôles dédiés, des artères.

---

**Mission de l'architecte** :
### Concevoir une chose qui sera perçue différemment selon son interlocuteur. Parler avec précision, mais être compris par tous les profils.

**Interlocuteurs** :
- L'utilisateur du produit. La personne qui sera en contact avec l'IHM. De son point de vue, l'application est une succession d'écrans d'information qu'elle manipule. Sa satisfaction réside dans la prise en compte de ses observations qui concernent l'ergonomie, et les fonctionnalités apparentes.
- Le client. Le client est celui qui achète le produit, qui financera donc, directement ou indirectement, son dveloppement. Sa satisfaction passe par l'espérance d'un gain, ou d'un ROI, souvent à court terme.
- Le décideur. Il est souvent l'une des facettes ou l'un des conseillers du client. Ses préoccupations vont à l'assurance qualité, à la pérennité du produit. Il sera donc plus sensible aux qualité établies sur le long terme du projet. 
- Le commercial. Légion sont les commerciaux qui vendent au quart du prix. Il ne faut jamais permettre à un commercial d'interroger un développeur sur les délais de réalisation.
- L'équipe de développement. Se souvenir de toujours multiplier par 5 un délai annoncé par un développeur.
- Le chef de projet est l'interlocuteur, et très pragmatiquement, le plus de documentation. Il attend une certaine stabilité du cahier des charges, et des objectifs clairs et techniques.
- Le responsable du SI. Sa préoccupation est la préservation des investissement et des matériels déjà réalisés et en place dans l'entreprise. Son souci est l'intégration future du produit dans ce contexte, ainsi que ses modalités d'administration.

Lister les services fournis par le SI à nos utilisateurs. Et à quel coùt.

Etre capable de partager la vision de chacune de ces catégories, et donc de comprendre les problèmes de chacun à leur niveau.

Chacun de ses interlocuteurs doit être entendu, et chacun doit recevoir une réponse dans son propre langage. Le projet sera donc expliqué, modélisé, en autant de documents relétant autant de points de vue que d'interlocuteurs.

### Rappel historique

1822 - La machine de Babbage

![La machine de Babbage](https://upload.wikimedia.org/wikipedia/commons/a/a4/Analytical_Engine_%282290032530%29.jpg)
_L'ordinateur mécanique de Babbage_

1940 - L'ordinateur élécromécanique

![Enigma](https://download.vikidia.org/vikidia/fr/images/1/1e/Enigma_%C3%A0_quatre_rotors.jpg)
_Enigma_

Voir aussi Alan Turring et la bombe de Turing, qui parallélise des machines Enigma et créé un algorithme, une machine intellectuelle. Il montre mathématiquement qu'on peut convertir un problème humain en une machine éléctro-mécanique.

![La bombe de Turing](https://www.apprendre-en-ligne.net/crypto/Enigma/bombe.jpg)
_Une bombe de Turing, plusieurs Enigma en parallèle_

1950 - Von Neumann construit le 1er ordinateur éléctronique

![L'ENIAC](https://i.go-travels.com/img/do-more/what-is-eniac-1.jpg)
_L'ENIAC, 150 000 watts..._

A l'époque, le programme Apollo veut envoyer des hommes sur la Lune. C'est envoyer un "missile" et calculer sa trajectoire.

Voir stéganographie et langue des oiseaux.

1971 - Arpanet
1974 - Intel vend le premier processeur 4004 à 108 Khz
1974 - Invention de la carte à puce

Invention du premier disque dur, avec par exemple le RAMAC 305, une tonne, 5 Mo de stockage.

Les nerds du club de trains éléctriques du MIT inventent l'Altair 8080, 8 Ko de ram et lecteur de disquette.

Puis Steve Wozniak se fabrique l'Apple 1.

![L'Apple 1](https://i0.wp.com/www.apple2history.org/wp-content/uploads/2008/11/applei.jpg?ssl=1)
_L'Apple 1, vendu 666$_

L'Apple II est une réussite commerciale, vendu de 1977 à 1988. IBM cherche à répliquer avec l'IBM PC. Mais ils n'ont pas les compétences en interne pour développer l'OS et lancent un appel d'offre. Bill Gates remporte le marché sans avoir d'OS, mais achète un noyau et développe juste un "shell". Il demande à pouvoir vendre son OS indépendemment, ce qu'IBM accepte en pensant faire une bonne affaire.
On connait la suite.

Voir et lire Andrew Tanenbaum.

### Architecture client/serveur
**Architecture centralisée - 1970** : l'ordinateur central effectue tous les traitements, les terminaux gèrent la saisie et l'affichage (terminaux passifs). 

**Architecture décentralisée - 1980** : arrivée des PC. On dédie des machines à des applications (serveurs), et on a des clients.

**Modèle peer to peer** : tout le monde est client et serveur. Devient plus efficace avec le nombre, à l'inverse du modèle client/serveur.

---

Voir "Le dessous des cartes" sur les cables sous-marins.

--- 

Penser à la clause de réversibilité.
