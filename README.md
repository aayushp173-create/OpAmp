# 📡 Folded Cascode Op-Amp for 5G Applications

## 📖 Overview
This project presents the design and simulation of a **two-stage Folded Cascode Operational Amplifier (Op-Amp)** optimized for **5G analog front-end applications**.

The design focuses on achieving:
- High DC Gain  
- Wide Bandwidth  
- Low Input Offset Voltage  
- High Stability  

---

## 🎯 Objectives
- Achieve **~100 dB DC Gain**
- Target **high Unity Gain Bandwidth (UGB)**
- Maintain **input offset < 10 µV**
- Ensure **good phase margin and stability**
- Analyze **transient & frequency response**

---

## 🏗️ Architecture

### 🔹 Two-Stage Op-Amp Design
- **Stage 1:** Folded Cascode (PMOS input pair)
- **Stage 2:** Common Source Amplifier
- **Compensation:** Miller Compensation with nulling resistor

### 📷 Schematic
![OpAmp Architecture](./images/opamp_schematic.png)

---

## ⚙️ Key Design Features
- PMOS differential input pair → better noise performance  
- High output impedance using folded cascode  
- Miller compensation for stability  
- Optimized transistor sizing  

---

## 📊 Performance Summary

| Parameter | Value |
|----------|------|
| DC Gain | ~100 dB |
| UGB | 264.3 MHz |
| Phase Margin | 60.91° |
| Slew Rate | 1.937 V/µs |
| CMRR | 96.44 dB |
| Input Noise | 46.56 nV/√Hz |
| Offset Voltage | 0.6 µV |

---

## 📈 Simulation Results

### 🔹 Frequency Response
![Bode Plot](./images/bode_plot.png)

### 🔹 Transient Response
![Transient](./images/transient_response.png)

### 🔹 Noise Analysis
![Noise](./images/noise_plot.png)

---

## 🧮 Key Equations

### Unity Gain Bandwidth
\[
f_{UGB} = \frac{g_m}{2\pi C_c}
\]

### Slew Rate
\[
SR = \frac{I_{tail}}{C_c}
\]

---

## 🛠️ Tools Used
- Cadence Virtuoso / LTSpice  
- CMOS 180nm Technology  

---
