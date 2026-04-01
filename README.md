# Full-Stack Contact Platform (Next.js + TypeScript + Tailwind)

**Live Demo:** https://nextjs-fullstack-contact-platform.vercel.app/  

A production-oriented full-stack web application built with **Next.js App Router** and **TypeScript**, designed to demonstrate **systems integration, API-driven workflows, reusable architecture, and structured frontend/backend development**.

This project was designed to demonstrate practical engineering around:

- **Frontend architecture** with reusable components and multi-page navigation
- **Backend/API workflows** for contact handling and controlled admin content updates
- **Rate limiting and environment-based configuration**
- **Email template integration** with MJML
- **Deployment and CI-ready project structure**

---

## Why I Built This

I built this project to practice full-stack development with a production-minded structure, combining frontend implementation, API route design, reusable components, deployment workflow, and environment-based configuration in a single application.

---

## What This Project Demonstrates

- Building a **modern full-stack application** with both UI and server-side logic
- Designing **API routes** for real user workflows
- Structuring a project for **maintainability, scalability, and clean separation of concerns**
- Supporting **content operations**, **email handling**, and **basic application protection**
- Applying a practical software engineering approach across **frontend, backend, and deployment tooling**

---

## Core Features

- **Next.js App Router** (`src/app`) with multiple pages and route-based structure
- **Contact API workflow** for form submission handling
- **Admin content endpoint** for controlled content updates
- **Reusable UI components** for maintainable frontend development
- **Rate limiting helper** for API protection
- **MJML email templates** for transactional and marketing communication
- **SEO support** through `sitemap.ts`, `robots.ts`, and metadata-friendly structure
- **Theming and UX enhancements**, including theme toggle and layout providers
- **i18n-ready utilities** and language toggle support
- **Automation/deployment scripting** with shell-based tooling
- **GitHub Actions CI workflow** for build validation

---

## Tech Stack

**Frontend**
- Next.js
- TypeScript
- Tailwind CSS

**Backend / Server Logic**
- Next.js Route Handlers
- API endpoints for contact and admin workflows

**Tooling / DevOps**
- GitHub Actions
- Bash deployment script
- Environment-based configuration

**Email / Communication**
- MJML templates

---

## Project Structure

```txt id="qevc9u"
.
├─ src/
│  ├─ app/
│  │  ├─ page.tsx                    # Home
│  │  ├─ about/page.tsx
│  │  ├─ services/page.tsx
│  │  ├─ portfolio/page.tsx
│  │  ├─ pricing/page.tsx
│  │  ├─ reviews/page.tsx
│  │  ├─ faq/page.tsx
│  │  ├─ contact/page.tsx
│  │  ├─ success/page.tsx
│  │  ├─ admin/page.tsx
│  │  ├─ legal/
│  │  │  ├─ terms/page.tsx
│  │  │  └─ privacy/page.tsx
│  │  ├─ api/
│  │  │  ├─ contact/route.ts         # Contact API
│  │  │  └─ admin/content/route.ts   # Admin content API
│  │  ├─ sitemap.ts                  # SEO sitemap
│  │  └─ robots.ts                   # SEO robots
│  ├─ components/                    # Reusable UI components
│  ├─ data/                          # Site content/constants
│  └─ lib/                           # Utilities (i18n, rate limit, helpers)
├─ emails/                           # MJML templates
├─ scripts/                          # Automation and deployment scripts
├─ .env.example                      # Environment variable template
├─ next.config.mjs
├─ tailwind.config.ts
├─ postcss.config.mjs
├─ tsconfig.json
└─ package.json
