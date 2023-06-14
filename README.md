# IoT-Doorbell
Smart doorbell with video and audio capabilities.

#### On visitor's side:
you press the button to let the house owner know your'e here, and you hear a message they recorded for visitors.
#### On house owner's side:
you get a push notification with an image of the visitor at the door when they press the button. by tapping the notification, you can see a live stream of your doorview. You can also see a log of visitors from all times, and upload a message for visitors.

## Features:
- Image capture on button press
- Audio message on button press
- Push notification with image on app
- Live stream of door view on app
- Events log on app

## Hardware Requirements:
- ESP32-CAM board
- ESP32 board
- MAX98357 audio DAC+amplifier board
- Button

## Connections Scheme:

<img src="https://github.com/shaharcc/IoT-Doorbell/blob/master/images/scheme.jpg" alt="alt text" width="200">

## App:

![](https://github.com/shaharcc/IoT-Doorbell/blob/master/images/Home.jpg | width=100)
![alt text](https://github.com/shaharcc/IoT-Doorbell/blob/master/images/Home.jpg)
![alt text](https://github.com/shaharcc/IoT-Doorbell/blob/master/images/EventsLog.jpg | width = 150)
![alt text](https://github.com/shaharcc/IoT-Doorbell/blob/master/images/Account.jpg | width = 150)

## Libraries Installation:
- ESP32-audioI2S-master
- Firebase Arduino Client Library for ESP8266 and ESP32
- ArduinoJson

## Installation and Usage:
- Follow this connections scheme
- Upload the code to each board using Arduino IDE
- Install the mobile application on your phone
- Press the button to capture an image and receive a notification on your phone
- View the live stream on your phone using the mobile application


### Contributors:
[Shahar Cohen](https://github.com/shaharcc), [Rony Juliusburger](https://github.com/ronyju) and [Oren Tal](https://github.com/oren-tal)
