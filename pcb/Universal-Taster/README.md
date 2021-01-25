# Taster

## Features

* ARM Cortex M4 CPU with 1MiB of flash and 256KiB of RAM.
* Compatible with OnSemi NCN5120 and NCN5121
* 6 universal GPIO pins
* 2 pins for I2C
* 2 RX/TX pins (without header)

## Pictures
<img src="https://raw.githubusercontent.com/basilfx/KNX-Taster/master/Taster/Pictures/TopView.png" width="384">

## Compatibility
This board is compatible with the [OnSemi NCN5121](http://www.onsemi.com/pub/Collateral/NCN5121-D.PDF) or the [OnSemi NCN5120](http://www.onsemi.com/pub/Collateral/NCN5120-D.PDF).

## Schema
You can find the schema [here](Taster.pdf).

## BOM
| **Ref** | **Value**     | **Footprint**                                          | **Farnell** | **DigiKey**         | **Notes**         |
|---------|---------------|--------------------------------------------------------|-------------|---------------------|-------------------|
| C1      | 18pF          | Capacitors_SMD:C_0603                                  | 2821267     |                     |                   |
| C2      | 18pF          | Capacitors_SMD:C_0603                                  | 2821267     |                     |                   |
| C3      | 1µF           | Capacitors_SMD:C_0603                                  |             | 587-1437-1-ND       | 35V               |
| C4      | 20pF          | Capacitors_SMD:C_0603                                  | 2627461     |                     |                   |
| C5      | 20pF          | Capacitors_SMD:C_0603                                  | 2627461     |                     |                   |
| C6      | 10pF          | Capacitors_SMD:C_0603                                  | 1414600     |                     |                   |
| C7      | 10pF          | Capacitors_SMD:C_0603                                  | 1414600     |                     |                   |
| C8      | 100nF         | Capacitors_SMD:C_0603                                  | 1833843     |                     |                   |
| C9      | 100nF         | Capacitors_SMD:C_0603                                  | 1833843     |                     |                   |
| C10     | 100nF         | Capacitors_SMD:C_0603                                  | 1833843     |                     |                   |
| C11     | 100µF         | Capacitors_SMD:CP_Elec_6.3x7.7                         |             | 732-8511-1-ND       | 35V               |
| C12     | 1µF           | Capacitors_SMD:C_0805                                  | 2346944     |                     | 35V 2R ESR        |
| C13     | 100nF         | Capacitors_SMD:C_0603                                  | 1833843     |                     |                   |
| C14     | 220nF         | Capacitors_SMD:C_0603                                  | 2346906     |                     | 50V               |
| C15     | 47nF          | Capacitors_SMD:C_0603                                  | 2524870     |                     | 50V               |
| C16     | 100nF         | Capacitors_SMD:C_0603                                  | 1833843     |                     |                   |
| C17     | 10µF          | Capacitors_SMD:C_0603                                  |             | 445-9104-1-ND       | 6.3V 0.1R ESR     |
| C18     | 100nF         | Capacitors_SMD:C_0603                                  | 1833843     |                     |                   |
| C19     | 100nF         | Capacitors_SMD:C_0603                                  | 1833843     |                     |                   |
| D1      | LED           | LEDs:LED_0603                                          | 2687487     |                     |                   |
| D2      | D             | Diodes_SMD:D_SMB                                       |             | 1SMA40CAT3GOSCT-ND  |                   |
| D3      | D_TVS         | Diodes_SMD:D_SMB                                       |             | SS16T3GOSCT-ND      |                   |
| D4      | D_TVS         | Diodes_SMD:D_0603                                      | 2368172     |                     |                   |
| D5      | D_TVS         | Diodes_SMD:D_0603                                      | 2368172     |                     |                   |
| D6      | D_TVS         | Diodes_SMD:D_0603                                      | 2368172     |                     |                   |
| D7      | D_TVS         | Diodes_SMD:D_0603                                      | 2368172     |                     |                   |
| D8      | D_TVS         | Diodes_SMD:D_0603                                      | 2368172     |                     |                   |
| D9      | D_TVS         | Diodes_SMD:D_0603                                      | 2368172     |                     |                   |
| D10     | D_TVS         | Diodes_SMD:D_0603                                      | 2368172     |                     |                   |
| D11     | D_TVS         | Diodes_SMD:D_0603                                      | 2368172     |                     |                   |
| J1      | I2C           | Connectors_JST:JST_SH_BM04B-SRSS-TB_04x1.00mm_Straight |             |                     | Ebay              |
| J2      | INTERFACE     | Connectors_JST:JST_SH_BM08B-SRSS-TB_08x1.00mm_Straight |             |                     | Ebay              |
| J3      | KNX_KLEMME    | KNX:KNX_KLEMME                                         |             | 36-1425-2-ND        | Two needed        |
| J4      | JTAG          | Pin_Headers:Pin_Header_Straight_2x03_Pitch1.27mm_SMD   | 2308512     |                     | Contra is 1865334 |
| L1      | 220µH         | PowerSwap:SRR5028                                      |             | SRR5028-221YCT-ND   |                   |
| R1      | 680           | Resistors_SMD:R_0603                                   |             | MCT0603-680-CFCT-ND |                   |
| R2      | 27            | Resistors_SMD:R_2512                                   | 2426565     |                     |                   |
| R3      | 1             | Resistors_SMD:R_0603                                   | 2078888     |                     |                   |
| R4      | 680           | Resistors_SMD:R_0603                                   |             | MCT0603-680-CFCT-ND |                   |
| R5      | 680           | Resistors_SMD:R_0603                                   |             | MCT0603-680-CFCT-ND |                   |
| R6      | 680           | Resistors_SMD:R_0603                                   |             | MCT0603-680-CFCT-ND |                   |
| R7      | 680           | Resistors_SMD:R_0603                                   |             | MCT0603-680-CFCT-ND |                   |
| R8      | 680           | Resistors_SMD:R_0603                                   |             | MCT0603-680-CFCT-ND |                   |
| R9      | 680           | Resistors_SMD:R_0603                                   |             | MCT0603-680-CFCT-ND |                   |
| R10     | 0             | Resistors_SMD:R_0603                                   |             | 311-0.0GRCT-ND      |                   |
| R11     | 0             | Resistors_SMD:R_0603                                   |             | 311-0.0GRCT-ND      |                   |
| R12     | 0             | Resistors_SMD:R_0603                                   |             | 311-0.0GRCT-ND      |                   |
| R13     | 0             | Resistors_SMD:R_0603                                   |             | 311-0.0GRCT-ND      |                   |
| SW1     | PROG          | Buttons_Switches_SMD:SW_SPST_B3U-1000P                 |             | SW1020CT-ND         |                   |
| U1      | EFM32PG12B500 | Housings_DFN_QFN:QFN-48-1EP_7x7mm_Pitch0.5mm           |             | 336-3941-ND         |                   |
| U2      | NCN5121       | Housings_DFN_QFN:QFN-40-1EP_6x6mm_Pitch0.5mm           |             | NCN5121MNTWGOSCT-ND |                   |
| U3      | MX25R8035F    | PowerSwap:winbond-USON-8(2X3UX)                        |             | 1092-1207-1-ND      |                   |
| Y1      | 32.768kHz     | Crystals:Crystal_SMD_2012-2pin_2.0x1.2mm               |             | XC2288CT-ND         |                   |
| Y2      | 40MHz         | Crystals:Crystal_SMD_2016-4pin_2.0x1.6mm               |             | 1253-1120-1-ND      |                   |
| Y3      | 16MHz         | Crystals:Crystal_SMD_2016-4pin_2.0x1.6mm               |             | 1253-1348-1-ND      |                   |
