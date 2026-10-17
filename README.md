# Pac-Man Game

## Aim

To develop an interactive Pac-Man-style game using a joystick for
directional control.

## What Is the Project?

An electronic game in which the player controls a character, navigates
the game area, and follows the rules programmed into the ESP32.

## How Does It Work?

1.  The HW-504 joystick detects movement along its horizontal and
    vertical axes.
2.  The joystick generates signals corresponding to the direction in
    which it is moved.
3.  The ESP32 reads these signals and determines the intended direction.
4.  The program updates the character's position and checks the game
    rules.
5.  The character and game elements are rendered on the display used in
    the project.
6.  The display is connected via configured Bluetooth to the device
    used.

## Components Used

-   ESP32 microcontroller
-   HW-504 joystick module
-   Breadboard
-   Jumper wires

## Connections

  Joystick Pin   Connection to ESP32
  -------------- ---------------------
  VCC            5V
  GND            GND
  VRx            GPIO 34 (G34)
  VRy            GPIO 35 (G35)
  SW             GPIO 32 (G32)
