# Fall-detection-system
IOT system for fall detection. 

## The idea and the method

A 3-member team researched the health hazard that accompanies "Falls" and explored different solutions to combat this problem. The team was organised in an agile manner utilising a Gantt Chart and commonly used communication tools, considering it was implemented during covid lockdown.

# How it works 
For a live demo of the system, look into "DEMO" folder!

## Specifications - end result
We wanted to make a system that is:
* Accurate enough in detecting fall
* Capable of immediately alerting a 3rd person in call for help
* Capable of low power, constant use with great autonomy
* Compact and tiny enough for a comfortable wearable device.
* Low cost

Tech used:
* ESP32 DEVKIT1
* WIFI protocol
* I2C protocol with interrupts of ADXL345 (accelerometre)
* MQTT protocol for node control
* Node-RED for node communication and alerts
* Alert system both via telegram and via siren node

In the end, such an IOT system was designed, implemented and tested with the following characteristics/functionalities:

![fall_detection_system](https://user-images.githubusercontent.com/56197365/135668019-98d7fccb-8332-4c6b-b373-082f4d4806e4.JPG)


* Battery monitoring-low consumption techniques (ex. Deep Sleep mode and interrupts)
* Fall detection algorithm inside the MCU
* Wifi connection
* Wifi credentials storage in Flash memory
* MQTT protocol and communication with NODE-red server
* Telegram Chatbot for alerts
* Siren esp32 node for sound alert.

As an end result, an academic paper was also written, containing all the above mentioned research plus testing results (85% TP 90% TN). The paper will not be published here, but I strongly encourage you to check the DEMO file in this github repo to see the device in live demos!

# Authors/Designers 
 - Dimitrios Lampros
 - Andreas Chadoumellis
 - Paris Stentoumis

Mentor: Dimitris Karagiannis 

