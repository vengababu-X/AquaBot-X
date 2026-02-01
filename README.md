<p align="center">
  <img src="assets/aquabot_hero.gif" width="100%">
</p>

<h1 align="center">🐟 AquaBot-X</h1>

<p align="center">
  <b>Biomimetic Smart AI Fish Robot</b><br>
  <i>Underwater Exploration • Pollution Monitoring • Smart Surveillance</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/IoT-ESP8266-blue">
  <img src="https://img.shields.io/badge/Robotics-Biomimetic-green">
  <img src="https://img.shields.io/badge/Sensors-MQ135%20%7C%20IR%20%7C%20Ultrasonic-orange">
  <img src="https://img.shields.io/badge/Status-Prototype-success">
</p>

---

## 🌊 Project Overview

<p align="center">
  <img src="assets/overview.gif" width="75%">
</p>

**AquaBot-X** is an AI-powered **robotic fish prototype** designed to mimic natural fish movement while performing intelligent underwater tasks such as:

- 🌍 Underwater exploration  
- 🧪 Pollution & gas monitoring  
- 🛢️ Oil detection  
- 🎮 Manual & autonomous navigation  
- 📡 Real-time alerts and monitoring  

The project integrates **IoT, robotics, and AI concepts** to create a **low-cost, educational, and scalable** solution for marine research and environmental protection.

---

## ✨ Key Features

<p align="center">
  <img src="assets/features.gif" width="80%">
</p>

- 🚤 **Fish-like swimming motion** using servo motors  
- ⚡ **Gas detection (MQ-135)** with live data visualization  
- 🌊 **Oil detection** using IR sensor  
- 🔋 **Battery monitoring** with percentage calculation  
- 📡 **BLE alerts** when pollution thresholds are exceeded  
- 🌐 **Local web server** for manual & autonomous navigation  
- 🍽️ **Fish feeding mechanism** using gear motor  
- 🤖 Hybrid control: **AI + IoT based automation**

---

## 🧠 How AquaBot-X Works

<p align="center">
  <img src="assets/architecture.svg" width="85%">
</p>


---

## 🧪 Pollution & Gas Monitoring

<p align="center">
  <img src="assets/gas_monitoring.gif" width="70%">
</p>

- MQ-135 continuously monitors air/water quality  
- Threshold-based alerts trigger **BLE notifications**  
- Live data visualization using web interface  

---

## 🌐 Web Interface Control

<p align="center">
  <img src="assets/web_ui.gif" width="70%">
</p>

- Local web server hosted on ESP8266  
- Manual navigation (direction & speed)  
- Autonomous mode switching  
- Real-time sensor feedback  

---

## 🐠 Biomimetic Movement System

<p align="center">
  <img src="assets/swimming.gif" width="70%">
</p>

- Servo-driven propulsion system  
- Fish-inspired oscillatory motion  
- Energy-efficient underwater movement  

---

## 🔧 Hardware Components Used

| Component | Purpose |
|--------|--------|
| NodeMCU ESP8266 | Main controller & IoT communication |
| MQ-135 Gas Sensor | Pollution & gas detection |
| IR Sensor | Oil detection |
| Ultrasonic Sensor (HC-SR04) | Obstacle detection |
| Servo Motors (x2) | Propulsion & steering |
| Gear Motor + L298N | Feeding mechanism |
| Mini Water Pump + Relay | Water flow control |
| HM-10 BLE Module | Alerts & wireless communication |

---

## 📂 Project Structure
```
AquaBot-X/
│
├── code/
│   └── fish_robot_code.ino
│
├── circuit/
│   ├── wiring_diagram.png
│   └── block_diagram.png
│
├── images/
│   ├── prototype1.jpg
│   ├── prototype2.jpg
│   └── poster.jpg
│
├── web_ui/
│   └── web_ui.png
│
├── assets/
│   ├── aquabot_hero.gif
│   ├── overview.gif
│   ├── features.gif
│   ├── gas_monitoring.gif
│   ├── web_ui.gif
│   ├── swimming.gif
│   └── architecture.svg
│
└── README.md
```
---

## ⚙️ How to Run the Project

```bash
git clone https://github.com/vengababu-X/AquaBot-X.git
