# 🧠 Agentic Chatbot using LangGraph, Groq & OpenAI

An agentic chatbot that leverages LangGraph ReAct agents, integrates real-time search tools, and supports multi-provider LLMs (Groq & OpenAI) — all hosted on Hugging Face Spaces with an interactive Streamlit UI.

---

## 🚀 Demo

🔗 **Live App:** [Try the chatbot on Hugging Face](https://huggingface.co/spaces/YOUR_USERNAME/YOUR_PROJECT_NAME)

🔗 **GitHub Repo:** [View Source Code](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME)

---

## 🧩 Features

- 🧠 Role-based agent behavior with custom instructions
- 🔁 Switch between Groq and OpenAI models on demand
- 🌐 Live internet access using Tavily web search tool
- 🔗 Modular LangGraph workflow design
- 🧪 Streamlit-based interactive UI
- 📡 FastAPI-powered backend integration

---

## 🧠 Problem Statement

- Traditional LLMs often return outdated responses with no access to current events.
- Fine-tuning LLMs for specific tasks or roles is expensive and resource-heavy.
- General-purpose bots lack personalization and tool-use flexibility.
- Real-time search capabilities are often missing in standard chatbot setups.

---

## 💡 Solution

- Build a reusable **agentic chatbot** that adapts to custom roles without retraining.
- Integrate **LangGraph ReAct agents** with LangChain tools for flexible orchestration.
- Combine **Groq** and **OpenAI** models for performance and versatility.
- Use **Tavily Search API** to fetch current information dynamically.
- Deploy everything on **Hugging Face Spaces** with an intuitive **Streamlit UI**.

---

## 🛠️ Tech Stack

| Technology       | Description                                                |
|------------------|------------------------------------------------------------|
| LangGraph Agents | Manages agent workflows and decision-making using graphs   |
| FastAPI          | API server to serve model and agent endpoints              |
| Groq & OpenAI    | Language models for generating intelligent responses       |
| Streamlit        | Builds the frontend interface for user interaction         |
| LangChain        | Connects LLMs with tools like search, memory, and agents   |
| Hugging Face     | Hosts the full application publicly for free               |

---

## 🧱 Architecture Overview

```plaintext
User ↔ Streamlit UI ↔ FastAPI ↔ LangGraph Agent ↔ LLMs (Groq/OpenAI) + Tools (Tavily)
