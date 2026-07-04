<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=190&section=header&text=Somya%20Bhawsar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Agentic%20AI%20%7C%20Full%20Stack%20Engineering&descAlignY=55&descSize=17" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=560&height=45&lines=Building+Netra+AI+%E2%80%94+Agentic+RAG+Chatbot;LangGraph+%2F+Groq+%2F+FAISS;Full+Stack+%7C+MERN+%2B+Python;Shipping+real+systems%2C+not+demos" alt="Typing SVG" />

<br/>

![Academic](https://img.shields.io/badge/E%26TC_Engineering-IET_DAVV_Indore-6D28D9?style=flat-square)
![Location](https://img.shields.io/badge/📍-Indore,_India-6D28D9?style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-6D28D9?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/somya-bhawsar-9230633a3/)
[![Email](https://img.shields.io/badge/Email-Contact-6D28D9?style=flat-square&logo=gmail&logoColor=white)](mailto:somyabhawsar194@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Somyabhawsar45-6D28D9?style=flat-square&logo=github&logoColor=white)](https://github.com/Somyabhawsar45)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Somyabhawsar45&color=6D28D9&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/Somyabhawsar45?style=flat-square&color=6D28D9&label=Followers)

</div>

<br/>

## About

Final-year E&TC Engineering student building **agentic AI systems** and full stack web apps, currently prepping for SDE placements. My flagship project is **Netra AI** — a deployed agentic RAG chatbot built on LangGraph, Groq, and FAISS, with per-user auth, cross-session memory, and four distinct usecases. I like shipping things that are actually deployed and used, not toy demos.

- 🔭 Building **Netra AI** — agentic RAG chatbot, live on Streamlit Community Cloud, plus a Chainlit interface
- 🎓 Also running **Schlor**, a full EdTech platform (MERN), deployed on Vercel + Render
- 🧠 Exploring multi-agent orchestration, ReAct patterns, and RAG evaluation
- 🎯 Actively interviewing for SDE roles — DSA, systems design, and full stack
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
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)

**Tooling**
<br/>
![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![VSCode](https://skillicons.dev/icons?i=vscode) ![Postman](https://skillicons.dev/icons?i=postman)

</div>

<br/>

## AI / ML Expertise

| Domain | Level | Details |
|---|---|---|
| **Agentic Orchestration** | Intermediate–Advanced | LangGraph stateful graphs, ReAct patterns, multi-turn flows across 4 usecases |
| **Retrieval-Augmented Generation** | Intermediate–Advanced | FAISS vector search, `all-MiniLM-L6-v2` embeddings, per-conversation indexing, PDF RAG |
| **LLM Integration** | Intermediate | Groq API for low-latency inference, persona/system-prompt design, streaming responses |
| **Backend for AI** | Intermediate | FastAPI REST layer (`/chat`, `/search`, `/rag`), SQLite-backed cross-session memory, bcrypt auth |
| **Deployment** | Intermediate | Streamlit Community Cloud, Chainlit UI, Render/Vercel full stack deploys |

<br/>

## Featured Projects

<details open>
<summary><b>🧠 Netra AI — Agentic RAG Chatbot</b></summary>
<br/>

An agentic AI assistant built with **LangGraph**, **Groq**, **FAISS**, and **Streamlit**, covering four usecases: Basic Chatbot, Chatbot With Web (Tavily search), AI News, and Chat with PDF. Ships with full bcrypt-based auth and per-user conversation scoping, plus a second Chainlit UI with tool-call trace visibility and a custom dark theme.

| Aspect | Details |
|---|---|
| **Stack** | LangGraph · Groq · Tavily · FAISS · FastAPI · Streamlit · Chainlit · SQLite |
| **Architecture** | Stateful LangGraph orchestration, FastAPI REST layer (`/api/v1/chat`, `/api/v1/search`, `/api/v1/rag`), streaming responses |
| **Retrieval** | Per-conversation FAISS indexing with `sentence-transformers/all-MiniLM-L6-v2`, PDF-based Q&A |
| **Auth & Security** | bcrypt password hashing, per-user conversation scoping, session-isolated vector indices |
| **Memory** | SQLite-persisted chat history injected directly into `graph.stream()` / `graph.invoke()` — conversations survive across sessions |
| **Live** | [netra-agentic-ai.streamlit.app](https://netra-agentic-ai.streamlit.app) |
| **Repository** | [github.com/Somyabhawsar45/Agentic-Chatbot](https://github.com/Somyabhawsar45/Agentic-Chatbot) |

</details>

<details>
<summary><b>🎓 Schlor — EdTech Platform</b></summary>
<br/>

A full-featured EdTech platform for course creation, purchase, and delivery — built MERN-stack with a production-grade backend: CI pipeline, integration tests, and real payment/email infra rather than stubbed services.

| Aspect | Details |
|---|---|
| **Stack** | React · Node.js · Express · MongoDB · Razorpay · Brevo (email API) |
| **Testing & CI** | 19 Jest/Supertest integration tests, GitHub Actions CI pipeline |
| **Payments** | Razorpay integration for course purchases |
| **Email** | Brevo HTTP REST API for OTP delivery (swapped off SMTP after Render's free tier blocked it) |
| **Access Control** | RBAC middleware for student/instructor roles |
| **Live** | [schlor.vercel.app](https://schlor.vercel.app) · API: [schlor-backend.onrender.com](https://schlor-backend.onrender.com) |
| **Repository** | [github.com/Somyabhawsar45/Schlor](https://github.com/Somyabhawsar45/Schlor) |

</details>

<details>
<summary><b>📰 NewsSync — AI-Enhanced News App</b></summary>
<br/>

A news aggregation app with AI-generated perspectives and article Q&A, layered on top of a caching and recommendation pipeline.

| Aspect | Details |
|---|---|
| **Stack** | JavaScript · GNews API · Redis (Upstash) · Groq (LLaMA) · FastAPI |
| **AI Features** | Groq-powered perspective generation on articles, conversational article Q&A |
| **Performance** | Redis caching via Upstash to cut redundant API calls |
| **Recommendations** | FastAPI microservice running a TF-IDF based recommender |
| **Repository** | [github.com/Somyabhawsar45/Newzapp](https://github.com/Somyabhawsar45/Newzapp) |

</details>

<br/>

## Experience

<!-- ✏️ Placeholder — add real internship/job details here once available -->
_No professional experience listed yet — actively interviewing for SDE roles._

<br/>

## Achievements

<!-- ✏️ Add real achievements here as they happen (no fabricated entries) -->
<div align="center">

| Recognition | Details |
|---|---|
| _Add here_ | _e.g. hackathon results, OA clears, contest ranks_ |

</div>

<br/>

## Certifications

<!-- ✏️ Add real certs — remove providers you have none from -->
_None added yet._

<br/>

## Coding Profiles

<!-- ✏️ Replace # with your real profile URLs -->
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](#)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](#)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](#)

<br/>

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats-fast-nine.vercel.app/api?username=Somyabhawsar45&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=A78BFA" width="48%"/>
<img src="https://github-readme-streak-stats-eight.vercel.app/?user=Somyabhawsar45&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA" width="48%"/>

<img src="https://github-readme-stats-fast-nine.vercel.app/api/top-langs/?username=Somyabhawsar45&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA" width="48%"/>

</div>

<br/>

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Somyabhawsar45&theme=algolia&no-frame=true&column=7&margin-w=8" width="100%"/>

</div>

<br/>

## Contribution Activity

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Somyabhawsar45&theme=react-dark&hide_border=true&bg_color=0D1117&color=A78BFA&line=A78BFA&point=ffffff" width="100%"/>

<br/>

## Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Somyabhawsar45/Somyabhawsar45/output/github-contribution-grid-snake-dark.svg">
  <img alt="snake animation" src="https://raw.githubusercontent.com/Somyabhawsar45/Somyabhawsar45/output/github-contribution-grid-snake.svg">
</picture>

<br/>

## Current Focus

```yaml
learning:   ["Multi-agent orchestration", "RAG evaluation metrics", "System design for SDE interviews"]
building:   ["Netra AI (agentic RAG chatbot)", "Schlor (EdTech platform)"]
exploring:  ["LangGraph ReAct patterns", "Vector search optimization", "Advanced DSA (DP, concurrency)"]
open_to:    ["SDE / Software Engineering roles", "AI-ML Engineering roles", "Open source collaboration"]
```

<br/>

## Connect

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:somyabhawsar194@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/somya-bhawsar-9230633a3/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Somyabhawsar45)

<br/>

<div align="center">

*"Building thoughtful systems, one commit at a time."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=90&section=footer" width="100%"/>

</div>
