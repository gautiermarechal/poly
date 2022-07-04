---
title: "World Cities API"
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

When working on a mapping feature on my [Singular Project](https://gaut.io/projects/singular/), I encountered a great problem when working with coordinates geo-located cities. I could not find a clean API that enables finding cities by their coordinates or simply an autocomplete by city name.
I was really surprised to see that this kind of API did not exist. Usually, the APIs I found did not offer simple features or lacked a lot of cities.

I decided to buil my own API.

I found three files with a total of more than 200,000 cities around the world with their coordinates. I treated the data with a python script, gathered the three files into one csv, and created my database.

Then I created a simple NodeJS server to acccess this data in a easy and safe way.

I posted the API on RapidAPI hub for developers to use it.

To have a full unlimited access, there is a 10$ plan for the coordinates endpoint. Other endpoints are totally free.

Here is the link to the Rapid API page: [Rapid API Link](https://rapidapi.com/gaut.marechal/api/world-cities6)

Here is the link to the Swagger: [Swagger Link](https://world-cities.herokuapp.com/api-docs/)

### Date

May 2022

### Technology

- NodeJS
- Swagger
- Python

### Github

https://github.com/gautiermarechal/cities-api
