# Gesture-Controlled-Robot
Gesture Controlled Robot

A wireless robot that moves based on hand tilt gestures using an MPU6050 accelerometer and Arduino compatible microcontroller. The robot interprets hand movements in real-time and moves accordingly, making it suitable for interactive robotics, automation learning, or hobby projects.

🚀 Features

Moves forward, backward, left, and right based on hand tilt gestures detected by MPU6050.

Wireless control using HC-05 Bluetooth module.

Real-time motor control for smooth and accurate movement.

Portable and suitable for robotics learning and demonstration projects.

🛠️ Tech Stack

Microcontroller: Arduino Uno 

Programming Language: /C++

Components:

MPU6050 Accelerometer

HC-05 Bluetooth Module

DC Motors

Motor Driver (L293D)

Wheels

Breadboard & Power Supply

⚡ Circuit Diagram (Connections)

Component	Arduino Pin
MPU6050 SDA	A4
MPU6050 SCL	A5
HC-05 TX	2
HC-05 RX	3
Motor Driver IN1	4
Motor Driver IN2	5
Motor Driver IN3	6
Motor Driver IN4	7
Motor Driver ENA	9
Motor Driver ENB	10
DC Motors	L293D pins

📜 Code
The complete Arduino / RobotC code is available in this repository: Gesture Controlled Robot Code

🔧 How It Works

The MPU6050 accelerometer detects hand tilt along X and Y axes.

Arduino reads sensor data via I2C and interprets the gestures.

Based on tilt direction, Arduino sends PWM signals to the motor driver to control DC motors.

HC-05 Bluetooth module allows wireless commands for additional control or calibration.

🚦 Future Improvements

Add smartphone app integration for gesture visualization.

Implement speed control based on hand tilt magnitude.

Integrate with IoT for remote monitoring or control.

📌 Author
👩‍💻 Yuktha Charith
🔗 GitHub Profile
