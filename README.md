# FlowForge – Multi-Tenant Workflow Automation SaaS

FlowForge is a production-grade, multi-tenant B2B SaaS platform that enables organizations to design, execute, and monitor automated business workflows through a visual drag-and-drop interface.

The platform implements:

- Multi-tenant architecture with strict Row Level Security (RLS)
- Role-Based Access Control (RBAC)
- Directed Acyclic Graph (DAG) execution engine
- Asynchronous job processing via Redis queues
- Webhook-based trigger system
- HTTP & Email action nodes
- AI-powered "Text-to-Workflow" generation using Google Gemini
- Subscription billing with Stripe
- Rate limiting and security hardening
- Unit, Integration, and End-to-End testing

---

## 🚀 Architecture Highlights

- **Frontend**: Next.js (App Router), React, TypeScript, TailwindCSS, React Flow  
- **Backend**: Next.js Server Actions & API Routes  
- **Database**: PostgreSQL (Supabase) with Prisma ORM  
- **Authentication**: Supabase Auth + PostgreSQL RLS  
- **Queue System**: Upstash Redis  
- **AI Integration**: Google Gemini API  
- **Payments**: Stripe (Test Mode)  
- **Monitoring**: Sentry  
- **Deployment**: Vercel + Supabase + Upstash  

---

## 🧠 Core Engineering Concepts Demonstrated

- Multi-tenant system design  
- Secure database-level data isolation  
- DAG graph traversal algorithms  
- Asynchronous task orchestration  
- Subscription feature gating  
- API rate limiting and SSRF prevention  
- CI/CD automation  
- Production deployment strategy  

---

## 💡 Why This Project Matters

FlowForge replicates the core architectural patterns used in modern B2B SaaS platforms such as workflow automation tools, integration platforms, and internal operations systems.

It demonstrates the ability to design, build, secure, and deploy a scalable system end-to-end.

---

## 📂 Project Structure (High-Level)
