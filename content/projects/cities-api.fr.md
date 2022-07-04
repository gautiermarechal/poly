---
title: "API de villes"
date: 2022-05-01T12:12:22+02:00
categories:
  - Web Development
  - NodeJS
  - Javascript
  - Back-End
cover:
  image: "/images/cities-api/cities-api-thumbnail.png"
  alt: "Cities Api Thumbnail"
  relative: false
ShowToc: false
---

Lorsque je travaillais sur une fonctionnalité de cartographie sur le [Projet Singular](https://gaut.io/fr/projects/singular/), j'ai rencontré un gros problème lorsque je travaillais avec des coordonnées de villes géolocalisées. Je n'ai pas trouvé d'API propre qui permette de trouver des villes par leurs coordonnées ou simplement une saisie semi-automatique par nom de ville.
J'ai été vraiment surpris de voir que ce genre d'API n'existait pas. Habituellement, les API que j'ai trouvées n'offraient pas de fonctionnalités simples ou manquaient de nombreuses villes.

J'ai décidé de créer ma propre API.

J'ai trouvé trois fichiers avec un total de plus de 200 000 villes à travers le monde avec leurs coordonnées. J'ai traité les données avec un script python, rassemblé les trois fichiers en un seul csv et créé ma base de données.

Ensuite, j'ai créé un simple serveur NodeJS pour accéder à ces données de manière simple et sûre.

J'ai posté l'API sur le hub RapidAPI pour que les développeurs l'utilisent.

Pour avoir un accès complet et illimité, il existe un forfait de 10$ pour le point de terminaison des coordonnées. Les autres ednpoints sont totalement gratuits.

Voici le lien vers la page Rapid API : [Lien Rapid API](https://rapidapi.com/gaut.marechal/api/world-cities6)

Voici le lien vers le Swagger : [Lien Swagger](https://world-cities.herokuapp.com/api-docs/)

### Date

May 2022

### Technologies

- NodeJS
- Swagger
- Python

### Github

https://github.com/gautiermarechal/cities-api
