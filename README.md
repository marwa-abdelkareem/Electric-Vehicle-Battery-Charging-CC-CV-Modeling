# EV Battery Charging System (CC–CV) – MATLAB/Simulink


## Project Summary

This project presents a **complete MATLAB/Simulink model of an Electric Vehicle (EV) battery charging system** based on the **Constant Current–Constant Voltage (CC–CV) charging strategy**.

The model demonstrates realistic lithium-ion battery charging behavior used in modern EV Battery Management Systems (BMS), ensuring safe and efficient charging performance.

---

## Objectives

- Implement CC–CV charging control strategy  
- Model lithium-ion battery charging behavior  
- Simulate smooth transition between charging modes  
- Analyze voltage and current dynamics during charging  

---

## System Architecture

<p align="center">
  <img src="Block Diagram1.png" width="750"/>
</p>

**Figure 1: EV charging system architecture (CC–CV control model)**

---

## Charging Methodology

###  Constant Current (CC) Mode
- Battery is charged with fixed current  
- Voltage gradually increases  
- Fast charging phase  

###  Constant Voltage (CV) Mode
- Voltage is held constant  
- Current decreases gradually  
- Ensures safe full charge without overcharging  

---

## Simulation Results

<p align="center">
  <img src="output signals.png" width="750"/>
</p>

**Figure 2: EV battery charging waveforms (Voltage & Current behavior)**

### Key Observations
- Smooth transition from CC to CV mode  
- Stable voltage regulation at full charge stage  
- Gradual current decay in CV region  
- Realistic lithium-ion battery response  

---

## System Features

- CC–CV charging algorithm implementation  
- Lithium-ion battery modeling  
- Smooth mode switching logic  
- Voltage and current monitoring  
- EV charging system simulation  

---

## Applications

- Electric Vehicle Battery Management Systems (BMS)  
- EV charging station design  
- Smart grid energy storage integration  
- Renewable energy charging systems  

---

## System Specifications

| Parameter | Description |
|-----------|------------|
| Charging Method | CC–CV Algorithm |
| Battery Type | Lithium-ion |
| Model Type | Simulink Dynamic Model |
| Output Analysis | Voltage & Current |
| Application | EV Charging Systems |

---

## Tools & Technologies

- MATLAB  
- Simulink  

---

## How to Run

1. Open `EVchargerCVCC.slx` in MATLAB Simulink  
2. Run simulation  
3. Observe voltage and current waveforms  
4. Analyze CC to CV transition behavior  

---

## Demo

https://www.youtube.com/watch?v=zZ1ymTjzyBU

---

## Engineering Insight

The CC–CV charging strategy is widely used in EV systems to balance:
- Fast charging requirements (CC mode)
- Battery safety constraints (CV mode)

This implementation ensures:
- Protection against overvoltage
- Controlled current decay during final charging stage
- Improved battery lifespan

---

## Author

**Marwa Abdelkareem**
