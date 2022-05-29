---
title: Les transistors et leur impact global
date: 2022-05-28T23:36:38+02:00
cover:
  image: "/images/transistors/transistors-thumbnail.webp"
  alt: "Transistors"
  relative: false
categories:
  - Informatique
  - Science
---

Aujourd’hui, on s’attaque aux transistors, ces petits composants électroniques qui ont révolutionné le monde de l’informatique depuis leur toute première création dans les années 1920. Qu’est ce qu’un transistor, comment ça marche et pourquoi est-ce si important? Et quel est le futur des transistors? Allons explorer ça.

## L’histoire de son invention

Au début du XXème siècle, l’électronique moderne grandit dans le but de mieux contrôler le courant électrique appliqué à un circuit afin de construire des machines de plus en plus sophistiquées. À cette époque, les tubes à vides sont utilisés à ces fins comme interrupteurs et amplificateurs dans les circuits.

Or, ces composants présentent un problème majeur: leur taille. En effet, les premiers ordinateurs à tubes à vides prennent énormément de place pour leur capacité. Par exemple, le Colossus, en service dès 1943 est considéré comme le premier ordinateur programmable de l’histoire. Il prenait l’espace entier dans un salon, pesait 8 tonnes, pour exécuter de simple calculs arithmétiques.

