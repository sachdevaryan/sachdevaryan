<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=280&section=header&text=Aryan%20Sachdeva&fontSize=60&fontColor=C9B6FF&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Full%20Stack%20%26%20Backend%20Systems&descAlignY=55&descAlign=50" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=B39DFF&center=true&vCenter=true&width=650&lines=Building+scalable+AI+%2B+backend+systems;FastAPI+%7C+Django+%7C+RAG+%7C+LLMs;Chemical+Engineering+%40+IIT+Jodhpur;Turning+ideas+into+production-grade+code" alt="Typing SVG" />
</a>

<br/>

![Education](https://img.shields.io/badge/IIT%20Jodhpur-Chemical%20Engineering-6A0DAD?style=flat-square&logo=googlescholar&logoColor=white)
![CGPA](https://img.shields.io/badge/CGPA-8.03-8A2BE2?style=flat-square&logo=bookstack&logoColor=white)
![Location](https://img.shields.io/badge/Location-Roorkee%2C%20India-4B0082?style=flat-square&logo=mapbox&logoColor=white)

<br/>

<a href="https://my-portfolio-lovat-eight-7suhz2z52h.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-7F00FF?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/aryan-sachdeva-8ba334321/"><img src="https://img.shields.io/badge/LinkedIn-6A0DAD?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:aryan01001s@gmail.com"><img src="https://img.shields.io/badge/Email-5D3FD3?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/sachdevaryan"><img src="https://img.shields.io/badge/GitHub-4B0082?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://leetcode.com/u/Aryan_Sachdeva01/"><img src="https://img.shields.io/badge/LeetCode-9370DB?style=for-the-badge&logo=leetcode&logoColor=white"/></a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=sachdevaryan&color=8a2be2&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/sachdevaryan?style=flat-square&color=7f00ff&label=Followers&logo=github)
![Stars](https://img.shields.io/github/stars/sachdevaryan?style=flat-square&color=6a0dad&label=Stars&logo=github)

</div>

<br/>

## 🪐 About Me

```yaml
name: "Aryan Sachdeva"
role: "AI Engineer @ Reoxide"
education: "B.Tech Chemical Engineering, IIT Jodhpur (2024 – 2028)"
focus:
  - Building production RAG systems and LLM-powered pipelines
  - Designing async, fault-tolerant backend architectures (FastAPI, Celery, Django)
  - Full-stack product engineering with a systems-first mindset
open_to:
  - Software Engineering / AI Engineering internships & full-time roles
  - Open-source collaboration on backend & AI infrastructure
  - Research collaborations in applied ML / NLP
```

I'm an engineering student and AI engineer who enjoys building systems that hold up under real load — async pipelines, hybrid retrieval architectures, and backend services engineered for correctness under failure, not just happy paths. My work spans **LLM-powered workflows**, **retrieval-augmented generation**, and **scalable backend infrastructure**, with a growing focus on shipping products end-to-end rather than isolated prototypes.

<br/>

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Skills](https://skillicons.dev/icons?i=python,c,cpp,js,postgres&theme=dark)

**Backend**

![Skills](https://skillicons.dev/icons?i=django,fastapi,redis,nginx&theme=dark)

**Frontend**

![Skills](https://skillicons.dev/icons?i=react,js,html,css,tailwind&theme=dark)

**Cloud, DevOps & Tooling**

![Skills](https://skillicons.dev/icons?i=docker,aws,git,github,githubactions,vercel&theme=dark)

</div>

<br/>

## 🧠 AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|:---:|---|
| **Retrieval-Augmented Generation (RAG)** | ⭐⭐⭐⭐⭐ | Hybrid FAISS + BM25 retrieval with Reciprocal Rank Fusion, ONNX embeddings |
| **LLM Integration** | ⭐⭐⭐⭐ | Gemini API, Groq streaming inference, LangChain pipelines |
| **Vector Search** | ⭐⭐⭐⭐ | FAISS indexing, 384-dim embeddings, Sentence Transformers |
| **Deep Learning Frameworks** | ⭐⭐⭐⭐ | PyTorch, TensorFlow, Scikit-learn |
| **Applied NLP** | ⭐⭐⭐⭐ | Document chunking, hybrid parsing, token-efficient summarization |

</div>

<br/>

## 🚀 Featured Projects

<details>
<summary><b>🧩 TaskForge — Async Image Processing Platform</b></summary>
<br/>

Async image-processing platform built with FastAPI, Celery, Redis, and PostgreSQL, containerized behind Nginx with Docker Compose and healthcheck-gated startup.

| Stack | Scale | Performance | Security | Impact | Repository |
|---|---|---|---|---|---|
| FastAPI · Celery · Redis · PostgreSQL · Docker · Nginx | 5 containerized services | API responses under 150ms | Idempotency guards, dead-letter recovery | High-priority jobs completed in under 1s despite a 10-job backlog | [TaskForge](https://github.com/sachdevaryan/TaskForge) |

Engineered two isolated Celery priority queues with dedicated worker pools to guarantee SLA-bound processing for high-priority jobs, backed by exponential-backoff retries (1s / 2s / 4s) and idempotency guards to prevent duplicate task delivery under failure conditions.

</details>

<details>
<summary><b>📚 Knowledge Base — Hybrid RAG System</b></summary>
<br/>

Hybrid retrieval-augmented generation system combining FAISS and BM25 with Reciprocal Rank Fusion for high-precision document retrieval over multi-document corpora.

| Stack | Scale | Performance | Security | Impact | Repository |
|---|---|---|---|---|---|
| FastAPI · React · FAISS · BM25 · Groq · ONNX | 8 REST/SSE endpoints | Sub-2s Groq token streaming latency | PDF ingestion validation pipeline | Top-5 chunk retrieval via RRF (k=60) across multi-document corpora | [Knowledge Base](https://github.com/sachdevaryan/rag-system) |

Persisted FAISS indexes using 384-dimensional ONNX embeddings, exposing streaming SSE endpoints for real-time token delivery. Deployed with a React frontend on Vercel and a FastAPI backend on Hugging Face.

</details>

<details>
<summary><b>🏥 PHC Booking System — Healthcare Scheduling Platform</b></summary>
<br/>

React and Django REST Framework healthcare booking platform supporting multi-role slot management, built as a design-credit project at IIT Jodhpur.

| Stack | Scale | Performance | Security | Impact | Repository |
|---|---|---|---|---|---|
| React · Django REST Framework · PostgreSQL · JWT | 3 user roles | Row-level locking for slot integrity | JWT auth, RBAC permission classes, silent token refresh | 10+ secured API endpoints for healthcare scheduling workflows | [PHC Booking System](https://github.com/sachdevaryan/phc_booking_system) |

Architected slot-management workflows with row-level locking to prevent double-booking, and secured all endpoints with JWT authentication, role-based access control, and Axios-based silent token refresh.

</details>

<br/>

## 💼 Experience

**AI Engineer** — Reoxide
`Jul 2026 – Present · Remote`

Working across the AI workflow stack for carbon-report analysis, combining LLM orchestration with large-scale data engineering.

- Reduced LLM token usage by 40% using hybrid text and visual parsing for carbon report analysis
- Built Python scrapers to collect and normalize data from 8,000+ carbon-credit projects

`Python` `Gemini API` `JavaScript` `Supabase`

---

**Assistant Developer** — PHC Booking System, IIT Jodhpur
`Jan 2026 – Apr 2026 · Design Credit Project under Prof. Romi Banerjee`

Built a full-stack healthcare booking platform from architecture through deployment.

- Architected a React + Django REST Framework platform supporting 3 user roles with slot-management workflows and row-level locking
- Secured 10+ API endpoints with JWT authentication, RBAC permission classes, and Axios-based silent token refresh

`React` `Django` `PostgreSQL` `JWT`

<br/>

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🥇 Amazon ML Summer School 2026 | Selected among 3,000 candidates from 134,000+ applicants nationwide |
| 💻 Competitive Programming | Solved 500+ algorithmic problems across LeetCode, Codeforces, and GeeksforGeeks |
| 📘 Academic Excellence | Earned A grades in Data Structures and Machine Learning coursework |

</div>

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sachdevaryan&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=B39DFF&icon_color=8A2BE2&text_color=C9C9C9" width="49%"/>
<img src="https://streak-stats.demolab.com?user=sachdevaryan&theme=tokyonight&hide_border=true&background=0D1117&ring=8A2BE2&fire=B39DFF&currStreakLabel=B39DFF" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sachdevaryan&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=B39DFF&text_color=C9C9C9" width="49%"/>

</div>

<br/>

## 🏅 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=sachdevaryan&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" width="100%"/>

</div>

<br/>

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sachdevaryan&theme=react-dark&hide_border=true&bg_color=0D1117&color=B39DFF&line=8A2BE2&point=C9B6FF" width="100%"/>

</div>

<br/>

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/sachdevaryan/sachdevaryan/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

> Snake animation requires a one-time GitHub Actions workflow — see setup notes below.

<br/>

## 🎯 Current Focus

```yaml
learning:
  - Distributed systems and large-scale retrieval architectures
  - Advanced LLM orchestration and agentic workflows
building:
  - Production-grade RAG and AI infrastructure tooling
  - Fault-tolerant async backend systems
exploring:
  - Vector database internals and hybrid search optimization
  - Applied ML for domain-specific report analysis
open_to:
  - AI Engineering / Software Engineering roles
  - Open-source collaboration
  - Technical discussions on RAG, backend architecture, and system design
```

<br/>

## 📫 Connect With Me

<div align="center">

<a href="mailto:aryan01001s@gmail.com"><img src="https://img.shields.io/badge/Gmail-5D3FD3?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/aryan-sachdeva-8ba334321/"><img src="https://img.shields.io/badge/LinkedIn-6A0DAD?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/sachdevaryan"><img src="https://img.shields.io/badge/GitHub-4B0082?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://my-portfolio-lovat-eight-7suhz2z52h.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-7F00FF?style=for-the-badge&logo=vercel&logoColor=white"/></a>

</div>

<br/>

<div align="center">

*"Systems that survive contact with real load are the only systems worth shipping."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=150&section=footer"/>

</div>
