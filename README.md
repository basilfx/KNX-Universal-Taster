# KNX Universal Taster
DIY universal taster interface for the KNX bus.

## Introduction
This repository contains my designs for creating a custom KNX universal taster
interface (or actor). This is board that can be used for several purposes, but
its main purpose is to convert pulse-based wall switches into KNX-enabled
switches. The boards are designed to be small and should fit wall boxes with a
depth of 50 mm.

[<img src="pcb/Universal-Taster/Pictures/Image4.jpg" width="256" alt="Image 4 of complete board.">](pcb/Universal-Taster/Pictures/Image4.jpg)
[<img src="pcb/Universal-Taster/Pictures/Image5.jpg" width="256" alt="Image 5 of complete board.">](pcb/Universal-Taster/Pictures/Image5.jpg)
[<img src="pcb/Universal-Taster/Pictures/Image6.jpg" width="256" alt="Image 6 of complete board.">](pcb/Universal-Taster/Pictures/Image6.jpg)

I currently have 25 boards installed in my house. As of writing (January 2021),
they have been running for more than two years.

## Features
While commercial alternatives exists, for example the [MDT Universal Interface](https://www.mdt.de/EN_Universal_Interface.html)
or the [ABB Universal Interface](https://new.abb.com/products/GHQ6310070R0111/us-u4-2-universal-interface-4-fold-fm),
I challenged myself to create a version that has more capabilities:

* Smaller.
* Programmable button options, e.g. multiple presses, long(er) presses.
* Support for (environmental) sensors.
* Universal use: data loggers, protocol gateways (Modbus, DSMR).
* Remote configuration via ETS or other software.

## Contents
You can find the following in this repository:

* [PCB designs](pcb) - KiCad designs for the main PCB and extensions

## Support
You can buy the boards from [Aisler.net](https://aisler.net/p/GGKCSYBF), and
help me to support the development.

## License
The work in this repository is covered by CC BY-NC-SA 4.0. See the `LICENSE.md`
file for more information.

## Disclaimer
Use this project or information at your own risk. I cannot be held responsible
for any injuries or damages.

This page and its content is not affiliated with the KNX Association. Most
certainly, this work is not certified by the KNX Association.
