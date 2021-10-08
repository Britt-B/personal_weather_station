# Personal Weather Station
demo:  https://youtu.be/_Ng35-6-K8M
***
## Task
Create an IOT product using the arduino UNO board, Arduino IDE, and various sensors.
***
## Criteria
* Project must be compatable with Arduino Uno and Arduino IDE
* Choice of sensors and functionality
* Data Collection and Analysis available
* Communication methods clear and user friendly
* Generate feedback for user
* Future work and adaptablility
***
## Summary
This Project was created as my team's submission for the final assignment of our Internet of Things class. We chose to create a weather station app due to our mutual interest in agricultural and industrial systems, abailability of sensors used, and numerous possible applications.
***
## Functionality
As shown in the demo video linked above, this system allows the user to interact with a personalized wether station. The user can use the potentiometer to adjust lcd screen brightness, and the button to scroll through display options. There are several sensors that give feedback for temperature, humidity, gas levels, light levels, and rainfall data.
***
## Design
The physical product was designed with simplicity in mind. We opted to keep the sensors lined up on the left side of the bread board and I/O on the right side. The button and potentiometer are set towards the front of the board while the sensors are tucked to the back. The LCD screen is off to the side so it can be aligned to the user's preference. This allows a user with less experience to easily interact with the product and find the compoinents they are looking for.

The code allows more experienced users to adjust the range appropriate for their needs. The warning light can be adjusted to be more or less restrictive based on individual sensor data collected, and the water level should be adjusted after testing local conditions (as impurities in the water can give different readings).
***
## Sensors
* DHT11 - Temperature and humidity sensor
* CDS*3 Photocell - light levels (ohms)
* MQ135 - air quality/gas sensor (parts per million) [NH3, NOx, alcohol, Benzene, smoke, CO2]
* ARCELI Hygrometer - water level sensor
***
## Run Locally
* Attatch Arduino UNO to computer port
* Open Arduino IDE with provided code
* Check that IDE is connected to the correct port and Arduino Uno model is detected
* Import dht11 library
* Compile and run code using IDE
* Code should upload to Uno, system will run connected to computer or external power supply
