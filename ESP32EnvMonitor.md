# ESP32 Environment Monitor

## Project introduction

This project is designed to be an environment monitor using an Espressif ESP32 microcontroller, a Bosch Sensortec BME280 sensor and a microSD card - these components comprise the server side of this project (there may be times where I have referred to the 'server' in the code etc, and this is referring to the ESP32.) The BME280 can capture temperature, pressure and relative humidity, so these are the measurements taken.

The SD card is used for data-logging, and stores the environment data in a CSV file for use in software such as Excel, MATLAB, Tableau etc.

The project uses WebSockets to communicate with the client devices to send the readings across, and there are two main client-side applications to view the data:

1. A JavaScript/HTML-based web application - this is saved on the SD card and allows viewing of the environment data, changing of settings and data downloads through most modern web browsers

2. An iOS application to view the data on an iOS/iPadOS device. This supports devices running iOS 13.0 or newer (iPhone 6S, iPad Air 2, iPad Mini 4 and iPod touch 7th generation or newer), and (as of July 2020) has most of the features of the web interface.

## Repositories

The code is contained within two GitHub repositories:

- ESP32 and HTML files - [ESP32_EnvironmentMonitor](https://github.com/fbm3334/ESP32_EnvironmentMonitor)
- iOS code - [ESP32-Environment-Monitor-iOS](https://github.com/fbm3334/ESP32-Environment-Monitor-iOS)

## Libraries used

The code uses external libraries - these are attributed here:

- ESP32 code
  - Espressif network libraries (ESPAsyncWebserver, WebSocketServer) - these come with PlatformIO when configured for ESP32.
  - [SparkFun BME280 Arduino library](https://github.com/sparkfun/SparkFun_BME280_Arduino_Library)

- iOS code
  - [Starscream WebSockets Swift library](https://github.com/daltoniam/Starscream) by daltoniam on GitHub

## Hardware setup

See [ESP32 Hardware Setup](ESP32HWSetup.md).

## ESP32 software setup

See [ESP32 Software Setup](ESP32SWSetup.md).

## iOS software setup

See [iOS Software Setup](EnvMoniOSSetup.md).

## Licensing

This work is licensed under the **MIT License.**

Copyright 2020 Finn Beckitt-Marshall

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
