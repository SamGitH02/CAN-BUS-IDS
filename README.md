# CAN-BUS-IDS
# CAN Bus Intrusion Detection System (IDS) Using AI

## Overview

This project focuses on developing an Intrusion Detection System (IDS) for the Controller Area Network (CAN) bus using Artificial Intelligence (AI). The CAN bus is a crucial communication backbone in modern vehicles, allowing various Electronic Control Units (ECUs) to communicate. With the rise in cyberattacks targeting automotive systems, AI-based security approaches can offer a robust defense by detecting anomalies and malicious behavior within the CAN network that traditional systems might miss.

### Key Use Case Example: SolarWinds Attack Detection

In a real-world scenario like the **SolarWinds attack**, AI played a crucial role in detecting the breach early by identifying unusual patterns in network traffic that traditional systems might have overlooked. Similarly, for CAN bus networks, AI can detect anomalies and prevent sophisticated cyberattacks before they cause significant harm.

## Features

- **Real-time Anomaly Detection:** AI models are trained to detect abnormal patterns in CAN bus communication.
- **Machine Learning Integration:** Leveraging both supervised and unsupervised learning algorithms to detect known and unknown attack vectors.
- **Low Latency Response:** The system is designed to respond to potential threats with minimal delay, ensuring timely interventions.
- **Scalable Architecture:** Suitable for integration with various automotive systems, from personal vehicles to industrial fleets.

### Example: Secure Over-the-Air (OTA) Updates

Automotive manufacturers are increasingly using **Over-the-Air (OTA) updates** to update vehicle software. With AI, the IDS can ensure that malicious updates are detected early and that any anomalies in the update process are flagged for investigation.

## System Architecture

1. **CAN Data Collection:**
   - Data from the CAN bus is captured in real-time using CAN sniffers.
   - Pre-processing and feature extraction to convert raw CAN data into a format suitable for AI analysis.
   
2. **AI-based Detection Module:**
   - Machine Learning models, such as Random Forest, Support Vector Machine (SVM), and Neural Networks, are trained on labeled datasets of normal and malicious CAN traffic.
   - Anomaly detection algorithms like Autoencoders or Isolation Forests for identifying previously unseen attack patterns.

3. **Alert and Response:**
   - Upon detection of suspicious activity, alerts are triggered, and appropriate defensive actions are taken (e.g., alerting the driver or triggering fail-safe mechanisms).

## Technology Stack

- **Programming Language:** Python
- **AI/ML Libraries:** TensorFlow, Scikit-learn, Keras
- **CAN Sniffing Tools:** SocketCAN (for Linux), Python-can
- **Data Preprocessing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

## Dataset

The dataset consists of CAN bus traffic logs from various vehicles under normal and attack conditions. Data sources include:

- **Normal CAN Data:** Regular vehicle communication logs.
- **Attack Scenarios:** Simulated attack logs such as message injection, replay attacks, and spoofing.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/can-bus-ids-ai.git
2. **install dependecies** 
    cd can-bus-ids-ai
    pip install -r requirements.txt
3. **run the application**
    python main.py

 

5.


