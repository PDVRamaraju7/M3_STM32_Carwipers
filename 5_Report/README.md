# OBJECTIVE OF THIS PROJECT:
By using STM32F407,buttons,4 LED's the project should be done using the timers and the sequence of glowing of LED's RED,GREEN,BLUE and the 4th acc mode either ON or OFF mode.If we press for a long time car should start or stop and by clicking the buttons the wipers speed mode should change.
# INTRODUCTION:

* we use the STM32F4xx-discovery board to illustrate an automobile wiper control system. Most automobile wipers are controlled by a DC motor, however because the STM32F4xx-discovery lacks a motor, we are exploring using LEDs in this application. As an example, the wiper control system. The STM32F4xx-discovery board has four LEDs and a Push Button. The colours of these LEDs are orange, green, red, and blue. A current limiting resistor connects four user LEDs to the PD12, PD13, PD14, and PD15 pins of PORTD on the Discovery board. To make a push button work with the STM32F407VG microcontroller, the GPIO pins will be set as digital input pins. If you push and hold the user button for two seconds, the Red When the ignition key is positioned at the ACC, the LED illuminates. Furthermore, the LEDs are flickering, indicating that the wipers are turned on.


# Abstract:
* A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. The prior system required manual wiper activation, and the operation of bringing up the wiper was difficult to manage. As a result, this method is proposed to address these issues. The project's goals are to improve ageing automobiles' systems by giving automated transmission. wiping system, to enhance the system by including a sensor and an actuator, and to create a simple software that would completely work with the system the framework.This proposed wiper system's principle is comparable to those of other existing conventional wipers.
                      
* we use the STM32F4xx-discovery board to illustrate an automobile wiper control system. Most automobile wipers are controlled by a DC motor, however because the STM32F4xx-discovery lacks a motor, we are exploring using LEDs in this application. As an example, the wiper control system. The STM32F4xx-discovery board has four LEDs and a Push Button. The colours of these LEDs are orange, green, red, and blue. A current limiting resistor connects four user LEDs to the PD12, PD13, PD14, and PD15 pins of PORTD on the Discovery board. To make a push button work with the STM32F407VG microcontroller, the GPIO pins will be set as digital input pins. If you push and hold the user button for two seconds, the Red When the ignition key is positioned at the ACC, the LED illuminates. Furthermore, the LEDs are flickering, indicating that the wipers are turned on.

# SOFTWARE REQUIREMENTS:
* STM32 CubeIDE
# COMPONENTS AND SUPPLIES:
1. STM32F407 Discovery Board
2. Push Button
3. LEDs
4. Resistors
5. Power Suppl


# DESCRIPTION:
* The STM32F405xx and STM32F407xx family is based on the high-performance Arm® Cortex®-M4 32-bit RISC    core operating at a frequency of up to 168 MHz. The Cortex-M4 core features a Floating point unit (FPU) single precision which supports all Arm single-precision data-processing instructions and data types. It also implements a full set of DSP instructions and a memory protection unit (MPU) which enhances application security. The STM32F405xx and STM32F407xx family incorporates high-speed embedded 
# STM32F407VG:

# FEATURES :
1. It will lock the vehicle when the button is squeezed once
2. It will open the vehicle when the button is squeezed two times
3. It will wiper on and it moves clock wise bearing and when the button is squeezed threefold
4. It will wiper off and it moves hostile to clock wise heading and when the button is squeezed multiple times
5. It will wiper complete one cycle when the button is squeezed multiple times.
6. Up to 1 Mbyte of Flash memory.
7.Up to 192+4 Kbytes of SRAM including 64-Kbyte of CCM (core coupled memory) data RAM.
8.512 bytes of OTP memory.
9. Flexible static memory controller supporting Compact Flash, SRAM, PSRAM, NOR and NAND memories.


# BLOCK DIAGRAM :

