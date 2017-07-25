# FingerLib

## Description
This library can be used to control up to 6 fingers, which allows control for an Open Bionics robotic hand ([Ada](../3Dprinting/ada.md), [Brunel](../3Dprinting/brunel.md)). Each finger is actuated using a Firgelli
linear actuator, where the position is determined by using the embedded linear potentiometer.

[FingerLib.h](https://github.com/Open-Bionics/FingerLib/blob/master/src/FingerLib.h) has been designed to closely resemble the Servo.h library, to allow ease of implementation for hobbyists and researchers.


## Supported Boards
- Almond board
- Chestnut board
- Arduino UNO (Timer 1)
- Atmega2560 (Timer 5)
- Arduino Zero (TC4)