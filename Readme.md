<div align="center">

<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Space+Grotesk&weight=700&size=34&duration=600&pause=1000&color=f6fcf5&center=true&vCenter=true&width=650&height=55&repeat=false&lines=Hi+%F0%9F%91%8B%2C+I'm+Sahil+Yuvraj+Kamble!" alt="Sahil Yuvraj Kamble" />

<img src="https://readme-typing-svg.demolab.com/?font=Space+Grotesk&weight=600&size=18&duration=500&pause=1000&color=11d6c9&center=true&vCenter=true&width=650&height=30&repeat=false&lines=Applied+AI+Software+Engineer+%7C+Aspiring+Forward+Deployed+Engineer" alt="Applied AI Software Engineer | Aspiring Forward Deployed Engineer" />

[Portfolio](https://portfolio-ten-opal-85.vercel.app/) &nbsp;|&nbsp; [sahil.kamble.work@gmail.com](mailto:sahil.kamble.work@gmail.com) &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/sahil-kamble-43b3ba279/)

</div>
</div>

<br>

## About

I build full-stack products with applied AI at the core: RAG pipelines, agentic systems with LangChain and LangGraph, and the web infrastructure around them. I like owning a feature end to end, from the database schema to the deployed UI.

| | |
|:--|:--|
| **Experience** | 💼 Software Development Intern at **Jivika**, an AI-native hiring platform. Optimized features on the company's internal admin portal (Next.js, Node.js). |
| **Open source** | 🌱 Contributor to [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise) (YC S23, 53k stars). Several PRs merged. |
| **Problem solving** | 🏆 Specialist on Codeforces · Top 6% globally on LeetCode · 3-star on CodeChef |
| **Currently** | 🎓 Building Reliable, High performance agentic software systems | Persuing Bachelors Degree at IIT Roorkee

🎓 B.Tech at IIT Roorkee (2023–2027)
💻 Focus areas: Software Engineering with applied AI — agentic AI systems (Langchain & LangGraph)
💼 Software Development Intern @ Jivika — optimized features on companies internal admin portal (Next.js, Node.js) for an AI-native hiring platform
🌱 Open-source contributor @ FlowiseAI (YC S23, 53k★) — Several PRs Merged
🏆 Specialist on Codeforces
🏆 Top 6% on LeetCode Globally
🏆 3★ on CodeChef


<br>

## Featured Projects

### RepoFlow: AI-Powered Version Control

<img src="https://img.shields.io/badge/React_19-0F172A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=3178C6"/> <img src="https://img.shields.io/badge/Node.js-0F172A?style=flat-square&logo=nodedotjs&logoColor=339933"/> <img src="https://img.shields.io/badge/MongoDB-0F172A?style=flat-square&logo=mongodb&logoColor=47A248"/> <img src="https://img.shields.io/badge/Socket.IO-0F172A?style=flat-square&logo=socketdotio&logoColor=white"/> <img src="https://img.shields.io/badge/Gemini-0F172A?style=flat-square&logo=googlegemini&logoColor=8E75B2"/> <img src="https://img.shields.io/badge/Pinecone-0F172A?style=flat-square&logo=pinecone&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-0F172A?style=flat-square&logo=amazonaws&logoColor=FF9900"/>

A GitHub-style platform built from scratch, with a custom CLI for version control, AI-powered duplicate issue detection, and real-time collaboration.

- Architected a full-stack VCS with **35 REST endpoints** across 4 MongoDB models: repos, issues, commits, notifications
- Built a Git-like CLI (`init`, `add`, `commit`, `push`, `pull`, `revert`) with local staging and payloads up to 50 MB pushed to AWS S3
- Designed a **Gemini + Pinecone RAG pipeline** over issue text to flag semantic duplicates, **cutting manual triage by 40%**
- Built a Socket.IO notification layer with private per-user rooms for instant cross-session alerts and zero client-side polling
- Added WebRTC peer review so any commit can be reviewed live over a shared video call
- JWT-secured API, deployed on AWS Amplify (frontend) and EC2 (backend)

<a href="https://github.com/sahil2448/RepoFlow"><img src="https://img.shields.io/badge/Repo-0F172A?style=flat-square&logo=github&logoColor=white"/></a> <a href="https://drive.google.com/file/d/1-U3LDvXbia_8QtzZlOFRlFdBKYkE7OMW/view?usp=drive_link"><img src="https://img.shields.io/badge/Demo_Video-2563EB?style=flat-square"/></a> <a href="https://main.d1zjk4pi7u9tt9.amplifyapp.com/"><img src="https://img.shields.io/badge/Live_App-2563EB?style=flat-square"/></a>

<br>

### SSR E-Commerce Admin Dashboard

<img src="https://img.shields.io/badge/Next.js_16-0F172A?style=flat-square&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=3178C6"/> <img src="https://img.shields.io/badge/MongoDB-0F172A?style=flat-square&logo=mongodb&logoColor=47A248"/> <img src="https://img.shields.io/badge/NextAuth.js-0F172A?style=flat-square&logo=auth0&logoColor=white"/> <img src="https://img.shields.io/badge/AWS_S3-0F172A?style=flat-square&logo=amazons3&logoColor=FF9900"/> <img src="https://img.shields.io/badge/Docker-0F172A?style=flat-square&logo=docker&logoColor=2496ED"/> <img src="https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38B2AC"/>

A production-grade, server-rendered catalog admin panel with role-based access, AI content generation, and live analytics.

- Built a server-side rendered dashboard in **Next.js 16** (App Router, Server Components) with full CRUD for 25+ SKUs, cutting initial load time by **40%**
- Implemented multi-provider auth (Email, GitHub, Google) with **NextAuth.js v5** and **3-tier RBAC** enforced in middleware
- Used **AWS S3 presigned URLs** for direct browser-to-S3 image uploads, removing server bandwidth overhead
- Built an AI description generator on OpenRouter with a 3-model fallback chain (LLaMA 3.2, Gemini 2.0 Flash, Phi-3 Mini)
- Shipped a real-time analytics suite (MongoDB aggregations feeding 4 Recharts dashboards) for 90-day sales and low-stock trends
- Dockerized with multi-stage builds for a **75% smaller image**, with SSR metadata tuned for AI-crawler and social-share SEO

<a href="https://github.com/sahil2448/ssr-ecommerce-admin-dashboard"><img src="https://img.shields.io/badge/Repo-0F172A?style=flat-square&logo=github&logoColor=white"/></a> <a href="https://ssr-ecommerce-admin-dashboard-bfev.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-2563EB?style=flat-square"/></a>

<br>

## Tech Stack

| | |
|:--|:--|
| **Languages** | <img src="https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=3178C6"/> <img src="https://img.shields.io/badge/JavaScript-0F172A?style=flat-square&logo=javascript&logoColor=F7DF1E"/> <img src="https://img.shields.io/badge/Java-0F172A?style=flat-square&logo=openjdk&logoColor=ED8B00"/> <img src="https://img.shields.io/badge/C++-0F172A?style=flat-square&logo=cplusplus&logoColor=00599C"/> <img src="https://img.shields.io/badge/Python-0F172A?style=flat-square&logo=python&logoColor=3776AB"/> |
| **Frontend** | <img src="https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/Next.js-0F172A?style=flat-square&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/Redux-0F172A?style=flat-square&logo=redux&logoColor=764ABC"/> <img src="https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38B2AC"/> <img src="https://img.shields.io/badge/shadcn/ui-0F172A?style=flat-square&logo=shadcnui&logoColor=white"/> <img src="https://img.shields.io/badge/Material_UI-0F172A?style=flat-square&logo=mui&logoColor=007FFF"/> <img src="https://img.shields.io/badge/GSAP-0F172A?style=flat-square&logo=greensock&logoColor=88CE02"/> |
| **Backend and Data** | <img src="https://img.shields.io/badge/Node.js-0F172A?style=flat-square&logo=nodedotjs&logoColor=339933"/> <img src="https://img.shields.io/badge/Express-0F172A?style=flat-square&logo=express&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-0F172A?style=flat-square&logo=mongodb&logoColor=47A248"/> <img src="https://img.shields.io/badge/PostgreSQL-0F172A?style=flat-square&logo=postgresql&logoColor=4169E1"/> <img src="https://img.shields.io/badge/Prisma-0F172A?style=flat-square&logo=prisma&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-0F172A?style=flat-square&logo=firebase&logoColor=FFCA28"/> <img src="https://img.shields.io/badge/Socket.IO-0F172A?style=flat-square&logo=socketdotio&logoColor=white"/> |
| **AI and Agents** | <img src="https://img.shields.io/badge/LangChain-0F172A?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/LangGraph-0F172A?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/Gemini-0F172A?style=flat-square&logo=googlegemini&logoColor=8E75B2"/> <img src="https://img.shields.io/badge/Pinecone-0F172A?style=flat-square&logo=pinecone&logoColor=white"/> <img src="https://img.shields.io/badge/OpenRouter-0F172A?style=flat-square&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-0F172A?style=flat-square&logo=pytorch&logoColor=EE4C2C"/> |
| **Cloud and Tools** | <img src="https://img.shields.io/badge/AWS-0F172A?style=flat-square&logo=amazonaws&logoColor=FF9900"/> <img src="https://img.shields.io/badge/Docker-0F172A?style=flat-square&logo=docker&logoColor=2496ED"/> <img src="https://img.shields.io/badge/Vercel-0F172A?style=flat-square&logo=vercel&logoColor=white"/> <img src="https://img.shields.io/badge/Git-0F172A?style=flat-square&logo=git&logoColor=F05032"/> <img src="https://img.shields.io/badge/VS_Code-0F172A?style=flat-square&logo=visualstudiocode&logoColor=007ACC"/> |

<br>

## GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=sahil2448&show_icons=true&theme=transparent&hide_border=true&count_private=true&title_color=60A5FA&icon_color=60A5FA&text_color=CBD5E1">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=sahil2448&show_icons=true&theme=transparent&hide_border=true&count_private=true&title_color=2563EB&icon_color=2563EB&text_color=334155">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=sahil2448&layout=compact&theme=transparent&hide_border=true&title_color=60A5FA&text_color=CBD5E1">
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahil2448&layout=compact&theme=transparent&hide_border=true&title_color=2563EB&text_color=334155">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=sahil2448&theme=transparent&hide_border=true&ring=60A5FA&fire=60A5FA&currStreakLabel=60A5FA&sideLabels=CBD5E1&currStreakNum=CBD5E1&sideNums=CBD5E1&dates=94A3B8">
  <img alt="Contribution streak" src="https://streak-stats.demolab.com?user=sahil2448&theme=transparent&hide_border=true&ring=2563EB&fire=2563EB&currStreakLabel=2563EB&sideLabels=334155&currStreakNum=334155&sideNums=334155&dates=64748B">
</picture>

</div>

<br>

<div align="center">

**Open to full-time Applied AI Software Engineering and Applied AI Full-Stack Engineering roles, remote or in-office.**

[Portfolio](https://portfolio-ten-opal-85.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/sahil-kamble-43b3ba279/) · [sahil.kamble.work@gmail.com](mailto:sahil.kamble.work@gmail.com)

</div>
