# Line Following Robot with IR Sensor

## Introduction
This project is an experiment to build a line-following robot using an infrared (IR) sensor. The IR sensor is a type of proximity sensor that emits an electromagnetic field or a beam of electromagnetic radiation, and it can detect changes in this field or signal. When light strikes a white surface, it is mostly reflected, while light striking a black surface is absorbed. In this project, we will use either a white or black surface for the robot to follow.

## Hardware Setup
Before working with the programming, it's essential to set up the hardware correctly. Here are the hardware components used in this project:

- **Motors**: The robot is equipped with two motors, with motor pins numbered as follows:
  - Motor 1: Right motor (Pin 1 and 2)
  - Motor 2: Left motor (Pin 3 and 4)

- **IR Sensors**: The robot is equipped with two IR sensors:
  - Left sensor, connected to space robo chip's pin number 6
  - Right sensor, connected across digital pin 5

## Programming
The core functionality of the line-following robot is based on the readings from the IR sensors. These sensors detect the contrast between the surface (white or black) and provide feedback to the robot's control system.

### Variable Declarations
In the code, the following variables are declared:
- `int l`: This variable will store the reading from the left sensor.
- `int r`: This variable will store the reading from the right sensor.

These variables are declared globally, making them accessible throughout the code.

### Void Setup
In the `void setup` section, any necessary initialization and configuration of the robot's components take place. For example, setting the motor pins as outputs and specifying the communication protocol for the IR sensors.

### Main Functionality
The main functionality of the line-following robot is implemented in the code. It relies on the readings from the left and right sensors (`l` and `r`) to make decisions about how the robot should navigate along the line.

The algorithm for the robot to follow the line can be implemented using conditional statements, loops, and motor control functions. The specifics of this algorithm will depend on the design and requirements of your robot.

## Contribution
Contributions to this project are welcome. If you'd like to contribute, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and test thoroughly.
- Create a pull request, explaining the changes you've made.

## Conclusion
This project demonstrates the creation of a line-following robot using IR sensors to detect and navigate along a line, typically drawn on a surface that provides a contrast in reflectivity. The provided information is a foundation for understanding the hardware setup and basic code structure. Further customization and refinement of the robot's behavior can be achieved by modifying the code to suit specific application requirements.

For detailed information on code implementation and specific functionalities, please refer to the code files included in this project.
