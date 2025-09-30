# 🤖 Multi-User Agent Chatbot using LangGraph  

This project is a step-by-step implementation of a **chatbot agent** built with **LangGraph**.  
It evolves from a **simple single-agent** to a **multi-user chatbot** with memory, web search, and weather capabilities.  

---

## 🚀 Project Objective
To explore **LangGraph agent design** by progressively adding complexity:  
- Build a simple agent.  
- Add external **tools** (Web Search, Weather API).  
- Enable **multi-user memory** with session IDs.  

---

## ⚙️ Features
- 🔹 **Simple Agent**: First implementation using LangGraph `StateGraph`.  
- 🔹 **Tool-Augmented Agent**: Uses Web Search + Weather API.  
- 🔹 **Conditional Routing**: Directs queries to tools only when needed.  
- 🔹 **Multi-User Memory**: Maintains context across sessions with `thread_id`.  
- 🔹 **Scalable Design**: Modular pipeline for real-world extension.  

---

## 🧪 Implementation Stages  

### 1️⃣ Simple Agent (LangGraph StateGraph)  
- Defined `GraphState` with `messages`.  
- Created a node for **LLM interaction**.  
- Entry & finish points managed by **StateGraph**.  

### 2️⃣ Agent with Tools (WebSearch + Weather API)  
- Integrated `TavilySearchResults` (web search).  
- Added **Weather API** for real-time weather info.  
- Used **conditional edges** (`tools_condition`) to dynamically route queries.  

### 3️⃣ Multi-User Chatbot (with Memory)  
- Added **InMemorySaver** for storing session conversations.  
- Introduced `thread_id` to differentiate users.  
- Preserves conversation history across multiple interactions.  

---

## 🎯 Use Cases
- 🌐 General Q&A with web search support.  
- ☁️ Weather updates in real time.  
- 👥 Customer support handling **multiple users simultaneously**.  
- 🏫 Education bots with **personalized student memory**.  

---

## 📚 Skills Learned
From this project, I gained practical knowledge of:  

- ✅ **LangGraph fundamentals** – StateGraph, nodes, conditional edges.  
- ✅ Designing **agents from scratch** instead of using prebuilt templates.  
- ✅ Building **tool-augmented agents** with external APIs.  
- ✅ Managing **conversation memory** across multiple sessions.  
- ✅ Conditional routing & flow control with `tools_condition`.  
- ✅ Designing **scalable and modular chatbot pipelines**.  
- ✅ Using `thread_id` for **multi-user support**.  

---

## 🛠 Tech Stack
- Python 3.9+  
- LangChain + LangGraph  
- OpenAI LLMs  
- Tavily Web Search API  
- Weather API  



## ▶️ How to Run
1. Clone the repo:  
   
   git clone https://github.com/GovindaTak/multi-user-agent-chatbot-langgraph.git
   cd multi-user-agent-chatbot-langgraph


2. Install dependencies:

3. Add your API keys 
4. Run the chatbot:


---

## 📜 License

MIT License – free to use and extend.

---

## 🙌 Author

👤 Govinda Tak
🔗 [GitHub Profile](https://github.com/GovindaTak)


