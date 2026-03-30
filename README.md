# IOT-Final-project
Automatic Pallet Transport Request System
# IoT Project – Automatic Pallet Transport Request by Forklifts

This project is an IoT-based system designed to automate pallet transport requests from machines to forklifts using MQTT and Node-RED. It simulates a smart warehouse environment with machine clients and a forklift dashboard.

## 🚀 Project Overview

- **Topic:** Automatic Pallet Transport Request by Forklifts  
- **Type:** IoT Mini Project (Academic)  
- **Developed with:** MQTT, Node-RED, InfluxDB, ESP8266, REST APIs, Dashboard, and Encryption  
- **Institution:** Instituto Politécnico de Bragança (IPB)  
- **Year:** 2025

## 🧠 Project Features

- 📦 **Machine Clients (4):** Simulated pallet transport requests
- 🚜 **Forklift Dashboard:** Accept or complete tasks using dashboard buttons
- 🔄 **FIFO Queue:** Manages request order centrally
- 📊 **InfluxDB Integration:** Tracks transport durations, generates statistics
- 🔐 **Security:** Basic encryption mechanism for MQTT messages
- 📡 **MQTT Broker:** Used for communication between machines and forklifts
- 📈 **Visual Dashboard:** Real-time monitoring of requests, transport status & timing

## 🧩 Technologies Used

- **Node-RED** – Workflow orchestration and dashboard
- **MQTT** – Lightweight publish/subscribe messaging protocol
- **InfluxDB** – Time-series database for transport tracking
- **ESP8266** – Simulated microcontroller clients (or mock logic)
- **REST API** – Used for historical data queries
- **JavaScript / JSON** – Data handling


## 📌 Highlights

- Calculates and displays:
  - Average transport time
  - Fastest and longest delivery per machine
- Forklift marks requests as “completed” from the UI, triggering InfluxDB storage
- Timestamp-based analysis of system efficiency

## 👤 Author

**Dibya Raj Khatri**   
📧 raj.dibya789@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/dibyaraaz) 

## 📝 License

This project is academic and for learning purposes only.  
All rights reserved © 2025 Dibya Raj Khatri


