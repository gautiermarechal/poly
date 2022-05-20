---
title: L'abstraction dans l'esprit et les ordinateurs
date: 2021-02-08T23:36:38+02:00
cover:
  image: "/images/abstraction-mind-computers/abstraction-0.png"
  alt: "Abstraction"
  relative: false
categories:
  - Informatique
  - Science
  - Psychologie
  - Philosophie
---

Le concept d'abstraction est fondamentalement essentiel et enraciné dans l'existence humaine. Depuis 200 000 ans, les humains ont accumulé un ensemble immense de connaissances dans de nombreux domaines différents. Cela a été rendu possible grâce à l'abstraction, un concept qui nous aide à développer nos connaissances de différentes manières. Nous explorerons ce qu'est l'abstraction dans une perspective philosophique, pour nous aider à comprendre l'abstraction en informatique et dans le cerveau humain.

L'une des réflexions les plus populaires sur l'abstraction en philosophie a été elaborée par John Locke en 1689. Dans le livre III, Locke mentionne que dans le langage, nous utilisons des termes généraux pour parler de éléments particuliers. En effet, Locke suppose qu'il se trouve trop de détails auxquels penser, et ce serait une tâche bein trop importante pour l'esprit de se souvenir de tous ces détails. Par conséquent, nous utilisons des termes généraux comme des mots qui classent des éléments spécifiques dans un groupe. Cette classification est rendue possible par l'abstraction.

![John Locke — Philosophe britannique (1632–1704)](/images/abstraction-mind-computers/abstraction-1.png "John Locke — Philosophe britannique (1632–1704)")

Par exemple, le mot « cheval » englobe tout ce qui ressemble à un cheval dans votre perception. Tous ces éléments particuliers du groupe sont liés par l'essence qui fait que chaque élément fait partie du groupe. Et cette essence est le résultat des idées abstraites que vous avez des chevaux. L'abstraction forme l'essence de l'esprit et crée la connaissance dans son ensemble.

Maintenant, qu'est-ce qui est clairement une abstraction ? Les racines du mot définissent quelque chose d'abstrait comme "quelque chose tiré ou éloigné". C'est exactement le processus dans lequel l'esprit s'engage lorsqu'il regroupe des idées comme mentionné ci-dessus. Il convertit l'élément réel en une apparence (ou idée) mentale et détache cette dernière de toute caractéristique de la vie réelle comme l'espace ou le temps.

