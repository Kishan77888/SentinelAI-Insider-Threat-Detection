# 🛡️ SentinelAI - Insider Threat Detection Platform

SentinelAI is a full-stack AI-powered cybersecurity system designed to detect insider threats in real-time using behavioral analysis and risk scoring.

## 🚀 Features

- 🔍 Real-time endpoint monitoring (USB, processes, network, login)
- 🧠 AI-based behavioral risk scoring (0–500 scale)
- ⚡ Live alerts using WebSockets
- 🖥️ SOC Analyst Dashboard (7 modules)
- 📊 Risk analytics & employee monitoring
- 🚫 Active response (block USB, warnings, forensic reports)

## 🏗️ Architecture

### 1. Endpoint Agent
- Python + psutil
- Monitors system activities
- Sends data every 15 seconds

### 2. Backend Server
- FastAPI + PostgreSQL
- Risk scoring engine
- WebSocket real-time updates

### 3. Frontend Dashboard
- React + Vite
- Real-time SOC interface
- Fully responsive UI

## ⚠️ Threat Detection Modules

- USB insertion
- Bulk file copy
- Unauthorized applications
- Keylogger detection
- Suspicious ports
- After-hours login

## 📊 Risk Levels

- LOW (0–49)
- MEDIUM (50–119)
- HIGH (120–500)

## 🛠️ Tech Stack

- Backend: FastAPI, PostgreSQL
- Frontend: React, Vite
- Agent: Python (psutil)
- Auth: JWT
- Realtime: WebSocket

## 🌐 Deployment

- Frontend: Vercel
- Backend: Railway

## 👨‍💻 Author

Kumar Kishan  
B.Tech CSE (Cybersecurity)

---
## 🌐 Live Demo

Experience SentinelAI in real-time:

🔗 **Dashboard (Frontend):**  
https://sentinelai-sigma.vercel.app  

🔗 **Backend API:**  
https://web-production-b96f9.up.railway.app  

📄 **API Documentation (Swagger):**  
https://web-production-b96f9.up.railway.app/api/docs  

---

## 🧪 Demo Credentials

Use the following credentials to explore the system:

- **Username:** admin  
- **Password:** SentinelAdmin2024!

---

## ⚡ How to Test

1. Login to the dashboard  
2. Register or connect an endpoint agent  
3. Trigger events:
   - Insert USB
   - Run unauthorized app
   - Copy multiple files
4. Watch real-time updates:
   - Risk score increases
   - Alerts generated instantly
   - Dashboard updates via WebSocket  

---

## 📱 Device Compatibility

- 💻 Desktop (Recommended)
- 📱 Mobile (Fully Responsive UI)
- 🌐 Works globally (Vercel CDN)

---

## 🚀 Deployment Info
## 🌐 Live Demo

Experience SentinelAI in real-time:

🔗 **Dashboard (Frontend):**  
https://sentinelai-sigma.vercel.app  

🔗 **Backend API:**  
https://web-production-b96f9.up.railway.app  

📄 **API Documentation (Swagger):**  
https://web-production-b96f9.up.railway.app/api/docs  

---

## 🧪 Demo Credentials

Use the following credentials to explore the system:

- **Username:** admin  
- **Password:** SentinelAdmin2024!

---

## ⚡ How to Test

1. Login to the dashboard  
2. Register or connect an endpoint agent  
3. Trigger events:
   - Insert USB
   - Run unauthorized app
   - Copy multiple files
4. Watch real-time updates:
   - Risk score increases
   - Alerts generated instantly
   - Dashboard updates via WebSocket  

---

## 📱 Device Compatibility

- 💻 Desktop (Recommended)
- 📱 Mobile (Fully Responsive UI)
- 🌐 Works globally (Vercel CDN)

---
⭐ If you like this project, give it a star!
