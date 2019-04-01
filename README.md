# Micromouse Kit library 

The MMkit is a library that provides an object-oriented interfacefor the [MicroMouse Kit Robot](https://www.micromouse.utad.pt/?page_id=998&lang=en), as well as some examples to help you start to program the MMKit. \
Some of this examples are: 

Basic: 
- MoveFoward
- TurnLeft
- TurnRight
- TesteIRSensors 

Advanced: 
- FloodFillAlgorithm
- RandomNextMove
- RightWallFollow

## The Kit

The robot as the following components

![MMKit with labels](https://www.micromouse.utad.pt/wp-content/uploads/2016/05/MicromouseKit-3.png)

| Label | Component                                      |
|:-----:|:-----------------------------------------------|
|    1  | Left IR Sensor                                 |
|    2  | Forward Left IR Sensor                         |
|    3  | AA Batteries Support (4 – AA)                  |
|    4  | ON/OFF AA Batteries                            |
|    5  | Left Stepper Motor                             |
|    6  | Configurable Switches for Control Software     |
|    7  | Connector for Right Motor                      |
|    8  | Right IR Sensor                                |
|    9  | Forward Right IR Sensor                        |
|   10  | Bluetooth Connector (module not included)      |
|   11  | LED pin 13 / Buzzer (Buzzer not included)      |
|   12  | LED ON/OFF                                     |
|   13  | Jumper for Selection AA Batteries/LiPo Battery |
|   14  | Right Stepper Motor                            |
|   15  | ON/OFF LiPo Battery (Battery not included)     |
|   16  | Connector for Left Motor                       |


## Installation

To install the library you need to first download its [latest release](https://github.com/micromouse-utad/MMKit/releases/latest)
, as weel as the AccelStepper library provided. \
After both downloads have finished, add the libraries as zip files in the Arduino IDE. \
To do so, open the IDE an go:

![Arduino Import Libraries](https://www.arduino.cc/en/uploads/Guide/ImportLibraryFromZIPFile.png)

After, just select the path on your local machine to the libraries.

For more information on how to intall the libraries, check: https://www.arduino.cc/en/Guide/Libraries#toc4
