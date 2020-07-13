# ESP32 Software Setup

## Prerequisites

- [PlatformIO](https://platformio.org) is required in order to install the software on the ESP32.
- A microSD card is required to save the HTML and CSS files.
- You will need a terminal emulation program such as [CoolTerm](https://freeware.the-meiers.org) in order set up the WiFi network - the baud rate is 115200.

## Installation instructions

1. Clone the [repository](https://github.com/fbm3334/ESP32_EnvironmentMonitor) into your PlatformIO projects folder.
2. Import the project by going onto PIO Home/Projects/Add Existing within Visual Studio Code.
3. Compile and upload the project by clicking on the Upload icon on the bottom of the Visual Studio Code window - it looks like ➡️.
4. Copy index.html and style.css from the webdata folder onto the root directory of the microSD card.
5. Configure the WiFi network by connecting the ESP32 to your PC and using your chosen terminal emulation program to follow the steps and connect to the network. **Make a note of your IP address as you will need this for the next step.**
6. Using a web browser (most modern browsers will work), type the IP address into the address bar. You should get a screen similar to this:
![Web interface screenshot](https://lh3.googleusercontent.com/Z6vCo0tBcz63fG-_OJhf6rupsg6Vfi0IJ0phYgvft4hVGBmRiidShhLyYO6O-FwAMSN12WjJv7fc90Hi2ryN1la9kP0skQYn9CsSAt8UnGJVTAe3TjX8qgCedbG87FB5Q4MzPFVihS7OCdxS1PR7uGckkxwEcU0W_9d4jTXHxmvaM-rNAYlB1doiWyfM5lDQPruBeBBt6sECh18t134zeuD5Ml_SEbwd3BKaYjE1ElwcC1rMV4WjWFJGluWr76CynIJP2mYrFBPZvpTp5_XkaZn2sI2HgwPsAlYbTNBF_xoEzZflTjbJiO0relD3nvLguph5fHA1kJLsOsb1m2C9j1AdKNmQht2sqq7EpUxw7cAtqv2nQ7rPexvOWWjbLeMQnrbDlaLac3GUL30ajyheleczPnJtgNDXI13dd6vGduKa5B0-wMLMqX_HpWGLP__stwQFEZV7tEUenmdj8Bisu4RT5bqDn1JCog1JELyl9GgDx0M0SXgEs31TLTol3zQMe1W4XMsaKs0-RyjNT9WTybkv3LHIXQIFGfG8gmKCrvUOo708XLdXslD2sCZa3onx4bfXFOeRkZzkoCwkMOTnmo_fTeRToWNnhn1agVeZBxo1_qSvjO2SF32eqAQNOSaaB3PN64fWgrBpdfXTcWbwFvRdHonugevtbHBMLYMRkrJWYz7vbhiYB-q38_PPNA=w790-h689-no?authuser=0 "Web interface screenshot")

Once you get to this point, you have successfully installed the ESP32 Environment Monitor software.