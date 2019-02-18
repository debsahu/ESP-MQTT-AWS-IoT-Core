# ESP-MQTT-AWS-IoT-Core
Arduino examples of connecting ESP8266/ESP32 to AWS IOT Core

[![Build Status](https://travis-ci.com/debsahu/ESP-MQTT-AWS-IoT-Core.svg?branch=master)](https://travis-ci.com/debsahu/ESP-MQTT-AWS-IoT-Core) [![License: MIT](https://img.shields.io/github/license/debsahu/ESP-MQTT-AWS-IoT-Core.svg)](https://opensource.org/licenses/MIT) [![LastCommit](https://img.shields.io/github/last-commit/debsahu/ESP-MQTT-AWS-IoT-Core.svg?style=social)](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/commits/master)

----------------
## Youtube
[![ESP-MQTT-AWS-IoT-Core](https://img.youtube.com/vi/OzNlSk7VU68/0.jpg)](https://www.youtube.com/watch?v=OzNlSk7VU68)

## AWS Instructions

[Follow instructions](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/tree/master/doc/README.md)

## Software requirements

ESP8266
- Use ESP8266 Arduino Core version **2.5.0-beta2 or greater**
- Will **NOT** work on ESP8266 Arduino Core v2.4.2 !!!

ESP32
- Use the latest release version

### Libraries Needed

[platformio.ini](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/platformio.ini) is included, use [PlatformIO](https://platformio.org/platformio-ide) and it will take care of installing the following libraries.

| Library                   | Link                                                       | Purpose                 |
|---------------------------|------------------------------------------------------------|-------------------------|
|Arduino MQTT               |https://github.com/256dpi/arduino-mqtt                      |communication (choose 1) |
|PubSubClient               |https://github.com/knolleary/pubsubclient                   |communication (choose 1) |
|ArduinoJSON                |https://github.com/bblanchon/ArduinoJson                    |example-data-formatting  |
