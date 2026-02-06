# Design and Simulation of a Low-Power CMOS Differential Amplifier  
### Cadence Virtuoso | SCL 180 nm Technology

---

## Overview
This project presents the **design and simulation of a low-power CMOS differential amplifier** implemented in **Cadence Virtuoso** using the **SCL 180 nm** technology.  
The amplifier employs an **NMOS tail current source** and a **PMOS current-mirror active load** to achieve high gain, good common-mode rejection, and stable high-speed performance.

---

## Tools & Technology
- **EDA Tool**: Cadence Virtuoso  
- **Simulator**: Spectre  
- **Technology Node**: SCL 180 nm  
- **Supply Voltage**: 1.8 V  

---

## Circuit Description
- **Topology**: CMOS Differential Amplifier  
- **Input Pair**: NMOS differential pair  
- **Tail Current Source**: NMOS current source  
- **Load**: PMOS current-mirror active load  
- **Bias Current**: 50 µA  

The NMOS tail current source provides stable biasing and improves common-mode rejection, while the PMOS current-mirror load increases output resistance and voltage gain.

---

## Analyses Performed
- **DC Operating Point Analysis**
  - Verified saturation operation of all MOSFETs  
- **AC Small-Signal Analysis**
  - Extracted DC gain, unity-gain bandwidth, and phase margin  
- **Transient Analysis**
  - Verified time-domain response and output swing  

---

## Performance Summary
| Parameter | Value |
|---------|------|
| Bias Current | 50 µA |
| DC Gain | ~22.5 dB |
| Unity-Gain Bandwidth | ~7.8 GHz |
| Phase Margin | ~73° |
| Output Swing | ~240 mV – 1.57 V |
| Supply Voltage | 1.8 V |
| Technology | SCL 180 nm |

---

## Key Results
- Achieved **low-power operation** with a tail bias current of **50 µA**  
- Demonstrated **stable high-speed performance** with **7.8 GHz unity-gain bandwidth**  
- Maintained **good phase margin (73°)** ensuring closed-loop stability  
- Verified **wide output swing (~240 mV–1.57 V)** on a **1.8 V supply**

---

