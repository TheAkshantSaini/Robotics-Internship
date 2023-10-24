# Bluetooth-Controlled Robot with Joystick

Welcome to the Bluetooth-Controlled Robot with Joystick project! In this repository, you will find the code and resources needed to construct a robot that can be controlled via a joystick using a Bluetooth module. This README will provide you with an overview of how the program has been designed and implemented.

## Program Overview

The objective of this project is to create a robot that can be maneuvered in four primary directions: forward, backward, left, and right. To achieve this, we've employed a character 't' to represent the control input. We've also assigned specific digital pins to various components of our robot:

- Digital Pin 2: R1
- Digital Pin 3: R2
- Digital Pin 4: L1
- Digital Pin 5: L2

## Inputs and Outputs

All of the mentioned pins (R1, R2, L1, and L2) are set as outputs in our program. To accomplish this, we use the 'pinMode' function in the Arduino code. The 'void loop' segment outlines this setup as follows:

arduino
pinMode(R1, OUTPUT);
pinMode(R2, OUTPUT);

We've previously defined 't' as a serial input, which plays a crucial role in determining the robot's behavior.

## Conditional Statements
The heart of the program lies in the conditional statements that dictate the robot's movements. Here's a breakdown:

- If 't' equals 'b,' the robot moves forward.
- If 't' equals 'l,' the robot first turns left and then turns right when 't' equals 'r.'

These character representations ('f,' 'b,' 'l,' and 'r') correspond to the switches commonly found in joystick controller programs, whether it's a mobile app or a dedicated physical controller.

## Running the Program
With the character mappings and pin configurations in place, you're all set to run the program and control your robot with ease.

## Getting Started
### To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Set up your hardware as described in the documentation.
3. Upload the Arduino code to your microcontroller.
4. Pair your Bluetooth module with your controller (e.g., mobile app).
5. Use the controller to send 'b,' 'l,' or 'r' to move your robot.
6. Enjoy exploring the capabilities of your Bluetooth-controlled robot with joystick!

# Contributing
If you have ideas for improvements or would like to contribute to this project, please feel free to submit a pull request.
