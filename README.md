# Radar Using Ultrasonic Sensor & Arduino

This project implements a simple radar system using an ultrasonic sensor mounted on a servo motor.  
The sensor rotates from 0° to 180° and measures distance to nearby objects, visualized using a Processing-based radar GUI.

---

## 📦 Components Used

- Arduino UNO  
- Ultrasonic Sensor (HC-SR04)  
- Servo Motor (SG90)  
- Jumper Wires  
- Breadboard  
- USB Cable  
- Laptop / PC  

---

## ⚡ Circuit Connections

- **HC-SR04 Trigger** → D9  
- **HC-SR04 Echo** → D10  
- **Servo Motor** → D11  
- **VCC** → 5V  
- **GND** → GND  

---

## 🛠 How to Use

1. Open `code.ino` in the Arduino IDE and upload it to the Arduino UNO.  
2. Open `radar_processing_pde.pde` in the Processing IDE.  
3. Select the correct COM port in Arduino and Processing.  
4. Confirm serial data at **9600 baud** in Arduino Serial Monitor.  
5. Run the Processing sketch to view the radar GUI.  
6. Mount the ultrasonic sensor on the servo and observe the radar sweep.

---

## 🎥 Demo Video

Watch the live working demonstration here:  
👉 **https://youtube.com/shorts/izTVSuXe0UE?si=S3Rz2kS1nIQ-uGib**

---

## 📊 Applications

- Object detection  
- Basic security systems  
- Robotics and automation  
- Distance measurement  
- Educational electronics projects  

---

## 🚀 Future Improvements

- Improve radar GUI (colors, labels, arcs, distance markers)  
- Add buzzer alert for close objects  
- Add OLED / LCD display for angle & distance  
- Add real-time data logging  

---

## 👤 Author

**Hemant Shelar**  
Electronics & Telecommunication Engineering  
Zeal College, Pune University  

---

## 📁 Project Files Included

- `code.ino` — Arduino code  
- `radar_processing_pde.pde` — Processing radar visualization code  
- README (this file)

---







