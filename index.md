---
title: Ashwin Shankar — Resume & Projects
description: Resume, experience, and projects portfolio.
---

# Ashwin Shankar
**Power Electronics • Power Systems • Analog Electronics • Control Systems**

📧 [ashwins1507@gmail.com](mailto:ashwins1507@gmail.com) •  
💻 [GitHub](https://github.com/shanks005) •  
🔗 [LinkedIn](https://www.linkedin.com/in/ashwin-shankar-8b3878246/)

[About Me](#about-me) • [View Projects](#projects)

---

## Quick Summary
I work across power systems, embedded systems, and controls—building and working on simulation of practical projects (EV systems, converters, motor control) and research prototypes (FOC, thrust estimation, dataset synthesis).

**Core areas:**  
`MATLAB/Simulink` `Power Electronics` `Embedded` `Controls` `EV Systems`

---

## About Me
A short intro and what I’m currently focused on.

I’m an electrical and electronics engineer interested in power electronics and analog circuit design, with hands-on work across converters, motor control, and simulation-driven system design. I enjoy building end-to-end prototypes—from modelling and control design to validation through simulation (and hardware where applicable).

Currently, I’m exploring the scope of AI in power electronics. Some of my notable projects include an **EV charging system** with closed-loop control implementation, and **Phantom**—a research project under [Open Horizon Robotics](https://openhorizonrobotics.com/) focusing on soft sensing solutions in aerospace applications, as well as implementation of a microgrid in grid-connected and standalone modes.

**Interested in internships / entry-level roles in:** power electronics, EV systems, motor drives, control, and simulation.

---

## Projects
Selected engineering projects with links and summaries.

---

### [Brake System Plausibility Device](https://github.com/shanks005/Brake-System-Plausibility-Device/blob/main/README.md)
**Tags:** `Proteus` `Analog` `Formula Student`

- Designed a standalone non-programmable circuit to detect hard braking under defined conditions and open the shutdown circuit of a Formula Student vehicle.
- Simulated using Proteus Design Suite.

---

### [DC Motor Speed Control Techniques](https://github.com/shanks005/DC_Motor_Speed_Control/blob/main/README.md)
**Tags:** `Arduino` `PWM` `PID`

- Designed a full-bridge inverter with a DC motor load and MOSFET switches.
- Programmed Arduino to control motor direction under specific conditions (forward 2s → stop 5s → reverse 3s).
- Designed and tested a PWM circuit for DC motor speed control; verified through hardware.
- Performed closed-loop control of a DC machine using PID control.
- Designed on Autodesk Tinkercad.

---

### [Automated Fan and Light System](https://github.com/shanks005/Automated-Fan-and-Light-System/blob/main/README.md)
**Tags:** `8051` `Assembly` `Proteus`

- Group project: automated fan and lighting system based on room occupancy.
- Used an IR sensor to detect occupants and sends data to 8051 Microcontroller.
- Wrote Assembly Code for the project; designed and simulated using Proteus Design Suite.

---

### Design of an EV Charging System
**Timeline:** Jun 2025 – Present  
**Role:** Research project under Dr. Anjan Padmasali  
**Tags:** `MATLAB/Simulink` `PFC Boost` `CC/CV Control` `Battery Management`

- Designing an EV charging system with voltage/current control and power factor correction.
- Implemented closed-loop control of a boost converter.
- Developing an algorithm to switch between Constant Current (CC) and Constant Voltage (CV) modes based on battery State of Charge (SoC).
- Working on active and passive cell balancing methods for protection of the battery system.

---

### [Phantom](https://github.com/shanks005/Phantom)
**Timeline:** Jan 2025 – Present  
**Role:** Research Project under [Open Horizon Robotics](https://openhorizonrobotics.com/projects/)  
**Tags:** `FOC` `IPMSM` `Propeller/Thrust Model` `Dataset Synthesis` `Fault/PD Testing`

- Research on soft sensing for aerospace/aviation systems, with an attempt to transfer power from a faulty to a healthy motor in pre-fault conditions.
- Built a simplified electrical model of NASA’s X-57 aircraft using an IPMSM and FOC for current and speed control.
- Synthesizing a dataset from the model to feed a custom ML model to reduce power losses during switching.
- Mathematically modelled the propeller driven by the IPMSM for thrust estimation.
- Currently testing partial discharge conditions.

---

### Island Microgrid Ecosystem
**Tags:** `MATLAB/Simulink` `Grid + Island Mode` `SVPWM` `PLL`

- Built a hybrid microgrid simulation integrating **24 kW Solar PV**, **10–20 kW wind**, and a **200 V, 100 Ah battery** feeding a **600 V DC bus** with a **15 Ω DC load**.
- Implemented a **35 kVA, 415 V (L-L), 50 Hz** inverter stage using **SVPWM** and designed a **single L-filter** (≈ **407 µH**) based on rated current and switching ripple constraints.
