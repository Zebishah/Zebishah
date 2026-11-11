<div align="center">

<a href="https://zohaib-haider-portfolio.vercel.app/">
  <img src="./assets/profile-hero.svg" width="100%" alt="Zohaib Haider — Full-stack engineering and intelligent systems" />
</a>

<br/>

**FULL-STACK SOFTWARE ENGINEER** &nbsp; • &nbsp; **AI SYSTEMS BUILDER** &nbsp; • &nbsp; **PRODUCT-FOCUSED ENGINEERING**

<br/>

<a href="https://zohaib-haider-portfolio.vercel.app/"><img src="https://img.shields.io/badge/VIEW_PORTFOLIO-104B36?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/zohaib-haider-390530228/"><img src="https://img.shields.io/badge/LET'S_CONNECT-1D674A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:zebihaider123@gmail.com"><img src="https://img.shields.io/badge/CONTACT_ME-315F42?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

<br/>

## The engineer behind the systems

I'm **Zohaib Haider**, a **Full-Stack & AI Software Engineer** with **2+ years of experience** contributing to **12+ production applications** across SaaS, marketplaces, CRM, financial workflows, and AI-powered products.

I build the **complete product**: thoughtful React/Next.js interfaces, secure Node.js/Python APIs, reliable data models, authentication, integrations, distributed jobs, cloud infrastructure, and automated testing. My applied AI work includes **RAG, LangGraph agents, MCP, human-in-the-loop approvals, LLM evaluation, speech-to-text, and LoRA/QLoRA fine-tuning workflows**.

> **My approach:** Make it useful. Make it secure. Make it reliable. Make it understandable.

<div align="center">

<a href="#featured-work"><img src="https://img.shields.io/badge/EXPLORE_PROJECTS-4_FLAGSHIP_SYSTEMS-104B36?style=flat-square" alt="Explore four featured projects" /></a>
<a href="#engineering-toolkit"><img src="https://img.shields.io/badge/EXPLORE_SKILLS-FULL_STACK_+_AI-315F42?style=flat-square" alt="Explore skills" /></a>

</div>

---

<a id="featured-work"></a>

## 01 / Featured work

**Four products. Different engineering challenges. One end-to-end mindset.**

These are selected systems where I worked across product functionality, API design, integration complexity, data reliability, and delivery—not generic CRUD demos.

### 01 — TraceOps · AI Incident Investigation

<a href="https://github.com/Zebishah/TraceOps"><img src="./assets/project-traceops.svg" width="100%" alt="TraceOps illustrated AI investigation workflow: triage, retrieve, reason, approve" /></a>

**A multi-tenant AI incident investigation and automation platform that prioritizes evidence before action.**

- **Agentic AI:** LangGraph investigation and review workflows, tenant-scoped RAG, cited knowledge, operational tools, and resumable **human approval gates**.
- **Operational reliability:** Inngest background investigations, retries, incident memory, workflow state, and n8n integration.
- **Model engineering:** MCP/OAuth connections, voice/STT interfaces, structured LLM evaluations, and an **optional Qwen LoRA/QLoRA classification training pipeline**.

**Core stack:** `Python` `FastAPI` `React` `TypeScript` `LangChain` `LangGraph` `Qdrant` `PostgreSQL` `Redis` `Inngest` `n8n` `MCP` `Hugging Face`

