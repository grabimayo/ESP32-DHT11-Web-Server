# 🌡️ ESP32 IoT Weather Station Dashboard
A real-time environmental monitoring system that serves a live, responsive web interface directly from an ESP32 microcontroller.

---

## 🚀 Overview
This project integrates hardware and software to create a localized IoT solution. The ESP32 acts as both a data processor and a web server, reading environmental variables from a DHT11 sensor and rendering them on a custom HTML/CSS dashboard.

## 🛠️ Hardware Stack
* **Microcontroller:** ESP32 DevKit V1
* **Sensor:** DHT11 (Temperature & Humidity)
* **Connectivity:** 2.4GHz Wi-Fi
* **Wiring:** * VCC -> 3.3V
    * GND -> GND
    * DATA -> GPIO 26

---

## 💻 Software & Libraries
The following libraries must be installed in the Arduino IDE:
* **DHT Sensor Library** by Adafruit (v1.4.x)
* **Adafruit Unified Sensor** (Required Dependency)
* **WiFi & WebServer** (Standard ESP32 Core)

## 🔧 Installation & Usage
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/ESP32-DHT11-Web-Server.git](https://github.com/YOUR_USERNAME/ESP32-DHT11-Web-Server.git)
