# ESP32 Software Setup

## Prerequisites

- [PlatformIO](https://platformio.org) is required in order to install the software on the ESP32.
- A microSD card is required to save the HTML and CSS files.
- You will need a terminal emulation program such as [CoolTerm](https://freeware.the-meiers.org) in order set up the WiFi network - the baud rate is 115200.

## Installation instructions

1. Clone the [repository](https://github.com/fbm3334/ESP32_EnvironmentMonitor) into your PlatformIO projects folder.
2. Import the project by going onto PIO Home/Projects/Add Existing within Visual Studio Code.
3. Compile and upload the project by clicking on the Upload icon on the bottom of the Visual Studio Code window - it looks like ➡️.
4. Copy index.html and style.css from the webdata folder onto the root directory of the microSD card.
5. Configure the WiFi network by connecting the ESP32 to your PC and using your chosen terminal emulation program to follow the steps and connect to the network. **Make a note of your IP address as you will need this for the next step.**
6. Using a web browser (most modern browsers will work), type the IP address into the address bar. You should get a screen similar to this:
![Web interface screenshot](https://github.com/fbm3334/fbm3334.github.io/blob/master/images/Screenshot%202020-07-03%20at%2013.56.01.png "Web interface screenshot")

Once you get to this point, you have successfully installed the ESP32 Environment Monitor software.