![Le Collosus - 1943](/images/transistors/transistors-1.png#center, "Le Collosus - 1943")

Les physiciens de l’époque savent que les tubes à vides peuvent être remplacés. En 1925, Julius Lilienfeld, physicien Austro-Hongrois dépose le premier brevet du transistor à effet de champ. Un peu plus tard, Oskar Heil dépose lui aussi un brevet de ce meme type de transistor en 1935. Mais ce n’est qu’en 1947 que le premier transistor sera réellement créé, dans les laboratoires de Bell au New Jersey.

## C’est quoi et comment ça marche?

### Contrôler le courant

Un transistor est un composant qui contrôle le mouvement des electrons comme un robinet contrôle le mouvement de l’eau. Nous ouvrons le robinet pour faire couler l’eau et contrôlons son debit d’écoulement; la quantité d’eau qui sort pas unité de temps.

![Robinet](/images/transistors/transistors-2.gif#center)

Un transistor fait de même avec des electrons.

Le transistor est formé de trois bouts de métal appelés électrodes. Il y’a **l’émetteur** (l’entrée des electrons), la **base** (l’électrode où l’on contrôle le courant) et le **collecteur** (la sortie des electrons) .

![Electrodes Transistor](/images/transistors/transistors-3.png#center "Electrodes Transistor")

Le **collecteur** permet aux electrons de rentrer, et l’émetteur permet aux electrons de sortir. Au milieu se trouve l’électrode de base qui va décider si oui ou non les électrons passerons. Si on applique une tension à cet electrode de base, le courant passera dans le transistor. On dit qu’il sera conduit. Or, si la base ne reçoit pas de tension, aucun courant ne passe. Ce qui différencie un transistor d’un simple interrupteur, c’est que l’on peut decider de la quantité d’electrons qui y passent à travers.

Ces cas de figures donnent la terme de semi-conducteur au transistor: le transistor peut conduire ou non le courant. C’est d’ailleurs de ce comportement qu’est né l’étymologie du mot transistor: _transfer resistor_ en anglais, ou resistance de transfère.

### Un atome semi-conducteur

Un atome est constitué d’un noyau et d’electrons se trouvant sur des coques orbital autour du noyau. La dernière de ces coques est appelée couche de Valence. Au dessus de cette couche de Valence se trouve la bande de conduction. Quand un electron atteint cette bande de conduction, il se libère de l’atome pour se déplacer vers d’autres atomes. C’est ça le courant électrique.

Il y’a donc trois types d’atomes:

| Type                  | Description                                                                                                                                                                                                                                   |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Atome isolant         | Sa couche de Valence est saturée en electrons, il n’y a plus de place et la bande de conduction est éloignée.                                                                                                                                 |
| Atome conducteur      | Sa couche de Valence peut accueillir de nouveaux electrons et la bande de conduction se trouve au même niveau que la couche de Valence.                                                                                                       |
| Atome semi-conducteur | Sa couche de Valence est saturée en electrons mais la bande de conduction est très proche de celle-ci. Si nous donnons assez d’énergie, les electrons pourrons passez dans la bande de conduction et se libérer pour faire passer le courant. |

### Les couches NPN et PNP

Dans un transistor, nous utilisons ces propriétés électriques pour contrôler ce courant.

Plongeons à l’intérieur du transistor pur voir ce qu’il se cache.

À l’intérieur nous trouvons deux types de couches de composants: type N et type P.

Une couche de type N est un bloc d’atomes en excès d’electrons. Ce bloc voudra donc **céder** ses electrons.

Une couche de type P est un bloc d’atomes en manque d’electrons. Elle voudra donc **recevoir** des electrons.

![Couches NPN et PNP](/images/transistors/transistors-4.png#center "Couches NPN et PNP")

En posant ces couches à la suite **_excès (N), manque (P), excès (N)_** ou **_manque (P), excès (N), manque (P)_**, si on fait passer un minimum de 0,7V dans le système, le courant passera, sinon il ne passe pas. Les couches N donneront des electrons aux couches P.

Pour une explication plus détaillée du processus, je vous renvoie à la vidéo suivante [[https://youtu.be/Ey1nnEoADcg?t=705](https://youtu.be/Ey1nnEoADcg?t=705)].

### Pourquoi c’est utile?

De nos jours, les transistors se trouvent dans n'importe quel appareil électronique que nous utilisons. De la machine à laver à l’ordinateur en passant par le smartphone, les transistors sont la base des circuits électroniques de nos appareils.

En pouvant laisser passer ou non le courant avec une tension électrique, nous pouvons associer plusieurs transistors ensemble pour laisser passer le courant à un état précis. Par exemple, si nous voulons qu’une LED s’allume quand 2 boutons sont pressés en même temps, nous pouvons utiliser un transistors lié à chaque bouton qui laissera passer le courant si le bouton est pressé.

Mais alors pourquoi ne pas directement utiliser les boutons?

Et bien si nous multiplions ce nombre de porte pour laisser ou non le courant passer, les interrupteurs mécaniques deviennent inefficaces. En effet, si l’on devait associer des centaines de portes logiques pour faire des calculs automatiquement, les interrupteurs serait trop lent, l’aspect mécanique amène plus de probabilités de problème technique et la place prise serait trop importante.

C’est pour cela que les transistors sont utilisés partout en informatique. Ils permettent aux circuits électroniques de nos appareils une rapidité d’ouverture et de fermeture de courant très haute, et donc une rapidité de calcul accrue.

### Exemples d’utilisations

- La mémoire flash (Clé USB, disque SSD etc…)
  - Nous pouvons lier la valeur 0 à un transistor isolant et une valeur de 1 à un transistor passant. Si nous disposons ces transistors en série, chaque valeur du transistor passant ou non donnera une suite de 0 et de 1 qui représente donc une information (Un texte, une image tec…)
  - Dans la puce ci-dessous, des milliards de transistors sont disposés pour représenter l’information.
    ![Mémoire Flash](/images/transistors/transistors-5.png#center "Mémoire Flash")
- Les processeurs (CPU)
  - Les transistors disposés dans le processeur permettent d’exécuter des calculs complexes, faisant la base de l’informatique.
    ![CPU](/images/transistors/transistors-6.png#center "CPU")

## Sources

1. [https://en.wikipedia.org/wiki/Colossus_computer](https://en.wikipedia.org/wiki/Colossus_computer)
2. [https://www.youtube.com/watch?v=Ey1nnEoADcg](https://www.youtube.com/watch?v=Ey1nnEoADcg)
3. [https://couleur-science.eu/?d=b3cf17--comment-fonctionne-la-memoire-flash-dun-lecteur-ssd](https://couleur-science.eu/?d=b3cf17--comment-fonctionne-la-memoire-flash-dun-lecteur-ssd)
