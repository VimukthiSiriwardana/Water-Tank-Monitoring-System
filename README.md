# 🚰 IoT-Based Water Tank Monitoring System

<div align="center">

### Embedded Systems & IoT Automation Project

Developed as part of a semester group project at SLIIT

</div>

---

## 📖 Project Overview

The **IoT-Based Water Tank Monitoring System** is a smart automation solution designed to monitor and manage water levels efficiently using IoT and embedded system technologies.

The system utilizes an **ESP8266 microcontroller** and an **HC-SR04 ultrasonic sensor** to continuously measure water levels in real time. Based on the detected water level, the system automatically controls the water pump through a relay module while providing live updates through an LCD display and alarm notifications.

This project was developed to reduce water wastage, prevent overflow conditions, minimize manual monitoring, and improve efficient water resource management.

---

## ✨ Key Features

- ✅ Real-time Water Level Monitoring  
- ✅ Automatic Pump ON/OFF Control  
- ✅ LCD Display Integration  
- ✅ Alarm Notifications for Critical Levels  
- ✅ Mobile Monitoring Support via WiFi  
- ✅ Overflow Prevention & Water Waste Reduction  
- ✅ Smart Automation using Embedded Systems  

---

## 🛠️ Technologies & Components

| Component                 | Description                               |
| ------------------------- | ----------------------------------------- |
| ESP8266                   | Main microcontroller with WiFi capability |
| HC-SR04 Ultrasonic Sensor | Water level detection                     |
| Relay Module              | Automatic pump switching                  |
| LCD 1602 Display          | Real-time status display                  |
| Water Pump                | Water pumping mechanism                   |
| Alarm/Buzzer              | Critical level notifications              |
| Arduino IDE               | Development environment                   |
| Embedded C                | Programming language                      |

---

## ⚙️ System Functionality

### 🔹 Water Level Detection

The ultrasonic sensor continuously measures the distance between the sensor and the water surface to determine the current water level.

### 🔹 Data Processing

The ESP8266 processes sensor readings and determines the system state based on predefined thresholds.

### 🔹 Automatic Pump Control

When the water level becomes low, the relay module activates the pump automatically. Once the tank reaches a safe level, the pump is turned OFF.

### 🔹 Real-Time Monitoring

The LCD display provides live water level updates while the alarm system alerts users during critical conditions.

---

## 📊 Project Workflow

```text
Start
   ↓
Sense Water Level
   ↓
Display Current Level
   ↓
Check Water Level Status
   ↓
Low Level? → Pump ON
   ↓
Tank Filled? → Pump OFF
   ↓
Repeat Monitoring Cycle
```

---

## 📷 Repository Contents

This repository includes:

* 📌 System Architecture Diagram
* 📌 Workflow / Flowchart
* 📌 Ultrasonic Sensor Working Concept
* 📌 Final Project Documentation

---

## 🎯 Learning Outcomes

This project helped us strengthen our understanding of:

* IoT-based system development
* Embedded systems programming
* Sensor integration and automation
* Real-time monitoring systems
* Hardware and software integration
* Team collaboration and problem-solving

---

## 👨‍💻 Team Members

* Vimukthi Siriwardana
* Pavitha M
* Dinali Sewmini
* Aloka Rathnayake
* Pasindu Himsara

---

## 📄 Documentation

The final project proposal and supporting diagrams are included in this repository.
