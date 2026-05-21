# Embedded Focus Monitoring System

Embedded AI focus-state monitoring system using Arduino Nano 33 BLE Sense and Edge Impulse.

<p align="center">
  <img src="images/system_architecture.png" width="1000"/>
</p>

---

# Overview

This project implements a real-time embedded focus monitoring system using physiological and motion-based sensor data.

The system combines:
- Pulse sensor readings
- IMU motion analysis
- Embedded machine learning
- Real-time classification
- Live monitoring interface

The model was trained using Edge Impulse and deployed directly onto the embedded hardware platform.

---

# Sensor Feature Extraction

<p align="center">
  <img src="images/sensor_output.png" width="900"/>
</p>

The system extracts features from:
- Pulse sensor activity
- Desk vibration and movement
- IMU acceleration changes

These features are used to classify user focus state in real time.

---

# Feature Visualization

<p align="center">
  <img src="images/feature_visualization.png" width="900"/>
</p>

Feature separation was analyzed using Edge Impulse to distinguish:
- Focused states
- Distracted states

---

# Model Training

<p align="center">
  <img src="images/model_training.png" width="900"/>
</p>

The neural network model was trained and optimized for embedded deployment on Arduino hardware.

---

# Live Dashboard Interface

## Focused State Monitoring

<p align="center">
  <img src="images/focused_state_dashboard.png" width="1000"/>
</p>

The dashboard displays:
- Real-time focus classification
- Confidence scores
- Pulse sensor activity
- Motion sensor readings
- Embedded inference output

---

## Distracted State Detection

<p align="center">
  <img src="images/distracted_state_dashboard.png" width="1000"/>
</p>

The system detects distracted states caused by:
- Typing activity
- Table tapping
- Motion disturbances
- Missing pulse contact

---

# Features

- Real-time focus-state classification
- Embedded AI inference
- Pulse + IMU sensor fusion
- Arduino deployment
- Live monitoring output
- Lightweight embedded model

---

# Hardware Platform

<p align="center">
  <img src="images/hardware_schematic.png" width="1000"/>
</p>

The system integrates:
- Arduino Nano 33 BLE Sense Rev2
- HW-827 pulse sensor
- Built-in IMU (accelerometer + gyroscope)
- USB power delivery
- Real-time sensor acquisition pipeline

---

# Technologies Used

- Arduino
- C++
- Edge Impulse
- Embedded AI
- IMU Sensors
- Pulse Sensors

---

# Results

| Metric | Result |
|---|---|
| Deployment Platform | Arduino Nano 33 BLE Sense |
| Sensors | Pulse + IMU |
| Classification | Focused vs Distracted |
| Inference | Real-time embedded execution |

---

# Performance Evaluation

<p align="center">
  <img src="images/confusion_matrix.png" width="850"/>
</p>

The embedded classification model was evaluated using real-time test sessions across focused and distracted activity states.

## Evaluation Metrics

| Metric | Value |
|---|---|
| Accuracy | 92.1% |
| Precision | 94.4% |
| Recall | 89.5% |
| Real-Time Inference | Yes |
| Deployment Platform | Arduino Nano 33 BLE Sense |

The confusion matrix demonstrates strong separation between focused and distracted behavioral states with minimal misclassification during live embedded inference.

---

# Future Work

- Improved classification accuracy
- Expanded sensor fusion
- Mobile dashboard integration
- Longer-term activity analysis

---

# Documentation

- [Full Technical Report](docs/embedded_focus_monitor_report.pdf)

---

# Authors

- Hasan Al Hussein
- Omar Yousef
- Ahmad Alhawamdeh

Khalifa University
