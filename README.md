DIY Ultrasonic Radar System
A real-time object detection and visualization system that mimics a radar screen using an Arduino microcontroller, an ultrasonic sensor, and a servo motor.

🚀 Project Overview
This project creates a sweeping radar system that calculates the distance to objects in its path and displays the data in real-time on a computer screen using the Processing IDE. It demonstrates core concepts of sensor interfacing, data processing, and serial communication.

🛠️ Hardware Components
Microcontroller: Arduino Uno (ATmega328P)

Sensor: HC-SR04 Ultrasonic Distance Sensor

Actuator: SG90 Micro Servo Motor

Connections: Jumper wires, Breadboard

⚙️ Software & Technologies
Embedded Programming: Arduino (C++)

Desktop Visualization: Processing (Java-based)

Design & Simulation: Proteus Design Suite

Tools: Arduino IDE, Processing IDE

📁 Project Structure
text
DIY-Ultrasonic-Radar-System/
│
├── Arduino/
│   └── radar_system.ino    # Main firmware for Arduino
│
├── Processing/
│   └── radar_display.pde   # Code for the visual display
│
├── Simulations/
│   └── radar_proteus.pdsprj  # Circuit simulation file
│
├── Images/
│   ├── circuit_diagram.png
│   ├── project_photo.jpg
│   └── screenshot.png
│
└── README.md
🔌 Circuit Diagram
https://Images/circuit_diagram.png

*How to connect the HC-SR04 sensor and SG90 servo to the Arduino Uno.*

🧪 How It Works
The Arduino program sweeps the servo motor from 0 to 180 degrees and back.

At each degree, it triggers the ultrasonic sensor to calculate the distance to any object.
This data (angle and distance) is sent serially to the computer.

The Processing sketch reads this data and plots it on a radar-like display.
