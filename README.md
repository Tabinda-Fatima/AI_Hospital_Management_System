# AI_Hospital_Management_System
This project is built using multiple specialized AI agents, each responsible for a specific task. The system does not rely on a single agent, instead it follows a modular, multi-agent architecture.
# AI Health Agent – Hospital Front Desk Automation

AI-powered multi-agent system for hospitals and clinics to automate patient registration, MRN lookup, appointment booking, and hospital information via chat (WhatsApp / Web).

Built using **n8n**, **AI Agents**, and **LLMs**.

---

## ✨ Key Features

- Patient triage (Registered / Not Registered)
- Medical Record Number (MRN) lookup
- New patient registration (step-by-step)
- Appointment booking workflow
- Hospital information (RAG-based)
- Session memory (no repeated questions)
- One-question-at-a-time interaction
- WhatsApp-friendly responses

---

## 🧠 Agents Overview

- **Greeting & Triage Agent**  
  Starts conversation and identifies patient status

- **Registration Lookup Agent (MRN)**  
  Verifies registered patients from database

- **New Patient Registration Agent**  
  Collects name, contact, and address sequentially

- **Appointment Agent**  
  Handles appointment type, token, date, and time

- **Knowledge / RAG Agent**  
  Provides hospital info, doctor details, timings, FAQs

---

## ⚙️ Tech Stack

- n8n (Version 2.0.3)
- AI Agents (LangChain-based)
- Groq LLM (OpenAI-compatible)
- Supabase / Vector Store (RAG)
- Google Sheets / Database
- Session-based Memory

---

## 🚀 Setup (Quick)

1. Install n8n (v2.0 or later)
2. Import the provided workflow JSON
3. Configure credentials (Groq, Database, Vector Store)
4. Activate the workflow
5. Test using chat input

> All credentials in the JSON are placeholders.

---

## 💰 Cost Estimate

Approx. **$30 – $100/month**, depending on usage and deployment.

---

## 📄 License

For educational and commercial use.  
Ensure compliance with local healthcare data regulations.
