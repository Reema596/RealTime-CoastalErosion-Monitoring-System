# 🌊 Real-Time Coastal Erosion Monitoring System

A **cloud-native, real-time monitoring system** designed to track **coastal erosion and shoreline changes** using **AWS serverless and IoT services**.  
The system enables **early detection of critical erosion patterns**, helping authorities and environmental teams respond faster and more effectively.

---

## 📌 Project Overview

Coastal erosion is a major environmental challenge that requires continuous and reliable monitoring.  
This project leverages **AWS IoT and serverless architecture** to collect, process, and analyze live sensor data from coastal regions in real time.

- **Timeline:** August 2025  
- **Role:** Cloud Engineer  

---

## 🎯 Key Objectives

- Monitor real-time environmental data from coastal sensors  
- Detect abnormal shoreline changes automatically  
- Enable scalable, cost-efficient data processing  
- Support early warning and decision-making systems  

---

## ⚙️ System Architecture

1. **IoT Sensors** collect real-time coastal data (wave intensity, soil movement, water level).
2. **AWS IoT Core** securely ingests live sensor readings.
3. **AWS Lambda** processes incoming data events without managing servers.
4. **Amazon DynamoDB** stores processed data for fast retrieval and analysis.
5. **Automated analysis** identifies erosion patterns and risk zones.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|----------|--------|
| **AWS IoT Core** | Secure ingestion of real-time sensor data |
| **AWS Lambda** | Serverless data processing and analysis |
| **Amazon DynamoDB** | Scalable NoSQL storage |
| **AWS CloudWatch** | Logging and monitoring |
| **AWS IAM** | Secure access and permissions |

---

## 🚀 Features

- 📡 Real-time environmental data ingestion  
- ⚡ Serverless and event-driven processing  
- 📊 Automated shoreline change detection  
- 💰 Cost-efficient and scalable cloud architecture  
- 🔒 Secure IoT communication using AWS IAM & policies  

---

## 📈 Impact & Use Cases

- Early detection of coastal erosion risks  
- Disaster prevention and preparedness  
- Environmental research and monitoring  
- Government and coastal authority decision support  

---

## 🧠 What I Learned

- Designing **event-driven cloud architectures**
- Working with **AWS IoT Core at scale**
- Implementing **serverless data pipelines**
- Building **cost-optimized monitoring systems**
- Handling real-time data using **DynamoDB**

---

## 🧩 Implementation Steps

### 🔹 Phase 1: Hardware Integration & Data Acquisition
- **Sensor Selection:**  
  - LiDAR for distance mapping  
  - Ultrasonic sensors for tide-level monitoring  
- **Imaging Hub:**  
  - High-resolution time-lapse cameras for photogrammetry  
- **Power & Durability:**  
  - Solar-powered battery system  
  - IP67 waterproof enclosures for sensor nodes  

---

### 🔹 Phase 2: Edge Computing & Communication
- **Local Processing:**  
  - Raspberry Pi / ESP32 used as Edge Units  
  - Noise filtering to remove false wave readings  
- **Connectivity:**  
  - LoRaWAN protocol for long-range transmission (up to 15 km)  
- **Data Serialization:**  
  - JSON-formatted sensor data  

---

### 🔹 Phase 3: Cloud Infrastructure & Analysis
- **Ingestion:**  
  - MQTT Broker (AWS IoT Core / Mosquitto)  
- **Processing Pipeline:**  
  - Kalman Filter for tidal fluctuation smoothing  
  - Python-based change detection logic  
- **Database:**  
  - Time-series storage using InfluxDB or PostgreSQL  

---

### 🔹 Phase 4: Visualization & Alerting
- **Dashboard:**  
  - Grafana or React-based UI displaying:
    - Live erosion rate (mm/month)  
    - Heatmaps of critical erosion zones  
- **Alerting:**  
  - Automated notifications via SMS (Twilio) or Email (SMTP)  

---
## 📸 Project Snapshot 📌 
*Architecture diagram and system flow available below* 
<p align="center">
  <img src="https://github.com/Reema596/RealTime-CoastalErosion-Monitoring-System/blob/main/Sample.png" 
       alt="Real-Time Coastal Erosion Monitoring System Architecture" 
       width="850"/>
</p>

<p align="center">
  <em>High-level architecture of the Real-Time Coastal Erosion Monitoring System using AWS IoT and Serverless services</em>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/AWS-IoT_Core-orange?style=for-the-badge&logo=amazonaws"/>
  <img src="https://img.shields.io/badge/AWS-Lambda-orange?style=for-the-badge&logo=aws-lambda"/>
  <img src="https://img.shields.io/badge/AWS-DynamoDB-orange?style=for-the-badge&logo=amazondynamodb"/>
  <img src="https://img.shields.io/badge/AWS-CloudWatch-orange?style=for-the-badge&logo=amazonaws"/>
</p>

---
## 👤 Author
**Reema** 

☁️ Cloud Engineer  
🔗 GitHub: https://github.com/Reema596  
🔗 LinkedIn: https://www.linkedin.com/in/reema12/

---
