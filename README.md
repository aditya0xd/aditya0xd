<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Aditya%20Yadav&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20%26%20Full-Stack%20Developer&descAlignY=55&descSize=20" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=700&lines=Building+scalable+backend+systems;Node.js+%2B+TypeScript+%2B+PostgreSQL;Caching+%7C+Queues+%7C+Multi-tenancy;Currently+diving+into+Distributed+Systems" alt="Typing SVG" />

<p>
  <a href="https://www.linkedin.com/in/aditya101201/"><img src="https://img.shields.io/badge/LinkedIn-Aditya%20Yadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:adityayadav168@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/aditya0xd"><img src="https://img.shields.io/badge/GitHub-aditya0xd-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<img src="https://komarev.com/ghpvc/?username=aditya0xd&label=Profile%20Views&color=38BDF8&style=for-the-badge" alt="Profile views" />

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2c5364,100:0f2027&height=3&width=100%" />

## 🧠 About Me

```yaml
name: Aditya Yadav
role: Backend & Full-Stack Developer
experience: 1+ years shipping production systems
focus:
  - Scalability & caching strategies
  - Asynchronous processing & job queues
  - Multi-tenant SaaS architecture
  - Reliable deployments & CI/CD
currently_exploring:
  - System Design
  - Distributed Systems
  - Database Internals
  - Event-driven architectures
  - Production-grade AI / RAG applications
fun_fact: "I'd rather build one real, production-shaped project coz I hate easy things"
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2c5364,100:0f2027&height=3&width=100%" />

## 🛠️ Tech Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,express,nestjs&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,prisma&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=docker,githubactions,nginx,aws,linux,git&theme=dark" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2c5364,100:0f2027&height=3&width=100%" />

## 🔥 Featured Projects

### 🏋️‍♂️ GymTrack Pro A Multi-Tenant Gym Management SaaS

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-7-2D3748?style=flat-square&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-16-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-cache--aside-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Razorpay-billing-0C2451?style=flat-square&logo=razorpay&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-ready-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

> A real SaaS product, not a demo: two fully separate portals (gym owner + platform superadmin), real money moving through Razorpay, real reminders going out over SMS/WhatsApp, and real churn/retention numbers on the dashboard.

**What's actually inside:**
- 🏢 **True multi-tenancy** — isolated owner accounts, protected route groups enforcing role-based access at the routing layer, plus a separate superadmin plane for platform-wide control
- 👥 **Full member lifecycle** — enrollment, custom membership plans with dynamic benefits, duration-based pricing (1–12 months), and active/expiring/expired status tracking at a glance
- 💳 **Real billing, not mocked** — Razorpay checkout + signature verification, auto-generated PDF receipts via `pdf-lib`, and an owner-facing invoice history
- ⏰ **Automated renewal reminders** — a secured daily cron job (Vercel Cron / bearer-secret protected, rate-limited against duplicate runs) fires SMS + WhatsApp nudges via Twilio one day before expiry, with full delivery logging
- ⚡ **Redis where it counts** — cache-aside pattern on the member list, sliding-window rate limiting on sensitive endpoints, and auth session caching
- 📊 **Analytics that mean something** — retention, churn, revenue-at-risk, and revenue-lost visibility, not just vanity charts
- 📱 **Installable PWA** — Next.js-native manifest, versioned service worker cache, offline fallback page, and RSC-aware caching that deliberately avoids caching server-component/prefetch payloads
- 📲 **Native Android shell** — a companion app wrapping the deployed web app via Capacitor, with native camera/splash/status-bar plugin access and a signed release APK
- 🔁 **Shipped like production** — dockerized local stack (Postgres + Redis), separate GitHub Actions pipelines for dev (lint/typecheck/build) and prod (migrate + build on merge to main), OpenAPI/Swagger docs across every route group
- 🇮🇳 **Built for the Indian market** — INR formatting and Razorpay as the native payment rail throughout

<p align="center">
  <img src="https://github.com/user-attachments/assets/62892cd6-c37d-4a1a-96c5-501bcb753533" width="49%" />
  <img src="https://github.com/user-attachments/assets/b5a42f24-b795-4410-8c68-337a2cd56edb" width="49%" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/c2684d36-b044-4073-8f21-d52b885a6bee" width="49%" />
  <img src="https://github.com/user-attachments/assets/70f6d12f-f524-49e8-858d-51de5d8a3160" width="49%" />
</p>

```text
Browser / PWA
     │
     ▼
