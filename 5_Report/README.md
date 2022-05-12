# SOFTWARE REQUIREMENTS:
* STM32 CubeIDE
# COMPONENTS:
* STM32F407VG MICROCONTROLLER BOARD
# Abstract:
* A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. The prior system required manual wiper activation, and the operation of bringing up the wiper was difficult to manage. As a result, this method is proposed to address these issues. The project's goals are to improve ageing automobiles' systems by giving automated transmission. wiping system, to enhance the system by including a sensor and an actuator, and to create a simple software that would completely work with the system the framework.This proposed wiper system's principle is comparable to those of other existing conventional wipers.
                      
* we use the STM32F4xx-discovery board to illustrate an automobile wiper control system. Most automobile wipers are controlled by a DC motor, however because the STM32F4xx-discovery lacks a motor, we are exploring using LEDs in this application. As an example, the wiper control system. The STM32F4xx-discovery board has four LEDs and a Push Button. The colours of these LEDs are orange, green, red, and blue. A current limiting resistor connects four user LEDs to the PD12, PD13, PD14, and PD15 pins of PORTD on the Discovery board. To make a push button work with the STM32F407VG microcontroller, the GPIO pins will be set as digital input pins. If you push and hold the user button for two seconds, the Red When the ignition key is positioned at the ACC, the LED illuminates. Furthermore, the LEDs are flickering, indicating that the wipers are turned on.
# DESCRIPTION:
* The STM32F405xx and STM32F407xx family is based on the high-performance Arm® Cortex®-M4 32-bit RISC    core operating at a frequency of up to 168 MHz. The Cortex-M4 core features a Floating point unit (FPU) single precision which supports all Arm single-precision data-processing instructions and data types. It also implements a full set of DSP instructions and a memory protection unit (MPU) which enhances application security. The STM32F405xx and STM32F407xx family incorporates high-speed embedded 
# STM32F407VG:

# FEATURES OF STM32F407VG MICROCONTROLLER:
* Up to 1 Mbyte of Flash memory.
* Up to 192+4 Kbytes of SRAM including 64-Kbyte of CCM (core coupled memory) data RAM.
* 512 bytes of OTP memory.
* Flexible static memory controller supporting Compact Flash, SRAM, PSRAM, NOR and NAND memories.
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





