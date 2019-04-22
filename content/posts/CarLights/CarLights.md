---
path: "/CarLightsElectronics"
title: "Car Lights Electronics"
date: "2018-11-25"
cover: "./carlightsbreadboardheading.jpg "
tags: [ 'coding', 'leds', 'electronics', 'scratch']
published: true
---

# Car Lights And Horn With Electronics


## Demo 

[![Car lights and horn electronics](./CarLights_gXLyQUFMQ9g.jpg)](https://www.youtube.com/watch?v=gXLyQUFMQ9g)


In this session, we'll use electronic lights and a buzzer, and switches to act like a real car:
- Horn sounds when button pressed
- Lights indicate movement: left, right, stopping.

In Part 1 [Simulating using Scratch](/car-lights-scratch) we modelled car lights in Scratch and coded them to respond to different key presses.
This activity builds on this, by implementing a real circuit with electronics.






| Movement      | Trigger        | Result   | What Happens]
|:------------- |:-------------| :-----| :-----|
| Stopping          | Red button            | Red | When we press the Red button, to indicate we're stoppping, the Red brake lights will light.|
| Left          | 2 way switch  | Left yellow lights flash front and rear | When we Move the toggle switch to the Left, to indicate we're turning left, left yellow lights flash front and rear|
| Right         | 2 way switch  | Right yellow lights flash front and rear |When we move the toggle switch to the Right,  to indicate we're turning right, right yellow lights flash front and rear|
| -             | Blue button    | Horn beeps |When we press the blue button, to alert other drivers, the buzzer beeps|



        


## Materials Required

1. Raspberry Pi and MicroSD card and power supply
2. Breakout cable and breadboard
3. 2 x Yellow and 1 x Red LEDs 
4. 2 x Push button switch
4. 1 x Left Right Toggle switch
   
## Build 
### Pre-activities drawing while waiting for activities to be setup 
![pre activities drawing](./Carlights_DoraSantawarmup.jpg)

Dora doodles while we get setup :)

### Circuit Diagram Symbols
![Electronics symbols](./carlightssymbols.jpg)
The circuit diagram symbols for the components we use in our circuit.

### Draw Circuit Diagram
![Drawings](./carlightsdrawings.jpg)
The circuit diagram showing:
- a push button switch
- a toggle switch



### Build Circuit
![Circuit](./carlightsbreadboard.jpg)

## Theory
[![Car lights and horn electronics theory](./CarLights1_od-3b_V7kIA.jpg)](https://www.youtube.com/watch?v=od-3b_V7kIA)    




## Part 3 Using Raspberry Pi
In Part 3 we'll use a Raspberry Pi to read the switches and write code to
1. play a tune when the horn button is pressed
2. flash the indicator lights for 3 seconds when the left-Right toggle switch is pressed.

