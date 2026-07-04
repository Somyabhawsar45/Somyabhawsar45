<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F2937,100:111827&height=190&section=header&text=Somya%20Bhawsar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Shipping%20real%20systems,%20not%20demos&descAlignY=55&descSize=17" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=94A3B8&center=true&vCenter=true&width=560&height=45&lines=Building+Netra+AI+%E2%80%94+Agentic+RAG+Chatbot;LangGraph+%2F+Groq+%2F+FAISS;Full+Stack+%7C+MERN+%2B+Python;Shipping+real+systems%2C+not+demos" alt="Typing SVG" />

<br/>

![Academic](https://img.shields.io/badge/E%26TC_Engineering-IET_DAVV_Indore-374151?style=flat-square)
![Location](https://img.shields.io/badge/📍-Indore,_India-374151?style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-374151?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/somya-bhawsar-9230633a3/)
[![Email](https://img.shields.io/badge/Email-Contact-374151?style=flat-square&logo=gmail&logoColor=white)](mailto:somyabhawsar194@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Somyabhawsar45-374151?style=flat-square&logo=github&logoColor=white)](https://github.com/Somyabhawsar45)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Somyabhawsar45&color=374151&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/Somyabhawsar45?style=flat-square&color=374151&label=Followers)

</div>

<br/>

## About

Final-year E&TC Engineering student building **agentic AI systems** and full stack web apps, currently prepping for SDE placements. My flagship project is **Netra AI** — a deployed agentic RAG chatbot built on LangGraph, Groq, and FAISS, with per-user auth, cross-session memory, and four distinct usecases. I like shipping things that are actually deployed and used, not toy demos.

- 🔭 Building **Netra AI** — agentic RAG chatbot, live on Streamlit Community Cloud, plus a Chainlit interface
- 🎓 Also running **Schlor**, a full EdTech platform (MERN), deployed on Vercel + Render
- 🧠 Exploring multi-agent orchestration, ReAct patterns, and RAG evaluation
- 🎯 Actively interviewing for SDE roles — DSA and full stack
- 📫 **somyabhawsar194@gmail.com**

<br/>

## Tech Stack

<div align="center">

**Languages & Core**
<br/>
![Python](https://skillicons.dev/icons?i=python) ![JavaScript](https://skillicons.dev/icons?i=js) ![C++](https://skillicons.dev/icons?i=cpp)

**Frontend**
<br/>
![React](https://skillicons.dev/icons?i=react) ![Tailwind](https://skillicons.dev/icons?i=tailwind) ![HTML5](https://skillicons.dev/icons?i=html) ![CSS3](https://skillicons.dev/icons?i=css)

**Backend & Data**
<br/>
![Node](https://skillicons.dev/icons?i=nodejs) ![Express](https://skillicons.dev/icons?i=express) ![FastAPI](https://skillicons.dev/icons?i=fastapi) ![MongoDB](https://skillicons.dev/icons?i=mongodb) ![SQLite](https://skillicons.dev/icons?i=sqlite) ![Redis](https://skillicons.dev/icons?i=redis)

**AI / Agentic**
<br/>
![LangChain](https://skillicons.dev/icons?i=langchain)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-374151?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)

**Tooling**
<br/>
![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![VSCode](https://skillicons.dev/icons?i=vscode) ![Postman](https://skillicons.dev/icons?i=postman)

</div>

<br/>

## AI / ML Expertise

| Domain | Level | What I've actually built |
|---|---|---|
| **Agentic Orchestration** | Intermediate–Advanced | Designed stateful LangGraph pipelines across 4 distinct usecases (chat, web search, news, PDF), each with its own graph and tool routing |
| **Retrieval-Augmented Generation** | Intermediate–Advanced | Built per-conversation FAISS indexing with `all-MiniLM-L6-v2` embeddings; PDF ingestion → chunking → retrieval → grounded answers |
| **LLM Integration** | Intermediate | Wired Groq for low-latency inference, wrote persona/system-prompt logic, implemented token streaming to the UI |
| **AI-Backed Infra** | Intermediate | FastAPI REST layer (`/chat`, `/search`, `/rag`) in front of the agent graph, bcrypt auth with per-user conversation scoping, SQLite for cross-session memory |
| **Applied ML (web)** | Intermediate | TF-IDF based recommender service (NewsSync) and Groq-driven content generation (perspective summaries, Q&A) layered onto a live app |
| **Deployment** | Intermediate | Shipped and maintained on Streamlit Community Cloud, Chainlit, and Render/Vercel — not just local notebooks |

<br/>

## Featured Projects

<details open>
<summary><b>🧠 Netra AI — Agentic RAG Chatbot</b></summary>
<br/>

An agentic AI assistant built with **LangGraph**, **Groq**, **FAISS**, and **Streamlit**, covering four usecases: Basic Chatbot, Chatbot With Web (Tavily search), AI News, and Chat with PDF. Ships with full bcrypt-based auth and per-user conversation scoping, plus a second Chainlit UI with tool-call trace visibility and a custom dark theme.

**Highlights**
- Stateful LangGraph orchestration with a dedicated graph per usecase
- FastAPI REST layer (`/api/v1/chat`, `/api/v1/search`, `/api/v1/rag`) with streaming responses
- Per-conversation FAISS indexing (`sentence-transformers/all-MiniLM-L6-v2`) for PDF-based Q&A
- bcrypt auth with session-isolated vector indices — no cross-user data leakage
- SQLite-persisted chat history injected directly into `graph.stream()` / `graph.invoke()`, so conversations survive across sessions

**Stack:** LangGraph · Groq · Tavily · FAISS · FastAPI · Streamlit · Chainlit · SQLite

**Live:** [netra-agentic-ai.streamlit.app](https://netra-agentic-ai.streamlit.app) · **Repo:** [Agentic-Chatbot](https://github.com/Somyabhawsar45/Agentic-Chatbot)

</details>

<details>
<summary><b>🎓 Schlor — EdTech Platform</b></summary>
<br/>

A full-featured EdTech platform for course creation, purchase, and delivery — built MERN-stack with production-grade backend practices rather than stubbed services.

**Highlights**
- 19 Jest/Supertest integration tests running in a GitHub Actions CI pipeline
- Razorpay integration for course payments
- Brevo HTTP REST API for OTP email delivery (swapped off SMTP after Render's free tier blocked outbound SMTP)
- RBAC middleware separating student/instructor permissions

**Stack:** React · Node.js · Express · MongoDB · Razorpay · Brevo

**Live:** [schlor.vercel.app](https://schlor.vercel.app) · API: [schlor-backend.onrender.com](https://schlor-backend.onrender.com) · **Repo:** [Schlor](https://github.com/Somyabhawsar45/Schlor)

</details>

<details>
<summary><b>📰 NewsSync — AI-Enhanced News App</b></summary>
<br/>

A news aggregation app with AI-generated perspectives and article Q&A, layered on top of a caching and recommendation pipeline.

**Highlights**
- Groq (LLaMA) powered perspective generation and conversational Q&A on articles
- Redis caching via Upstash to cut redundant API calls
- FastAPI microservice running a TF-IDF based article recommender

**Stack:** JavaScript · GNews API · Redis (Upstash) · Groq · FastAPI

**Repo:** [Newzapp](https://github.com/Somyabhawsar45/Newzapp)

</details>

<br/>

## Current Focus

```yaml
right_now:
  - Interview prep: DSA (DP, binary search, backtracking, concurrency in C++)
  - Core CS: OOP, DBMS, OS, CN — exam-ready depth
  - Polishing Netra AI: dedup display_result.py, adding a test suite

building:
  - Netra AI — deepening RAG eval and multi-agent patterns
  - Schlor — production hardening, RBAC and CI coverage

next_up:
  - RAG evaluation metrics for Netra AI
  - Demo GIFs and portfolio-ready docs for both projects

open_to:
  - SDE / Software Engineering roles
  - AI-ML Engineering roles
```

<br/>

## Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Somyabhawsar45/Somyabhawsar45/output/github-contribution-grid-snake-dark.svg">
  <img alt="snake animation" src="https://raw.githubusercontent.com/Somyabhawsar45/Somyabhawsar45/output/github-contribution-grid-snake.svg">
</picture>

<br/>

## Connect

[![Gmail](https://img.shields.io/badge/Gmail-374151?style=for-the-badge&logo=gmail&logoColor=white)](mailto:somyabhawsar194@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-374151?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/somya-bhawsar-9230633a3/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Somyabhawsar45)

<br/>

<div align="center">

*"Building thoughtful systems, one commit at a time."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F2937,100:111827&height=90&section=footer" width="100%"/>

</div>
