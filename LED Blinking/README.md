 LED Blinking with MSP430

Project Overview:
This project implements basic LED control functionality using an MSP430 microcontroller. It demonstrates simple input/output operations through button presses and LED responses.

Author: Efua Yankey

Date Written: 4th September, 2024

Last updated: 18th September 2024

Library:
<msp430.h> : The core library for MSP430 microcontroller programming, providing essential functions and definitions for hardware control.

File Descriptions:
GPIO_Driver.h: This is the header file for the GPIO driver. It declares the function prototypes for the functions implemented in GPIO_Driver.c, allowing other parts of the program to use these functions.

GPIO_Driver.c: This file contains the implementation of a GPIO driver functions for the MSP430 microcontroller. Implementation of the 

main.c: This file demonstrates the use of the GPIO driver functions: It initializes P4.1 and P2.3 as inputs, and P1.0 and P6.6 as outputs using the driver functions. Read the status of input pins, and Control the state of output pins.

lab1_Q1.c : This file contains a program that toggles the red LED (P1.0) when Button 1 (P4.1) is pressed.

lab1_Q2.c: This file contains a program that toggles the green LED (P6.6) when Button 2 (P2.3) is pressed.



