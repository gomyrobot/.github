# GoMyRobot
**Physical Intelligence Foundation Models**

[Research](https://gomyrobot.com) • [Platform](https://gomyrobot.com) • [Documentation](https://gomyrobot.com) • [Careers](https://gomyrobot.com)

---

### π-Zero: Physical Intelligence Unleashed
We develop foundation models that enable robots to learn through interaction rather than rigid programming. Our core architecture, **π-Zero**, leverages Vision-Language-Action (VLA) pipelines to achieve zero-shot generalization across diverse hardware.

#### 🛠 Core Stack
| Layer | Technology | Implementation |
| :--- | :--- | :--- |
| **Compute** | RISC-V | Custom Vector Extensions for edge-inference |
| **Kernel** | Linux RT | Ubuntu 22.04 with RT-PREEMPT (5.15) |
| **Middleware** | ROS2 | Humble Hawksbill / MicroROS for embedded |
| **Intelligence** | DRL | PPO, SAC, TD3 via Stable Baselines3 |

---

### 🔬 Active Research Areas

*   **π-Zero Foundation Models**
    Generalist policies for manipulation and dexterity. Training involves internet-scale pre-training coupled with 1M+ physical task demonstrations.
*   **Sim-to-Real Transfer**
    Advanced domain randomization techniques to bypass fine-tuning on physical hardware.
*   **Neural Hardware Acceleration**
    Custom RISC-V instructions designed specifically for 30Hz real-time control loops.

---

### 🏗 Architecture Overview
*   **Perception:** Multi-modal fusion (RGBD, LiDAR, Tactile) for 3D scene understanding.
*   **Reasoning:** High-level task planning and long-horizon decision making.
*   **Execution:** Model Predictive Control (MPC) integrated with neural action generation.

---

### 📈 Deployment Metrics
*   **Platforms:** 50+ unique robot configurations supported.
*   **Data:** 100K+ collective training hours in diverse environments.
*   **Learning:** 24/7 autonomous data collection and policy refinement.

---

### 🌐 Contributing & Community
We are "Open Source First." Most of our middleware and ROS2 drivers are public. 
*   **Issues:** For bug reports related to our ROS2 stacks, please use the specific repo issue trackers.
*   **Partnerships:** For enterprise deployment and research collaboration, contact [cherniyassine@gomyrobot.com](mailto:cherniyassine@gomyrobot.com).

---
<p align="left">
  <sub>© 2026 GoMyRobot Foundation. Built for the physical world.</sub>
</p>
