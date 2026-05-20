# 🔬 XY-Controlled Low-Cost Ultrasonic Spray Pyrolysis System for Thin Film Deposition

A cost-effective laboratory instrument for precision thin-film deposition, featuring a mechanised XY-motion platform with stepper motor control — bringing commercial-grade deposition capability to academic research at a fraction of the cost.

---

## 📌 Problem Statement

Commercial spray pyrolysis systems for thin-film deposition cost upwards of several lakhs, making them inaccessible for most academic and small-scale research labs. Researchers are left with manual, non-uniform deposition methods that produce inconsistent thin-film thickness and poor reproducibility.

---

## 💡 Solution

A fully assembled, low-cost ultrasonic spray pyrolysis apparatus with a motorised XY-motion platform. Stepper motor control algorithms execute precise traversal patterns to ensure uniform precursor deposition across substrate surfaces — delivering repeatable, research-grade thin films at a fraction of commercial costs.

---

## 🏗️ System Architecture

```
[Ultrasonic Atomiser]
   └── Converts liquid precursor → fine mist
         │
   [XY Motion Platform]
   ├── X-axis Stepper Motor
   └── Y-axis Stepper Motor
         │
   [Microcontroller]
   ├── G-code / traversal pattern execution
   ├── Stepper motor driver control
   └── Deposition parameter configuration
         │
   [Heated Substrate Stage]
   └── Pyrolysis of deposited precursor → thin film
```

---

## ⚙️ Hardware Stack

| Component | Purpose |
|---|---|
| Ultrasonic Atomiser / Nebuliser | Precursor atomisation |
| NEMA 17 Stepper Motors (x2) | XY-axis motion |
| A4988 / DRV8825 Stepper Drivers | Motor current control |
| Arduino / Microcontroller | Motion control and sequencing |
| Linear Rails + Lead Screws | Precision XY stage |
| Heated Substrate Platform | Pyrolysis temperature maintenance |
| Enclosure Frame | Structural housing |

---

## 💻 Control Software

- **Language:** Embedded C / Arduino
- **Features:**
  - Configurable XY traversal patterns (raster, spiral, custom)
  - Adjustable speed and step resolution
  - Deposition pass counter
  - Substrate area definition via software parameters
  - Serial interface for parameter input

---

## 🧪 Thin Film Deposition Process

```
1. Prepare precursor solution (material-specific)
2. Load substrate onto heated stage
3. Set substrate temperature (material-dependent)
4. Configure XY traversal pattern in software
5. Start ultrasonic atomisation + XY scan
6. Precursor mist deposits → pyrolysis → thin film
7. Repeat passes for desired film thickness
```

---

## 📐 Key Design Parameters

| Parameter | Specification |
|---|---|
| Motion Control | Stepper motor, microstepping |
| Traversal Pattern | Configurable raster/custom |
| Deposition Uniformity | Validated across substrate surface |
| Cost vs Commercial | Fraction of commercial system cost |
| Substrate Compatibility | Flexible (glass, ITO, silicon) |

---

## 📊 Results

- Deposition uniformity experimentally confirmed across substrate surface
- Repeatable thin-film thickness across multiple runs validated
- System demonstrated suitable for academic thin-film research workflows
- Fully functional prototype delivered and tested

---

## 🔬 Applications

- Solar cell absorber layer deposition (ZnO, TiO₂, CuO)
- Transparent conducting oxide films
- Gas sensor material deposition
- Photocatalytic thin-film research
- Any solution-processable thin-film material

---

## 👤 Author

**Sri Srujan Hari T**
B.E – Electronics & Communication Engineering, BMSIT&M
[LinkedIn](https://www.linkedin.com/in/srujan-hari-undefined-1a7364399) | thammineedisrujanhari@gmail.com