![Block Diagram](https://user-images.githubusercontent.com/102654901/168133233-625f90a3-a883-4ded-831e-3c5ec85f07e5.png)

# FLOWCHART :

![Flow chart](https://user-images.githubusercontent.com/102654901/168133468-fac8da58-33f5-4dd4-972e-99b5ae87e56f.png)

# WORKING PRINCIPLE:
* Assume that the automobile is the microcontroller. If the button is hit, the first led (red) will turn on, Clicking again the wiper will start, and the second led (blue) will turn on for a desired rate. If the button is pressed again, the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange), and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.
# USES:

# 4W & H (WHO,WHAT,WHEN,WHERE,HOW):

# WHAT:
* The operational speed of a vehicle wiper is controlled by a wiper speed control mechanism based on rain conditions. To generate, the control system incorporates a rain sensor (30) that detects rain conditions. The amplitude of an analogue signal depends on the detected rain conditions.
# WHY:
* To keep the windscreen clean enough to give adequate view at all times. #WHEN The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
# WHO:
* Mark Anderson invented on 1902
# STRENGTH:
* Low Budget
* Good Reputation
* High Bargaining Power Supliers
* Big Influence on the Market

# WEAKNESS:
* Structural Inertia
* High Transaction Cost
* No Focus on Private Sector
* Week Focus on Process Innovations

# OPPORTUNITIES:
* Emerging New Markets
* Technological Development
* Demand for Saver Equipments
* Technological Lock in of Product

# THREATS:
* Low Bargaining Power Buyers
* Highly REgulated Industry
* Ethical Pressure
* Econimical Crisis

# HIGH LEVEL REQUIREMENTS:
![HIGH](https://user-images.githubusercontent.com/102654901/168132048-2cd38c8f-9681-4766-9d16-d11e40d6b595.png)

# LOW LEVEL REQUIREMENTS:
![LOW](https://user-images.githubusercontent.com/102654901/168132311-239ead4b-1455-48ae-8607-ede11062d87a.png)

# TEST CASES AND CORRESPONDING OUTPUT:

# High Level Test Cases:

![High level test case](https://user-images.githubusercontent.com/102654901/168135668-49a1e8d4-27b0-43f5-a957-bc9c5a33f9fb.png)

# Low Level Test Cases:

![Low level test case](https://user-images.githubusercontent.com/102654901/168135790-337190fe-7244-43c6-a816-e5812422ec54.png)

# OUTPUT IMAGES
1. user button and hold it for two seconds
![user button and hold it for two seconds](https://user-images.githubusercontent.com/102654901/168221668-2e2a29ec-fc46-402c-bf53-31056d4d11b9.png)

2. WIPER SPEED LOW
![WIPER SPEED LOW](https://user-images.githubusercontent.com/102654901/168221719-4518fed3-fc67-4895-8292-dd0dab209dd9.png)

3. WIPER SPEED MEDIUM

![WIPER SPEED MEDIUM](https://user-images.githubusercontent.com/102654901/168221767-7e6adad0-d0a4-431a-bebe-cde4ab4b945a.png)

4. WIPER SPEED IS HIGH
![WIPER SPEED IS HIGH](https://user-images.githubusercontent.com/102654901/168221829-3520926e-e234-4a0d-96a2-e247806dc7db.png)

5. user button is pressed and held for 2 seconds, the red LED is off
![use button is pressed and held for 2 seconds,the red LED is off](https://user-images.githubusercontent.com/102654901/168221898-40387bc9-4d7b-40a4-aada-9558acb188dc.png)


# ADVANTAGES:
* To save money during wet seasons, turn off the irrigation system. Electricity bills are lowered as a consequence.
* Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
* As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
* It is quite simple to use.
* As a consequence, less energy is consumed.
* Rain sensor-based systems are extremely simple to install.
* Individual rain sensors are fairly inexpensive.

# Disadvantages:
* When water falls squarely on the rain sensor, the mechanism activates.
* The entire system cost rises when more components, including a rain sensor, are required.
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain. 
