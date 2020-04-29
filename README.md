# Task-1
# Mini Task-1 
# Project 1 - Advanced Irrigation System :    
Purpose - Automated Irrigation system to overcome over or under irrigation.   
Based on -  IoT   
This project deals with the building of an IoT based smart irrigation system by analyzing the soil parameters and weather conditions. Sensors are used to detect various parameters like pressure, humidity, temperature,pH,etc. This data from the Arduino is gathered using an IoT module. The system is trained based on this data and then is tested for accuracy. So, this system uses machine learning to compare real values obtained from sensors with a test value that has been fed to the machine for analysis. The results decide whether irrigation should be done or not. This system has many other cool features like Alert Control (reporting the changes to the user through email or a text message) and Anomaly detection (identifying unexpected events by defining some threshold values).   
Project link : https://www.hackster.io/narangrahulrahul8/advanced-irrigation-system-eeb622   

# Project 2 - DIY GY-906 Infrared Thermometer using Arduino:
Purpose - No contact Temperature sensing      
Based on - Arduino     
This project is to build a No-Contact Infrared Thermometer using an Arduino Nano and a GY-906 Temperature Sensor to measure the surface temperature of an object and display on an OLED display. All the components are assembled as per the circuit diagram. The MLX90614 sensor collects the data and the installed program continuously reads this data and displays the temperature on the OLED screen when the switch is touched. The casing for the thermometer components is obtained by 3D-Printing. These thermometers are now in great use, in the first line of detection of corona virus.   
Project link : https://www.hackster.io/hardyedela/diy-arduino-gy-906-infrared-thermometer-5881aa   

# Project 3 - DIY Hand Soap/Sanitizer Dispenser :
Purpose - Touch free Soap/Sanitizer dispendsing      
Based on - Arduino    
This project is to build a Touch free Soap/Sanitizer dispenser using Arduino, an ultrasonic sensor and a servo motor. An IR Sensor could also be used but an ultrasonic sensor, though a bit expensive is more accurate. The servo motor and a copper wire are used to generate a downward force to push the sanitizer. The code is uploaded defining all the basic setups and then it is ready to use. All the components are packed properly. The sanitizer is pushed when a target is 10cm or closer to the sensor.    
Project link : https://www.hackster.io/MissionCritical/diy-hand-sanitizer-dispenser-using-arduino-143de1   


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

# Project 10 - Raspberry Pi Security Camera :   
Purpose - To make a security camera    
Topic - IoT    
This project uses Raspberry Pi 3, Pi Camera and a PIR motion sensor. The camera is connected to the camera module port of the Pi and the PIR Motion Sensor is connected to the Pi's GPIO pins accordingly. An SD card is also inserted. Pi is turned in and the internet connectivity is checked. Then the camera is enabled in the interfacing options. Picamera module is also installed. All the required modules are created and the codes too. Then the server can be started and through the IP address, the webpage can be accessed and the camera can be controlled remotely.

# Project 11 - Reading text files from an SD card using Arduino :
Purpose - To read and display the text from a text file stored in an SD Card    
Topic - Arduino    
This project uses an SD card breakout board. SD card breakout boards are used as an external storage devices due to the limited capacity of microcontrollers. We can insert an SD card into the breakout board and thi=e data from this can be fed to any microcontroller device. We first create a tet file in an SD card and insert it in the breakout board. The connections are then made between the SD card breakout board and the Arduino and from the Arduino to the LCD display suitably. The Arduino reads the text file in the SD card and then displays it on the LCD.

# Project 12 - VLF Metal Detector :
Purpose - To make a detector that can detect metal objects upto 25cm or closer   
Topic - Electronics    
This project uses two D-shaped coils, A Signal generator module, a Mofset transistor and required capacitors and resistors. The detector contains two coils - one transmitter and one receiver. The resonant frequency of the transmitter coil is calculated and it is set in the signal generator with 50% duty cycle. The potentiometer is used to control the current through the transmitter coil. The receiver coil connects to the microphone and the smartphone according to the circuit diagram. The phones output is amplified and we hear a beep when the metal is detected by interfering with the magnetic field through the coil. 

