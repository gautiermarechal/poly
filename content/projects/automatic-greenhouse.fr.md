---
title: "Serre Automatique"
date: 2022-04-23T12:12:22+02:00
categories:
  - Arduino
  - Electroniques
  - Hardware
cover:
  image: "../images/automatic-greenhouse/automatic-greenhouse-thumbnail.jpeg"
  alt: "Serre Automatique image"
  relative: false
ShowToc: false
---

Cela faisait longtemps que je souhaitais approfondir mes connaissances en Arduino et en électronique. Le printemps arrivant dans le sud de la France, j'ai pensé à lier technologie et jardinage. J'ai donc décidé de construire une serre automatique.

## But

L'idée est d'automatiser tout ce qu'un humain doit gérer avec une serre. Mon but n'est pas de créer un produit qui pourrait être commercialisé. J'avais seulement l'intention d'en apprendre le plus possible avec ce projet, liant électronique et jardinage.

Ma motivation était de réaliser ce que je pouvais accomplir avec mes connaissances de base en électronique et Arduino.

## Liste des composants

### Électronique

- Capteur de température et d'humidité de l'air (DHT22) x 1
- Capteurs d'humidité du sol x 2
- Arduino Uno x 1
- Module 4 relais x 1
- Ventilateur 12V CC x 2
- Pompe à eau 5V x 1

### Autre

#### Structure de la serre

- Pièces de bois de 80 cm x 2
- Pièces de bois de 40 cm x 2
- Plexiglas x 4

#### Installation d'eau

- Tube plastique 3m
- Vannes d'eau x 6
- Réservoir d'eau 1L

## Input à contrôler

| Input                             | Output                         |
| --------------------------------- | ------------------------------ |
| La température est trop élevée    | Allumez les ventilateurs       |
| La température est trop basse     | Éteignez les ventilateurs      |
| L'humidité du sol est trop faible | Allumez la pompe pendant 1 min |

Aussi simple que cela. La seule intervention humaine consiste à remplir le réservoir d'eau lorsqu'il est vide.

## Comment ça fonctionne

L'arduino surveille la température de l'air et l'humidité du sol via les capteurs. Elle allume et éteint les ventilateurs et la pompe via le module 4 relais. Le module 4 relais est connecté aux ventilateurs et à la pompe. Les ventilateurs sont de 12 V et nécessitent donc une source d'énergie différente de celle du reste du système qui permet un maximum de 5 V. J'aurais pu utiliser des résistances pour utiliser une alimentation à tension plus élevée et n'utiliser qu'une seule source.

## Ce qui pourrait être amélioré

Beaucoup de choses. Ce projet est juste pour le plaisir.

Améliorations possibles:

- Ajout d'un écran LCD pour afficher des informations telles que la température, l'humidité du sol, etc...

- Ajouter un moteur pour ouvrir le plafond de la serre lorsqu'il fait trop chaud, pour une meilleure réduction de la température que les ventilateurs.

- Améliorer les câblages du système qui sont assez brouillons en ce moment.

- Ajoutez un capteur à ultrasons au réservoir d'eau pour surveiller le niveau d'eau.

## Pensées

Dans le futur, pourrons-nous disposer d'une technologie durable qui pourrait se lier avec la nature à l'échelle locale ? Ce genre de projets prouve que l'agriculture individuelle peut potentiellement se développer avec ce genre d'innovations. Ce projet ne coûte pas cher et pourrait être facilement commercialisé. Je suis presque sûr que des entreprises existent déjà. L'objectif de ce billet de projet est également de montrer que ce type de technologie existe et peut être utile pour que les gens soient un peu plus autonomes.
Le problème n'est pas le manque de technologie mais le manque de sensibilisation à ces technologies. Arduino et d'autres fournisseurs de boards apportent quelque chose d'intéressant et les gens doivent le savoir.
