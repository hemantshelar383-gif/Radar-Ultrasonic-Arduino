# Ultrasonic Radar System using Arduino

A real-time ultrasonic radar system built using Arduino, HC-SR04 ultrasonic sensor and a servo motor.  
The radar scans the environment in a 180° range and displays object distance on a Processing IDE GUI.

---

## 📌 Project Overview

This project visualizes distance readings from an ultrasonic sensor in the form of a radar sweep.  
A servo motor rotates the sensor, and the Processing interface renders a live radar display using serial data sent from the Arduino.

This project demonstrates embedded systems fundamentals, serial communication, and hardware–software integration.

---

## 🛠️ Components Used

- **Arduino Uno**
- **HC-SR04 Ultrasonic Sensor**
- **SG90 Servo Motor**
- **Jumper Wires**
- **Breadboard**
- **USB Cable (Arduino Upload)**

---

## ⚙️ Working Principle

1. The servo rotates from **0° to 180°** and back.  
2. At each angle, the HC-SR04 sensor measures distance using ultrasonic pulses.  
3. Arduino sends the angle + distance to the PC via Serial communication.  
4. The Processing sketch reads the data and draws a real-time radar visualization.

This creates a scanning radar effect similar to actual radar systems.

---

## 🔧 Arduino Code

The Arduino sketch:
- Controls the servo motor sweep  
- Reads distance from HC-SR04  
- Sends JSON-like data packets to Processing  

📁 **Location:** `Arduino/Ultrasonic_Radar.ino`

---

## 💻 Processing IDE Code

The Processing sketch:
- Receives serial data from Arduino  
- Draws a radar arc  
- Displays object distance visually in real time  

📁 **Location:** `Processing/Radar_Processing.pde`

---






