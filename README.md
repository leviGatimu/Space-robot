<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,100:4A00E0&height=220&section=header&text=PLANETARY%20SCOUT&fontSize=70&animation=fadeIn&fontAlignY=35&desc=Autonomous%20Sample%20Collection%20Unit&descAlignY=55&descAllign=60" alt="Planetary Scout Header" width="100%"/>
</div>

<div align="center">

![Mission Status](https://img.shields.io/badge/Mission_Phase-Phase_1:_Design_&_Prototyping-8A2BE2?style=for-the-badge&logo=shuttle&logoColor=white)
![Operator](https://img.shields.io/badge/Operator-Autonomous_AI-00C853?style=for-the-badge&logo=robot&logoColor=white)
![Environment](https://img.shields.io/badge/Target_Environment-Hazardous_Exoplanets-FF3D00?style=for-the-badge&logo=googleearth&logoColor=white)

</div>

---

### <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2196F3&width=435&lines=Mission+Directive%3A;Go+where+humans+cannot.;Collect+samples.+Return+home." alt="Typing SVG" />

> **The Goal:** To develop a semi-autonomous rover capable of navigating extraterrestrial terrain, identifying viable geological samples, and retrieving them securely—keeping human astronauts safe in orbit.

---

## 📡 The Design Phase

We are currently in **Phase 1: Blueprint & Logic Mapping**. Before we cut metal, we are finalizing the chassis geometry and the sensor array integration.

<div align="center">

| **Current Core Schematic** |
| :---: |
| <img src="" alt="Robot Design Sketch" width="600"/> |
| *Fig 1.0: Initial Concept Draft - Focusing on high-clearance suspension.* |

*(Be sure to add your `design_sketch.png` to the `assets/images/` folder!)*

</div>

---

## 🧠 Robot Brain & Tech Stack

We are using a hybrid processing architecture to handle navigation and vision simultaneously.

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/Vision-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)](https://opencv.org/)
[![ROS Noetic](https://img.shields.io/badge/OS-ROS_Noetic-22314E?style=flat-square&logo=ros&logoColor=white)](https://www.ros.org/)
[![Raspberry Pi](https://img.shields.io/badge/Hardware-Raspberry_Pi_4-C51A4A?style=flat-square&logo=Raspberry%20Pi&logoColor=white)](https://www.raspberrypi.org/)

</div>

### Mission Modules Structure

Instead of basic code, we are building distinct operational modules:

```mermaid
graph TD;
    A[🛰️ Mission Control] -->|Coordinates| B(🧠 Main Logic Core);
    B --> C{Obstacle Detected?};
    C -- Yes --> D[🛡️ Evasive Maneuvers];
    C -- No --> E[🔭 Scan for Samples];
    E --> F{Sample Found?};
    F -- Yes --> G[🦾 Activate Arm Sequence];
    F -- No --> B;
    G --> H[📦 Secure Storage];
    H --> B;
```
🛠️ Hardware Materials & Manifest
We have compiled the initial Bill of Materials required to move to the build phase.

<a href=""📄 CLICK HERE TO VIEW THE FULL MATERIALS PDF


Includes specs for high-torque servos, LiPo power specs, and chassis aluminum grades.
