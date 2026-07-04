<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:0F172A&height=190&section=header&text=Somya%20Bhawsar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Shipping%20real%20systems,%20not%20demos&descAlignY=55&descSize=17" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=800&color=60A5FA&center=true&vCenter=true&width=650&height=45&lines=Full+Stack+Developer;LangGraph+%2F+Groq+%2F+FAISS;MERN+%2B+Python;Shipping+real+systems%2C+not+demos" alt="Typing SVG" />

<br/>

![Academic](https://img.shields.io/badge/E%26TC_Engineering-IET_DAVV_Indore-1E3A8A?style=flat-square)
![Location](https://img.shields.io/badge/📍-Indore,_India-1E3A8A?style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-1E3A8A?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/somya-bhawsar-9230633a3/)
[![Email](https://img.shields.io/badge/Email-Contact-1E3A8A?style=flat-square&logo=gmail&logoColor=white)](mailto:somyabhawsar194@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Somyabhawsar45-1E3A8A?style=flat-square&logo=github&logoColor=white)](https://github.com/Somyabhawsar45)

</div>

<br/>

## About

Final-year E&TC Engineering student building agentic AI systems and full stack web apps, currently prepping for SDE placements. I care more about shipping deployed, working software than portfolio filler — every project below is live, not a local demo.

- 🧠 Built **Netra AI**, an agentic RAG chatbot on LangGraph, Groq, and FAISS with per-user auth and cross-session memory
- 🎓 Shipped **Schlor**, a full MERN EdTech platform with real payments, CI, and RBAC
- 📰 Built **NewsSync**, a news app with AI-generated perspectives and a TF-IDF recommender
- ⚙️ Comfortable across the stack — React/Tailwind on the frontend, Node/FastAPI on the backend
- 🔍 Exploring multi-agent orchestration, ReAct patterns, and RAG evaluation
- 🎯 Actively interviewing for SDE roles — strong in DSA, systems fundamentals, and full stack delivery

📫 **somyabhawsar194@gmail.com**

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
![FAISS](https://img.shields.io/badge/FAISS-1E3A8A?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1E3A8A?style=for-the-badge)

**Tooling**
<br/>
![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![VSCode](https://skillicons.dev/icons?i=vscode) ![Postman](https://skillicons.dev/icons?i=postman)

</div>

<br/>

## AI / ML Expertise

- **Agentic Orchestration** — Stateful LangGraph pipelines across 4 usecases, each with its own graph and tool routing
- **RAG** — Per-conversation FAISS indexing with `all-MiniLM-L6-v2` embeddings; PDF ingestion → chunking → retrieval → grounded answers
- **LLM Integration** — Groq for low-latency inference, persona/system-prompt design, token streaming to the UI
- **AI-Backed Infra** — FastAPI layer in front of the agent graph, bcrypt auth with per-user scoping, SQLite cross-session memory
- **Applied ML** — TF-IDF recommender and Groq-driven content generation shipped in a live app, not a notebook

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

**Live:** [newzapp-nine.vercel.app](https://newzapp-nine.vercel.app/) · **Repo:** [Newzapp](https://github.com/Somyabhawsar45/Newzapp)

</details>

<br/>

## Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Somyabhawsar45/Somyabhawsar45/output/github-contribution-grid-snake-dark.svg">
  <img alt="snake animation" src="https://raw.githubusercontent.com/Somyabhawsar45/Somyabhawsar45/output/github-contribution-grid-snake.svg">
</picture>

<br/>

<div align="center">

### Let's build something

<a href="mailto:somyabhawsar194@gmail.com"><img src="https://img.shields.io/badge/Email-somyabhawsar194%40gmail.com-1E3A8A?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0F172A"/></a>
<a href="https://www.linkedin.com/in/somya-bhawsar-9230633a3/"><img src="https://img.shields.io/badge/LinkedIn-Somya_Bhawsar-1E3A8A?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0F172A"/></a>
<a href="https://github.com/Somyabhawsar45"><img src="https://img.shields.io/badge/GitHub-Somyabhawsar45-1E3A8A?style=for-the-badge&logo=github&logoColor=white&labelColor=0F172A"/></a>

<br/><br/>

*Building thoughtful systems, one commit at a time.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:0F172A&height=100&section=footer" width="100%"/>

</div>
