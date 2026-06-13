# ⚡ Variable DC Power Supply (LM317-Based)

## Overview
Designed and built an adjustable bench DC power supply using the **LM317 voltage 
regulator**, progressing from breadboard prototype to a fully enclosed, functional 
device. The supply converts AC mains into a smooth, adjustable DC output with 
built-in protection and real-time voltage monitoring — verified using a UNI-T 
UT33C+ digital multimeter.

---

## 🔧 Key Features
- Adjustable output voltage using LM317
- Digital voltmeter for real-time output monitoring
- Transformer-based isolated AC to DC conversion
- Bridge rectifier and filtering stage
- Reverse polarity protection circuit
- Power switch and fuse protection
- Compact custom-built enclosure

---

## ⚙️ Circuit Overview
The circuit uses a step-down transformer followed by a **bridge rectifier** and 
**filter capacitor** to convert AC mains into smooth DC. An **LM317 voltage 
regulator** provides adjustable output through a potentiometer, following the 
standard LM317 equation:
Vout = 1.25V × (1 + R2/R1)
A **reverse polarity protection circuit**, built using transistor and MOSFET-based 
control, prevents damage to the supply or connected load if the connections are 
accidentally reversed.

---

## 📋 Specifications
| Parameter | Value |
|-----------|-------|
| Input Supply | 220V AC Mains |
| Regulator IC | LM317 |
| Output Voltage Range | Adjustable (1.25V – 30V, set by potentiometer) |
| Rectification | Full-wave Bridge Rectifier |
| Filtering | Electrolytic Filter Capacitor |
| Protection | Reverse Polarity + Fuse |
| Monitoring | Digital 7-Segment Voltmeter |
| Enclosure | Custom-built |

*(Adjust the voltage range above to match your actual potentiometer/resistor values)*

---

## 🛠️ Development Process
1. Breadboard prototyping and testing of the LM317 regulator circuit
2. Validation of rectification, filtering, and voltage adjustment
3. Perfboard assembly and soldering of the complete circuit
4. Integration into a custom enclosure with switch, fuse, and digital voltmeter
5. Final testing and calibration using a digital multimeter

---

## 📚 What I Learned
- AC-DC power conversion fundamentals
- Rectification and ripple filtering
- LM317 voltage regulator design
- Reverse polarity protection techniques
- Perfboard layout and soldering practices
- Troubleshooting and fault diagnosis
- Electrical safety in mains-powered circuits

---

## 🐞 Challenges
One of the biggest challenges was tracking down a short-circuit issue that 
initially prevented the supply from working correctly. Debugging each stage of 
the circuit individually — transformer, rectifier, filter, and regulator — helped 
build a deeper understanding of the design and ultimately led to a successful build.

---

## 📄 License
Personal hardware project — power electronics and circuit design practice.
