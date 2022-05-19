---
title: "Automatic Greenhouse"
date: 2022-04-23T12:12:22+02:00
categories:
  - Arduino
  - Electronics
  - Hardware
cover:
  image: "../images/automatic-greenhouse/automatic-greenhouse-thumbnail.jpeg"
  alt: "Booking Appointment System Thumbnail"
  relative: false
ShowToc: false
---

It's been a long time since I wanted to expand my Arduino and electronics knowledge. Spring season coming in south of France, I thought of linking technology and harvesting. So I decided to build an automatic greenhouse.

## Goal

The idea is to automatize everything a human has to manage with a greenhouse. My ultimate goal is not to create a product that could be commercialized. I only had intentions to learn as much as possible with this project, linking electronics and gardening.

My biggest wish was to realize what could I accomplish with my basic knowedge of electronics and Arduino.

## List of components

### Electronics

- Air temperature and humidity sensor (DHT22) x 1
- Soil moisture sensors x 2
- Arduino Uno x 1
- 4 relays module x 1
- 12V DC fan x 2
- 5V water pump x 1

### Other

#### Greenhouse Structure

- 80 cm wood pieces x 2
- 40 cm wood pieces x 2
- Plexiglas x 4

#### Water Installation

- Plastic tube 3m
- Water valves x 6
- Water tank 1L

## Inputs to control

| Input                    | Output                |
| ------------------------ | --------------------- |
| Temperature is too high  | Turn ON Fans          |
| Temperature is too low   | Turn OFF Fans         |
| Soil Moisture is too low | Turn ON pump for 1min |

Simple as that. The only human input is to fill the water tank when it's empty.

## How it works

The arduino is monitoring air temperature and soil moisture via the sensors. It turns on and off fans and pump via the 4 relays module. The 4 relays module is connected to the fans and pump. Fans are 12V so require a different source of energy than the rest of the system that allows a maximum of 5V. I could have used resistors to use a higher voltage power supply and use only one source.

## What sould be improved

A lot of things. This project is just for fun.

I would:

- Add and LCD screen to display informations such as temperature, soil moisture etc...

- Add a motor to open the ceiling of the greenhouse when too hot, for a better reduction of temperature than fans.

- Improve the wirings of the system that is quite messy right now.

- Add an ultrasonic sensor to the water tank to monitor water level.

## Thoughts

In the future, will we be able to have a sustainable technology that could symbioses with nature at a local scale? These kinds of projects prove that individual agriculture could potentially develop with these kinds of innovations. This project does not cost a lot of money and could be easily commercialized. I am pretty sure companies already exist. The goal of this project post is also to show that this kind of technology exist and may be useful for people to be slightly more self-sustainable.
The problem is not the lack of technology but the lack of awareness about these technologies. Arduino and other board providers are bringing something interesting and people should know.
