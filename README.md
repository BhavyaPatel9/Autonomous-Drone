# Samarthya — Autonomous Delivery Drone

![ROS1](https://img.shields.io/badge/ROS1-Noetic-22314E?style=flat-square&logo=ros&logoColor=white)
![ArduPilot](https://img.shields.io/badge/Autopilot-ArduPilot-orange?style=flat-square)
![Gazebo](https://img.shields.io/badge/Simulation-Gazebo-darkblue?style=flat-square)
![DroneKit](https://img.shields.io/badge/API-DroneKit-green?style=flat-square)
![MAVProxy](https://img.shields.io/badge/GCS-MAVProxy-blue?style=flat-square)
![RTK-GPS](https://img.shields.io/badge/Navigation-RTK--GPS-red?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.x-yellow?style=flat-square&logo=python)
![Ubuntu](https://img.shields.io/badge/OS-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**Samarthya** is a fully custom-built **autonomous delivery drone system** developed for the **SAE-INDIA Autonomous Drone Development Challenge (ADDC) 2025**, securing **AIR 2 nationwide**.

The platform focuses on **high-precision navigation, autonomous mission execution, and vision-assisted landing** for delivery applications.

---

## 🏆 Achievement

🥈 **AIR 2 – SAE INDIA ADDC 2025**

Designed, built, and deployed a **fully autonomous UAV** capable of precision navigation and landing using **RTK-GPS and vision-based guidance**.

<p align="center">
  <img src="https://raw.githubusercontent.com/BhavyaPatel9/Autonomous-Drone/main/Smarthya_trophy.jpg" width="500">
</p>

---

## ✨ Key Features

- 📍 **RTK-GPS based autonomous waypoint navigation**
- 🎯 **ArUco marker precision landing**
- 🛰 **Centimeter-level positioning**
- 🖥 **Custom GUI with live telemetry**
- 🚁 Fully autonomous **mission execution**
- 🔬 **Simulation-first testing pipeline**

---

## ⚙️ Tech Stack

| Layer | Technology |
|------|------------|
| Autopilot | ArduPilot |
| Robotics Middleware | ROS1 Noetic |
| Simulation | Gazebo + ArduPilot SITL |
| Navigation | RTK-GPS |
| Vision | ArUco Marker Detection |
| Ground Control | MAVProxy |
| API | DroneKit |
| Language | Python |

---

## 🧪 Simulation Pipeline

Before real-world deployment, the system was extensively tested using:

- **ArduPilot SITL**
- **ROS1 Noetic**
- **Gazebo Simulation**

Validated capabilities:

- waypoint navigation  
- mission automation  
- landing accuracy  
- telemetry monitoring  

This ensured **safe and repeatable testing before hardware flights**.

---

## 🎯 Precision Landing

The landing system combines:

**RTK-GPS**
- centimeter-level global positioning

**ArUco Marker Vision**
- visual correction during final descent
- accurate delivery landing

This hybrid approach ensures **high reliability even with GPS drift**.

---

## 🖥 Ground Control Interface

A **custom GUI integrated with the GCS** provides:

- live telemetry visualization  
- flight logs  
- mission monitoring  
- simplified mission control  

<p align="center">
  <img src="https://raw.githubusercontent.com/BhavyaPatel9/Autonomous-Drone/main/GUI.png" width="700">
</p>

---


---

## 🚀 System Workflow

```

Mission Planning → MAVProxy / GUI
↓
ArduPilot Flight Controller
↓
DroneKit Autonomy Logic
↓
RTK-GPS + ArUco Vision
↓
Autonomous Navigation & Precision Landing

```
---

## 📌 Capabilities

✔ Autonomous waypoint navigation  
✔ Vision-assisted precision landing  
✔ Delivery mission automation  
✔ Telemetry monitoring  
✔ Simulation-first validation  

---

## 👨‍💻 Author

**Bhavya Patel**  
ECE — Sardar Vallabhbhai National Institute of Technology (SVNIT)

Autonomous UAV Systems • Robotics • Navigation • SLAM