# Project 13 - Gesture Controlled Wheelchair :
Purpose - To control wheelchair movements thorugh pre-defined hand gestures   
Topic - Arduino   
This project deals with developing a prototype for a robotic wheelchair that can be controlled using simple hand gestures. It uses Arduino Uno and Nano and a Gyroscope (measures the angular position of the hand). A communication is first set-up between the Uno (Wheelchair module) and the Nano (the hand with the gyroscope). The Nano here behaves as the master and the Uno as the slave. The gestures (basically the angles) and the required movements are fed through the code to the Uno. So this gyroscope information is fed to the Uno through the Nano and the Uno performs the required action as per the code through the driver motors connected to it and gives out the required movement. We can add gestures for all the required mechanical movements.

# Project 14 - Raspberry Pi based Weather Station:
Purpose - To get the weather information   
Based on - Raspberry Pi   
This project is to build a compact weather station using a wireless Raspberry Pi Zero. They used AZ-Touch Pi0 kit for the display. It is made compatible with Pizero. Then the Raspbian image is copied into an SD card and is put into the Pizero. This Raspbian image is burned and a SSH connection is enabled and the details are entered. The Raspberry Pi is then rebooted. The weather station will be launched after rebooting.

# Project 15 - Locker Monitor using Bolt :
Purpose - To keep track of the lockers    
Topic - IoT      
This project is to build a module to monitor lockers using Bolt IoT device and an LDR. The resistance of LDR depends on the light intensity falling on it. When the locker is closed, it will be at a particular value. But, when it is opened, this value changes and hence this is used as a trigger to send an alert that the locker is open. The LDR are the Bolt module are suitably wired. The bolt device and the bolt cloud are connected. In the bolt cloud, the pins are configured and the code is imported as required. This configuration is deployed for setting-up a connecction between the device and the cloud. A third-party messaging app is used to send a text alert by collecting data from the bolt cloud. 

# Project 16 - Automated Parking Lot using Arduino :
Purpose - To build a parking lot model for a hassle free parking experience   
Topic - Arduino    
This project requires an Arduino, a Piezo sensor, an ultrasonic sensor, a Bluetooth module and servo motors (for the mechanical outputs). There will be a change in pressure when the car travels on the piezo sensor. The sensor sends this information to the Arduino  which in turn drives the servo motors to open the parking gates. The code consisting the required actions is uploaded to the Arduino.
Ultrasonic sensors are placed at all the parking spots to identify whether it is occupied/free. This information of where the free spots are located is made available to the user through the Bluetooth module. 

# Project 17 - Raspberry Pi Bluetooth Speaker Audio Streaming System :
 Purpose - To make a wireless Bluetooth speaker that can take audio from your phone's mic and play it on a speaker/ can also stream live            music from phone's music gallery or YouTube.     
 Topic - Raspberry Pi   
 This project requires a Raspberry Pi with built-in WiFi and Bluetooth. The RPi takes the audio via bluetooth from the phone and then transfers it to its own analogue pin (TRRS pin). But this output signal will be weak and inaudible and hence need to be amplified. This is done using a PAM amplifier module and the audio comes out of the speakers. For setting up, the RPi and the audio device (phone) are paired over bluetooth and the audio device should also be selected as the input audio. To use the phone as a mic, a suitable app is installed on it and it can be streamed over RPi.
 
# Project 18 - Sun Tracking Solar Panel :
Purpose - A Solar Panel circuit to track the Sun and position the Solar Panels accordingly    
Topic - Microcontrollers    
This project consists of two LDR's, a solar panel, a servo motor and an ATmega328 Microcontroller. The components are connected according to the circuit diagram. LDR's resistance is inversely proportional to the light intensity falling on it. Two LDR's are placed at the two ends of the solar panel. So, the panel moves towards the side where the LDR has low resistance i.e. high intensity with the help of servo motor. The code defining this is uploaded to the ATmega238 using Arduino IDE.

# Project 19 - Password Based Door Lock System :
Purpose - A secure door unlocking system using a password    
Topic - Microcontrollers    
This project uses 8051 Microcontroller. A 4x4 Matrix Keypad is used to enter the password which is compared with the predefined password and the door unlocks when the passwords match. An LCD is used to display if the Password entered is wrong and a motor is used for opening the door. The Microcontroller, keypad, Motor driver, the LCD and DC motor are connected according to the circuit diagram. The code is compiled and uploaded. When the circuit is switched ON, it sends a command to display "enter password" on the LCD screen. Then the password is entered. When the passwords match, the microcontroller activates the motor driver, which in turn rotates the motor and opens the door.

# Project 20 - Line Follower Robot :











 
