# Bluetooth-Controlled Robot with Joystick

Welcome to the Bluetooth-Controlled Robot with Joystick project! In this repository, you will find the code and resources needed to construct a robot that can be controlled via a joystick using a Bluetooth module. This README will provide you with an overview of how the program has been designed and implemented.

## Prerequisites

Before getting started, make sure you have the following prerequisites in place:

- An Arduino-compatible microcontroller (e.g., Arduino Uno or Arduino Nano).
- A Bluetooth module (e.g., HC-05 or HC-06).
- Joystick controller, which could be a mobile app or a physical controller.
- Basic knowledge of Arduino programming and circuit connections.
- Arduino IDE installed on your computer.

## Wiring

To set up the hardware for this project, follow these wiring instructions:

1. Connect the Bluetooth module to your Arduino:
   - VCC -> 5V
   - GND -> GND
   - TXD -> RX (Receive on Arduino)
   - RXD -> TX (Transmit on Arduino)

2. Connect the motor drivers and motors to the Arduino using the following pin configurations:

- Digital Pin 2: R1 (Right Motor 1)
- Digital Pin 3: R2 (Right Motor 2)
- Digital Pin 4: L1 (Left Motor 1)
- Digital Pin 5: L2 (Left Motor 2)

Make sure your robot chassis and motor drivers are properly connected to the motors and wheels.
![Screenshot 2023-10-25 014110](https://github.com/TheAkshantSaini/Robotics-Internship/assets/92256182/31013863-f94d-45ea-9606-85ee0cf394d6)


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

Now that you have your hardware set up, follow these steps to run the program:

1. Clone this repository to your local machine.

2. Open the Arduino IDE and load the provided Arduino sketch (`.ino` file).

3. Select the appropriate board type and COM port from the Arduino IDE.

4. Upload the code to your microcontroller.

5. Pair your Bluetooth module with your controller (e.g., mobile app) according to the manufacturer's instructions.

6. Use your controller to send commands 'b' (backward), 'l' (left), or 'r' (right) to control your robot.

Enjoy exploring the capabilities of your Bluetooth-controlled robot with a joystick!

## Getting Started
### To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Set up your hardware as described in the documentation.
3. Upload the Arduino code to your microcontroller.
4. Pair your Bluetooth module with your controller (e.g., mobile app).
5. Use the controller to send 'b,' 'l,' or 'r' to move your robot.
6. Enjoy exploring the capabilities of your Bluetooth-controlled robot with joystick!

## Contributing

We welcome contributions from the community to enhance and expand this project. If you have ideas for improvements, additional features, or bug fixes, feel free to contribute. Here's how you can get involved:

1. Fork the project repository to your GitHub account.

2. Clone the forked repository to your local machine.

3. Create a new branch for your feature or bug fix.

4. Make your changes and test them thoroughly.

5. Commit your changes with descriptive commit messages.

6. Push your changes to your GitHub repository.

7. Create a pull request from your repository to the original project repository.

8. Your contribution will be reviewed, and if everything is in order, it will be merged into the project.

Thank you for your contributions!

Let's build amazing robots together! 🤖✨
