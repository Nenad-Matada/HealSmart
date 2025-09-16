**HealSmart+ 🩺🤖**

HealSmart+ is an AI-powered healthcare assistant that provides intelligent, real-time healthcare support.
It is designed to make healthcare more accessible by combining AI-driven insights with an easy-to-use interface.


**🚀 Features**

**Symptom Checker 🧾** – Analyze symptoms and suggest possible conditions.

**AI Chatbot 💬** – Answer health-related queries instantly.

**Doctor Recommendation 👨‍⚕️** – Suggest relevant specialists based on symptoms.

**Drug Interaction Checker 💊** – Ensure safe prescriptions and avoid harmful combinations.


**🛠 Tech Stack**

Backend: FastAPI (Python)

Frontend: React.js

AI/ML: Python libraries for AI model integration

Database: (Optional – add PostgreSQL/Firebase if you integrate later)

**⚡ Installation & Setup**

**🔹 Backend (FastAPI)**
cd backend

python -m venv venv

.\venv\Scripts\activate   # (Windows)

pip install -r requirements.txt

python -m uvicorn app:app --reload --port 8000

Your backend will run at 👉 http://127.0.0.1:8000

**🔹 Frontend (React.js)**
cd frontend

npm install

npm start

Your frontend will run at 👉 http://localhost:3000


**🎯 How It Works**

Users enter symptoms or queries in the frontend.

Requests are sent to the FastAPI backend.

AI/ML models process the request and generate predictions/answers.

Results (doctor recommendations, chatbot responses, or drug checks) are sent back to the frontend for display.


**📸 Demo**

[![Watch the Demo](https://img.shields.io/badge/Watch-Demo-blue)](https://github.com/manju79960/HealSmart/releases/download/v1.0.0/HealSmart+.mp4)

