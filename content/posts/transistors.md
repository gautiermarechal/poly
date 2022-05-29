---
title: Transistors and their global impact
date: 2022-05-28T23:36:38+02:00
cover:
  image: "/images/transistors/transistors-thumbnail.webp"
  alt: "Transistors"
  relative: false
categories:
  - Computer Science
  - Science
---

Today, we are tackling transistors, these small electronic components that have revolutionized the world of computing since their very first creation in the 1920s. What is a transistor, how does it work and why is it? what so important? And what is the future of transistors? Let's explore this.

## The story of its invention

At the beginning of the 20th century, modern electronics grew with the aim of better controlling the electric current applied to a circuit in order to build increasingly sophisticated machines. At that time, vacuum tubes were used for these purposes as switches and amplifiers in circuits.

However, these components present a major problem: their size. Indeed, the first vacuum tube computers took up a lot of space for their capacity. For example, the Colossus, in service since 1943, is considered the first programmable computer in history. It took up the entire space in a living room, weighed 8 tons, to perform simple arithmetic calculations.

![The Collosus computer - 1943](/images/transistors/transistors-1.png#center, "The Collosus computer - 1943")

Physicists of the time knew that vacuum tubes could be replaced. In 1925, Julius Lilienfeld, an Austro-Hungarian physicist filed the first patent for the field effect transistor. A little later, Oskar Heil also filed a patent for this same type of transistor in 1935. But it was not until 1947 that the first transistor was actually created, in the Bell laboratories in New Jersey.

## What is it and how does it work?

### Control the current

A transistor is a component that controls the movement of electrons like a faucet controls the movement of water. We open the tap to let the water flow and control its flow rate; the amount of water coming out per unit of time.

![Faucet](/images/transistors/transistors-2.gif#center)

A transistor does the same with electrons.

The transistor is made up of three pieces of metal called electrodes. There is **the emitter** (the entrance of the electrons), the **base** (the electrode where the current is controlled) and the **collector** (the exit of the electrons) .

![Electrodes Transistor](/images/transistors/transistors-3.png#center "Electrodes Transistor")

The **collector** lets electrons in, and the emitter lets electrons out. In the middle is the base electrode which will decide whether or not the electrons will pass. If a voltage is applied to this base electrode, current will flow through the transistor. They say he will be led. However, if the base receives no voltage, no current flows. What differentiates a transistor from a simple switch is that you can decide how many electrons pass through it.

These cases of figures give the term of semiconductor to the transistor: the transistor can conduct the current or not. It is also from this behavior that the etymology of the word transistor was born: _transfer resistor_ in English, or transfer resistance.

### A semiconductor atom

An atom consists of a nucleus and electrons in orbital shells around the nucleus. The last of these shells is called the Valence layer. Above this Valence layer is the conduction band. When an electron reaches this conduction band, it breaks free from the atom to move to other atoms. That's electric current.

There are therefore three types of atoms:

| Kind               | Description                                                                                                                                                                                                   |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Insulating atom    | Its Valence layer is saturated with electrons, there is no more room and the conduction band is far away.                                                                                                     |
| conductive atom    | Its Valence layer can accommodate new electrons and the conduction band is at the same level as the Valence layer.                                                                                            |
| Semiconductor atom | Its Valence layer is saturated with electrons but the conduction band is very close to it. If we give enough energy, the electrons can pass into the conduction band and free themselves to pass the current. |

### The NPN and PNP layers

In a transistor, we use these electrical properties to control this current.

Let's dive inside the transistor to see what it hides.

Inside we find two types of component layers: type N and type P.

An N-type shell is a block of atoms with excess electrons. This block will therefore want to **give up** its electrons.

A P-type shell is a block of electron-starved atoms. It will therefore want to **receive** electrons.

![NPN and PNP Layers](/images/transistors/transistors-4.png#center "NPN and PNP Layers")

By applying these layers following **_excess (N), lack (P), excess (N)_** or **_lack (P), excess (N), lack (P)_**, if we do pass a minimum of 0.7V in the system, the current will pass, otherwise it will not pass. The N shells will donate electrons to the P shells.

For a more detailed explanation of the process, I refer you to the following video [[https://youtu.be/Ey1nnEoADcg?t=705](https://www.youtube.com/watch?v=J4oO7PT_nzQ&t=705s)].

### Why is this useful?

Nowadays, transistors are found in any electronic device that we use. From the washing machine to the computer via the smartphone, transistors are the basis of the electronic circuits of our devices.

By being able to let the current flow or not with an electrical voltage, we can associate several transistors together to let the current flow at a precise state. For example, if we want an LED to light up when 2 buttons are pressed at the same time, we can use a transistor linked to each button which will let current flow if the button is pressed.

But then why not use the buttons directly?

Well if we multiply this number of gates to let or not the current pass, the mechanical switches become ineffective. Indeed, if we were to associate hundreds of logic gates to make calculations automatically, the switches would be too slow, the mechanical aspect leads to more probabilities of technical problems and the space taken up would be too large.

This is why transistors are used everywhere in computing. They allow the electronic circuits of our devices to open and close the current very quickly, and therefore increase the speed of calculation.

### Examples of uses

- Flash memory (USB key, SSD disk, etc.)
  - We can link the value 0 to an isolating transistor and a value of 1 to a passing transistor. If we have these transistors in series, each value of the transistor on or off will give a series of 0s and 1s which therefore represents information (a text, a technical image, etc.)
  - In the chip below, billions of transistors are arranged to represent information.
    ![Flash Memory](/images/transistors/transistors-5.png#center "Flash Memory")
- Processors (CPUs)
  - The transistors arranged in the processor make it possible to perform complex calculations, forming the basis of computing.
    ![CPU](/images/transistors/transistors-6.png#center "CPU")

## Sources

1. [https://en.wikipedia.org/wiki/Colossus_computer](https://en.wikipedia.org/wiki/Colossus_computer)
2. [https://www.youtube.com/watch?v=Ey1nnEoADcg](https://www.youtube.com/watch?v=Ey1nnEoADcg)
3. [https://couleur-science.eu/?d=b3cf17--comment-fonctionne-la-memoire-flash-dun-lecteur-ssd](https://couleur-science.eu/?d=b3cf17--comment-fonctionne-la-memoire-flash-dun-lecteur-ssd)
