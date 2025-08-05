# Arduino-Based Obstacle Avoiding Smart Robotic Vacuum Cleaner

## Description
An Arduino-based obstacle avoiding smart robotic vacuum cleaner is an autonomous cleaning robot designed to detect and avoid obstacles using ultrasonic and IR sensors. Controlled by an Arduino, it navigates intelligently while vacuuming dust, making it ideal for home cleaning automation.

## Features
- Obstacle avoidance using ultrasonic sensors  
- Edge/cliff detection with IR sensors  
- Autonomous movement and cleaning  
- Controlled by Arduino microcontroller  
- Affordable and customizable DIY solution  

## Components Required
- Arduino Uno or Nano  
- L298N Motor Driver Module  
- 2x DC Geared Motors with Wheels  
- Ultrasonic Sensor (HC-SR04)  
- IR Sensors (for edge detection)  
- Vacuum Motor or Fan  
- Rechargeable Battery Pack  
- Robot Chassis  
- Jumper Wires, Screws, and Connectors  

## Working Principle

The Arduino-based obstacle avoiding smart robotic vacuum cleaner works by integrating sensor inputs and controlling motors to navigate and clean autonomously. Here's how it functions step-by-step:

### 1. Obstacle Detection using Ultrasonic Sensor
- The ultrasonic sensor emits waves and measures the echo time to detect nearby objects.
- If an object is detected within a set distance (e.g., 20 cm), the Arduino redirects the robot to avoid a collision.

### 2. Edge/Cliff Detection using IR Sensors
- IR sensors monitor for sudden drops (like stairs).
- When a cliff is detected (no reflected signal), the robot stops and changes direction to prevent falling.

### 3. Movement and Navigation
- The L298N motor driver controls two DC motors for wheel movement.
- The robot navigates based on sensor data:
  - Moves forward if the path is clear  
  - Turns or reverses when an obstacle or edge is detected  

### 4. Cleaning Mechanism
- A vacuum motor creates suction to collect dust and debris.
- The vacuum remains on while the robot moves, gathering dirt into an onboard dustbin.

### 5. Power Supply
- A rechargeable battery pack powers all components.
- Voltage regulation ensures proper power delivery to Arduino, sensors, and motors.

### 6. Autonomous Loop
- The Arduino runs a loop that:
  - Continuously reads sensor data  
  - Makes decisions to avoid obstacles  
  - Controls movement and cleaning  
- This loop enables fully autonomous operation without human input.

## Circuit Diagram
> ![WhatsApp Image 2025-08-05 at 22 58 40_3eda9e58](https://github.com/user-attachments/assets/bfeec0cb-ee50-46fe-8b4e-8fd29b767fab)

## Setup Instructions
1. Mount all components onto the robot chassis.  
2. Connect all electronics as per the circuit diagram.  
3. Upload the Arduino sketch using Arduino IDE.  
4. Power the robot and place it on the floor to start autonomous cleaning.

## Arduino Code
> (https://github.com/ChaitanyaJenne/Arduino-Based-Obstacle-Avoiding-Smart-Robotic-Vacuum-Cleaner/blob/main/ARDUINO_OBSTACLE_AVOIDING_CAR.ino)

## Future Enhancements
- Add Bluetooth or Wi-Fi for smartphone control  
- Implement automatic charging dock  
- Use SLAM or path optimization algorithms  
- Add a dust sensor for targeted cleaning  

## License
This project is open-source and free for educational and personal use.

## Author
*JenneChaitanya*  
Contact: jennechaitanya@gmail.com
