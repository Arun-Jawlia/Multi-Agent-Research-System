# ResearchMind 🔎

**Multi-Agent AI Research System** built with **LangChain, OpenAI, and Streamlit**.

ResearchMind automates the research workflow using specialized AI agents that search the web, extract information, generate reports, and critically review the output.

## 🚀 Features

- 🔎 **Search Agent** — Finds relevant web sources.
- 📖 **Reader Agent** — Extracts useful content from URLs.
- ✍️ **Writer Agent** — Generates structured research reports.
- 🧐 **Critic Agent** — Reviews and evaluates generated reports.
- 🔄 **Multi-Agent Pipeline** — Agents share research state.
- 🖥️ **Streamlit UI** — Simple interface for running research.

## 🏗️ Workflow

```text
User Query
    ↓
Search Agent
    ↓
Reader Agent
    ↓
Writer Agent
    ↓
Critic Agent
    ↓
Research Report
```

## 🛠️ Tech Stack

- Python
- LangChain
- OpenAI
- Streamlit
- Web Search (Tavily)

## ⚙️ Run Locally

```bash
git clone https://github.com/Arun-Jawlia/Multi-Agent-Research-System
cd ResearchMind
pip install -r requirements.txt
```

Create `.env`:

```env
OPENAI_API_KEY=your_api_key
TAVILY_API_KEY=your_tavily_api_key
```

Run:

```bash
streamlit run app.py
```

## 📚 What You'll Learn

- AI Agents vs LLM Chains
- Multi-Agent Architecture
- Web Search & Content Extraction
- Report Generation & Criticism
- Shared Agent State
- Building Agentic AI applications with Streamlit