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

<table>
  <tr>
    <th>Label</th>
    <th>Component</th>
    <th>Image</th>
  <tr>
    <td>1</td>
    <td>Left IR Sensor</td>
    <td rowspan="16"><img src="https://raw.githubusercontent.com/micromouse-utad/MMKit-PH/master/imgs/mmkit_components.jpeg"</img></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Forward Left IR Sensor</td>
  </tr>
  <tr>
    <td>3</td>
    <td>AA Batteries Support (4 – AA)</td>
  </tr>
  <tr>
    <td>4</td>
    <td>ON/OFF AA Batteries</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Left Stepper Motor</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Configurable Switches for Control Software</td>
  </tr>
  <tr>
    <td>7</td>
    <td>Connector for Right Motor</td>
  </tr>
  <tr>
    <td>8</td>
    <td>Right IR Sensor</td>
  </tr>
  <tr>
    <td>9</td>
    <td>Forward Right IR Sensor</td>
  </tr>
  <tr>
    <td>10</td>
    <td>Bluetootd Connector (module not included)</td>
  </tr>
  <tr>
    <td>11</td>
    <td>LED pin 13 / Buzzer (Buzzer not included)</td>
  </tr>
  <tr>
    <td>12</td>
    <td>LED ON/OFF</td>
  </tr>
  <tr>
    <td>13</td>
    <td>Jumper for Selection AA Batteries/LiPo Battery</td>
  </tr>
  <tr>
    <td>14</td>
    <td>Right Stepper Motor</td>
  </tr>
  <tr>
    <td>15</td>
    <td>ON/OFF LiPo Battery (Battery not included)    </td>
  </tr>
  <tr>
    <td>16</td>
    <td>Connector for Left Motor</td>
  </tr>
</table>

## Installation

To install the library you need to first download its [latest release](https://github.com/micromouse-utad/MMKit/releases/latest)
, as weel as the AccelStepper library provided. \
After both downloads have finished, add the libraries as zip files in the Arduino IDE. \
To do so, open the IDE an go:

![Arduino Import Libraries](https://www.arduino.cc/en/uploads/Guide/ImportLibraryFromZIPFile.png)

After, just select the path on your local machine to the libraries.

For more information on how to intall the libraries, check: https://www.arduino.cc/en/Guide/Libraries#toc4
