# Semi_Active_Suspension_Model_for_TwoWheelers_Using_Simulink

### Project Overview
This project focuses on the **design and simulation of a semi-active suspension system** for two-wheelers using **MATLAB/Simulink**.  
The objective is to improve **ride comfort and handling performance** by dynamically adjusting damping characteristics based on road conditions and vehicle responses.
---
### Objectives
- Develop a **Simulink model** of a quarter-vehicle two-wheeler suspension system.  
- Implement a **semi-active damping control strategy**.  
- Compare system responses with a **passive suspension model** under identical road profiles.  
- Evaluate performance metrics such as **body displacement, acceleration, and ride comfort index**.

---

### System Description
The model consists of:
- **Sprung and Unsprung masses** representing the rider and wheel assembly.  
- **Spring and variable damper** to model suspension stiffness and damping.  
- **Road profile input**.  
- **Controller subsystem** to vary the damping coefficient in real time.

---

### Control Strategy
The PID controller adjusts damping force based on the relative velocity between sprung and unsprung masses:
- Damping coefficient varies between **900 (Cmin)** and **1700 (Cmax)** limits.

---

### Simulation Details
- Platform: **MATLAB/Simulink R2024b (or compatible)**  
- Simulation type: **Time-domain response**  
- Road inputs: Step / Single-Sinusoidal wave (Bump) / Random profiles  
- Output plots:
  - Sprung mass displacement vs. time  
  - Unsprung mass displacement vs. time
  - Comparison of passive vs. semi-active behavior

---

### Key Results
- **Improved ride comfort** in semi-active mode.
- Faster settling time and better damping control over uneven road profiles.
- Quantified improvement in comfort index and dynamic stability.

---

### 🧾 Future Scope
- Integration of **real-time road estimation** via sensors.  
- Implementation of **machine learning-based adaptive damping control**.  
- Extension to **full-vehicle model** for comprehensive analysis. 

Focus Areas: NVH, Vehicle Dynamics, Model-Based Design  

-
