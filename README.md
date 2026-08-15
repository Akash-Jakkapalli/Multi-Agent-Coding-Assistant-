# 🤖 Multi-Agent Coding Assistant

An **AI-powered multi-agent coding assistant** that converts natural-language software requirements into functional, multi-file code projects using **LLMs and LangGraph**.

## 🚀 Overview

The system works like an AI software development team. Instead of generating code directly from a single prompt, it uses multiple specialized agents to plan, design, and generate the project.

### Agent Workflow

**User Request → Planner → Architect → Coder → Generated Project**

* **Planner Agent:** Analyzes the user's requirements and creates a development plan.
* **Architect Agent:** Breaks the plan into specific engineering tasks and determines the project structure.
* **Coder Agent:** Generates the required code and writes it into project files.

## ✨ Features

* Convert natural-language requirements into software projects
* Multi-agent workflow using **LangGraph**
* Automated project planning and architecture
* AI-powered multi-file code generation
* Supports generation of web applications and APIs
* Streamlit-based user interface
* Download generated projects for local use

## 🛠️ Tech Stack

* **Language:** Python
* **Agent Framework:** LangGraph
* **AI:** Large Language Models (LLMs)
* **Frontend:** Streamlit
* **Version Control:** Git & GitHub

## 📂 Project Architecture

```text
User Request
     │
     ▼
 Planner Agent
     │
     ▼
Architect Agent
     │
     ▼
  Coder Agent
     │
     ▼
Generated Project
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/multi-agent-coding-assistant.git
cd multi-agent-coding-assistant
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Keys

Create a `.env` file and add the required LLM/API credentials:

```env
API_KEY=your_api_key_here
```

> Do not upload your API keys or `.env` file to GitHub.

### 5. Run the application

```bash
streamlit run app.py
```

Open the Streamlit URL shown in your terminal.

## 💡 Example

### Input

```text
Build a calculator web application with
add, subtract, multiply and divide buttons.
```

### Output

The system analyzes the request, creates a project plan and architecture, and generates the required project files automatically.

## 🎯 Use Cases

* AI-assisted software development
* Rapid application prototyping
* Automated code generation
* Multi-agent AI experimentation
* Learning Agentic AI and LLM application development

## 🔮 Future Improvements

* Add more specialized coding agents
* Support additional programming languages
* Add automated code testing and debugging
* Add code review and optimization agents
* Improve error handling and project validation
* Deploy the application as a cloud-based service

## 👨‍💻 Author

**Akash Jakkapalli**

GitHub: https://github.com/Akash-Jakkapalli
