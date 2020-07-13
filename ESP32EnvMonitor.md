# ESP32 Environment Monitor

## Project introduction

This project is designed to be an environment monitor using an Espressif ESP32 microcontroller, a Bosch Sensortec BME280 sensor and a microSD card - these components comprise the server side of this project (there may be times where I have referred to the 'server' in the code etc, and this is referring to the ESP32.) The BME280 can capture temperature, pressure and relative humidity, so these are the measurements taken.

The SD card is used for data-logging, and stores the environment data in a CSV file for use in software such as Excel, MATLAB, Tableau etc.

The project uses WebSockets to communicate with the client devices to send the readings across, and there are two main client-side applications to view the data:

1. A JavaScript/HTML-based web application - this is saved on the SD card and allows viewing of the environment data, changing of settings and data downloads through most modern web browsers

2. An iOS application to view the data on an iOS/iPadOS device. This supports devices running iOS 13.0 or newer (iPhone 6S, iPad Air 2, iPad Mini 4 and iPod touch 7th generation or newer), and (as of July 2020) has most of the features of the web interface.

## GitHub repositories

The code is contained within two GitHub repositories:

- ESP32 and HTML files - [ESP32_EnvironmentMonitor](https://github.com/fbm3334/ESP32_EnvironmentMonitor)
- iOS code - [ESP32-Environment-Monitor-iOS](https://github.com/fbm3334/ESP32-Environment-Monitor-iOS)

## Hardware setup

See [ESP32 Hardware Setup](ESP32HWSetup.md).

## ESP32 software setup

See [ESP32 Software Setup](ESP32SWSetup.md).

## iOS software setup

See [iOS Software Setup](EnvMoniOSSetup.md).
