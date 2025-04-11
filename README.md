# 🌡️ Automatic Fan Speed Controller Based on Temperature

An **Automatic Fan Speed Controller** adjusts the speed of a fan depending on the ambient temperature using a microcontroller and temperature sensor. It provides efficient cooling while saving power and reducing noise.

---

## 🔧 Features

- Automatically controls fan speed based on temperature
- Real-time temperature monitoring
- Uses PWM for smooth fan speed control
- Optional LCD display for temperature and fan speed
- Energy-efficient and quiet operation

---

## 🧰 Components Required

| Component               | Quantity |
|------------------------|----------|
| Arduino Uno            | 1        |
| Temperature Sensor (LM35/DHT11) | 1        |
| NPN Transistor (e.g., TIP120/MOSFET) | 1        |
| DC Fan (5V or 12V)      | 1        |
| Resistor (220Ω or 1kΩ)  | 1        |
| LCD Display (optional) | 1        |
| Breadboard & Jumper Wires | As needed |
| Power Supply           | As required |

---

## ⚙️ How It Works

1. The temperature sensor reads the ambient temperature.
2. The Arduino processes the data and generates a PWM signal.
3. The PWM signal controls the transistor to vary the voltage to the fan.
4. Fan speed increases with temperature, and vice versa.

---

🧪 Applications
PC/Server cooling systems

Smart home ventilation

Industrial automation

Greenhouses and incubators

✅ Benefits
💡 Energy saving

🔇 Low noise

🔁 Longer fan life

🔧 Minimal maintenance









