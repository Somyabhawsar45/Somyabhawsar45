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
- 🎓 Shipped **Scholr**, a full MERN EdTech platform with real payments, CI, and RBAC
- 📰 Built **NewsSync**, a news app with AI-generated perspectives and a TF-IDF recommender
- ⚙️ Comfortable across the stack — React/Tailwind on the frontend, Node/FastAPI on the backend
- 🎯 Actively interviewing for SDE roles — strong in DSA, systems fundamentals, and full stack delivery

📫 **somyabhawsar194@gmail.com**

<br/>

## Tech Stack

<div align="center">

**Languages & Core**
<br/>
<br/>
![Python](https://skillicons.dev/icons?i=python) ![JavaScript](https://skillicons.dev/icons?i=js) ![C++](https://skillicons.dev/icons?i=cpp)
<br/>

**Frontend**
<br/>
<br/>
![React](https://skillicons.dev/icons?i=react) ![Tailwind](https://skillicons.dev/icons?i=tailwind) ![HTML5](https://skillicons.dev/icons?i=html) ![CSS3](https://skillicons.dev/icons?i=css)
<br/>

**Backend & Data**
<br/>
<br/>
![Node](https://skillicons.dev/icons?i=nodejs) ![Express](https://skillicons.dev/icons?i=express) ![FastAPI](https://skillicons.dev/icons?i=fastapi) ![MongoDB](https://skillicons.dev/icons?i=mongodb) ![SQLite](https://skillicons.dev/icons?i=sqlite) ![Redis](https://skillicons.dev/icons?i=redis)
<br/>

**AI / Agentic**
<br/>
<br/>
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1E3A8A?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-1E3A8A?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Tavily](https://img.shields.io/badge/Tavily-1E3A8A?style=for-the-badge)
<br/>

**Payments & Deployment**
<br/>
<br/>
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=for-the-badge&logo=razorpay&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-1E3A8A?style=for-the-badge&logo=render&logoColor=white)
<br/>

**Tooling**
<br/>
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

<br/>

### 🧠 Netra AI — Agentic RAG Chatbot

![LangGraph](https://img.shields.io/badge/LangGraph-1E3A8A?style=flat-square) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-1E3A8A?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Chainlit](https://img.shields.io/badge/Chainlit-1E3A8A?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)

An agentic AI assistant built on **LangGraph's StateGraph**, with multi-step reasoning, tool-calling, and a modular graph architecture separating nodes, tools, RAG pipeline, and LLM state. Ships with full bcrypt-based auth and per-user conversation scoping, plus a second Chainlit UI with tool-call trace visibility and a custom dark theme.

- Stateful LangGraph orchestration with multi-step reasoning and tool-calling, backed by a custom SQLite schema for persistent, user-scoped conversation memory
- FastAPI REST layer (`/chat`, `/search`, `/rag`) — also consumed by Scholr's doubt-solving feature
- FAISS-based RAG with HuggingFace embeddings for PDF Q&A, plus real-time web search via Tavily API
- bcrypt-based auth with per-user isolated sessions — no cross-user data leakage
- Multi-LLM backend support (Groq, OpenAI), using Groq for low-latency inference

**🔗 Live:** [netra-agentic-ai.streamlit.app](https://netra-agentic-ai.streamlit.app) &nbsp;·&nbsp; **📦 Repo:** [Agentic-Chatbot](https://github.com/Somyabhawsar45/Agentic-Chatbot)

<br/>

---

<br/>

### 🎓 Scholr — EdTech Platform

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white) ![Brevo](https://img.shields.io/badge/Brevo-1E3A8A?style=flat-square)

A full-featured EdTech platform for course creation, purchase, and delivery — built MERN-stack with production-grade backend practices rather than stubbed services.

- Role-based access control (Student, Instructor, Admin) via JWT + bcrypt across 10+ RESTful APIs
- Razorpay checkout secured with HMAC-SHA256 webhook verification — tamper-proof, validated by 19 Jest/Supertest integration tests in a GitHub Actions CI pipeline
- Diagnosed a silent SMTP failure and migrated OTP delivery to Brevo's HTTP REST API
- On-demand PDF certificate generation via Puppeteer with unique-ID verification
- Admin analytics dashboard for platform-wide insights
- AI-powered doubt-solving via Netra AI's RAG pipeline, integrated as a FastAPI microservice
- Auto-generated course descriptions using Groq's LLM API (`gpt-oss-20b`)

**🔗 Live:** [schlor.vercel.app](https://schlor.vercel.app) &nbsp;·&nbsp; **API:** [schlor-backend.onrender.com](https://schlor-backend.onrender.com) &nbsp;·&nbsp; **📦 Repo:** [Schlor](https://github.com/Somyabhawsar45/Schlor)

<br/>

---

<br/>

### 📰 NewsSync — AI-Enhanced News App

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

A full-stack news aggregator with AI-generated perspectives, article Q&A, and a recommendation pipeline — React frontend, Node.js/Express backend proxy, and a Python FastAPI TF-IDF recommendation engine, deployed across Vercel + Render.

- "Ask the Article" Q&A and "Other Side" perspective generation using Groq AI, plus real-time summarization
- Time-range Trending Dashboard for surfacing top stories
- 6-hour TTL caching via Upstash Redis, with in-memory fallback and backup key rotation for GNews rate-limit handling
- JWT auth with MongoDB-based bookmarking
- Dark/light mode via CSS variable injection

**🔗 Live:** [newzapp-nine.vercel.app](https://newzapp-nine.vercel.app/) &nbsp;·&nbsp; **📦 Repo:** [Newzapp](https://github.com/Somyabhawsar45/Newzapp)

<br/>
<div align="center">

*Thanks for stopping by — let's build something together.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:0F172A&height=100&section=footer" width="100%"/>

</div>
