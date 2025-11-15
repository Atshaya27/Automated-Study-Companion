# Automated Study Companion  
### Multi-Agent Study Planner, Notes Generator, and Quiz Assistant  
Track: Concierge Agents — Kaggle AI Agents Capstone Project (Nov 2025)

---

## 📌 Overview
Automated Study Companion is a multi-agent learning assistant that researches topics, produces structured study notes, generates quizzes, and tracks learner progress using session and long-term memory.  
It automates the most time-consuming steps in studying: research, note creation, question generation, and spaced repetition tracking.

This project is built using **ADK-Python**, includes multi-agent orchestration, tool integrations, observability, memory, and long-running operations.

---

## 🎯 Key Features
- **Multi-Agent System**
  - Controller Agent  
  - Research Agent  
  - Summarizer Agent  
  - Quiz Agent  
  - Progress Agent  
- **Tooling**
  - Custom Search Tool  
  - Code Execution Tool for validating programming-related answers  
- **Memory**
  - Session memory (InMemorySessionService)  
  - Long-term Memory Bank (JSON persistence)  
- **Long-running Operations**
  - Research tasks can pause/resume  
- **Observability**
  - Structured logs  
  - Metrics for research quality, quiz difficulty, accuracy  
- **Agent Evaluation**
  - Auto-grader checks student answers  
  - Human evaluation loop supported  

---

## 🧠 Architecture
