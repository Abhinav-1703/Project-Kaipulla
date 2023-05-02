# Project-Kaipulla
#Hand Gesture Controlled Robot Using Mpu6050 And Esps
This repository contains the code and schematics for a hand gesture controlled robot using the MPU6050 accelerometer and two ESP microcontrollers. The project aims to control the movement of a robot by sensing the orientation of the user's hand.

# Hardware Requirements
MPU6050 accelerometer module
Two ESP microcontrollers
Robot chassis with two motors
L298N motor driver
Breadboard
Jumper wires
Power source (battery pack)
#Circuit Diagram
The circuit diagram for the project can be found in the schematics directory.

# Libraries
The following libraries are required to run the code:

These libraries can be installed using the Arduino Library Manager.

# Code
Clone the repository or download the zip file and extract its contents.
Open hand_gesture_controlled_robot.ino in the Arduino IDE.
Connect the MPU6050 and ESP microcontrollers to the breadboard as shown in the circuit diagram.
Upload the code to the ESP microcontrollers. Make sure to select the correct board and port in the Arduino IDE.
Connect the L298N motor driver to the motors and power source.
Turn on the power source and wait for the ESP microcontrollers to connect to each other via ESPNow.
Usage
Turn on the power source.
Connect to the Wi-Fi network created by the receiving ESP microcontroller.
Hold the MPU6050 and orient your hand to control the robot's movement.
Release the MPU6050 to stop the robot.
Contributing
If you have any suggestions for improvements or bug fixes, feel free to open an issue or a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
