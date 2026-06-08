# 🌱 IoT-Based Smart Irrigation System

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Arduino](https://img.shields.io/badge/Arduino-Mega-blue.svg)
![IoT](https://img.shields.io/badge/Technology-IoT-orange.svg)

An IoT-based Smart Irrigation System that automates plant watering using real-time soil moisture monitoring. The system detects soil moisture levels through a sensor and automatically activates a water pump when the soil becomes dry, ensuring efficient water usage and healthy plant growth.

---

## 📖 Overview

Traditional irrigation methods often result in water wastage due to manual monitoring and watering. This project addresses that issue by implementing an automated irrigation system using an Arduino Mega, a soil moisture sensor, and a relay-controlled water pump.

The system continuously monitors soil moisture levels and automatically irrigates plants whenever the moisture level falls below a predefined threshold.

---

## ✨ Features

- Real-time soil moisture monitoring
- Automatic water pump activation and deactivation
- Intelligent irrigation based on moisture threshold values
- Reduces water wastage and prevents overwatering
- Low-cost and easy-to-implement solution
- Serial Monitor output for live sensor readings
- Suitable for home gardens and small-scale agriculture

---

## 🛠️ Hardware Components

| Component | Quantity |
|------------|----------|
| Arduino Mega | 1 |
| Soil Moisture Sensor | 1 |
| Relay Module | 1 |
| Water Pump | 1 |
| Water Reservoir | 1 |
| Jumper Wires | As Required |
| USB Cable | 1 |
| Power Supply | 1 |

---

## 💻 Software Requirements

- Arduino IDE
- Arduino Mega Board Support Package

---

## ⚙️ System Architecture

```text
Soil Moisture Sensor
          │
          ▼
     Arduino Mega
          │
          ▼
   Threshold Comparison
          │
   ┌──────┴──────┐
   ▼             ▼
Dry Soil      Moist Soil
   │             │
Pump ON      Pump OFF
   │
Water Supply
```

---

## 🔌 Circuit Connections

| Component | Arduino Pin |
|------------|-------------|
| Soil Moisture Sensor (AO) | A0 |
| Relay Module (IN) | D8 |
| VCC | 5V |
| GND | GND |

---

## 🚀 Working Principle

1. The soil moisture sensor continuously measures soil moisture levels.
2. Arduino Mega reads the sensor data through the analog input pin.
3. The measured value is compared with a predefined threshold.
4. If the soil becomes dry, the relay module activates the water pump.
5. Water is supplied from the reservoir to the plant.
6. Once sufficient moisture is detected, the pump automatically turns off.
7. The cycle repeats continuously to maintain optimal soil moisture levels.

---

## 📂 Project Structure

```text
IoT-Based-Smart-Irrigation-System/
│
├── README.md
├── LICENSE
├── Smart_Irrigation.ino
├── images/
│   ├── setup1.jpg
│   ├── setup2.jpg
│   └── setup3.jpg
└── docs/
    └── circuit_diagram.png
```

---

## 📸 Project Demonstration

### Prototype Setup

Add your project images inside the `images` folder and display them using:

```markdown
![Project Setup 1](images/setup1.jpg)

![Project Setup 2](images/setup2.jpg)

![Project Setup 3](images/setup3.jpg)
```

---

## 📊 Applications

- Smart Agriculture
- Home Gardening
- Greenhouse Automation
- Plant Nurseries
- Water Conservation Systems
- Precision Farming

---

## 🔮 Future Enhancements

- ESP8266/ESP32 Wi-Fi Integration
- Mobile Application for Remote Monitoring
- Cloud-Based Data Storage and Analytics
- Weather Forecast Integration
- Solar-Powered Operation
- Multiple Sensor Support
- Automated Water Usage Reports

---

## 👨‍💻 Author

**Soham Patil**

- LinkedIn: www.linkedin.com/in/soham-patil-52b7ab28b
- GitHub: https://github.com/soham111111

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

⭐ If you found this project useful, consider giving it a star on GitHub.