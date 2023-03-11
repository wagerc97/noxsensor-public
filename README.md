# Showcase: NOXSENSOR project
[Purpose](#Purpose) |
[Usage](#Usage) |
[Code](#Code) |
[Features](#Features) |
[Retrospective](#Retrospective) |
[Pictures](/Pictures) 


## Purpose
For the noxsensor project I build a device that visually detects hazardous gas in a highly corrosive environment. 
With the choice of an optical sensor and an airtight housing the final product is a very durable exhaust air sensor. 
It is designed to monitor the function of the exhaust air system and to send an alarm signal in case of emergency.
The device also features a magnetic reed sensor to monitor the fan functionality. 
The occurrence of NOx gas / nitrous gas with typical orange-red color in the exhaust air or a failure of the fan in the exhaust air system is reported as an emergency. 

Detailed description: [EN](/Descriptions/EN_Description.pdf) | [DE](/Descriptions/DE_Funktionsweise.pdf)

## Usage
The device operates on the plug-and-play principle. As soon as the RPI is supplied with power, 
the automatic monitoring program starts. For more information, see the Internal Processes chapter.

## Code
The code is stored in a private repository. For access requests, please contact me directly. 

## Features
- plug-and-play functionality
- total acid and corrosion protection in special 3D printed housing 
- out of the box Wi-Fi connection 
- logging all actions with logrotate 
- easy to install through shell script 
- auto-calibration to environment
- E-mail communication in case of emergency or need for maintenance

## Retrospective
Since this was already my second Raspberry Pi project, I was able to deepen my know-how in working with Raspberry Pi and implement new ideas. 
Overall, I spend 100+ working hours on this project and gained lots of experience. 
For the first time I worked on sensor implementations, and I experimented with different modules. 
Also, I learned how to solder and improved my knowledge of electrical engineering. 
