# AquaBot-X
“Biomimetic Smart AI Fish Robot for underwater exploration, pollution monitoring, and surveillance using NodeMCU, sensors, and servo motors.”

# 🐟 AquaBot-X  
**Biomimetic Smart AI Fish Robot** for underwater exploration, pollution monitoring, and surveillance using **NodeMCU, sensors, and servo motors**.  

---

## 📌 Project Overview  
AquaBot-X is a prototype **AI-powered robotic fish** designed for:  
- Underwater exploration  
- Pollution monitoring  
- Oil detection and gas sensing  
- Automatic and manual navigation  
- BLE alerts and real-time web interface  

This project combines **IoT, robotics, and AI** to create a low-cost and educational solution for marine research and environmental monitoring.  

---

## ✨ Features  
- 🚤 Fish-like swimming motion with servo motors  
- ⚡ Gas detection (MQ-135) with live charts  
- 🌊 Oil detection using IR sensor  
- 🔋 Battery monitoring with percentage calculation  
- 📡 BLE alerts when thresholds are exceeded  
- 🌐 Local web server for manual + autonomous navigation  
- 🍽️ Fish feeding mechanism with gear motor  

---

## 🔧 Components Used  
- NodeMCU ESP8266  
- MQ-135 Gas Sensor  
- IR Sensor (oil detection)  
- Ultrasonic Sensor (HC-SR04)  
- 2 Servo Motors (propulsion + steering)  
- Gear Motor + L298N Motor Driver (feeding)  
- Mini Water Pump + Relay Module  
- HM-10 BLE Module  

---
## 📂 Project Structure  

AquaBot-X/  
│  
├── code/  
│   └── fish_robot_code.ino      # Main Arduino/NodeMCU code  
│  
├── circuit/  
│   ├── wiring_diagram.png       # Wiring diagram  
│   └── block_diagram.png        # Block connections  
│  
├── images/  
│   ├── prototype1.jpg           # Prototype photo 1  
│   ├── prototype2.jpg           # Prototype photo 2  
│   └── poster.jpg               # Poster for presentation  
│  
├── web_ui/  
│   └── web_ui.png               # Local server web UI screenshot  
│  
└── README.md                    # Project documentation


## ⚙️ How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/AquaBot-X.git

2. Open fish_robot_code.ino in Arduino IDE.


3. Install required libraries for ESP8266 and sensors.


4. Upload code to NodeMCU.


5. Open the local web server in your browser to control the fish bot.


🏆 Applications

Underwater surveillance

Marine pollution monitoring

Educational robotics projects

Low-cost biomimetic research

👨‍💻 Author

Vengababu – Electronics & Communication Engineer, Google Student Ambassador