**[Explore source code](https://github.com/Zebishah/TraceOps)** &nbsp;·&nbsp; **[Open live demo](https://trace-ops-pearl.vercel.app/)** &nbsp;·&nbsp; [Read architecture](https://github.com/Zebishah/TraceOps/blob/main/docs/architecture.md)

<br/>

### 02 — DrivePilot · Marketplace & Payments

<a href="https://github.com/Zebishah/DrivePilot"><img src="./assets/project-drivepilot.svg" width="100%" alt="DrivePilot illustrated scheduling and Stripe Connect payment interface" /></a>

**A driving-instructor marketplace with connected experiences for students, instructors, and administrators.**

- **Full-stack product:** Instructor discovery, location and availability search, lesson bookings, progress tracking, reviews, management dashboards, and real-time messaging.
- **Financial workflows:** **Stripe Connect** payments, delayed/off-session charging, refunds, commissions, payouts, and payment state synchronization.
- **Consistency & recovery:** Slot booking guards, idempotent webhook processing, durable jobs, retries, and reconciliation for failed or incomplete payment operations.

**Core stack:** `React` `TypeScript` `Node.js` `Express` `Apollo GraphQL` `MongoDB` `Redis` `Socket.IO` `Stripe Connect` `AWS S3`

**[Explore source code](https://github.com/Zebishah/DrivePilot)** &nbsp;·&nbsp; **[Open live demo](https://drive-pilot-topaz.vercel.app/)**

<br/>

### 03 — DealerFlow · Dealership CRM & Vehicle Intelligence

<a href="https://github.com/Zebishah/DealerFlow"><img src="./assets/project-dealerflow.svg" width="100%" alt="DealerFlow illustrated role-aware dashboard, vehicle intelligence, and AI assistance" /></a>

**A role-aware dealership operations platform connecting business workflows with vehicle intelligence.**

- **Multi-role dashboards:** Leads, appointments, sales, finance, commissions, performance analytics, staff records, and granular permission management.
- **Data acquisition:** Approved vehicle sources, standardized records, source health visibility, and **on-demand Apify Actors** in the current deployment.
- **AI & architecture:** Grounded assistant, PostgreSQL/Drizzle data layer, Redis caching and limits; **AWS SQS/Lambda and BullMQ** remain implemented/documented alternative pipeline paths.

**Core stack:** `React` `TypeScript` `Node.js` `Express` `PostgreSQL` `Drizzle` `Redis` `Apify` `Playwright` `Gemini / Groq` `AWS S3`

**[Explore source code](https://github.com/Zebishah/DealerFlow)** &nbsp;·&nbsp; **[Open live demo](https://dealer-flow-kappa.vercel.app/)** &nbsp;·&nbsp; [Current architecture](https://github.com/Zebishah/DealerFlow/blob/main/rta-marketing/docs/architecture/current-production.md)

<br/>

### 04 — CaseLens · Intercom HR Case Intelligence

<a href="https://github.com/Zebishah/CaseLens"><img src="./assets/project-caselens.svg" width="100%" alt="CaseLens illustrated Intercom HR case intelligence sidebar" /></a>

**An AI-assisted case intelligence platform that brings employee context directly into Intercom.**

- **Embedded AI workflow:** Intercom Canvas Kit sidebar, Gemini-supported HR case classification, contextual insights, conversation tagging, and notes.
- **Identity & relevance:** Employee matching with aliases and **PostgreSQL trigram similarity**, related-case retrieval, reviewer context, and stakeholder-routing suggestions.
- **Reliable integrations:** Signed webhooks, transactional outbox, revision-aware processing, **on-demand Apify** execution; BullMQ/Redis remains an optional processing mode.

**Core stack:** `Next.js` `React` `TypeScript` `Node.js` `Express` `PostgreSQL` `Drizzle` `Gemini` `Intercom Canvas` `Box` `Apify` `Redis / BullMQ`

**[Explore source code](https://github.com/Zebishah/CaseLens)** &nbsp;·&nbsp; **[Open live demo](https://case-lens-amber.vercel.app/)**

<br/>

<div align="center">

### Interested in the architecture behind these applications?

**[See the interactive portfolio & detailed case studies](https://zohaib-haider-portfolio.vercel.app/)**

</div>

---

<a id="engineering-toolkit"></a>

## 02 / Engineering toolkit

**A practical stack across product development, distributed backends, cloud infrastructure, and applied AI.**

<img src="./assets/profile-capabilities.svg" width="100%" alt="Engineering capability dashboard: frontend, backend, data, applied AI, distributed systems, and delivery" />

### Frontend & product interfaces

`JavaScript` · `TypeScript` · `React` · `Next.js` · `Vite` · `Tailwind CSS` · `shadcn/ui` · `Radix UI` · `Material UI` · `Ant Design` · `Redux Toolkit` · `Zustand` · `TanStack Query` · `React Hook Form` · `Zod` · `Framer Motion` · `Three.js` · `React Three Fiber` · `Recharts` · `ApexCharts`

### Backend, API design & security

`Node.js` · `Express` · `NestJS` · `Python` · `FastAPI` · `Pydantic` · `REST APIs` · `GraphQL` · `Apollo Server` · `Socket.IO` · `WebSockets` · `JWT` · `OAuth 2.0` · `RBAC` · `Multi-tenancy` · `Webhooks` · `Rate Limiting` · `API Validation`

### Applied AI, agents & model engineering

`LLM Integration` · `LangChain` · `LangGraph` · `Agent Workflows` · `RAG` · `Vector Search` · `Embeddings` · `BM25` · `Reranking` · `Qdrant` · `MCP` · `Tool Calling` · `Structured Outputs` · `Human-in-the-loop` · `LLM Evaluation` · `Prompt Engineering` · `LoRA` · `QLoRA` · `Qwen` · `PyTorch` · `Hugging Face` · `Voice / Speech-to-text` · `Gemini` · `Groq`

### Data, messaging & distributed systems

`PostgreSQL` · `Neon` · `MongoDB` · `Mongoose` · `MySQL` · `Redis` · `Upstash` · `Drizzle ORM` · `SQLAlchemy` · `Alembic` · `pg_trgm` · `BullMQ` · `AWS SQS` · `AWS Lambda` · `Inngest` · `n8n` · `Apify Actors` · `Job Queues` · `Idempotency` · `Transactional Outbox` · `Retries / Backoff` · `Reconciliation` · `Caching`

### Cloud, integrations & delivery

`AWS EC2` · `AWS S3` · `AWS CloudFront` · `AWS Route 53` · `AWS IAM` · `Docker` · `Docker Compose` · `Nginx` · `GitHub Actions` · `CI/CD` · `Vercel` · `Render` · `Linux` · `Stripe` · `Stripe Connect` · `PayPal` · `QuickBooks` · `Zoho Books` · `Intercom` · `Box` · `Resend`

### Testing & engineering quality

`Jest` · `Vitest` · `React Testing Library` · `Playwright` · `Cypress` · `pytest` · `Ruff` · `mypy` · `ESLint` · `TypeScript Checks` · `API Integration Tests` · `End-to-end Tests` · `Accessibility Testing` · `Observability`

---

## 03 / How I think about engineering

| Product experience | Reliable systems | Responsible AI |
| :--- | :--- | :--- |
| Accessible interfaces, useful workflows, clear interactions, and consistent design | Secure authorization, durable state, idempotency, observability, and graceful failure recovery | Grounded retrieval, scoped tools, evaluation, transparent evidence, and human control over consequential actions |

**The goal is not simply to connect technologies. It's to deliver software people can trust and teams can maintain.**

---

## 04 / GitHub activity

<div align="center">

<img height="165" alt="GitHub contribution overview" src="https://github-readme-stats.vercel.app/api?username=Zebishah&show_icons=true&hide_border=true&bg_color=09291f&title_color=c8db76&text_color=f4f5e8&icon_color=c8db76" />
<img height="165" alt="Top languages on public repositories" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zebishah&layout=compact&hide_border=true&bg_color=09291f&title_color=c8db76&text_color=f4f5e8" />

</div>

---

<div align="center">

### Have something ambitious to build?

**Open to full-stack engineering, AI systems, freelance collaborations, and thoughtful product work.**

<a href="https://zohaib-haider-portfolio.vercel.app/"><img src="https://img.shields.io/badge/PORTFOLIO-104B36?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/zohaib-haider-390530228/"><img src="https://img.shields.io/badge/LINKEDIN-1D674A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:zebihaider123@gmail.com"><img src="https://img.shields.io/badge/EMAIL-315F42?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<sub>Built with engineering depth, product thinking, and attention to detail.</sub>

</div>
