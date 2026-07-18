🤖 Smart Digital Twin — Robotic Arm Predictive Maintenance

An AI-powered predictive maintenance system for robotic arms, using Reduced-Order Modeling (ROM) and Machine Learning, designed to monitor, analyze, and predict equipment health in real time.
🌟 Key Features

    🦾 3-DOF Robotic Arm Visualization — Real-time digital twin simulation

    🧠 AI-Powered Predictive Maintenance — Detect, predict, and prevent faults

    ⚙️ Fault Simulation & Testing — Validate performance under stress

    📡 Real-Time Sensor Monitoring — Visualize temperature, vibration & voltage data

    💗 Health Score Tracking — Continuous degradation analysis

    ⏳ Remaining Useful Life (RUL) — Intelligent lifespan estimation

    📈 Interactive Charts & Analytics — Insightful, user-friendly dashboards

    📤 Data Export Functionality — Share results in multiple formats

🏗️ System Architecture

text
┌──────────────────┐        ┌────────────────────┐         ┌───────────────────┐
│     Frontend     │  <──>  │      Backend       │  <──>   │     ML Model      │
│  (React.js)      │        │  (Node.js/Express) │         │  (Python / ML)    │
└──────────────────┘        └────────────────────┘         └───────────────────┘
         ▲                           ▲                               ▲
         │                           │                               │
         ▼                           ▼                               ▼
                    ┌────────────────────────────────────────────┐
                    │           WebSocket Layer (Real-Time)       │
                    └────────────────────────────────────────────┘

    Frontend: React.js dashboard for visualization and analytics

    Backend: Node.js + Express API for data handling and coordination

    AI Engine: Python ML model for predictive analysis and RUL estimation

    WebSocket: Enables real-time communication between all components

⚙️ Setup & Installation
Prerequisites

    Node.js v18

    Python 3.8+

    npm or yarn

1. Clone the Repository

bash
git clone https://github.com/yourusername/robotic-arm-digital-twin.git
cd robotic-arm-digital-twin

2. Install Frontend Dependencies

bash
cd frontend
npm install

3. Install Backend Dependencies

bash
cd ../backend
npm install

4. Install ML Dependencies

bash
cd ../ml-model
pip install -r requirements.txt

🚀 Run the Application
Start Backend Server

bash
cd backend
npm run dev

Start Frontend

bash
cd frontend
npm start

Access Application

Open your browser at 👉 http://localhost:3000
🧠 AI Model Capabilities

    🔥 Temperature anomaly detection

    ⚡ Voltage drop prediction

    🌀 Vibration pattern recognition

    ⚙️ Motor failure forecasting

    🧾 Remaining Useful Life (RUL) estimation
