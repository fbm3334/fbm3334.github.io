# Setting up the Environment Monitor app on iOS

## Prerequisites

As this app is only a personal project at the moment, I have decided not to publish it on the Apple App Store for now. This means it needs to be sideloaded using the correct hardware:

- An iOS or iPadOS device running iOS 13.0/iPadOS 13.1 or later. The compatible devices are:
  - iPhone 6S or newer
  - iPad Air 2/iPad Mini 4 or newer
  - All iPad Pro models
  - iPod touch 7th generation or newer
- A Mac running macOS Mojave 10.14.4 or newer, as well as Xcode 11 or newer

## Installation instructions

1. Clone the [GitHub repository](https://github.com/fbm3334/ESP32-Environment-Monitor-iOS) onto your Mac.
2. Open Xcode, and navigate to the project folder. Open the "ESP32 Environment Monitor.xcodeproj" file in Xcode, which should open the project.
3. Make sure your iOS device is connected to your Mac via a Lightning/USB-C cable, and make sure it is selected in the top left corner (there is a box that should say something like "ESP32 Environment Monitor > your iOS device")
4. Click the play button in the top-left corner. This will install the app, and you should get a notification that this is successful.
5. The app will launch in a debug mode - when you are done with this, click on the stop button in the top-left corner.