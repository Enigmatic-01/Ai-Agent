# 🤖 AI Agents from Scratch using LangChain

This project demonstrates how to build **AI agents from scratch** using **LangChain**, including agents with and without tool binding, and a simple agent that integrates **weather data** and **web search** for real-time responses.

---

## 🚀 Features

- Agents built from scratch (no prebuilt agent templates)
- Tool-bound agent using LangChain tool calling
- Non-tool conversational agent
- Simple agent with weather + web search tools
- Real-time data access via APIs
- Conversation memory handling
- Modular and extensible design

---

## 🧠 Agents Overview

### 1️⃣ Tool-Bound Agent
- Uses LangChain **tool binding**
- Decides when to call tools automatically
- Integrates **DuckDuckGo Search**
- Maintains conversation history
- Best for real-time information retrieval

---

### 2️⃣ Non-Bound Tool Agent
- LLM-based conversational agent
* Does not use tool binding
- Calls tools explicitly through custom logic
- Uses prompt + conversation memory for context
- Tools are triggered manually (developer-controlled)
- Best for controlled workflows, reasoning, explanations, and general Q&A
---

### 3️⃣ Simple Agent (Weather + Search)
- Lightweight agent implementation
- Uses:
  - DuckDuckGo Search
  - OpenWeatherMap API
- Handles practical real-world queries
- Focused on simplicity and clarity

---

## 🛠 Tech Stack

- **Language:** Python
- **Framework:** LangChain
- **LLM:** OpenAI (ChatOpenAI)
- **Search Tool:** DuckDuckGoSearchRun
- **Weather API:** OpenWeatherMap

---

## 📦 Tools Used

- DuckDuckGoSearchRun (Web search)
- Custom Weather Tool (OpenWeather API)
- LangChain Tool Binding

---