![Espace et Temps](/images/abstraction-mind-computers/abstraction-2.png#center)

Alors voici le processus d'abstraction de l'esprit:

1. L'esprit identifie une chose réelle
2. Le convertit en idée
3. Se détache de la vie réelle
4. Observe l'essence de l'élément
5. Regroupe l'élément sous une idée générale = une idée abstraite.

Identifions maintenant l'abstraction en informatique, un domaine créé par l'homme, et voyons comment ce processus d'abstraction peut se refléter dans ce domaine.

Un ordinateur contient un processeur, le cerveau de l'ordinateur. Le CPU reçoit du courant électrique à travers son architecture. Le câblage à l'intérieur du CPU interprétera un courant électrique comme un 1 et une absence de courant électrique comme un 0. Ces ensembles de 1 et de 0 sont des instructions envoyées de la RAM au CPU, lui disant d'exécuter certaines tâches. Ensuite, lorsque le processeur connait ses tâches à accomplir, il traite à nouveau les instructions sous forme de courant électrique vers d'autres composants de la carte mère.

Pour exécuter de telles tâches, le CPU doit effectuer des calculs sous la forme de calculs. Ces calculs sont rendus possibles avec des portes logiques. Les portes logiques sont des composants électroniques appelés transistors, que l'on retrouve sur le tableau électrique. Une porte logique accepte le courant électrique en entrée et produira un 0 ou un 1. La sortie dépend de l'entrée, et il existe différentes portes logiques qui auront une logique différente pour produire le résultat.

![Tous les types de portes logiques et leurs tables logiques](/images/abstraction-mind-computers/abstraction-3.png#center, "Tous les types de portes logiques et leurs tables logiques")

Prenons la porte AND. Il sort un 1 seulement si toutes les entrées sont des 1, sinon il sort un 0.
Donc si on donne 1 et 0, le résultat sera 0.

Imaginez maintenant une carte électronique entière constituée d'un grand nombre de ces portes, et les possibilités de calculs.

![La porte logique ET](/images/abstraction-mind-computers/abstraction-4.png#center, "La porte logique ET")

Toutes les choses mentionnées ci-dessus sont au niveau physique, ou le niveau d'abstraction le plus bas possible. Cela signifie que nous sommes au plus proche de la réalité, car l'électricité est un processus naturel d'électrons circulant à travers la matière. Maintenant, augmentons le niveau d'abstraction du courant électrique à un ensemble structuré d'instructions.

D'où viennent toutes ces instructions à l'origine ?

La réponse: les programmes. Les programmes informatiques ne sont qu'un moyen pour les humains d'envoyer des instructions au processeur. Nous sommes maintenant à un niveau d'abstraction supérieur au niveau physique.

![Compilateur](/images/abstraction-mind-computers/abstraction-5.png#center, "Compilateur")

Dans les programmes informatiques, il existe plusieurs niveaux d'abstraction en fonction de leur "distance" par rapport aux composants physiques de la carte mère.

![Niveaux d'abstraction — Langages informatiques](/images/abstraction-mind-computers/abstraction-6.png#center, "Niveaux d'abstraction — Langages informatiques")

Le langage de programmation le plus bas est le langage machine, qui contient des fonctions sous forme de bits, envoyés directement au CPU.

![Instruction en code machine](/images/abstraction-mind-computers/abstraction-7.png#center, "Instruction en code machine")

Ensuite, si nous augmentons le niveau d'abstraction, ou en d'autres termes, nous nous détachons encore plus de la réalité du courant électrique, nous avons le langage d'assemblage.

Le langage d'assemblage contient des instructions compréhensibles par l'homme pour communiquer avec le processeur. Par exemple, l'instruction « MOV » permet aux langages d'assemblage de dire au processeur de déplacer les données à un endroit spécifique.

![Instruction en langage d'assemblage](/images/abstraction-mind-computers/abstraction-8.png#center, "Instruction en langage d'assemblage")

Remontons maintenant au niveau d'abstraction supérieur et voyons les langages de haut niveau.

Les langages de haut niveau sont des langages de programmation avec lesquels les programmeurs peuvent utiliser le langage naturel pour écrire des programmes qui enverront des instructions au CPU. En Java, qui est un langage dit de "haut niveau", vous écrirez `System.out.print("Hello World");` pour afficher sur le moniteur "Hello World".

Le mot `print` correspond directement à l'idée d'impression pour le programmeur, ce qui rend le langage pratique à utiliser.

![Programme Java](/images/abstraction-mind-computers/abstraction-9.png#center, "Programme Java")

Le langage sera traduit en langage d'assemblage via un compilateur, puis le langage d'assemblage donnera le code machine, instruisant le CPU sous forme de courant éléctrique.

Et au dessus de tout ces langages, existent des langages visuels ou même l'entrée d'un utilisateur. L'entrée déclenchera des instructions de langage de haut niveau qui déclencheront la cascade d'évènements indiquée précédemment.

Tous ces différents niveaux du langage informatique sont tous liés grâce à l'abstraction. Ce processus est similaire aux idées abstraites dont John Locke a discuté au 17ème siècle. De la même manière que les idées spécifiques dans l'esprit transformées en idées générales par abstraction, le spécifique qu'est le courant électrique est traduit à travers de multiples couches jusqu'au niveau de compréhension pour les humains. Le courant électrique qui est réel, est vu comme une apparence mentale, détachée de la réalité, transformée en langages de mots naturels. Ces langages de mots naturels sont des langages de programmation que nous utilisons de nos jours et qui dictent une grande partie de nos sociétés.
