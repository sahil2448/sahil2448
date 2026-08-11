<!-- Sahil Yuvraj Kamble | Developer Portfolio -->

<div align="center">

<!-- Animated Header -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=1000&size=32&pause=50&color=26ec50&center=true&vCenter=true&random=false&width=1000&lines=Hi+%F0%9F%91%8B%2C+I'm+Sahil+Yuvraj+Kamble!;Full-Stack+AI+Engineer+%7C+Problem+Solver;4th+Year+%40+IIT+Roorkee+%F0%9F%8F%9B%EF%B8%8F;Building+Products+That+Matter+%F0%9F%9A%80" alt="Typing SVG" />

</div>
<br>

---

## 👨‍💻 About Me

I'm a Chemical Engineering undergraduate at **IIT Roorkee** (Class of 2027) who pivoted into software engineering, with a focus on **Applied AI Software Engineering**. I enjoy building products end-to-end — from REST APIs and real-time infrastructure to AI-powered features — and I'm currently looking for full-time SDE / AI Engineer roles.

- 🎓 **B.Tech, Chemical Engineering** — IIT Roorkee (2023 – 2027)
- 💼 **Software Development Intern** @ Jivika (AI-Native Hiring Platform)
- 🌱 **Open-source contributor** @ [FlowiseAI](https://github.com/FlowiseAI/Flowise) (YC S23) — 3 merged PRs on a 53k+ ⭐ repo
- 🏆 **Specialist** on Codeforces.
- 🏆 **Top 6%** on LeetCode Globaly· 
- 🏆 **3 Star** on Codechef.
- 💼 **Portfolio** : https://portfolio-ten-opal-85.vercel.app/
- 💼 **Email** : sahil.kamble.work@gmail.com
---

## 🚀 Featured Projects

### 🗂️ RepoFlow — AI Powered Version Control System (Github Alternative)

<p>
  <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" alt="Socket.io"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
</p>

A GitHub-style platform built from scratch with a custom CLI for version control, an AI-powered duplicate-issue detector, and real-time collaboration.

- Architected a full-stack VCS platform with **23+ REST API endpoints** across **4 MongoDB models**, covering repositories, issues, commits, and notifications.
- Built a custom **Git-like CLI** (`init`, `add`, `commit`, `push`, `pull`, `revert`) with local staging and UUID-based commit versioning, pushing payloads up to **50MB** to AWS S3 with automatic MongoDB fallback.
- Developed a **WebRTC - Peer Review** feature where every commit can be reviewed instantly by sharing real time video meet link with teammate or a manager etc.  
- Designed a **Gemini + Pinecone RAG pipeline** that embeds issue text (768-dim, title-weighted) to flag semantic duplicates above a 0.82 cosine-similarity threshold, **cutting manual triage by 40%**.
- Engineered a **Socket.IO** notification layer with private per-user rooms, delivering instant cross-session alerts for stars, follows, and issue activity — eliminating client-side polling entirely.
- Implemented secure **JWT authentication** and React/TypeScript workflows for repo CRUD, starring, following, and a GitHub-style contribution heatmap, **improving state sync speed by 35%**.
- Deployed frontend  on AWS Amplify with environment-based configuration, and backend on EC2 Instance, shipping a fully working live demo.
📂 [Repository](https://github.com/sahil2448/RepoFlow)·&nbsp;
🔗 [Live Video Demo](https://drive.google.com/file/d/1kclURA520SmDoM05o3Skc294tdsIHdTn/view?usp=sharing) &nbsp;
🔗 [Live Deployed URL (AWS-Amplify)](https://main.d1zjk4pi7u9tt9.amplifyapp.com/) &nbsp;·&nbsp; 

<br>

### 🛒 SSR E-Commerce Admin Dashboard

<p>
  <img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/NextAuth.js-000000?style=for-the-badge&logo=auth0&logoColor=white" alt="NextAuth"/>
  <img src="https://img.shields.io/badge/AWS_S3-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS S3"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind"/>
</p>

A production-grade, server-rendered admin dashboard for managing an e-commerce catalog with role-based access, AI content generation, and live analytics.

- Built a **server-side rendered** dashboard in **Next.js 16** (App Router + Server Components) with full CRUD for **25+ SKUs**, cutting initial load time by **40%**.
- Implemented multi-provider auth (Email/Password, GitHub OAuth, Google OAuth) via **NextAuth.js v5** with a **3-tier RBAC** system (Admin/Editor/Viewer) enforced through middleware-based route protection and JWT sessions.
- Designed a **3-step product creation wizard** (Basic Info → Pricing & Stock → Images) with **Zod** validation and React Hook Form, backed by a paginated, searchable product table.
- Integrated **AWS S3 presigned URLs** for direct browser-to-S3 image uploads (up to 8 images/product) with automatic cleanup on deletion — removing server bandwidth overhead.
- Built an **AI description generator** via the OpenRouter API with a 3-model fallback chain (LLaMA 3.2, Gemini 2.0 Flash, Phi-3 Mini), plus a real-time analytics suite using MongoDB aggregations powering **4 Recharts dashboards** for 90-day sales and low-stock trends.
- Authored a database seeding script generating 25 sample products and 90 days of order data for realistic demo/testing.
- Optimized SEO of web application for Bots as well as AI Crawlers.

🔗 [Live Demo](https://ssr-ecommerce-admin-dashboard-bfev.vercel.app/) &nbsp;·&nbsp; 📂 [Repository](https://github.com/sahil2448/ssr-ecommerce-admin-dashboard)

---

## 🛠️ Technical Skills

<div align="center">

### **Frontend Development**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" alt="Redux"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

### **Styling & UI Libraries**

<p>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind"/>
  <img src="https://img.shields.io/badge/Material_UI-0081CB?style=for-the-badge&logo=mui&logoColor=white" alt="MUI"/>
  <img src="https://img.shields.io/badge/Shadcn/UI-000000?style=for-the-badge&logo=shadcnui&logoColor=white" alt="ShadCN"/>
  <img src="https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white" alt="DaisyUI"/>
  <img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black" alt="GSAP"/>
</p>

### **Backend & Databases**

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
</p>

### **Programming Languages & Tools**

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode"/>
</p>

</div>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=38B2AC&center=true&vCenter=true&random=false&width=600&lines=Always+learning%2C+building%2C+exploring+%F0%9F%9A%80;Open+to+collaboration+and+new+opportunities;Let's+create+something+amazing+together!" alt="Footer" />

</div>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=sahil2448&color=3B82F6&style=for-the-badge" alt="Profile Views"/>

</div>
