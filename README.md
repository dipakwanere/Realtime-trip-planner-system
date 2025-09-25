# Realtime Trip Planner System

## Project Agenda
Build an End-to-End Agentic AI Project using:
- Langchain
- Langraph
- RAG (Retrieval-Augmented Generation)
- Agentic RAG
- MCP (Model Context Protocol)
- Other relevant libraries and frameworks (e.g., uv)

### Prerequisites
- Python (modular programming)
- Langchain, Langraph, RAG, Agentic RAG, MCP
- NLP, Deep Learning, Generative AI

## Problem Statement
Design and implement an agentic AI application for a **Realtime Trip Planner System**. The goal is to enable AI agents to collaborate and solve complex travel planning workflows in real time. The system should leverage agentic RAG and graph-based mechanisms (Langraph) to optimize trip planning, adapt to changing requirements, and provide intelligent recommendations.

## Project Structure

### Project Setup with uv

#### 1. Check your uv version:
```powershell
uv --version
```
Displays the installed uv version. If not installed, visit: [https://docs.astral.sh/uv/](https://docs.astral.sh/uv/)

#### 2. Initialize a new project:
```powershell
uv init project_name
```
Creates a new project structure automatically.

#### 3. Change to the project directory:
```powershell
cd project_name
```

#### 4. Open the project in VS Code:
```powershell
code .
```

#### 5. Create and activate a virtual environment:
python -m venv venv
.\venv\Scripts\Activate.ps1
```

### Trip Planner Agent Tasks
This app will plan a trip for any city worldwide using real-time data:
- Real-time weather info
- Attractions & activities in the city
- Hotels and costs
- Currency conversion
- Total expenses
- Generate the trip summary

```powershell
uv python list
```
Lists all Python versions detected by uv.

---

> venv, README.md, and requirements.txt have been created and updated as part of the initial setup.

---

- **Main:** Agentic AI Application
     - AI agents collaborate with other AI agents to solve complex workflows
     - Langraph: Mechanism using graph API for agent collaboration

### Key Concepts
- **Nodes:** Fundamental units representing tasks, agents, or data sources in the graph
- **Edges:** Connections between nodes, representing relationships or data flow
- **Stategraph:** The evolving state of the system as agents interact and solve tasks

## Implementation & Deployment
- Full project implementation
- Deployment using LLMOps best practices

---
