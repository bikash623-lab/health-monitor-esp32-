# AI-Powered Health & Motion Monitor (ESP32)

A wearable device using ESP32 to monitor:
- Heart Rate (MAX30102)
- SpO₂ (MAX30102)
- ECG (MAX30003)
- Body Temperature (MAX30205)
- Motion (BMI270)
- Environmental factors (BME688)
- Gestures (APDS-9960)

Features:
- BLE communication to mobile app
- TinyML anomaly detection
- AWS IoT Cloud connectivity

## 🛠 Hardware Components
- ESP32 Dev Board
- MAX30102
- MAX30003
- MAX30205
- BMI270
- BME688
- APDS-9960

## 🔧 Software Features
- Real-time sensor reading
- FreeRTOS task scheduling
- BLE GATT services
- AWS IoT MQTT publishing
- TinyML anomaly detection

## 🔌 Wiring Diagram
![Wiring Diagram](docs/wiring_diagram.png)

## 📈 System Architecture
![System Architecture](docs/system_architecture.png)

## ☁ Cloud Architecture
![Cloud Architecture](docs/cloud_architecture.png)

## 🚀 Setup
```bash
pio run --target upload
pio device monitor
