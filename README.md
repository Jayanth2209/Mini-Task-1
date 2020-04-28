# Task-1
# Project 1 - Advanced Irrigation System :    
Purpose - Automated Irrigation system to overcome over or under irrigation.   
Based on -  IoT and Arduino   
This project deals with the building of an IoT based smart irrigation system by analyzing the soil parameters and weather conditions. Sensors are used to detect various parameters like pressure, humidity, temperature,pH,etc. This data from the Arduino is gathered using an IoT module. The system is trained based on this data and then is tested for accuracy. So, this system uses machine learning to compare real values obtained from sensors with a test value that has been fed to the machine for analysis. The results decide whether irrigation should be done or not. This system has many other cool features like Alert Control (reporting the changes to the user through email or a text message) and Anomaly detection (identifying unexpected events by defining some threshold values).

# Project 2 - DIY GY-906 Infrared Thermometer using Arduino:
Purpose - No contact Temperature sensing      
Based on - Arduino     
This project is to build a No-Contact Infrared Thermometer using an Arduino Nano and a GY-906 Temperature Sensor to measure the surface temperature of an object and display on an OLED display. All the components are assembled as per the circuit diagram. The MLX90614 sensor collects the data and the installed program continuously reads this data and displays the temperature on the OLED screen when the switch is touched. The casing for the thermometer components is obtained by 3D-Printing. These thermometers are now in great use, in the first line of detection of corona virus.

# Project 3 - DIY Hand Sanitizer Dispenser :
Purpose - Touch free Soap/Sanitizer dispendsing      
Based on - Arduino    
This project is to build a Touch free Soap/Sanitizer dispenser using Arduino, an ultrasonic sensor and a servo motor. An IR Sensor could also be used but an ultrasonic sensor, though a bit expensive is more accurate. The servo motor and a copper wire are used to generate a downward force to push the sanitizer. The code is uploaded defining all the basic setups and then it is ready to use. All the components are packed properly. The sanitizer is pushed when a target is 10cm or closer to the sensor.

# Project 4 - COVID 19 Real Time Data Monitoring using NodeMCU :   
Purpose - To get the statistics of Covid-19    
Based on - NodeMCU    
This project is fairly simple to build. NodeMCU is an open source IoT platform built around ESP8266(wifi SoC). Using it we collect the statistics of COVID 19 and then it is displayed on the display attached. Suitable connections are made between the display and NodeMCU. The code includes libraries and lines for fetching the Covid data from a website and to display it on the screen.

# Project 5 - GPS Monitoring :
Purpose - To monitor the location of some person/object    
Based on - Microcontrollers   
This project is based around a GPS module (ATGM332D) and an ATSAMD21J18B Microcontroller. The circuit is powered by USB 5V source and the display is througha 0.96'OLED display. USART is used to communicate with the GPS module and SPI to communicate with the OLED. GPIO's are to control the LEDs. To get the location,date and time, they used GPRMC sentence (GPS NMEA sentence - To receive a GPS signal). This system takes 20-30 seconds in clear weather conditions to retreive the required information.

# Project 6 - Inhouse IoT Air Quality Sensor :   
Purpose - A device to monitor inhouse air conditions   
Based on - IoT   
This project uses NodeMCU ESP8266 and the sensors Pimoroni BME680 (to detect Humidity, Temperature, Pressure,etc.) and PMS5003 (to detect Air particle density). This device connects to your home network. Then the Arduino environment for the NodeMCU is built, all the required libraries are installed and the sensors are also included in the code. All the firmware is compiled and uploaded. The Web UI (User Interface) is uploaded and the sensors are added and configured. The system is rebooted and can now be used for sensing the air quality in a room.

# Project 7 - Easy Soil Moisture Sensor Arduino 7 Segment Display :
Purpose - Testing moisture content in a soil   
Based on - Arduino   
This is a fairly easy project to make. It's used to check the moisture content of the soil and display it on a 7-segment display using an Arduino Uno and a Soil Moisture sensor. Suitable wiring is done. To check the moisture content, the sensor is dipped into the soil and the display on the 7-segment display shows the moisture content in the soil.   

# Project 8 - Continuously Rotating Solar Motor :
Purpose - A continuously rotating solar powered sphere   
Topic - Electronics   
This project uses A solar panel, a super capacitor, Hall sensor, Comparator, IC:XC 6206 LDO (driver IC) and Neodymium magnets. The solar panel charges the super capacitor via a low-dropout regulator. The Hall sensor detects the rotor magnet. The pulse passes through the pulse shaper, comparator and the driver IC and activates the pulse coil. Magnetic bearings are used to reduce the friction of the rotor shaft. Rotor is made from a styrofoam globe and has magnets placed around the middle. This is an efficient pulse motor driven by small and stable nanopower circuit.

# Project 9 - Use a Stepper Motor as a Rotary Encoder :
Purpose - Making a Rotary Encoder   
Topic - Electronics
A rotary encoder is a device that converts the angular position of a shaft to an analog or digital output used in automated machinery, position control, etc. This project uses a stepper motor (which generates electric pulses when rotated), but since it cannot generate enough voltage when rotated slowly, an amplifying circuit is required.    
So the stepper motor is suitably connected to the Arduino through the amplifier and the code is uploaded. This circuit can now be used to control the brightness of LED connected to pin 'D13'by adjusting the duty cycle on the output pin with the rotary encoder.

# Project 14 - Raspberry Pi based Weather Station:
Purpose - To get the weather information   
Based on - Raspberry Pi   
This project is to build a compact weather station using a wireless Raspberry Pi Zero. They used AZ-Touch Pi0 kit for the display. It is made compatible with Pizero. Then the Raspbian image is copied into an SD card and is put into the Pizero. This Raspbian image is burned and a SSH connection is enabled and the details are entered. The Raspberry Pi is then rebooted. The weather station will be launched after rebooting.
