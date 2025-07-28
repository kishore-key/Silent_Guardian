# 🔐 SilentGuardian – An IoT-Based Women Safety Alert Device

A rapid-response smart alert system built using **ESP32-C3**, **Telegram Bot API**, and a **vibration sensor** to provide **instant emergency notifications** without requiring GPS, external apps, or cloud dependencies.  
Developed in **12 hours** during the 🛠️ *LionCircuits x PCB Cupid 1.0 Hackathon* by Team 19 – SSN College of Engineering.

---

## 📹 Demo

🎥 [Click here to watch the working video](https://drive.google.com/file/d/15r_9ggiSoyBdhbDEd-R7voO9MUKwHn2Z/view?usp=drive_link)

---

## 📄 Downloads

- 📘 [View Documentation (PDF)](https://drive.google.com/file/d/1_DZSehVQ4mV-5An1KjDha0OluFvK2ii_/view?usp=drive_link)
- 💻 [Download Source Code (TXT)](https://drive.google.com/file/d/1zjA1uGXCpuU8vgXpuDz5dklDD1pkejVt/view?usp=drive_link)
- 🔧 [View Circuit Diagram](https://drive.google.com/file/d/1ueZmfGkveJkQSkrMLZSevIJGoFG96frH/view?usp=drive_link)

---

## 🚨 What It Does

- **Manual Alert:** Pressing a push button sends a Telegram alert instantly.
- **Passive Alert:** Sudden vibration triggers emergency message automatically.
- **Live Location:** Sends Wi-Fi-based Google Maps link to a private Telegram group.
- **Offline-Friendly:** Works without GPS or mobile app — just Wi-Fi.

---

## 🧠 Skills Applied

- Embedded Programming (Arduino + ESP32-C3)
- IoT Protocols (HTTP, Wi-Fi)
- Telegram Bot API Integration
- Sensor Interfacing (Tilt/Vibration)
- Google Maps Link Generation
- Real-Time Alert Systems

---

## 🧰 Hardware & Tools Used

- **ESP32-C3 (Glyph C3)**
- **SW-420 Vibration Sensor**
- **Tactile Push Button**
- **5mm LED + Resistors**
- **Jumper Wires + Breadboard**
- **Arduino IDE**
- **KiCad 9.0**

---

## 🔗 Pin Mapping

| Component        | GPIO Pin | Function               |
|------------------|----------|------------------------|
| Push Button      | GPIO 8   | Emergency Trigger      |
| Vibration Sensor | GPIO 3   | Motion Detection       |
| LED              | GPIO 2   | Visual Feedback        |
| Power Supply     | 3V3/GND  | All Components         |

---

## 🌍 Real-World Applications

- 👩‍🦰 Women & Child Safety
- 🧓 Elderly Emergency Support
- 🧒 Child Tracking & Alerts
- 🧭 Solo Worker Monitoring
- 🚑 Medical Emergency Triggers
- 🌍 Disaster Rescue Beacon

---

## 🧪 Working Principle

- Monitors both **button press** and **vibration trigger**
- On activation:
  - Sends SOS message over Telegram
  - Shares real-time location (via Google Maps link)
  - Lights LED for feedback
- Can be worn or embedded into accessories

---

## 📌 Future Improvements

- 📍 **Add GPS Module (NEO-6M)** for precise outdoor location
- 🖐️ **Touch Sensor (TTP223)** for silent activation
- 📞 **Direct Calling via GSM (SIM800L)** fallback
- 🎤 **Voice Recording Module (mic + SD card)** for evidence
- 🔋 **Battery Backup (Li-ion + TP4056)** for portability

---

## 🚀 Built At

🎯 **LionCircuits x PCB Cupid 1.0 Hackathon**  
⏱️ **Duration:** 12 Hours  
👨‍💻 **Team:** Kishore R, R Kishore, Moulieswaran A, Sree Balaji P  
🏫 **Institution:** SSN College of Engineering

---

## 🔗 Quick Start

```bash
# Clone this repository
git clone https://github.com/kishore-key/SilentGuardian.git

# Navigate into the project
cd SilentGuardian

# Open and upload code via Arduino IDE (ESP32-C3 board selected)
