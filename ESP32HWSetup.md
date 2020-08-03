# ESP32 Hardware Setup

At the moment (as of mid June 2020), the project is in a prototype stage. I plan to work on a PCB design and finalised BOM in the future.

## Parts used

- Espressif ESP32-DEVKITC-32D development board (the ESP32-DEVKITC-32U can be used too, as the only difference is that it uses an external antenna rather than an integrated one)
- microSD SPI breakout board + microSD card (I believe there are compatibility issues with SDXC cards, so SDHC cards will work better)
- BME280 breakout board with I<sup>2</sup>C compability (the SparkFun boards support it, as do many cheap boards from eBay or AliExpress)
  - Depending on the board used, you may need to change the I<sup>2</sup>C address in src/main.cpp

## Schematic

This is a quick schematic created in Fritzing - I plan to use other software to create a proper schematic when I design the PCB.

![Schematic](https://github.com/fbm3334/fbm3334.github.io/blob/master/images/SD%2BBME280_schem.jpg "Schematic")
