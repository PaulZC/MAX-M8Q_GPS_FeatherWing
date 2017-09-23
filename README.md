# MAX-M8Q GPS FeatherWing

A clone of the Adafruit Ultimate GPS FeatherWing but with the u-blox MAX-M8Q (external antenna) replacing the GlobalTop FGPMMOPA6H

**23-09-2017: Updated PCB now includes: pull-up resistors for SCL and SDA; a decoupling capacitor for VCC_RF; a test pad for SAFEBOOT**

![MAX-M8Q_FeatherWing](https://github.com/PaulZC/MAX-M8Q_GPS_FeatherWing/blob/master/img/MAX-M8Q_FeatherWing.jpg)

See [MAX-M8Q_GPS_FeatherWing.pdf](https://github.com/PaulZC/MAX-M8Q_GPS_FeatherWing/blob/master/MAX-M8Q_GPS_FeatherWing.pdf) for the BOM etc.

The [Eagle](https://github.com/PaulZC/MAX-M8Q_GPS_FeatherWing/tree/master/Eagle) directory contains the schematic and pcb design

The [Arduino](https://github.com/PaulZC/MAX-M8Q_GPS_FeatherWing/tree/master/Arduino) directory contains code for the [Adafruit Feather M0 Adalogger](https://www.adafruit.com/products/2796) which will log your route to SD card in GPX and CSV format
- https://www.adafruit.com/products/2796
- https://learn.adafruit.com/adafruit-feather-m0-adalogger

![MAX-M8Q_and_Adalogger_1](https://github.com/PaulZC/MAX-M8Q_GPS_FeatherWing/blob/master/img/MAX-M8Q_and_Adalogger_1.jpg)

![MAX-M8Q_and_Adalogger_2](https://github.com/PaulZC/MAX-M8Q_GPS_FeatherWing/blob/master/img/MAX-M8Q_and_Adalogger_2.jpg)

Useful documentation about the MAX-M8Q and its protocol specification can be found at:
- https://www.u-blox.com/en/files/max-m8datasheetubx-13004644pdf
- https://www.u-blox.com/en/files/max-m8himubx-13004876pdf
- https://www.u-blox.com/en/files/u-bloxm8receiverdescrprotspecubx-13003221publicpdf

Based on an original design by Adafruit Industries:
- https://www.adafruit.com/product/3133
- https://learn.adafruit.com/adafruit-ultimate-gps-featherwing
- https://github.com/adafruit/Adafruit-Ultimate-GPS-FeatherWing-PCB

Distributed under a Creative Commons Attribution, Share-Alike license

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Enjoy!

**_Paul_**