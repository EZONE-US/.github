# 🌐 EZ ONE – Intelligent Software, Built for Growth

**EZ ONE** is a technology company specializing in full-stack SaaS development, AI automation, and digital transformation.
We build our own in-house products — like the **EZ ONE Hub**, an ecosystem of tools for restaurants — and also deliver **custom enterprise solutions** for clients in hospitality, retail, logistics, finance, and other industries.

Our mission: **connect data, design, and automation** to help businesses scale efficiently.

---

## 🏗️ What We Build

### 🧠 In-House Platform – EZ ONE Hub
A modular SaaS platform built to centralize operations for multi-location businesses.

| Module | Purpose |
|--------|----------|
| **EZ Orders** | Unified order management across delivery platforms (Uber Eats, DoorDash, Grubhub, Gloria’s Food). |
| **EZ Menu** | Menu synchronization and pricing automation. |
| **EZ Pay** | White-label Stripe Connect payments for invoices, deposits, and event transactions. |
| **EZ Marketing** | Multi-channel campaigns via SMS, Email, and Push notifications. |
| **EZ Coupon** | QR-based coupon engine with analytics. |
| **EZ Loyalty** | Points and rewards system for customer retention. |
| **EZ Reservation** | Aggregated reservation hub (OpenTable, Toast, native widgets). |
| **EZ Reputation** | Review management with AI-generated replies. |
| **EZ Listing** | Directory synchronization through Yext API. |
| **PICKD** | Delivery logistics using Shipday integration. |
| **EZ AI** | Conversational and remarketing agents powered by GPT models. |
| **EZ CRM** | Cross-module customer intelligence database. |

---

### 🧩 Custom Software Development

Beyond our own ecosystem, we design and deliver **custom technology solutions** for B2B clients:

- Web & Mobile App Development
- API Integrations & Microservices
- AI Automation Agents & Chatbots
- Cloud Infrastructure (AWS / Google Cloud / Render / Vercel)
- Stripe / Twilio / Shipday / Yext / Google Business Integrations
- SaaS Design & Branding Consulting

We treat every project as part of the same philosophy — modular, scalable, and data-driven.

---

## ⚙️ Technology Stack

| Layer | Stack |
|-------|-------|
| **Backend** | Nest.js · TypeScript · TypeORM · PostgreSQL (Supabase) |
| **Frontend** | React · TypeScript · TailwindCSS · Vite |
| **Mobile** | Ionic React |
| **Hosting** | Render (backend) · Vercel (frontend) |
| **Integrations** | Stripe · Twilio · Google Cloud · Yext · Shipday · OpenAI |
| **CI/CD** | GitHub Actions → Render / Vercel |
| **Auth** | JWT + 2FA (SMS / Email) |

---

## 🧱 Repository Overview

| Repository | Description |
|-------------|-------------|
| **ezone-backend** | Nest.js API, TypeORM, Supabase, integrations layer. |
| **ezone-frontend** | React + Tailwind web dashboard for all user roles. |
| **ezone-mobile** | Ionic React app (EZ Manager App). |
| **ezone-integrations** | Shared connectors for Stripe, Twilio, Shipday, Google, Yext. |
| **ezone-docs** | Architecture diagrams, API references, and internal standards. |
| **ezone-ai** | Core AI services for automations and chat agents. |

---

## 🧭 Branching Strategy
```
main       → Production (auto-deploy)
develop    → Development
feature/*  → New feature branches
hotfix/*   → Critical fixes

All pull requests require review before merging into `main`.
```

---

## 🧾 CI/CD Workflow

| Stage | Platform | Action |
|--------|-----------|--------|
| Backend | Render | Auto-deploy on merge to `main` |
| Frontend | Vercel | Auto-deploy on merge to `main` |
| Database | Supabase | Managed migrations |
| Monitoring | Logtail / Sentry | Centralized error tracking |

---

## 🔐 Security & Standards

- 2FA mandatory for all organization contributors.
- Secrets stored only in Render / Supabase Vault.
- Follow ESLint + Prettier formatting rules.
- Commit style:

feat(module): add feature
fix(auth): resolve 2FA validation
refactor(menu): optimize sync logic

---

## 👥 Team Roles

| Role | Responsibility |
|------|----------------|
| **Product Owner / CEO** | Defines business goals, product vision. |
| **Lead Developer** | Oversees architecture, code quality, and deployments. |
| **Full-Stack Developers** | Implement features across frontend & backend. |
| **Mobile Developer** | Manages Ionic app development. |
| **UI/UX Designer** | Designs consistent, scalable user experiences. |
| **DevOps Engineer** | Configures Render, Supabase, and Vercel environments. |

---

## 🧠 Best Practices

- Modularize every feature — one domain per module.
- Keep controllers thin, logic in services.
- Validate all incoming data with DTOs.
- Version all endpoints (`/api/v1/...`).
- Use React Context or SWR for global data handling.
- Commit frequently with clear messages.
- Open small PRs — easier to review and merge.

---

## 📦 Toolchain

- **IDE:** VS Code (with Prettier + ESLint)
- **Version Control:** Git + GitHub
- **Project Management:** Asana (Scrum Sprints)
- **Design:** Figma (EZ ONE UI Kit)
- **Docs:** Notion + GitHub Wiki
- **Communication:** Slack · Google Meet

---

## 🤝 Collaboration & Services

We partner with companies seeking:
- SaaS modernization and integration with Stripe, Twilio, Yext, or Google Business.
- End-to-end development teams to build new products.
- White-label technology based on our EZ ONE framework.
- AI automation agents customized for specific business workflows.

📩 **Contact us:** info@ez1solutions.com
🌐 **Website:** [https://ezonehub.com](https://ezonehub.com)

---

## 🧾 License
```
Copyright © 2026
All rights reserved by **EZ ONE LLC**
```
