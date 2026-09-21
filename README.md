🌱 Smart Irrigation System using ESP32

## 📌 Project Overview

The **Smart Irrigation System** is an IoT-based automation project developed using an **ESP32** and simulated in **Wokwi**.

The system monitors **soil moisture, temperature, and humidity** and automatically controls a water pump based on predefined conditions. This helps reduce unnecessary water usage and provides an automated approach to irrigation.

---

## 🎯 Objectives

- 🌱 Monitor soil moisture continuously
- 🌡️ Measure temperature and humidity
- 💧 Automatically control the water pump
- 🤖 Implement sensor-based decision making
- ⚙️ Understand actuator and relay control
- 🧪 Simulate the complete system using Wokwi

---

## 🛠️ Components & Technologies

| Component | Purpose |
|---|---|
| 🤖 ESP32 | Main microcontroller |
| 🌱 Soil Moisture Sensor | Measures soil moisture |
| 🌡️ DHT22 | Measures temperature and humidity |
| 🔌 Relay Module | Controls the water pump |
| 💧 Water Pump | Provides irrigation |
| 💡 LED | Indicates system/pump status |
| 💻 Wokwi | Circuit simulation |
| 👨‍💻 Arduino/C | Programming language |

---

## ⚙️ Working Principle

The system continuously reads data from the connected sensors.

1. 🌱 The soil moisture sensor measures the moisture level.
2. 🌡️ The DHT22 measures temperature and humidity.
3. 🤖 ESP32 receives and processes the sensor readings.
4. 🧠 The control logic determines whether irrigation is required.
5. 🔌 The relay is activated when watering is needed.
6. 💧 The water pump turns ON automatically.
7. 💡 The LED indicates the pump/system status.

### 🔄 System Flow

```text
Soil Moisture Sensor
        ↓
      ESP32
        ↓
  Decision Logic
        ↓
    Relay Module
        ↓
    Water Pump
