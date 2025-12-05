<div align="center">
  
# 🔥 Flame Sensor 🔥
### **by: Diego Esquivel**

</div>

---
## 📘 Description
The **Keyestudio Flame Sensor** is designed to detect infrared (IR) light that is emitted from the flames.
It's sensitive to light wavelengths between **760 nm and 1100 nm**, allowing it to identify fire.
When a flame is present, the sensor sends a signal to the Arduino, which can then trigger optional actions like alarms, LEDs, or on-screen alerts. 

---

## ⚙ Functions of Flame Sensor
The Flame Sensor's main function is to **detect the presence or intensity of a flame** using infrared light.
It provides two types of outputs:
- **Analog Output:** Changes based on how strong or close/far the flame is.
- **Digital Output:** Sends a simple HIGH or LOW signal to indicate if a flame is detected.

---

## 🔌 How it Works
The sensor uses a photodiode that recognizes infrared radiation.
When it detects IR light from a flame:
- The **photodiode** senses the light.
- A **comparator circuit** processes the signa.
- The sensor sends the result to the **Arduino** through the output pins.

---

## 🔧 How to Use It
### 📃 Components You'll Need
- Arduino
- Keyestudio Flame Sensor
- Jumper wires

### 🔗 Circuit Connections
| Flame Sensor Pin | Connects to |
|------------------|-------------|
|VCC               | 5V on Arduino |
|GND               | GND on Arduino |
|AO (Analog Out)   | Analog in 0  |
