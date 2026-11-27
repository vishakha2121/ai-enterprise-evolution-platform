# 🚀 AI Autonomous Enterprise Evolution Platform

> **An AI-powered platform that continuously redesigns an enterprise's workflows, teams, KPIs, technologies, and business processes in response to changing market conditions — powered by Google Gemini.**

![Status](https://img.shields.io/badge/Status-In_Development-yellow)
![Python](https://img.shields.io/badge/Backend-FastAPI-009688?logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/Frontend-React_+_Vite-61DAFB?logo=react&logoColor=black)
![Database](https://img.shields.io/badge/Database-SQLite-003B57?logo=sqlite&logoColor=white)
![AI](https://img.shields.io/badge/AI-Google_Gemini-4285F4?logo=google&logoColor=white)

---

## 📖 About The Project

Enterprises struggle to keep up with fast-changing markets. When a new competitor arrives, a new technology emerges, or the economy shifts, organizations need to adapt their internal structure quickly. 

**The AI Autonomous Enterprise Evolution Platform** solves this. Users input their current enterprise setup (workflows, teams, KPIs, tech stack, and business processes) and feed in external market signals. Using **Google Gemini AI**, the platform analyzes the gap and proposes prioritized, actionable evolution suggestions. Users can simulate "what-if" scenarios, apply changes, and track a full evolution history.

### 🎯 Key Features
- **Enterprise State Management:** Define and manage current workflows, teams, KPIs, technologies, and business processes.
- **Market Signals Input:** Feed in external conditions (new competitors, economic shifts, tech trends).
- **AI Evolution Engine (Gemini):** Get AI-driven suggestions to redesign the enterprise.
- **What-If Simulation:** Simulate the impact of applying specific changes before committing.
- **Evolution Timeline:** Track the history of all past changes and AI suggestions.
- **Interactive Dashboard:** Beautiful charts and insights showing company health and market pulse.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React, Vite, Tailwind CSS, Framer Motion, Recharts |
| **Backend** | Python, FastAPI, SQLAlchemy, Pydantic |
| **Database** | SQLite (Practice), easily scalable to PostgreSQL |
| **AI Engine** | Google Gemini API (`gemini-2.0-flash`) |
| **Authentication** | JWT (JSON Web Tokens) |

---

## 📂 Project Structure

```text
ai-enterprise-evolution-platform/
├── backend/                  # FastAPI Backend
│   ├── app/
│   │   ├── routers/          # API Endpoints (auth, workflows, evolution, etc.)
│   │   ├── models.py         # SQLAlchemy DB Models
│   │   ├── schemas.py        # Pydantic Schemas
│   │   ├── services/         # Gemini & Evolution logic
│   │   └── database.py       # SQLite connection
│   ├── database/             # SQLite DB file & seed data
│   └── main.py               # Entry point
│
├── frontend/                 # React Frontend
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Dashboard, Evolution, Settings, etc.
│   │   ├── hooks/            # Custom React hooks
│   │   ├── services/         # API calling functions
│   │   └── layouts/          # Page layouts
│   └── package.json
│
├── docs/                     # API & Architecture documentation
└── scripts/                  # Setup & test scripts