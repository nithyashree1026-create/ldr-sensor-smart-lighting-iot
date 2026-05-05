# 💡 LDR Sensor – Smart Lighting & IoT Automation
## 📌 Overview
The Light Dependent Resistor (LDR) is a passive sensor used to detect light intensity. Its resistance varies inversely with the amount of light falling on it, making it ideal for automatic lighting and energy-efficient systems.
This repository explores the working principle, electrical characteristics, circuit design, and ESP32-based IoT integration of LDR sensors.
## 🧠 Working Principle
An LDR operates based on **photoconductivity**.
When light photons strike the surface of the LDR, electrons gain energy and move into the conduction band, reducing resistance.
### 🔹 Behavior:
* High light intensity → Low resistance  
* Low light intensity → High resistance  
## ⚙️ Electrical Characteristics
LDR is not a digital sensor; it provides analog output.
### 🔹 Key Properties:
* Resistance range: KΩ to MΩ  
* Slow response time compared to photodiodes  
* Sensitive to visible light spectrum  
## 🔌 Circuit Design (Voltage Divider)
LDR is typically used in a voltage divider configuration.
### 🔹 Setup:
* LDR connected with fixed resistor  
* Output voltage taken from junction  
### 🔹 Insight:
Output voltage varies based on light intensity and can be read using ADC of ESP32.
