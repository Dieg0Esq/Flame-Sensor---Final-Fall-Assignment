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
It provides the following outputs:
- **Analog Output:** Changes based on how strong or close/far the flame is.

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
- Keyestudio Flame Sensor (Ks0036)
- Jumper wires

### 🔗 Circuit Connections
| Flame Sensor Pin | Connects to |
|------------------|-------------|
|VCC               | 5V on Arduino |
|GND               | GND on Arduino |
|AO (Analog Out)   | Analog in 0  |

<img src="blob:chrome-untrusted://media-app/b9da19bf-9eae-4158-8ff2-42c48ca9e8ea" alt="979ab5d5-2351-4bb8-a06b-b55e11e01e2b.jpg"/><img width="629" height="419" alt="image" src="https://github.com/user-attachments/assets/450c82c9-2261-44fa-9a1f-43d0f316fe42" />
