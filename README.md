<div align="center">

# Mayank Gupta

### Software Engineer | Full-Stack Developer | Applied AI/ML

I build full-stack products where good interfaces are backed by reliable APIs, deliberate data models, and tested failure handling. My recent work covers transactional booking, multimodal AI chat, real-time collaboration, and explainable AML investigation.

<p>
  <a href="https://mayank2142.github.io/Portfolio-Website/"><img src="https://img.shields.io/badge/Portfolio-0F766E?style=flat-square" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/mayank-gupta-14b95428b/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/Mayank2142"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://leetcode.com/u/Mayank1720/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
  <a href="https://codolio.com/profile/Mayank1720"><img src="https://img.shields.io/badge/Codolio-334155?style=flat-square" alt="Codolio" /></a>
</p>

[About](#about) · [Projects](#featured-projects) · [Tech Stack](#tech-stack) · [Engineering Interests](#engineering-interests) · [Activity](#activity) · [Contact](#contact)

</div>

---

## About

I work across frontend, backend, and applied AI. I am most interested in projects where product behavior depends on engineering correctness: concurrent state changes, authentication and authorization, real-time synchronization, secure model calls, explainable decisions, and recovery from failure.

I am currently looking for **Software Engineer Intern**, **Full-Stack**, **Backend**, and **Applied AI/ML** opportunities.

## What I build

> **Full-Stack Applications** — Product-focused React and Next.js applications connected to real APIs, authentication, relational or real-time data, and production deployments.

> **Backend Systems** — Transactional workflows, role-based access, validation, API design, scheduled cleanup, database consistency, and integration testing.

> **Applied AI/ML** — Secure LLM integration, hybrid anomaly detection, evidence-linked explanations, model fallbacks, and human review workflows.

> **Real-Time & Connected Systems** — Collaborative Firebase applications and Flutter/ESP32 systems that connect sensors, cloud state, and mobile interfaces.

## Currently building

### [CineBook](https://github.com/Mayank2142/ticket-booking)

A concurrency-safe movie and concert booking system. The technically interesting work is the seat-allocation state machine: atomic holds, expiry, booking, cancellation, and fair waitlist reassignment.

`Next.js` `TypeScript` `Prisma` `SQLite` `JWT` `Tailwind CSS`

[Live demo](https://ticket-booking-production-9e71.up.railway.app/) · [Repository](https://github.com/Mayank2142/ticket-booking) · [System design](https://github.com/Mayank2142/ticket-booking/blob/main/SYSTEM_DESIGN.md)

### [Darwix AI Chat](https://github.com/Mayank2142/SmartChat)

An accessible Gemini chat application with multimodal attachments, secure server-side model calls, persistent and temporary sessions, failure recovery, and automated quality checks.

`React` `TypeScript` `Vite` `Vitest` `Gemini API` `Vercel`

[Live demo](https://smart-chat-green.vercel.app/) · [Repository](https://github.com/Mayank2142/SmartChat) · [CI](https://github.com/Mayank2142/SmartChat/actions)

## Featured projects

### CineBook — concurrency-safe ticket allocation

<p align="center">
  <a href="https://ticket-booking-production-9e71.up.railway.app/">
    <img src="https://raw.githubusercontent.com/Mayank2142/ticket-booking/main/output/playwright/events-home.png" width="760" alt="CineBook event discovery interface" />
  </a>
</p>

CineBook addresses the consistency problems behind high-demand booking, not only the visual seat picker.

- Conditional database updates and transactions prevent two customers from owning the same seat.
- Expiring holds and waitlist offers are released both during reads and by a protected scheduled cleanup job.
- Cancellation triggers FIFO waitlist allocation with single-use offer tokens.
- JWT role checks separate customer, organiser, and administrator workflows.
- The repository includes six isolated integration and concurrency scenarios using a disposable SQLite database.

`Next.js 14` `TypeScript` `Prisma` `SQLite` `Nodemailer` `QR tickets` `Railway`

<p>
  <a href="https://ticket-booking-production-9e71.up.railway.app/"><img src="https://img.shields.io/badge/Live_demo-0F766E?style=flat-square" alt="CineBook live demo" /></a>
  <a href="https://github.com/Mayank2142/ticket-booking"><img src="https://img.shields.io/badge/Source_code-181717?style=flat-square&logo=github&logoColor=white" alt="CineBook source code" /></a>
  <a href="https://github.com/Mayank2142/ticket-booking/blob/main/SYSTEM_DESIGN.md"><img src="https://img.shields.io/badge/System_design-334155?style=flat-square" alt="CineBook system design" /></a>
</p>

---

### Sentinel AML — explainable investigation workflow

<p align="center">
  <a href="https://sentinel-aml-gamma.vercel.app/">
    <img src="https://raw.githubusercontent.com/Mayank2142/AI-Powered-Suspicious-Activity-Detection/main/docs/screenshots/command-center.png" width="760" alt="Sentinel AML investigation console" />
  </a>
</p>

Sentinel is a team-built decision-support workspace that turns an analyst's natural-language question into a bounded, auditable investigation.

- The planner selects only the tools relevant to the query and records skipped tools with reasons.
- Rules, statistical detection, Isolation Forest, and optional graph analysis contribute evidence to risk scoring.
- Explanations are tied to computed signals, feature values, and controlled AML knowledge.
- Investigations retain dataset, model, policy, execution, evidence, and reviewer provenance.
- The workflow keeps escalation and final regulatory decisions under human control.

My documented contribution: **product experience, frontend architecture, visualization, and integration**.

`React` `TypeScript` `FastAPI` `Python` `DuckDB` `scikit-learn` `NetworkX` `Groq`

<p>
  <a href="https://sentinel-aml-gamma.vercel.app/"><img src="https://img.shields.io/badge/Live_demo-0F766E?style=flat-square" alt="Sentinel AML live demo" /></a>
  <a href="https://github.com/Mayank2142/AI-Powered-Suspicious-Activity-Detection"><img src="https://img.shields.io/badge/Source_code-181717?style=flat-square&logo=github&logoColor=white" alt="Sentinel AML source code" /></a>
  <a href="https://mayank2142-sentinel-aml-api.hf.space/docs"><img src="https://img.shields.io/badge/API_docs-334155?style=flat-square" alt="Sentinel AML API documentation" /></a>
</p>

---

### Darwix AI Chat — resilient multimodal interaction

<p align="center">
  <a href="https://smart-chat-green.vercel.app/">
    <img src="https://raw.githubusercontent.com/Mayank2142/SmartChat/main/output/playwright/phase-10/desktop-dark.png" width="760" alt="Darwix AI Chat interface" />
  </a>
</p>

Darwix focuses on the complete message lifecycle around an AI model, including the states that are easy to overlook.

- A same-origin server endpoint keeps the Gemini API key out of browser JavaScript.
- A single-flight request lock, cancellation, retry, and stable message IDs prevent duplicate or conflicting requests.
- Saved sessions recover interrupted requests; temporary sessions are never persisted.
- Progressive history loading bounds mounted messages while preserving scroll position.
- The documented 45-test suite covers interaction, failure recovery, persistence, attachments, accessibility, and large histories; CI runs lint, tests, and production build.

`React 19` `TypeScript` `Vite` `Vitest` `Testing Library` `Gemini API` `GitHub Actions`

<p>
  <a href="https://smart-chat-green.vercel.app/"><img src="https://img.shields.io/badge/Live_demo-0F766E?style=flat-square" alt="Darwix AI Chat live demo" /></a>
  <a href="https://github.com/Mayank2142/SmartChat"><img src="https://img.shields.io/badge/Source_code-181717?style=flat-square&logo=github&logoColor=white" alt="Darwix AI Chat source code" /></a>
  <a href="https://github.com/Mayank2142/SmartChat/blob/main/IMPLEMENTATION.md"><img src="https://img.shields.io/badge/Implementation-334155?style=flat-square" alt="Darwix AI Chat implementation documentation" /></a>
</p>

## More projects

### [SpreadTheSheets](https://github.com/Mayank2142/SpreadTheSheets)

Real-time collaborative spreadsheet with Firestore synchronization, formulas, presence, sharing, version history, chat, charts, CSV export, and AI-assisted workflows.  
`Next.js` `TypeScript` `Firebase` `Firestore` — [Live demo](https://spreadthesheets.vercel.app/)

### [Smart Helmet](https://github.com/Mayank2142/Smart_Helmet)

Connected accident-detection prototype combining ESP32 firmware, MPU6050 sensing, Firebase telemetry, a Flutter monitoring app, and GPS-tagged emergency alerts.  
`Flutter` `Dart` `ESP32` `Firebase` — [Project documentation](https://github.com/Mayank2142/Smart_Helmet/blob/main/PROJECT_DOCUMENTATION.md)

### [CampusMate](https://github.com/Mayank2142/Campus-Mate)

Flutter campus-tour application with Supabase authentication, Google Maps, 360° panoramas, 3D room previews, audio tours, and detailed location data.  
`Flutter` `Dart` `Supabase` `Google Maps` — [Screenshots](https://github.com/Mayank2142/Campus-Mate#-app-screenshots)

## Tech stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**Frontend and mobile**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend and data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=111)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**AI/ML and delivery**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## Engineering interests

- Backend and API architecture
- Transactional workflows and database consistency
- System design and failure handling
- Applied AI, LLM integration, and explainability
- Machine-learning systems with human review
- Real-time synchronization and connected applications
- Testing, CI, and maintainable developer workflows

## Engineering mindset

**Build → Test → Understand → Improve**

I care about correctness before cleverness, visible failure states instead of silent errors, and documentation that explains decisions and tradeoffs. A polished interface matters, but so do the behavior under concurrency, invalid input, unavailable services, and partial failure.

## Activity

GitHub's native contribution calendar appears below this profile README. For current code-quality signals, these repository workflows are more useful than a streak counter:

[![SmartChat CI](https://github.com/Mayank2142/SmartChat/actions/workflows/ci.yml/badge.svg)](https://github.com/Mayank2142/SmartChat/actions/workflows/ci.yml)
[![Sentinel AML CI](https://github.com/Mayank2142/AI-Powered-Suspicious-Activity-Detection/actions/workflows/ci.yml/badge.svg)](https://github.com/Mayank2142/AI-Powered-Suspicious-Activity-Detection/actions/workflows/ci.yml)

## Contact

The best way to reach me is through [LinkedIn](https://www.linkedin.com/in/mayank-gupta-14b95428b/). You can also find my work and problem-solving profiles here:

- [Portfolio](https://mayank2142.github.io/Portfolio-Website/)
- [GitHub](https://github.com/Mayank2142)
- [LeetCode](https://leetcode.com/u/Mayank1720/)
- [Codolio](https://codolio.com/profile/Mayank1720)

