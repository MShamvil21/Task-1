# Project 1- Line Follower Robot (Without Microcontroller)
#### Purpose-IR based line follower robot from scratch
#### Topic-Electronics
This project is totally based on electronics no programming and coding is required. Based on the concept of reflection of infrared rays and Infrared rays are totally absorbed by black colored surfaces .The IR receiver has to be reverse biased. The reflected IR needs to be amplified and IC358 is use to built the amplifier and voltage comparator. Voltage divider is build using the receiver diode and a 10k resistor. Now the sensors are connected with motors using  IC L293D(Connecting the sensors directly with motors  will destroy the circuit since large current is required to run motors).A suitable power supply is connected to the bot preferably 18650 Lithium ion battery.

*Project Link*:https://www.instructables.com/IR-Based-Line-Following-Robot-From-Scratch-No-Micr/

# Project 2-CO2 Level Indicator-Anti Covid-19 Measure
#### Purpose- A device to measure CO2 Concentration
#### Topic- Microcontrollers

This device will help us to maintain proper ventilation in room which is one of the important aspect in stopping the spread of Covid -19.This device is built around Adafruit Feather328P(other than this any similar similar Arduino Microcontroller can be use).Adafruit Featherwing OLED is used to display the concentration along with date and time, it contains a small OLED screen which communicates through I2C and one more reason for using this particular model is that it contains 3 buttons which are use to interact with device interface. Featherwing Adalogger is used to save the concentration data in SD card this component is a combination of I2C RTC and SPI SD card reader. A  Gravity CO2 sensor is use to measure the gas concentration and LED to use to indicate the level. After connecting all the components code is uploaded using Arduino IDE.
*Project Link*:https://www.instructables.com/CO2-Monitoring-As-an-Anti-Covid19-Measure/

# Project 3- Dust Monitoring System
#### Purpose- Using IOT to built a Dust monitoring system
#### Topics- Arduino and IOT
An IOT based Dust density monitor which can measure the surrounding dust and send the data through internet ,which can be used to graphically monitor the long term value of dust density in a place. Sharp gp2y1014auOf is a particulate sensor built around IR led and uses light scattering technique   to measure the dust concentration in the surrounding.To make this IOT based Arduino Microcontroller and ESP8266(ESP01) WiFi module for internet connectivity is used .After configuring all the components ,Blynk  app setup is done and code needs to be uploaded .
One suggestion from my side is that a buzzer should be added to warn when the dust concentration is high.
*Project Link*:https://www.hackster.io/abid_hossain/long-term-dust-monitoring-system-eeeeea

# Project 4-Pulse Oximeter and Heart Rate Monitor
#### Purpose-To build a pulse oximeter and heart rate monitor using MAX30102 sensor.
#### Topic-Arduino
~~Disclaimer~~: It should be stated that this device is not reliable and accurate enough for medical diagnosis. Fun Project to show off the capabilities of Arduino and few other components!!

MAX30102 sensor is used which uses a technique called photoplethysmography to monitor the heart rate. The results are displayed on I2C OLED screen. After connecting the sensor and OLED screen with the arduino ,code is uploaded and green and red led  indicates the range of your SP02 level.

*Project Link*:https://www.instructables.com/Pulse-Oximeter-and-Heart-Rate-Monitor/

# Project 5-Illuminexa (Homemade Alexa with ESP32)
#### Purpose-To build a device that reacts to your voice and show what you ask for .
#### Topic-ESP32 and Voice Recognition Module
This project uses Voice Recognition Module V3 to communicate which can store upto 80 voice commands each with duration of 1500 milliseconds. A 8x32 neopixel panel is use to display the output in return of the voice command covered by a translucent sheet.ESP32 is powered by Micro USB cable to avoid voltage loses and configured with the led panel and voice recognition module. Before using the voice recognition module, first we need to train it with the commands that we are going to use (There is no language barrier!!).

*Project Link*:https://www.instructables.com/ILUMINEXA-HomeMade-Alexa-With-ESP32/

# Project 6- Glove Control Robotic Hand
#### Purpose-To build a fully functional Robotic Hand that can be controlled by glove with flex sensors.
#### Topic-Arduino and Flex Sensors
Robotic hand finger is constructed using foam, springs,tape and string. The arm base contains 5 servo motors which are responsible for finger movements, arduino and breadboard is also embedded in the base of robotic arm. The 5 servo motors are powered by a separate battery for smooth functioning. After organizing all the components and configuring them robotic hand is ready. Now for building glove controller flex sensors are the most important part and purchasing them will increase the budget so rather than buying them it’s possible to DIY them(https://www.youtube.com/watch?time_continue=303&v=SJNYbSpvlP8&feature=emb_logo). Once we are done with the flex sensors we need to upload the code but coding for this project is bit difficult.
We can make the experience better better by using 3-d printed materials and purchasing flex sensors.

*Project Link*:https://www.hackster.io/laurencemlai/diy-glove-controlled-robotic-hand-ff5d63

![P 6](https://user-images.githubusercontent.com/85311689/122218843-79614480-cecc-11eb-9df9-ec7a57efafb8.jpg)






