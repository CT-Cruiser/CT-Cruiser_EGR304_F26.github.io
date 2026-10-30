---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview
The following block diagram describes the flow sensing subsystem I was responsible for. The board's purpose is to provide a status of whether or not water is flowing through the system. This device runs solely from +5v dc with two options for power: barrel jack or +5v from main voltage bus. This board makes use of a photoresistor to detect whether or not water is flowing through a transparent tube. The photoresistor is connected to a circuit that drives a opamp chip where the output is eventually amplified and taken to the input on the PIC Curiosity nano. My board is a "slave" board  hat communicates with the "master" board. This board exclusively outputs. The outputs consist two wires that can be pulled high or low by the PIC totalling to 4 output states.





## Flow-Sensing Module Block Diagram 
![Cole's Current Block Diagram](BlockFinal.drawio.png)