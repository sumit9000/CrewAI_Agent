# 🤖 CrewAI Autonomous Multi-Agent System

![image](https://github.com/user-attachments/assets/b1713d5c-bddc-4b4d-b11e-9542bb861a5b)


An advanced AI system leveraging **CrewAI** to orchestrate a team of collaborative agents using **LLMs** (OpenAI GPT), **LangChain tools**, and structured workflows to autonomously complete complex tasks like content generation, research, and analysis.

---

## 🚀 Overview

This project demonstrates how to create a **crew** of intelligent agents, each with a defined role, goal, and toolset. Using **CrewAI**, these agents collaborate to complete a shared objective – in this case, writing a technical blog post from scratch based on a user-defined topic.

🧩 Components:
- **Agents**: Specialized personas (e.g., Researcher, Analyst, Writer)
- **Tools**: LangChain-enabled APIs (Wikipedia, SerpAPI, file I/O)
- **LLMs**: GPT-4/GPT-3.5 for reasoning, research & content generation
- **Task Pipeline**: Sequential delegation of tasks among agents

---

## 📸 Preview

### 👥 Agent Collaboration in Action
![image](https://github.com/user-attachments/assets/f1eebc50-fa5e-425b-b1c9-9f863edfd1f7)


> Each agent independently reasons, queries tools, and communicates with others in the crew to fulfill their part of the workflow.

---

## ⚙️ Technical Stack

| Layer | Technology |
|------|-------------|
| 💬 Language Model | OpenAI GPT-4 / GPT-3.5 |
| 🧠 Agent Framework | [CrewAI](https://github.com/joaomdmoura/crewai) |
| 🔗 Orchestration | LangChain |
| 🧰 Tooling | Wikipedia Tool, SerpAPI, File Write Tool |
| 🖥️ Notebook Interface | Jupyter (Python) |
| 📂 Data Handling | LangChain DocumentLoader, Text Splitting |

---

## 🧠 Key Concepts

### 🧑‍💻 Autonomous Agents

Agents are instantiated with:
- **Role**: e.g., "Researcher", "Writer"
- **Goal**: a defined purpose like "gather topic background"
- **Backstory**: context for better prompting
- **Tools**: APIs or utilities the agent can use

### 🔧 Tool-Integrated Reasoning

Agents use LangChain Tools like:
- `WikipediaTool`
- `SerpAPITool`
- `WriteFileTool`

to search, gather, and save information.

### 🔁 Sequential Task Delegation

Tasks are executed in a pipeline:
1. Research Topic ➡️
2. Analyze Insights ➡️
3. Draft Blog ➡️
4. Final Output Saved

---

## 🧪 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/crewai-agent-system.git
   cd crewai-agent-system
2.**Install Dependencies**
```bash
  pip install -r requirements.txt
  OPENAI_API_KEY=your-key
  SERPAPI_API_KEY=your-key
