# Assistant Temperature Fan
This project is a AI assisted fan. It begins with the user entering a room, or in our case, pressing a button and turning on the LED light. Using the temperature sensor, it will continue reading and displaying the room's temperature in Celcius. When the LED light button is pressed, it prompts the user to verbally answer with an amount of time in seconds and/or minutes. When the inputed time is up, the fan will stop automatically and begin to sense and display the room's temperature. When the temperature in the room falls below 35° Celcius, it will not turn on. Anything higher than 35° Celcius will automatically turn on the fan. 

# Requirements
Arduino IDE

Arduino Mega 2560

Python 3.11

Speech Recognition 3.14

PySerial

Python Elements

Pylance




Arduino IDE libraries:

- Adafruit Unified Sensor 1.1.15 by Adafruit

- BH1750 1.3.0 By Christopher Laws

- DFRobot_DHT11 1.0.0 by DFRobot

- DHT Sensors Non-Blocking 1.0.4 by Toan Nguyen
