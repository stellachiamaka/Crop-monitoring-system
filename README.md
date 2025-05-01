# Crop-monitoring-system
# 🌱 Smart Crop Monitoring System

An IoT-based system for real-time farm monitoring and **automated irrigation**, designed to help optimize crop health and water usage.


---

## 🚀 Features

- 📡 Real-time monitoring of **soil moisture**, **temperature**, and **humidity**
- 💧 Automated water pump activation when soil moisture is low
- 📲 Remote dashboard on **Blynk app** for live data tracking
- ⚡ Energy-efficient setup using ESP32 microcontroller

---

## 🛠️ Tech Stack

- **Microcontroller:** ESP32  
- **Sensors:** Soil Moisture Sensor, DHT11 (Temperature & Humidity)  
- **Actuators:** DC Water Pump  
- **Platform:** Blynk IoT App  
- **Language:** Embedded C  
- **Tools:** Arduino IDE

---

## 📷 Demo

🎥 [Watch the project demo](https://www.linkedin.com/posts/stella-chiamaka_smart-crop-monitoring-system-iot-agriculture-activity-123456789/)  
*(Replace with actual LinkedIn or YouTube video link)*

---

## ⚙️ How It Works

1. Soil moisture and environmental data are continuously collected.
2. Data is transmitted to the Blynk dashboard in real time.
3. If soil moisture drops below threshold, ESP32 triggers the water pump.
4. Users can monitor and control the system remotely via smartphone.

---

## 📂 Folder Structure

```bash
SmartCropMonitoring/
├── SmartCrop.ino         # Arduino code
├── wiring_diagram.png    # Optional circuit diagram
└── README.md
