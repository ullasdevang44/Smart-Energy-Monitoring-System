# 🚀 Smart Energy Monitoring System
## 🔹 Real-time Power Consumption Tracker with IoT Integration

### 🌟 Project Overview
This project is a **Smart Energy Monitoring System** that allows users to **track power consumption** in real-time using **ESP32, sensors, and IoT dashboards**. It helps in **reducing energy waste** and optimizing power usage by providing analytics and alerts for abnormal consumption.

---

## 📌 Features
✅ **Real-time Energy Monitoring** – Displays voltage, current, power, and energy consumption in real time.  
✅ **IoT Integration** – Sends data to the cloud (Firebase, ThingSpeak, or MQTT).  
✅ **Web Dashboard** – View consumption data remotely on a custom IoT dashboard.  
✅ **Overload Detection** – Sends alerts when power usage exceeds a threshold.  
✅ **Data Logging** – Stores past consumption data for analysis.  
✅ **Wi-Fi Connectivity** – Uses ESP32 to send data wirelessly.  
✅ **Power Efficiency Insights** – Helps in identifying high energy-consuming devices.  

---

## 🛠️ Hardware & Components
| Component         | Specification       |
|------------------|--------------------|
| **ESP32**        | Wi-Fi-enabled microcontroller |
| **Current Sensor** | ACS712 (5A/20A/30A) |
| **Voltage Sensor** | ZMPT101B |
| **OLED Display**  | 0.96" SSD1306 |
| **Relay Module**  | 5V Relay for Load Control |
| **Resistors**     | 10kΩ, 1kΩ |
| **Capacitors**    | 100μF, 10μF |
| **Wi-Fi Router**  | For ESP32 Connectivity |

---

## 🖥️ Software Requirements
- **Arduino IDE** (for ESP32 programming)
- **Firebase / ThingSpeak** (for cloud data logging)
- **Blynk / Node-RED** (for IoT dashboard)
- **C/C++** (for embedded programming)
- **Python** (for data analysis, optional)

---

## 🛠️ Circuit Diagram
🎯 You can create a simple circuit where the **ACS712 sensor** measures current and **ZMPT101B** measures voltage. The ESP32 processes this data and sends it to a cloud dashboard.

📝 *(Add a custom circuit diagram here—use Fritzing or Tinkercad to design it.)*

---

## 🔥 How It Works
1️⃣ The **ESP32** reads data from **ACS712 & ZMPT101B sensors**.  
2️⃣ The data is **processed and converted** into power consumption values.  
3️⃣ The ESP32 **sends the data** to a cloud platform via Wi-Fi.  
4️⃣ Users can **monitor real-time stats** on a **web dashboard**.  
5️⃣ If the power usage **exceeds a limit**, an **alert is triggered**.  

---

