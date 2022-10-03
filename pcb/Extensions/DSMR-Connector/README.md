# DSMR-Connector

## Introduction
This board converts the P1 port found on Dutch Smart Energy Meters to UART,
opto-isolated from the Taster module. You can find more information in the
[P1 Companion Standard](https://www.netbeheernederland.nl/_upload/Files/Slimme_meter_15_a727fce1f1.pdf).

This board is only compatible with DSMR 5.0, since that version is using two
additional pins (therefore RJ-12 instead of RJ-11) to supply the bidirectional
optocoupler.

## Board
<img src="Pictures/DSMR-Connector_Top.svg" width="384" title="Top layer">
<img src="Pictures/DSMR-Connector_Bottom.svg" width="384" title="Bottom layer">

## Schema
You can find the schema [here](DSMR-Connector.pdf).

## BoM
The (interactive) BoM can be found [here](https://basilfx.github.io/KNX-Universal-Taster/pcb/Extensions/DSMR-Connector/BoM/ibom.html).

