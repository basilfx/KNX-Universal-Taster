# DSMR-Connector

## Introduction
This board converts the P1 port found on Dutch Smart Energy Meters to UART, opto-isolated from the Taster module. You can find more information in the [P1 Companion Standard](https://www.netbeheernederland.nl/_upload/Files/Slimme_meter_15_a727fce1f1.pdf).

This board is only compatible with DSMR 5.0, since that version is using two additional pins (therefore RJ-12 instead of RJ-11) to supply the bidirectional optocoupler.

## Pictures
<img src="https://raw.githubusercontent.com/basilfx/KNX-Taster/master/Modules/DSMR-Connector/Pictures/TopView.png" width="384">

## Schema
You can find the schema [here](DSMR-Connector.pdf).

## BOM
| **Ref** | **Value**     | **Footprint**                                          | **Farnell** | **DigiKey**         | **Notes**         |
|---------|---------------|--------------------------------------------------------|-------------|---------------------|-------------------|
| C1      | 100nF         | Capacitor_SMD:C_0603                                   | 1833843     |                     |                   |
| C2      | 100nF         | Capacitor_SMD:C_0603                                   | 1833843     |                     |                   |
| J1      |               | Connector_RJ:RJ12_Amphenol_54601                       | 1833843     |                     |                   |
| J2      |               | Connector_PinHeader_1.27mm:PinHeader_1x04_P1.27mm      | 1833843     |                     |                   |
| U1      |               | Package_SO:SOIC-8_3.9x4.9mm_P1.27mm                    | 1833843     | FOD8012A-ND         |                   |
