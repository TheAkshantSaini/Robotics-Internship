# Ultrasonic Basics:

An ultrasonic sensor is an electronic device that measures the distance of a target object by emitting ultrasonic sound waves. Usually a normal ultrasonic sensor will have 4 pins.
In order to generate the ultrasound we need to set the Trigger Pin on a High State for 10 microseconds.
That will send out an 8 cycle sonic burst which will travel at the speed sound and it will be received in the Echo Pin. 
The Echo Pin will output the time in microseconds the sound wave traveled.

## Experiment Connections:
![Screenshot 2023-10-25 013710](https://github.com/TheAkshantSaini/Robotics-Internship/assets/92256182/6a445c49-f5b3-44c7-b05f-29f55e702e66)

• Vcc to 5V of Space Robochip
• Trig to Digital Pin 5 of Space Robochip
• Echo to Digital Pin 6 of Space Robochip
• GND to GND of Space Robochip

## Code Description:

The code provided is for an Arduino sketch that measures the distance to an object using an ultrasonic sensor.
The sensor sends out a pulse of sound waves and measures the time it takes for the waves to bounce back.
By knowing the speed of sound, the code calculates the distance to the object and prints it to the serial monitor.
