# buddy-ide
# CoderBuddy AI 🤖💻
> A specialized AI companion designed to streamline the web development workflow by bridging the gap between natural language requirements and production-ready code.

---

## 🌟 Overview
CoderBuddy AI is an intelligent development assistant that goes beyond simple code completion. It understands project context, assists in architectural decisions, and helps developers build full-stack applications from scratch. This project was developed as an engineering initiative to explore the intersection of **Large Language Models (LLMs)** and **Integrated Development Environments (IDEs)**.

## 🚀 Key Features
* **Context-Aware Coding:** Uses RAG (Retrieval-Augmented Generation) to understand your existing codebase.
* **Boilerplate Generation:** Instantly scaffolds React/Next.js components and FastAPI backends.
* **Visual Debugger:** (Planned) Multimodal support to analyze UI/UX screenshots and suggest CSS fixes.
* **Natural Language to Code:** Translate complex logic requirements into clean, PEP-8 or Airbnb-standard code.

## 🛠️ Tech Stack
| Layer | Technology |
| :--- | :--- |
| **Frontend** | React.js, Monaco Editor (VS Code Engine), Tailwind CSS |
| **Backend** | Python, FastAPI |
| **AI Engine** | Gemini 1.5 Pro / DeepSeek-Coder (via API or Ollama) |
| **Orchestration** | LangChain / LangGraph |
| **Database** | ChromaDB (Vector Store for code context) |

---

## 📂 Project Structure
```text
├── backend/           # FastAPI server & AI logic
│   ├── engine/        # LLM prompts and RAG implementation
│   └── main.py        # API endpoints
├── frontend/          # React-based IDE interface
│   ├── src/           # Components & State management
│   └── public/        # Static assets
└── docs/              # System architecture & Research notes
