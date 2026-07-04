<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:0F172A&height=190&section=header&text=Somya%20Bhawsar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Shipping%20real%20systems,%20not%20demos&descAlignY=55&descSize=17" width="100%"/>

<br/>

**Full Stack Developer &nbsp;·&nbsp; Agentic AI (LangGraph / Groq / FAISS) &nbsp;·&nbsp; MERN**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-1E3A8A?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/somya-bhawsar-9230633a3/)
[![Gmail](https://img.shields.io/badge/Gmail-1E3A8A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:somyabhawsar194@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-1E3A8A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Somyabhawsar45)

</div>
<br/>

## About

Final-year E&TC Engineering student building agentic AI systems and full stack web apps, currently prepping for SDE placements. I care more about shipping deployed, working software than portfolio filler — every project below is live, not a local demo.

- 🧠 Built **Netra AI**, an agentic RAG chatbot on LangGraph, Groq, and FAISS with per-user auth and cross-session memory
- 🎓 Shipped **Schlor**, a full MERN EdTech platform with real payments, CI, and RBAC
- 📰 Built **NewsSync**, a news app with AI-generated perspectives and a TF-IDF recommender
- ⚙️ Comfortable across the stack — React/Tailwind on the frontend, Node/FastAPI on the backend
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

## What I Work With

- **Agentic Systems** — Designing multi-step, tool-using AI workflows with stateful orchestration and conditional routing
- **RAG Pipelines** — Building retrieval systems end-to-end, from embedding generation to grounded, source-backed responses
- **LLM Integration** — Working with inference APIs for low-latency responses, prompt/persona design, and streaming output
- **Applied ML** — Shipping recommendation engines and content-generation features in live products, not just notebooks

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

<div align="center">

*Thanks for stopping by — let's build something together.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:0F172A&height=100&section=footer" width="100%"/>

</div>
