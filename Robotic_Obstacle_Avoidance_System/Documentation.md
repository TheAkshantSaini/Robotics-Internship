# Obstacle Avoiding Robot with Ultrasonic Sensor

Welcome to the Obstacle Avoiding Robot project! This project is designed to help you create a robot that can autonomously move and avoid obstacles using an ultrasonic sensor. Follow the instructions below to get started with this exciting experiment.

## Getting Started

### Prerequisites

To build and run this project, you'll need the following components:

- Arduino board
- HC-SR04 ultrasonic sensor
- Space Robo Chip
- 4 motors (2 for the left side, 2 for the right side)
- Computer for programming and debugging

### Wiring

1. Connect the ultrasonic sensor to your Arduino board as follows:
   - Trigger pin of the sensor to pin 5 on your Arduino (define as `#define echo 5` in your code).
   - Echo pin of the sensor to pin 6 on your Arduino (define as `#define trigger 6` in your code).

2. Connect the four motor pins to your Arduino board. The left-side motors should be connected to pins 1 and 2, while the right-side motors should be connected to pins 3 and 4.

### Installing the Arduino IDE

If you haven't already, download and install the [Arduino IDE](https://www.arduino.cc/en/software) on your computer. This IDE will be used to upload the code to your Arduino board.

## Running the Program

1. Open the Arduino IDE on your computer.

2. Copy the code provided in the project's repository and paste it into the Arduino IDE.

3. Connect your Arduino board to your computer using a USB cable.

4. In the Arduino IDE, select the correct board and port in the "Tools" menu.

5. Click the "Upload" button in the Arduino IDE to compile and upload the code to your Arduino board.

6. Once the code is uploaded, you can disconnect the Arduino board from your computer and power it using an appropriate power source.

Your obstacle-avoiding robot is now ready to run! It will move autonomously, and when it detects an obstacle within 100 cm, it will stop.

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

## Conclusion

This project provides a basic framework for constructing an obstacle-avoiding robot using an ultrasonic sensor. With the provided code and wiring instructions, you can build your own robot that moves freely, detects obstacles, and stops when necessary. Enjoy experimenting and enhancing the capabilities of your robot!
