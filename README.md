# 🦴 Osteo Sentinel – Osteoporosis Fracture Risk Prediction Using Machine Learning

## 📌 Project Overview

**Osteo Sentinel** is an embedded and IoT-based healthcare system designed to predict **osteoporosis fracture risk in real time using Machine Learning**.

The system collects physiological and motion-related data using multiple sensors connected to an **ESP32 microcontroller**. The collected data is transmitted through IoT connectivity to a cloud platform, where a **Random Forest Machine Learning model** analyzes the data and classifies fracture risk into **Low, Medium, or High** levels.

The system also provides real-time monitoring, alerts, and personalized food and doctor recommendations to support early intervention and preventive healthcare.

---

## 🎯 Objectives

* Monitor physiological and motion-related parameters in real time.
* Predict osteoporosis-related fracture risk using Machine Learning.
* Classify risk levels as **Low, Medium, or High**.
* Enable remote monitoring through IoT and cloud connectivity.
* Provide real-time alerts for high-risk conditions.
* Support preventive healthcare through recommendations.

---

## ⚙️ How the System Works

```text
Sensors
   ↓
ESP32 Microcontroller
   ↓
Data Processing
   ↓
Wi-Fi / IoT Connectivity
   ↓
Cloud Platform
   ↓
Data Preprocessing & Feature Extraction
   ↓
Random Forest ML Model
   ↓
Fracture Risk Prediction
   ↓
LCD + Mobile Dashboard + Alerts
```

The sensors continuously collect health and motion data. The **ESP32** processes the data and sends it to the cloud through Wi-Fi. After preprocessing and feature extraction, the **Random Forest model** predicts the fracture risk level. The result is displayed through the LCD and mobile application.

---

## 🔧 Hardware Components

* **ESP32 Microcontroller** – Central controller with Wi-Fi connectivity
* **MPU6050 Accelerometer** – Detects acceleration, motion, falls, and sudden movements
* **Force Sensitive Resistor (FSR)** – Measures pressure and load changes
* **Blood Pressure Sensor** – Monitors systolic and diastolic blood pressure
* **MAX30100 / MAX30102 SpO₂ Sensor** – Measures oxygen saturation and pulse rate
* **16×2 LCD Display** – Displays real-time sensor readings and risk levels

---

## 💻 Software & Technologies

### Programming Languages

* Embedded C
* Python

### Development Tools

* Arduino IDE
* Visual Studio Code

### IoT & Cloud

* Blynk
* Firebase
* AWS Cloud

### Machine Learning

* Python
* NumPy
* Pandas
* Scikit-learn
* Random Forest Algorithm

---

## 🤖 Machine Learning Model

### Random Forest

The project uses the **Random Forest classification algorithm** to predict fracture risk.

Random Forest combines multiple decision trees and uses **majority voting** to determine the final prediction.

### Main Components

* Decision Trees
* Bootstrap Sampling
* Feature Randomisation
* Majority Voting

The model classifies the collected data into:

```text
LOW
MEDIUM
HIGH
```

This approach is used to provide stable fracture-risk classification from the collected sensor data.

---

## 📊 Dataset

The dataset contains sensor and physiological parameters used for fracture-risk prediction.

### Features

| Feature      | Description              |
| ------------ | ------------------------ |
| Pulse        | Pulse rate               |
| Accel_X      | X-axis acceleration      |
| Accel_Y      | Y-axis acceleration      |
| Accel_Z      | Z-axis acceleration      |
| BP_Diastolic | Diastolic blood pressure |
| BP_Systolic  | Systolic blood pressure  |
| SpO₂         | Blood oxygen saturation  |
| Force        | Applied pressure/load    |
| Risk         | Predicted risk category  |

The dataset contains sample records labelled as **LOW, MEDIUM, and HIGH** risk levels.

---

## 📱 Real-Time Monitoring

The system provides a monitoring interface through the **Blynk application**.

The dashboard displays:

* Real-time health parameters
* Fracture risk level
* Graphical health trends
* High-risk alert notifications
* User-friendly monitoring interface

---

## ✨ Key Features

* 🦴 Real-time fracture risk prediction
* 📡 IoT-based remote monitoring
* 📊 Machine Learning-based classification
* 📱 Mobile dashboard
* 🚨 High-risk alerts
* ☁️ Cloud data storage
* 📈 Health trend visualization
* 💡 Personalized recommendations
* 🔋 Portable and cost-effective system

---

## 🌍 Applications

* Elderly healthcare monitoring
* Home healthcare systems
* Rehabilitation and post-fracture recovery
* Smart healthcare systems
* Telemedicine applications

---

## 🚀 Project Outcome

Osteo Sentinel combines **Embedded Systems, IoT, Cloud Computing, and Machine Learning** to provide a real-time osteoporosis fracture-risk monitoring solution.

The system enables continuous tracking, early risk detection, remote monitoring, and smart alerts to support preventive healthcare management.

---

## 👩‍💻 Project Team

**Janani S**
Vidyaa Vikas College of Engineering and Technology – Tiruchengode

**Project:** Osteo Sentinel – Embedded and IoT System for Real-Time Osteoporosis Fracture Risk Prediction using Machine Learning
