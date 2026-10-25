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
<img width="1800" height="4000" alt="WhatsApp Image 2026-10-25 at 19 52 23" src="https://github.com/user-attachments/assets/cfd39e22-05fa-4013-87bb-3b5028223e52" />
<img width="4000" height="1800" alt="WhatsApp Image 2026-10-25 at 19 52 24" src="https://github.com/user-attachments/assets/05894d49-1a54-4aed-afac-466471627186" />
<img width="1800" height="4000" alt="WhatsApp Image 2026-10-25 at 19 52 24f" src="https://github.com/user-attachments/assets/93700d40-5c5f-4944-9041-0cdbdadcd92d" />
<img width="3648" height="2052" alt="WhatsApp Image 2026-10-25 at 19 52 24g" src="https://github.com/user-attachments/assets/af906d25-8c45-4973-8125-73b3ce939e7f" />
<img width="1600" height="720" alt="f12" src="https://github.com/user-attachments/assets/fc31b353-37f8-4b18-892b-aac7e84b7d3f" />
<img width="1600" height="720" alt="f13" src="https://github.com/user-attachments/assets/50075b52-8b43-440c-8aa1-d72507670875" />

## 📝 What I Learned
- Real-time data communication between microcontrollers and a central server.
- Database management (SQL) and hardware-software integration.
- Professional PCB design and CNC manufacturing processes.
- Full project lifecycle: from Gantt chart planning to final technical report.
