# Enterprise Agentic RAG System 🚀

## Overview
This project implements a **production-ready Enterprise Agentic Retrieval-Augmented Generation (RAG) system** designed to answer complex questions over internal company documents.

The system combines **LLMs, vector databases, agent orchestration, tool calling, evaluation, and API deployment** to demonstrate how modern GenAI systems can be safely and reliably used in real-world enterprise environments.

This project is built end-to-end with a **production mindset**, including evaluation, observability, and deployment considerations.

---

## Business Problem
Enterprises store critical knowledge across PDFs, documents, and internal files. Traditional keyword search fails to provide:
- Context-aware answers
- Reasoning across multiple documents
- Explainability and traceability

This system enables:
- Intelligent document question answering
- Agent-based reasoning
- Auditable and reproducible AI outputs

---

## Key Features
- 📄 Document ingestion (PDF/Text)
- 🔍 Semantic & hybrid retrieval
- 🧠 Agentic reasoning loop
- 🛠️ Tool-using agents
- 💬 Conversation memory
- 📊 RAG evaluation using RAGAS
- 🌐 FastAPI-based service
- 🐳 Dockerized deployment
- ☁️ Cloud-ready (AWS)

---

## Tech Stack
- **Language:** Python
- **LLMs:** OpenAI-compatible models
- **Agent Framework:** LangChain / LangGraph
- **Vector Database:** Pinecone or Weaviate
- **API:** FastAPI
- **Evaluation:** RAGAS
- **Deployment:** Docker, AWS (lightweight)
- **Logging:** Python logging

---

## Evaluation
The system is evaluated using **RAGAS**, measuring:
- Faithfulness
- Answer relevance
- Context precision
- Context recall

Evaluation results are documented and used to iteratively improve prompts and retrieval strategies.

---

## Deployment
- Containerized using Docker
- Environment-variable based configuration
- Cloud-ready for AWS deployment

---

## Limitations & Future Work
- Authentication & access control
- Advanced observability (metrics, tracing)
- Multi-agent collaboration
- Cost optimization strategies

---

## Demo
🎥 A short demo video (30–60s) showcasing the system in action is included.

---

## Author
Built as part of a focused **Applied AI / GenAI Engineering portfolio** to demonstrate production-ready LLM systems.

