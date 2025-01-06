# Firmware

## Introduction
This folder contains the firmware releases of the firmware for the Universal
Taster.

This section is work in progress.

## Versions
* [v0.3.0](v0.3.0)

## Features
* Designed to work with the Environmental Sensors board
  * If not used, temperature sensor is connected to the internal temperature
    sensor
* LED + programming button (hold to enable)
* 6 universal inputs
  * Switch mode
  * Intelligent dim: press + hold will dim up, double press + hold will dim
    down
* Temperature and pressure sensor support
* Programmable using ETS5
* Over-the-wire updating (requires separate tool)
* UART shell

## Installation

### From source
The firmware is based on [RIOT-OS](https://github.com/RIOT-OS/RIOT). A
preliminary version of a KNX stack has been developed for this purpose as well.
The firmware source code can be found [here](https://github.com/basilfx/RIOT/tree/feature/knx/examples/gnrc_knx_taster)
(the application will move to another repository in the near future).

To get started, ensure that you have the right tools installed for RIOT-OS.
This includes:

* Git
* GNU Make 4.x
* GNU Arm Embedded Toolchain
* J-Link (flashing)

You will need a J-Link debugger and hook it up to the debug header. The pinout
is as follows (from above, KNX connector on bottom side):

* GND - RESET - 3V3
* SWO - SWDCLK - SWDIO

While not mandatory, the back side contains four pads for a UART (from above,
KNX connector on bottom side):

* GND
* RX
* TX
* 3V3

Start by cloning the repository. Then navigate to the `examples/gnrc_knx_taster`
folder, and read the `README.md` file carefully.

Once you meet all requirements, run `BOARD=basilfx-taster make` to compile the
firmware. To flash it, run `BOARD=basilfx-taster make flash`.

The firmware now be running.

### Precompiled version
You need a J-Link debugger for flashing the firmware. See the above section on
how to connect it.

If the debugger is working, you can run `JLinkExe` to start the programmer.
Follow the on-screen instructions (make sure to select SWD instead of JTAG) to
connect the board.

Once connected, run `loadbin gnrc_knx_taster_slot0-extended.bin 0x0` to flash
the firmware. The firmware now be running.

## Configure using ETS5
A `*.knxprod` file is included, which can be imported in the KNX product
catalog. This file is created using tools listed [here](https://github.com/basilfx/SignKnxProd).

The product will be added under the manufacturer 'Not Assigned'.

Note: in some cases, ETS5 may throw exceptions while importing this product
definition. Sometimes it may help to remove the old definitions from the
catalog, clean-up the product store (Diagnostics -> Troubleshooting), restart
ETS5 and import again.
