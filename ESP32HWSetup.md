# ESP32 Hardware Setup

At the moment (as of mid June 2020), the project is in a prototype stage. I plan to work on a PCB design and finalised BOM in the future.

## Parts used

- Espressif ESP32-DEVKITC-32D development board (the ESP32-DEVKITC-32U can be used too, as the only difference is that it uses an external antenna rather than an integrated one)
- microSD SPI breakout board + microSD card (I believe there are compatibility issues with SDXC cards, so SDHC cards will work better)
- BME280 breakout board with I<sup>2</sup>C compability (the SparkFun boards support it, as do many cheap boards from eBay or AliExpress)
  - Depending on the board used, you may need to change the I<sup>2</sup>C address in src/main.cpp

## Schematic

This is a quick schematic created in Fritzing - I plan to use other software to create a proper schematic when I design the PCB.

![Schematic](https://lh3.googleusercontent.com/l7B37R2WasyRuEfZulgA3QtJMyHMdDcoTcWZWvtUMvGT4Hj5U_-7B9puqe9Ui-31QzU1ZrHoJ5oTRITa_ZwlSsmdDEcacD_6zieAyuYBzCFM8YGilLWG5XD5xwLgMeaWGPWTCDNdUBaJKohQ_8uCcxMwOR_3UdC5VsySVva-mT6Tna3A97AHZcyR8kvxFbGJEoMNCq7oWljGqeez7roSlWZeKAXHjYqCe1dSpjLb2GRwGyDAG6sPOpKvlbHfxMsZlHHQ5WMnlyyxN9il6xpGChtdHJr87habsaHt4Y_VJ6pYVxJ6JZ8s8qucLI9_jYz0ciGZm4HByPv0b1nttSX4ttFQBfGqjaSevRCdZ5zykNI-1kq3IjVWyju-bQ-AtSmGsQABdp67lFprKULGVz0cKGu0nLVUXn6VWfrlTMnzKVCZG6yPpxJvyaz_BFtlzwIjQNnPqLabs7oW4re-hsQhCmmbXcD7cHmPCoFMapZyWH6k09qxg8mnIPn13W5ZoCDOCrnfKSb12vGaWyZXrfJ3V3b3bRsiFl_XocAWzGqfejNLT1ps3SwPW2T0qqTMnyrPVq2yD0OSKLewbe67UyKF4XtE_Cs5C0LGSD8YWAe0e74ExTAXuy_DkqCf3x_mpWn7F-v78k1b7N76Kb3h54MuqQRf7i1IsFLoDCJgTnBqP8PVRiblhCjc0zswpTnQ5w=w925-h869-no?authuser=0 "Schematic")