
This project controls 4 servo motors to demonstrate basic movement patterns for a humanoid robot, with an algorithm for walking mechanics.

## Features
- Synchronized control of 4 servos
- Position holding at 90°
- Walking algorithm for bipedal motion

## Hardware Requirements
- Arduino Uno/Nano
- 4 servo motors
- Jumper wires
- 5V power supply

## Installation
1. Connect servos to pins 3, 5, 6, and 10
2. Upload the code to Arduino
3. Power the system


## Walking Algorithm
The walking sequence follows these phases:

1. Right Step Phase

Lift right leg (20° hip rotation)

Swing forward (20° knee rotation)

Lower leg

Weight shift left (-10° adjustment)

2. Left Step Phase

Lift left leg

Swing forward

Lower leg

Weight shift right
