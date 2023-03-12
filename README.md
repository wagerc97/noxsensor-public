# Showcase: NOXSENSOR project
[Purpose](#Purpose) |
[Usage](#Usage) |
[Code](#Code) |
[Features](#Features) |
[Retrospective](#Retrospective) |
[Pictures](/Pictures/picture_series.pdf) 


## Purpose
For the noxsensor project I build a device that visually detects hazardous gas in a highly corrosive environment. 
With the choice of an optical sensor and an airtight housing the final product is a very durable exhaust air sensor. 
It is designed to monitor the function of the exhaust air system and to send an alarm signal in case of emergency.
The device also features a magnetic reed sensor to monitor the fan functionality. 
The occurrence of NOx gas / nitrous gas with typical orange-red color in the exhaust air or a failure of the fan in the exhaust air system is reported as an emergency. 

Detailed description: [EN](/Descriptions/EN_Description.pdf) | [DE](/Descriptions/DE_Funktionsweise.pdf)

## Usage
The device operates on the plug-and-play principle and is designed to run non-stop. 
The Raspberry Pi needs network access (preferably Wi-Fi).
Then the user sets up the device at the desired location and within range of the network.
When the Raspberry Pi is supplied with power, the automatic monitoring program starts. 

To set up a fresh Raspberry Pi a script for complete installation is provided in the private repository. 
Only client specific customizations (e.g. alert email addresses, calibration intervals, etc.) have to be done.

Maintenance will be necessary depending on the environment. Most likely because the plexiglass window panes in the 3D printed housing will wear down over time.


## Code
The source code is stored in a private repository. For access requests, please contact me directly. 

## Features
- designed to run 24/7
- plug-and-play functionality
- easy to install through shell script
- out of the box Wi-Fi connection possible
- auto-calibration to environmental light conditions
- full logging with log rotation to manage device storage
- total acid and corrosion protection in special 3D printed housing
- sends E-mail alert in case of emergency or need for maintenance

## Retrospective
Since this was already my second Raspberry Pi project, I was able to deepen my know-how in working with Raspberry Pi and implement new ideas. 
Overall, I spend 100+ working hours on this project and gained lots of experience. 
For the first time I worked on sensor implementations, and I experimented with different modules. 
Also, I learned how to solder and improved my knowledge of electrical engineering. 
