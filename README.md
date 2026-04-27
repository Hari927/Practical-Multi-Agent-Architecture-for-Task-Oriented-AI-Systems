# Practical-Multi-Agent-Architecture-for-Task-Oriented-AI-Systems

# 🚀 Multi-Agent AI System using LangGraph & LLMs

## 📌 Overview

This project demonstrates a practical implementation of a **Multi-Agent Architecture** where multiple intelligent agents collaborate to solve complex tasks efficiently.

The system is designed using **LangChain, LangGraph, and LLMs**, enabling dynamic task routing, reasoning, and execution through specialized agents.

---

## 🧠 Key Concept

A **multi-agent system** consists of independent agents working together, each handling specific responsibilities such as:

* Understanding and refining user queries
* Gathering relevant information
* Performing computations or coding tasks
* Validating final outputs

---

## ⚙️ Architecture Design

The system follows a **Supervisor-based workflow architecture**:

### 🔹 Agents in the System:

1. **Enhancer Agent**

   * Refines unclear or vague user queries
   * Improves prompt clarity and structure

2. **Researcher Agent**

   * Fetches real-time or contextual information
   * Uses external tools for search

3. **Coder Agent**

   * Handles technical tasks
   * Performs calculations and executes code

4. **Validator Agent**

   * Evaluates the final response
   * Ensures accuracy and completeness

5. **Supervisor Agent**

   * Central decision-maker
   * Routes tasks dynamically between agents

---

## 🔁 Workflow

1. User submits a query
2. Supervisor analyzes the request
3. Routes to:

   * Enhancer (if unclear)
   * Researcher (if information needed)
   * Coder (if technical task)
4. Output is sent to Validator
5. Validator decides:

   * Finish workflow ✅
   * Or re-route to Supervisor 🔄

---

## 🧩 Technologies Used

* Python
* LangChain
* LangGraph
* ChatGroq (LLM)
* Tavily Search API
* Riza Code Interpreter

---

## 📦 Installation

```bash
pip install -q langchain langchain_groq langchain_community langgraph rizaio
```

---

## 🔑 Environment Setup

Set your API keys in Google Colab or environment:

```python
os.environ["GROQ_API_KEY"] = "your_key"
os.environ["TAVILY_API_KEY"] = "your_key"
os.environ["RIZA_API_KEY"] = "your_key"
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Install dependencies
3. Add API keys
4. Run all cells
5. Provide input queries

---

## 💡 Example Queries

* “What is the weather in Chicago?”
* “Difference between Apple stock price in 2021 vs 2023”
* “Impact of climate change on agriculture”
* “Count occurrences of a letter in a string”

---

## ✨ Key Features

* ✔️ Modular agent design
* ✔️ Dynamic workflow routing
* ✔️ Real-time decision making
* ✔️ Tool integration (Search + Code execution)
* ✔️ Automatic validation mechanism
* ✔️ Scalable and extensible architecture

---

## 📊 Use Cases

* Intelligent assistants
* Research automation systems
* Coding assistants
* Decision-support systems
* AI workflow orchestration

---

## 🔮 Future Improvements

* Add memory-based agents
* Integrate vector databases (RAG)
* Improve reasoning with agent collaboration
* Add UI dashboard for visualization
* Deploy as API or web application

---

## 📜 License

This project is for educational and research purposes.

---

## 👨‍💻 Author

Hari Sankar
