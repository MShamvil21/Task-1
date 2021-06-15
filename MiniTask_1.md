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
