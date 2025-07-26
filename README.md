# Schedy
# 🧠 AI Scheduler – Intelligent Employee Shift Planner

An end-to-end AI-powered employee shift scheduling tool that helps managers create optimal weekly schedules based on staff availability and staffing requirements — built with Flask, React, MongoDB, and integrated GPT through LangChain.

## 🚀 Features

- 📅 **Weekly Shift Setup** – Define required staffing per shift/day.
- 👥 **Employee Availability Collection** – Share unique links for employees to submit their availability.
- 🤖 **AI-Powered Scheduling** – Generate optimal shift schedules using GPT via LangChain.
- 🔒 **Role-Secure Authentication** – JWT-based login system with Admin/Employee roles.
- 💡 **Real-Time Feedback Loop** – Edit and regenerate schedules based on changing constraints.
- 🌐 **Modern UI** – Built using React and Ant Design for responsive and intuitive UX.
- 🧩 **Modular Backend** – Python Flask API with MongoDB for data storage.

---

## 🛠️ Tech Stack

| Frontend | Backend | AI Integration | Database | Auth |
|----------|---------|----------------|----------|------|
| React + Ant Design | Flask (Python) | LangChain + GPT | MongoDB | JWT |

---


## 🧩 Architecture Overview

```plaintext
React UI  <-->  Flask API  <-->  MongoDB
                          |
                      LangChain
                          |
                        GPT (OpenAI/LLM)


## Develop[ed BY 
- Daksh Malhotra - www.dakshmalhotra.dev
- Bharat Kumar
