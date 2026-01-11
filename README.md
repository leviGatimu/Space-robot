# 🚀 Planetary Scout: Autonomous Sample Collector

![Project Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)
![Mission](https://img.shields.io/badge/Mission-Sample%20Collection-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **Mission Directive:** To autonomously navigate extraterrestrial terrains, identify viable geological samples, and retrieve them safely—eliminating the risk to human astronauts.

---

## 🌌 Overview
This project focuses on building a semi-autonomous rover designed for high-risk planetary environments. Unlike traditional rovers that require constant manual input, the **Planetary Scout** uses onboard sensors to detect obstacles and identifies interesting rock formations for collection.

### Key Features
* **🤖 Autonomous Navigation:** Obstacle avoidance using ultrasonic/LiDAR sensors.
* **🪨 Sample Retrieval:** Robotic arm mechanics for grabbing and storing soil/rock samples.
* **📡 Telemetry:** Real-time data transmission of temperature, radiation levels, and visual feeds.
* **🔋 Solar Efficiency:** Power management system for long-duration missions.

---

## 🛠️ Build Materials & Hardware
We have compiled a complete list of all sensors, motors, chassis parts, and microcontrollers used in this build.

📄 **[Download the Full Materials List (PDF)](./docs/materials.pdf)**

*Quick Specs:*
* **Microcontroller:** (e.g., Raspberry Pi 4 / Arduino Mega)
* **Motors:** High-torque DC motors with encoders
* **Chassis:** Reinforced aluminum alloy
* **Power:** LiPo Battery Pack + Solar trickle charge

---

## 📸 Mission Gallery
*A look at the rover in action and the design process.*

| Prototype Design | First Test Run |
| :---: | :---: |
| ![Design Sketch](./assets/images/design_sketch.png) | ![Test Run](./assets/images/test_run.jpg) |
| *Initial CAD rendering* | *Field test in rocky terrain* |

*(Note: Upload your images to the `assets/images/` folder and update the filenames above to match!)*

---

## 💻 Tech Stack
* **Language:** Python (for vision/logic) / C++ (for motor control)
* **Libraries:** OpenCV, GPIO Zero
* **Simulation:** ROS (Robot Operating System) / Gazebo

## 🚀 Getting Started

### Prerequisites
1.  Python 3.8+
2.  (List any specific drivers needed)

### Installation
```bash
# Clone the repository
git clone [https://github.com/yourusername/space-robot-project.git](https://github.com/yourusername/space-robot-project.git)

# Navigate to directory
cd space-robot-project

# Install dependencies
pip install -r requirements.txt
