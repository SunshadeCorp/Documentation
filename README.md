# EasyBMS

easyBMS is a battery management system for lithium-ion battery modules for solar energy installations.
Currently, easyBMS integrates primarily with NMC batteries, both 8s and 12s types, and Sungrow Hybrid inverters.
The battery management system consists of two parts: The BMS slaves and the BMS master together with a monitoring application.

## BMS Slave

The BMS slave has mainly two tasks: Balancing the cells of the battery systems and measuring cell voltages, temperatures and currents in order to monitor the battery health and the state of the system for safety.

![This is an image](https://raw.githubusercontent.com/SunshadeCorp/Documentation/main/pictures/bms.jpg)


## Control Box and BMS master

![This is an image](https://raw.githubusercontent.com/SunshadeCorp/Documentation/main/pictures/control-box.jpg)
![This is an image](https://raw.githubusercontent.com/SunshadeCorp/Documentation/main/pictures/control-box-open.jpg)

The Control Box contains a Raspberry Pi and different auxillary devices in order to create a BMS master that controls all the BMS slaves.
The box can feature a touch screen that shows an energy dashboard for the user.

## High Voltage Box (HV Box)

The High Voltage Box contains high voltage relais in order to be able to cut off the battery from the system.
The HV box is controlled by control lines from the Control Box.

![This is an image](https://raw.githubusercontent.com/SunshadeCorp/Documentation/main/pictures/hv-box.jpg)

## The Battery Cabinet

You can use your favorite battery with up to 12 sequential cells. The battery should be connected to the HV box over fuses.

## Installation

Below is a sample installation in a system with two solar roofs and one battery system, connected over an HV-Box and a Control-Box to a hybrid solar inverter.

![This is an image](https://github.com/SunshadeCorp/Documentation/blob/main/pictures/installation.jpg)

