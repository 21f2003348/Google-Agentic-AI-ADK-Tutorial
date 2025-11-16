## 📘 Overview

This repository contains all assignments, notebooks, code exercises, and notes from the **Google × Kaggle 5-Day Agentic AI ADK Workshop**.  
It covers the full lifecycle of modern AI agent development — from basic agent capabilities to production-ready multi-agent systems deployed on Vertex AI.

The materials in this repository include hands-on labs using **Google’s Agent Developer Kit (ADK)**, **Gemini models**, **MCP tools**, context engineering, observability, and end-to-end agent workflows.

---

## 🚀 Course Structure & Contents

### **🔹 Day 1 — Introduction to Agents**
- What AI Agents are  
- Taxonomy of agent capabilities  
- Agent Ops: reliability, governance, safety  
- Interoperability & identity  
- Building your first agent using ADK  
- Adding external tools (Google Search)  
- Building multi-agent systems  
- Architectural patterns for agent teams  

---

### **🔹 Day 2 — Agent Tools & MCP**
- Designing effective agent tools  
- Turning Python functions into tools  
- Model Context Protocol (MCP)  
  - Architecture  
  - Communication layer  
  - Interoperability  
- Using MCP tools in agents  
- Long-running operations  
- Pause & resume mechanics  
  - `request_confirmation()`  
  - `adk_request_confirmation` event  
  - `invocation_id` and resuming execution  

---

### **🔹 Day 3 — Context Engineering (Sessions & Memory)**
- What is context engineering  
- Sessions vs memory  
- Managing conversation history  
- Working memory (short-term)  
- Session state management  
- Long-term memory  
- Creating custom tools for session data  
- Using `MemoryService`  
- Transferring session state to memory  
- `load_memory` vs `preload_memory`  

---

### **🔹 Day 4 — Agent Quality**
- Agent quality assessment  
- Observability fundamentals  
  - Logs  
  - Traces  
  - Metrics  
- Debugging agent workflows  
- Understanding agent decisions  
- LLM-as-a-Judge evaluation  
- Human-in-the-loop (HITL) evaluation  
- Building evaluation pipelines  
- Scoring responses and tool usage  

---

### **🔹 Day 5 — Prototype to Production**
- Designing production-grade agent systems  
- Deployment patterns & scaling  
- Agent lifecycle management  
- Agent-to-Agent (A2A) protocol  
- Multi-agent communication systems  
- Deploying agents to Vertex AI Agent Engine  
- Turning prototypes into cloud services  

---

## 📦 What This Repository Includes
- Complete Jupyter/Colab notebooks  
- Python code for ADK Agents & MCP tools  
- Notes and explanations for each day  
- Evaluation pipelines and HITL examples  
- Prototype agent implementations  
- Exercises and assignments from the workshop  

---

## 🎯 Purpose of This Repository
This repository acts as a **comprehensive reference** for:
- Learning ADK and agent system design  
- Understanding modern agent workflows  
- Building tools, memory systems & multi-agent teams  
- Deploying production-ready agents using Google’s ecosystem  

It is structured so others can **reproduce your work** and follow the course independently.

---
