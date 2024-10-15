DESIGN SMART HOME (LAB 5)

Author: Efua Yankey
Date Written: 27th Sept, 2024
Last updated: 9th Oct, 2024

Overview
This project uses an MSP430 microcontroller to create a basic smart home system. It includes sensors for gas, temperature, motion, and light, along with LED and buzzer outputs.

Components:
Gas sensor
Temperature sensor
Motion detector
Light sensor (photoresistor)
LEDs and buzzer for alerts

Features:
Monitors gas levels
Measures temperature
Detects motion
Responds to light levels
Provides visual (LED) and audio (buzzer) alerts

Files:
gas_sensor.c: Contains code which can be used for Gas detection and LED control
external_temperature_sensor.c: Contains code which can be used for Temperature reading and LED control
buzzer_and_LED.c: Contains code which can be used for Motion detection with LED and buzzer response
Photo-resistor.c: Contains code which can be used for Light sensing and LED control

Setup
Connect sensors and outputs to the MSP430 as per pin configurations in each file.

Usage
Compile and flash each file to the MSP430 using a compatible IDE. The system will automatically monitor the environment and respond to changes.





TRANSFERRING DATA TO A WEB APPLICATION (LAB 4)

Author: Efua Yankey
Date Written: 27th Sept, 2024
Last updated: 3rd Oct, 2024

Overview:
This project transfers temperature data from an MSP430 microcontroller to a web application via a Windows Forms interface.

Components:
1. MSP430 Program (CSS_lab4_main.c):
   - Reads temperature from internal sensor
   - Sends data via UART

2. Windows Forms App (Form1.cs):
   - Receives data from MSP430
   - Uploads to ThingSpeak

Setup:
1. Program MSP430
2. Connect MSP430 to PC
3. Run Windows Forms app
4. Click 'Start' to begin data transfer

Note: Update COM port and ThingSpeak API Key before use.
