<div align="center">

# Sahil Yuvraj Kamble

### Full-Stack Engineer · AI/RAG Systems · IIT Roorkee '27

Building production-grade web platforms with AI woven into the core — from RAG-based semantic search to real-time collaboration infra. Open to **SDE / Full-Stack / AI Engineer** roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-ten-opal-85.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:sahil.kamble.work@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sahil2448)

</div>

<br>

## About Me

- 🎓 B.Tech, Chemical Engineering @ **IIT Roorkee** (2023–2027) — pivoted into software engineering
- 💻 Focus areas: full-stack web development (React/Next.js + Node.js) and applied AI (RAG pipelines, vector search, LLM integration)
- 💼 Software Development Intern @ **Jivika** — built an internal admin portal (Next.js SSR) for an AI-native hiring platform
- 🌱 Open-source contributor @ [FlowiseAI](https://github.com/FlowiseAI/Flowise) (YC S23, 53k★) — 3 merged PRs
- 🔭 Currently building an ML-driven product intelligence system (CLIP embeddings, vector search, dedup clustering)
- 🏆 Codeforces Specialist · Top 6% on LeetCode Globally · 3★ on CodeChef

<br>

## Featured Projects

### 🗂️ RepoFlow — AI-Powered Git Platform (GitHub Alternative)

<p>
<img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
</p>

A GitHub-style platform built from scratch: custom CLI for version control, AI-powered duplicate-issue detection, and real-time collaboration.

- Architected a full-stack VCS with **23+ REST endpoints** across 4 MongoDB models — repos, issues, commits, notifications
- Built a custom **Git-like CLI** (`init` / `add` / `commit` / `push` / `pull` / `revert`) with local staging, pushing payloads up to 50MB to AWS S3
- Designed a **Gemini + Pinecone RAG pipeline** over issue text to flag semantic duplicates, **cutting manual triage by 40%**
- Built a **Socket.IO** notification layer with private per-user rooms — instant cross-session alerts, zero client-side polling
- Added **WebRTC peer review**: any commit can be reviewed live over a shared video call
- JWT-secured REST API; deployed on AWS Amplify (frontend) + EC2 (backend)

📂 [Repo](https://github.com/sahil2448/RepoFlow) · 🎥 [Demo Video](https://drive.google.com/file/d/1kclURA520SmDoM05o3Skc294tdsIHdTn/view?usp=sharing) · 🔗 [Live App](https://main.d1zjk4pi7u9tt9.amplifyapp.com/)

<br>

### 🛒 SSR E-Commerce Admin Dashboard

<p>
<img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/NextAuth.js-000000?style=flat-square&logo=auth0&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_S3-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white"/>
</p>

A production-grade, server-rendered catalog admin panel with role-based access, AI content generation, and live analytics.

- Built a **server-side rendered** dashboard in **Next.js 16** (App Router + Server Components) with full CRUD for 25+ SKUs, cutting initial load time by **40%**
- Implemented multi-provider auth (Email, GitHub, Google) via **NextAuth.js v5** with **3-tier RBAC** enforced through middleware route protection
- Integrated **AWS S3 presigned URLs** for direct browser-to-S3 image uploads, removing all server bandwidth overhead
- Built an **AI description generator** on OpenRouter with a 3-model fallback chain (LLaMA 3.2, Gemini 2.0 Flash, Phi-3 Mini)
- Shipped a real-time analytics suite (MongoDB aggregations → 4 Recharts dashboards) for 90-day sales and low-stock trends
- Dockerized with multi-stage builds (**75% smaller image**); SSR metadata tuned for AI-crawler and social-share SEO

🔗 [Live Demo](https://ssr-ecommerce-admin-dashboard-bfev.vercel.app/) · 📂 [Repo](https://github.com/sahil2448/ssr-ecommerce-admin-dashboard)

<br>

## Tech Stack

**Languages**
<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
</p>

**Frontend**
<p>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Redux-593D88?style=flat-square&logo=redux&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white"/>
<img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui&logoColor=white"/>
<img src="https://img.shields.io/badge/Material_UI-0081CB?style=flat-square&logo=mui&logoColor=white"/>
<img src="https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black"/>
</p>

**Backend & Databases**
<p>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
<img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
</p>

**AI / ML & Vector Search**
<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenRouter-6C5CE7?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
</p>

**Cloud & DevOps**
<p>
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white"/>
</p>

<br>

## GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=sahil2448&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahil2448&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
<img src="https://streak-stats.demolab.com?user=sahil2448&theme=tokyonight&hide_border=true" />
</div>

<br>

<div align="center">

**Open to full-time SDE / AI Engineer roles — remote or in-office.**
Reach out: [sahil.kamble.work@gmail.com](mailto:sahil.kamble.work@gmail.com) · [Portfolio](https://portfolio-ten-opal-85.vercel.app/)

<img src="https://komarev.com/ghpvc/?username=sahil2448&color=3B82F6&style=flat-square" alt="Profile Views"/>

</div>