Next.js App Router (TypeScript)
     ├── /owner/*        → Owner portal (protected)
     ├── /superadmin/*   → Platform console (protected)
     └── /api/*          → REST routes
              ├── Prisma ORM → PostgreSQL (Supabase)
              ├── Redis      → cache-aside + rate limiting
              ├── Razorpay   → checkout + verification
              └── Twilio     → SMS + WhatsApp reminders
```

<p align="center">
  <a href="https://gym-track-sigma-ten.vercel.app/login"><img src="https://img.shields.io/badge/🚀_Live_Demo-Visit_App-38BDF8?style=for-the-badge" /></a>
  <a href="https://github.com/aditya0xd/GymTrack-Pro"><img src="https://img.shields.io/badge/⭐_Source-View_Repo-181717?style=for-the-badge&logo=github" /></a>
  <a href="https://github.com/aditya0xd/Gym_Track-mobile_app"><img src="https://img.shields.io/badge/📱_Android-Mobile_Repo-3DDC84?style=for-the-badge&logo=android&logoColor=white" /></a>
</p>

---

### 🤖 DedupRAG An Async RAG Engine for PDF Q&A

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-runtime-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-API-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/BullMQ-job_queue-C0392B?style=flat-square" />
  <img src="https://img.shields.io/badge/Redis%2FValkey-broker-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-embeddings-4285F4?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" />
</p>

> Upload a PDF, get a job ID back instantly, and start asking it questions — the heavy lifting (parsing, chunking, embedding) happens off the request thread entirely.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b211618f-0778-4915-864a-46435bf032c4" alt="DedupRAG UI Preview" width="700" />
</p>

**What's actually inside:**
- 🔀 **Decoupled server + worker** — a lean Express API (`src/server.ts`) handles uploads and chat, while a dedicated BullMQ worker (`src/worker.ts`) does all PDF processing in the background — the API never blocks
- 📄 **PDF → chunk → embed pipeline** — text extraction, paragraph/sentence-boundary-aware chunking, then batched vector embedding via Gemini's `gemini-embedding-001`, comfortably handling **500+ chunks per document**
- 🧠 **RAG-powered Q&A** — retrieves the most relevant chunks per question and grounds Gemini's answer in the actual document content, with multi-turn chat via `sessionId`
- ♻️ **SHA-256 content-hash deduplication** — hashes the raw PDF buffer before processing, so re-uploading a document you've already embedded is a cache hit, not a re-run
- 📬 **Redis/Valkey as the backbone** — powers the BullMQ job queue *and* doubles as the shared vector store, so embeddings are available across the server and worker processes
- 🔁 **Built for real traffic** — request throttling and retry logic baked into the pipeline instead of bolted on after the fact

```text
Client
  │  POST /api/uploadPdf ──► Express API ──► Redis/Valkey queue
  │                                              │
  │                                              ▼
  │                                     BullMQ Worker
  │                                       ├─ SHA-256 dedupe check
  │                                       ├─ Extract + chunk PDF
  │                                       └─ Batch embed (Gemini)
  │
  └─ POST /api/ask/:jobId ──► retrieve relevant chunks ──► Gemini answer
```

**Endpoints at a glance**

| Method | Route | Purpose |
|---|---|---|
| `POST` | `/api/uploadPdf` | Upload a PDF, kick off async processing, get back a `jobId` |
| `POST` | `/api/ask/:jobId` | Ask a question against that document, with optional `sessionId` for multi-turn chat |

<p align="center">
  <a href="https://github.com/aditya0xd/DedupRAG"><img src="https://img.shields.io/badge/⭐_Source-View_Repo-181717?style=for-the-badge&logo=github" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2c5364,100:0f2027&height=3&width=100%" />

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aditya0xd&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aditya0xd&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="180" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aditya0xd&theme=tokyonight&hide_border=true" height="180" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=aditya0xd&theme=tokyo-night&hide_border=true" width="100%" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2c5364,100:0f2027&height=3&width=100%" />

## 🎯 Currently Exploring

<p align="left">
  <img src="https://img.shields.io/badge/System_Design-38BDF8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Distributed_Systems-38BDF8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Database_Internals-38BDF8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Event--Driven_Architecture-38BDF8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Production_AI%2FLLM_Apps-38BDF8?style=for-the-badge" />
</p>

## 🤝 Open To

🚀 Backend Developer Roles &nbsp;|&nbsp; 💻 Full-Stack Developer Roles &nbsp;|&nbsp; 🌍 Open-Source Contributions &nbsp;|&nbsp; 🤝 Interesting Engineering Collaborations

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2c5364,100:0f2027&height=3&width=100%" />

<div align="center">

### 📫 Let's Connect

<a href="mailto:adityayadav168@gmail.com"><img src="https://img.shields.io/badge/Email-adityayadav168%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/aditya101201/"><img src="https://img.shields.io/badge/LinkedIn-Aditya%20Yadav-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/aditya0xd"><img src="https://img.shields.io/badge/GitHub-aditya0xd-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

<i>"Build systems. Understand how they work. Then make them better."</i>

<br/>

⭐ Feel free to explore my repositories and connect with me!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=100&section=footer" width="100%"/>

</div>
