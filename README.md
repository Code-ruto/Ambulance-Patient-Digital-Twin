# Ambulance-Patient-Digital-Twin
Educational digital twin prototype demonstrating real-time patient monitoring, predictive analytics, and EMS decision support.

An interactive HTML application that demonstrates how a **digital twin** can support emergency medical responders by continuously monitoring a simulated patient and updating recommendations in real time.

Built for **ITAI 4371 – Digital Twins & Virtual Simulation** at **Houston Community College**.

> **Educational Prototype**  
> All patient data, hospitals, medical devices, and protocols are simulated for educational purposes only. This application is **not intended for clinical use.**

---

## LIVE DEMO

View the interactive simulation here:

[Launch Ambulance Digital Twin](https://code-ruto.github.io/Ambulance-Patient-Digital-Twin/)

---

## 📖 Overview

Emergency medical crews often have to make critical decisions with incomplete information.

Our project demonstrates how a **Digital Twin** can help by creating a live virtual model of a patient inside an ambulance.

As patient vital signs change, the digital twin continuously recalculates and recommends:

- 🚑 Appropriate responder level
- 🏥 Best hospital destination
- 🩺 Required medical equipment
- ⚠️ Patient triage priority

Unlike a static dashboard, the model updates every second, making it a true digital twin rather than a simple monitoring application.

---

## ✨ Features

### 📊 Live Patient Monitoring

- Real-time vital signs
- Heart Rate
- Blood Pressure
- Oxygen Saturation (SpO₂)
- Respiration Rate

---

### 🟢 Early Warning Score

Implements an educational version of the **NEWS2 Early Warning Score** to classify patients into:

- Low Risk
- Medium Risk
- High Risk

The score updates automatically as patient conditions change.

---

### 🧠 Intelligent Decision Support

The application continuously recommends:

- Required responder level (BLS or ALS)
- Hospital destination
- Medical equipment
- Patient priority

Every recommendation includes a human-readable explanation.

---

### 📈 Predictive Forecasting

Instead of only displaying current vital signs, the application predicts future trends using:

- Trend graphs
- Threshold warnings
- Forecast indicators

This allows responders to anticipate patient deterioration.

---

### 🚑 Crew Interventions

Users can simulate emergency treatment including:

- Oxygen
- IV Fluids
- Epinephrine
- Assisted Ventilation

The patient's condition immediately changes, and the Digital Twin recalculates its recommendations.

---

### 🏥 Dynamic Hospital Routing

The simulation includes multiple hospitals with changing availability.

If a hospital goes on diversion, the Digital Twin automatically reroutes the patient and records the decision.

---

### 📋 Audit Log

Every important event is timestamped, including:

- Vital changes
- Crew actions
- Recommendation updates
- Hospital rerouting
- Accept/Override decisions

---

### ⏪ Replay Mode

Users can review an entire simulation after completion using a replay timeline for demonstrations and debriefing.

---

## 🛠 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

No external libraries or frameworks are required.

Everything runs inside a single HTML file.

---

## 🚀 Running the Project

1. Clone this repository.

```bash
git clone https://github.com/your-organization/ambulance-digital-twin.git
```

2. Open

```
ambulance_digital_twin_v6.html
```

in any modern web browser.

No installation is required.

No server is required.

No internet connection is required.

---

## 📸 Screenshots

Add screenshots here after uploading them.

Examples:

- Home Screen
- Live Vitals Dashboard
- Hospital Routing
- Crew Intervention
- Replay Mode

---

## 🎯 Learning Objectives

This project demonstrates concepts in:

- Digital Twins
- Virtual Simulation
- Decision Support Systems
- Human-Computer Interaction
- Healthcare AI
- Predictive Analytics
- Real-Time Data Visualization



---

## 👥 Team AI Titans

| Team Member | Responsibilities |
|-------------|------------------|
| Anthony Randall | *(Project Manager)* |
| Andrew | *(Prompt Engineer)* |
| Oscar | *(Business Analyst)* |
| Win | *(AI Research and Development Lead)* |

---

## 📚 Course

ITAI 4371

Digital Twins & Virtual Simulation

Houston Community College

Summer 2026

---

## ⚠ Disclaimer

This software is an educational demonstration created for academic purposes.

All patient information, hospitals, emergency scenarios, routing decisions, and medical protocols are simulated and should not be used for real clinical decision-making.
