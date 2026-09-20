# CareerGuide AI 🚀

> An AI-powered career guidance platform designed to help users explore careers, jobs, business opportunities, skills, and personalized action plans.

🌐 **Live Demo:** https://career-guide-ai-fpvk.onrender.com

---

## 🧠 What is CareerGuide AI?

CareerGuide AI is an AI-powered career agent that helps users make informed decisions about their professional future.

Instead of simply answering questions, it can:

- 🎯 Explore career paths
- 💼 Analyze job requirements
- 📚 Identify skills to learn
- 🗺️ Create personalized career roadmaps
- 🔎 Research current information from the web
- 🏢 Explore business ideas
- 🧭 Compare different career directions
- 👤 Personalize guidance using user profiles

CareerGuide AI is designed to **guide decisions, not make decisions for the user.**

---

## ✨ Core Features

### 🎯 Career Mode
Explore career options, required skills, learning paths, projects, internships, and interview preparation.

### 💼 Job Mode
Understand target roles, skill requirements, skill gaps, portfolio needs, resumes, interviews, and application strategies.

### 🏢 Business Mode
Explore business ideas, customers, competitors, business models, costs, risks, validation, and growth strategies.

### 🧭 Exploration Mode
Discover possible career directions based on interests, strengths, education, goals, available time, and constraints.

### 🔎 AI Web Research
CareerGuide AI can research current information when freshness matters, such as:

- Job requirements
- AI/technology trends
- Certifications
- Salaries
- Hiring requirements
- Industry developments

### 👤 Personalized Guidance
User profiles allow the system to adapt recommendations to individual circumstances.

### 🛡️ AI Safety & Guardrails
The system includes input and output guardrails designed to reduce unsafe or inappropriate responses.

### 📊 Analytics
Google Analytics is integrated to monitor website usage and understand how users interact with the platform.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | AI/backend development |
| OpenAI Agents SDK | Agent orchestration |
| FastAPI | Backend API |
| Supabase | Multi-user persistence |
| OpenRouter | Model fallback |
| Web Research | Current information retrieval |
| HTML/CSS/JavaScript | Frontend |
| Git & GitHub | Version control |
| Render | Cloud deployment |
| Google Analytics | Usage analytics |

---

## ☁️ Deployment

CareerGuide AI is deployed as a cloud application.

Users can access the application directly from a browser without installing Python, VS Code, or the project locally.

**Live Application:**

https://career-guide-ai-fpvk.onrender.com

---

## 🔐 Security

The production source code is maintained in a private repository.

Sensitive credentials such as:

- API keys
- Database credentials
- Authentication secrets

are kept outside the public repository.

The public repository is a **project showcase**, not the application's source code.

---

## 🎓 Project Purpose

CareerGuide AI was built as a practical AI engineering project to explore:

- AI agents
- Multi-agent architecture
- Web research
- Tool calling
- Personalization
- Guardrails
- Persistent user sessions
- Cloud deployment
- Production APIs
- AI application analytics

---

## 👨‍💻 Developer

**Mohammed Hasnain**

CSE AI/ML Developer

Built as part of an ongoing AI/ML engineering journey.

## 🏗️ Architecture

```text
                    USER
                      │
                      ▼
             CareerGuide Web UI
                      │
                      ▼
               FastAPI Backend
                      │
                      ▼
          CareerGuide Manager Agent
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
   Web Research    User Profile   Specialists
                      │
              ┌───────┼────────┐
              ▼       ▼        ▼
           Career    Job     Business
         Specialist Specialist Specialist
                      │
                      ▼
              Research + Reasoning
                      │
                      ▼
               Personalized Plan
                      │
                      ▼
                     USER
