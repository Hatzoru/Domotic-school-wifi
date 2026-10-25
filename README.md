# Advanced School Domotics System (IoT) 🤖🏫

## 📌 Project Overview
Developed a comprehensive IoT-based security and automation system for a school environment. The project aimed to solve specific issues like bicycle shed security (using fingerprint access), gas leak detection in classrooms, and energy efficiency (motion-sensor lighting).

## ⚙️ Architecture & Tech Stack
- **Central Server:** Raspberry Pi 3 B+ (running the main web server and database).
- **Slave Modules:** ESP8266 (D1 Mini) microcontrollers.
- **Sensors:** MQ-2 (Gas/Smoke), PIR SR501 (Motion), DHT11/DHT22 (Temp/Humidity), AS606 (Fingerprint).
- **Communication:** WebSockets (real-time updates), Wi-Fi.
- **Database:** SQL (for logging access times and user data).
- **UI:** VirtuinoIOT (Mobile app) and a web interface.

## 🔧 Hardware & Manufacturing
- **PCB Design:** 3 custom PCBs designed in Proteus.
- **Manufacturing:** Milled using a CNC machine (Gerber export via FlatCAM).
- **Actuators:** 5V Relays, 12V exhaust fans, LED strips, 12V motor for sliding gate.
- **Power:** Custom linear power supply (LM7805).

## 📸 Media & Documentation
*(Replace these with actual links to your photos/videos)*
- [Photo 1: Final PCB with ESP8266 and Relays]
- [Photo 2: Fingerprint sensor mounted in the electrical box]
- [Video: Web interface controlling the lights and displaying sensor data]

## 📝 What I Learned
- Real-time data communication between microcontrollers and a central server.
- Database management (SQL) and hardware-software integration.
- Professional PCB design and CNC manufacturing processes.
- Full project lifecycle: from Gantt chart planning to final technical report.
