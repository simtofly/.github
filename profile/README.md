<div align="center">

# 🚁 SimToFly

**From Simulation to Flight**

*Complete, beginner-friendly tutorials for autonomous drones with ROS2 and ArduPilot*

[![GitHub Stars](https://img.shields.io/github/stars/simtofly?style=social)](https://github.com/simtofly)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[📚 Start Learning](#-getting-started) • [🎯 Features](#-what-makes-us-different) • [🤝 Contribute](#-contribute) • [💬 Community](#-community)

</div>

---

## 👋 Welcome to SimToFly

We bridge the gap between **drone simulation** and **real-world flight**.

Most tutorials stop at simulation or skip critical steps. **SimToFly provides the complete journey:**
```
Simulation → ROS2 Integration → Companion Computer → Real Hardware → Flight
```

---

## 🎯 What Makes Us Different

| Feature | SimToFly | Others |
|---------|----------|--------|
| **Stack** | ROS2 Humble (current) | Mostly ROS1 (legacy) |
| **Hardware** | ✅ Tested on real drones | ⚠️ Simulation only |
| **Companion Computer** | ✅ Complete RPi setup | ⚠️ Brief mentions |
| **Beginner-Friendly** | ✅ Assumes zero knowledge | ⚠️ Assumes experience |
| **Maintenance** | ✅ Actively updated | ⚠️ Often outdated |

---

## 📚 Getting Started

### [📖 simtofly-guide](https://github.com/simtofly/simtofly-guide)
**Main tutorial repository** — Start here!

Complete path from simulation to real flight:
- **Phase 1:** ArduPilot SITL + Gazebo simulation
- **Phase 2:** ROS2 + MAVROS integration  
- **Phase 3:** Raspberry Pi companion computer
- **Phase 4:** Real hardware deployment

**Status:** 🚧 Phase 1 under development

---

### [🤖 simtofly-ros2](https://github.com/simtofly/simtofly-ros2)
**ROS2 packages and examples** *(coming soon)*

Reusable packages for drone control:
- Basic telemetry and control nodes
- Mission planning and execution
- Perception and navigation

**Status:** 📋 Planned for Phase 2

---

### [⚙️ simtofly-setup](https://github.com/simtofly/simtofly-setup)
**Automated setup scripts** *(coming soon)*

One-command installation:
- ArduPilot SITL
- Gazebo Garden
- ROS2 Humble + MAVROS
- Raspberry Pi configuration

**Status:** 📋 Planned

---

## 🛠️ Technology Stack

<div align="center">

| Simulation | Middleware | Hardware | Tools |
|:----------:|:----------:|:--------:|:-----:|
| ArduPilot SITL | ROS2 Humble | Pixhawk/Cube Orange | Gazebo Garden |
| MAVProxy | MAVROS | Raspberry Pi 4 | RViz |
| Gazebo | Python 3 | GPS/Sensors | Git |

</div>

---

## 🚀 Quick Start

**New to drone autonomy?** Follow this path:
```bash
# 1. Start with the main guide
git clone https://github.com/simtofly/simtofly-guide.git

# 2. Follow Phase 1: Simulation Mastery
cd simtofly-guide/docs/phase-1-simulation

# 3. Progress through phases at your own pace
```

**Prerequisites:**
- Ubuntu 22.04 LTS
- 8GB RAM minimum
- Basic terminal comfort
- Patience and willingness to learn

**No prior ROS or ArduPilot experience required!**

---

## 🎓 Learning Path
```mermaid
graph LR
    A[Complete Beginner] --> B[Phase 1: Simulation]
    B --> C[Phase 2: ROS2]
    C --> D[Phase 3: Companion Computer]
    D --> E[Phase 4: Real Flight]
    E --> F[Advanced Topics]
    
    style A fill:#e1f5ff
    style E fill:#c8e6c9
    style F fill:#fff9c4
```

**After completing the foundation:**
- Obstacle avoidance
- ArUco marker detection
- Visual SLAM
- Multi-drone systems
- *(Advanced repos coming soon)*

---

## 🤝 Contribute

We welcome contributions! Here's how you can help:

- 🐛 **Found a bug?** [Open an issue](https://github.com/simtofly/simtofly-guide/issues)
- 📝 **Improve docs?** [Submit a pull request](https://github.com/simtofly/simtofly-guide/pulls)
- 💡 **Have ideas?** [Start a discussion](https://github.com/simtofly/simtofly-guide/discussions)
- ⭐ **Like our work?** Star our repositories!

**Read our [Contributing Guidelines](https://github.com/simtofly/simtofly-guide/blob/main/CONTRIBUTING.md)**

---

## 💬 Community

**Get help and connect:**

- 📖 **Documentation:** Main tutorials in [simtofly-guide](https://github.com/simtofly/simtofly-guide)
- 🐛 **Issues:** Report problems in respective repositories
- 💬 **Discussions:** Coming soon (Discord/Forum)
- 🌟 **Updates:** Star repositories to get notified

---

## 📊 Project Status

**Current Focus:** Phase 1 (Simulation Mastery)

| Phase | Status | Target |
|-------|--------|--------|
| Phase 1: Simulation | 🚧 In Progress | January 2026 |
| Phase 2: ROS2 | 📋 Planned | February 2026 |
| Phase 3: Companion | 📋 Planned | March 2026 |
| Phase 4: Real Hardware | 📋 Planned | April 2026 |

**Follow our progress:** [Project Roadmap](https://github.com/simtofly/simtofly-guide/blob/main/SIMTOFLY_PROJECT_TODO.md)

---

## 🙏 Acknowledgments

Built on the shoulders of giants:

- [ArduPilot](https://ardupilot.org/) — Open-source autopilot
- [ROS2](https://docs.ros.org/) — Robot Operating System
- [MAVROS](https://github.com/mavlink/mavros) — MAVLink ↔ ROS bridge
- [Gazebo](https://gazebosim.org/) — Robot simulation

**Special thanks** to the open-source drone community for continuous inspiration and support.

---

## 📜 License

All SimToFly repositories are released under the **MIT License**.

You are free to use, modify, and distribute for personal or commercial projects.

---

## 👤 Creator

**Created by:** [@sidharthmohannair](https://github.com/sidharthmohannair)

**Mission:** Make drone autonomy accessible to everyone, from complete beginners to experienced developers.

---

<div align="center">

### Ready to Start Your Journey?

**[👉 Begin with Phase 1: Simulation Mastery](https://github.com/simtofly/simtofly-guide/blob/main/docs/phase-1-simulation/README.md)**

---

*Making autonomous drones accessible to everyone* 🚁

**SimToFly** • [GitHub](https://github.com/simtofly) • [Tutorials](https://github.com/simtofly/simtofly-guide)

</div>
