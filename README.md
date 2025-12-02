\# Radar System using Ultrasonic Sensor and Arduino



This project creates a simple radar system using an HC-SR04 ultrasonic sensor and Arduino UNO. 

The servo rotates the sensor from 0° to 180° and measures distance to display object detection.



\## Components Used

\- Arduino UNO

\- HC-SR04 Ultrasonic Sensor

\- SG90 Servo Motor

\- Jumper Wires

\- Breadboard



\## Working Principle

\- The servo rotates the ultrasonic sensor.

\- The sensor sends ultrasonic pulses and receives echoes.

\- Arduino calculates distance.

\- Results can be displayed on Serial Monitor or Processing Radar GUI.



\## Connections

\- Trigger → D9  

\- Echo → D10  

\- Servo Signal → D11  

\- VCC → 5V  

\- GND → GND



\## How to Use

1\. Upload the code from `code.ino` to Arduino UNO.

2.after uploading in Arduino uno upload the code from 'radar\_processing.pde' to processing ide.

3. Open Serial Monitor at 9600 baud.

4. Mount ultrasonic sensor on servo.

5. Observe rotation + distance reading.





\## Future Improvements

\- Add graphical radar using Processing.

\- Add buzzer alert.

\- Add LCD display.



