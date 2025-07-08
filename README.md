# 🧠 AI Agent CLI – LangChain + Claude + Web Tools

A lightweight, command-line AI agent built in Python, designed to explore agentic reasoning and tool use with modern LLMs. This prototype uses **Anthropic's Claude API** as the reasoning engine and leverages **LangChain** to orchestrate interaction with real-world tools like **DuckDuckGo** and **Wikipedia**.

---

## 🚀 Getting Started

### 1. Clone & Set Up

```bash
git clone https://github.com/jsbarton/python_ai_agent.git
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

### 2. Set API Keys

Create a `.env` file or export the following environment variable:

```bash
ANTHROPIC_API_KEY=your_claude_api_key_here
```

No API key is required for DuckDuckGo or Wikipedia tools.

---

## 💬 Usage

```bash
python main.py
```

Then type a query like:

```
> Help me find a recipe for blueberry muffins.
```

---

## 🧱 Tech Stack

* [Anthropic Claude API](https://docs.anthropic.com/)
* [LangChain](https://docs.langchain.com/)
* [DuckDuckGo Search via `langchain_community`](https://python.langchain.com/docs/integrations/tools/ddg/)
* [Wikipedia Search Tool](https://python.langchain.com/docs/integrations/tools/wikipedia/)

---

## 🧪 Status

This is an experimental prototype meant for exploration and learning around LLM agents, tool use, and retrieval-augmented generation. Not intended for production use.

