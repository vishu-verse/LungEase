
# LungEase – AI-Powered Smart Spirometer for Early Lung Health Screening

**LungEase** is a low-cost, AI-enabled spirometry device designed to assist in the early detection and monitoring of respiratory conditions such as asthma, COPD, and tuberculosis. It aims to provide an accessible and affordable lung health solution, especially for patients in rural and underserved communities.

---

## 📌 Problem Statement

In India and many developing regions, millions of individuals lack access to proper pulmonary testing due to the high cost and unavailability of medical-grade spirometers. This results in delayed diagnoses and worsening of respiratory diseases.

---

## 💡 Our Solution

LungEase bridges the gap by combining:
- **ESP32** microcontroller and a **pressure sensor (MPX5010)** to capture real-time breathing patterns.
- A **React.js frontend** for an intuitive user interface.
- A lightweight **machine learning model** for classifying lung health conditions based on spirometric data.

The result: a compact, affordable, and intelligent device that empowers local clinics, caregivers, and even patients to monitor lung health with minimal training.

---

## 📂 Project Structure

| Folder         | Description                                      |
|----------------|--------------------------------------------------|
| `frontend/`    | React.js web application (User interface)        |
| `backend/`     | Backend server and machine learning logic        |
| `hardware/`    | ESP32 microcontroller code, circuit design       |
| `assets/`      | Images, diagrams, pitch deck, and demo video     |

---

## 🔧 Tech Stack

- **Hardware:** ESP32, MPX5010 Pressure Sensor
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Python (Flask / FastAPI), ML (Scikit-learn / TensorFlow Lite)
- **ML Model:** Lung condition classification using time-series pressure data
- **Storage (Planned):** Firebase / Local CSV-based history

---

## 🖼️ Preview

> Demo screenshots and system diagram will be added during the hackathon.

---

## 🚀 How to Run the Project

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

### Backend Setup
```bash
cd backend
# Optional: create a virtual environment
pip install -r requirements.txt
python app.py
```

### Hardware Setup
- Connect MPX5010 pressure sensor to ESP32.
- Upload the `main.ino` file using the Arduino IDE.
- Ensure the device sends data over serial/Wi-Fi to the backend.

---

## 📽️ Demo Video

A complete walkthrough of the system will be added here post-hackathon.

---

## 📊 Pitch Deck

> Pitch Deck will be added during the hackathon.

---

## 👥 Team

- **Niharka Dhaka and Aayushi** – Frontend Development, UX Design
- **Chirag Malik and Fiza Khan** – Machine Learning & Backend Integration
- **Aayushi and Chirag Malik** – Hardware Engineering & Embedded Systems

---

## 🔐 Legal Notice

```
⚠️ This project is not open-source. All rights reserved.

The content of this repository, including source code, designs, diagrams, and documentation, is the intellectual property of the LungEase team. Redistribution, reproduction, modification, or use of any part of this project without explicit written permission is strictly prohibited.
```

If you are interested in collaborating, licensing, or supporting this project, please contact us directly.

---

## 📌 Referral Code

> Pranav
