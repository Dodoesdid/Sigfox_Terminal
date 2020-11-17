# Sigfox Terminal

## Overview
This is collaboration done by four students in NTUST. Anshul and Pratik are PhD students from ME, Quency and Jonathan are undergraduate students from ECE. This projects aims at making a low power Sigfox terminal device.

## Features
* 2 year long battery life
* Notifications through Sigfox in case of a peripheral update

## Specifications
1. MCU: stm32f103c8t6 
2. Sigfox Transciever: UnaMkr Mini
3. PCB: 4 layered
4. Components: SMD 0805 to 2010

## Design Environment
* Embedded C: KeilARM
* PCB: EasyPC
> Note: These two IDEs are both free with limited access

## File Structure
```C
+---
|   +---Drivers             // drivers provided by ARM and ST
|   |   +---CMSIS
|   |   +---STM32F1xx_HAL_Driver
|   \---Inc
|   \---MDK-ARM
|   \---Src                 // User code
\---PCB
    +---Design_1            // First Design using DIP components   
    \---Design_2            // Second Design using SMD components
        |   Project_2.sch   // Schematic file
        |   Project_2_1.pcb // PCB file
        \---Outputs
            +---BOM         // Bill of Material (Component List)
            +---Gerber      // File for PCB Manufacturer
            \---Schematic   // PDF schematics for reading purpose
```
## Final Product

### Device
![](https://i.imgur.com/F9VdhVe.jpg)
### Sigfox Backend
![](https://i.imgur.com/8MeSyO2.png)



