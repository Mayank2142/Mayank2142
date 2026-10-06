<div align="center">

# 👋 Hi, I'm Mayank Gupta

### Software Engineer · Full-Stack Developer · Applied AI/ML

**Interfaces people enjoy. Systems they can trust.**

I build across web, backend, AI and connected devices—with a focus on reliable workflows, clear user experiences and explainable decisions.

[![Portfolio](https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mayank2142.github.io/Portfolio-Website/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayank-gupta-14b95428b/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Mayank1720/)
[![Codolio](https://img.shields.io/badge/Codolio-334155?style=for-the-badge)](https://codolio.com/profile/Mayank1720)

[Projects](#-featured-projects) · [More repositories](#-more-projects) · [About](#-about-me) · [Tech stack](#-tech-stack) · [Activity](#-github-activity) · [Connect](#-lets-connect)

</div>

## 🚀 Featured projects

Start here: my most substantial product, backend and AI work. Deployed projects include a live demo; local-only projects link to their setup instructions.

### 01 · CineBook — movies, live events & reliable seat booking

<a href="https://ticket-booking-production-dd12.up.railway.app/">
  <img src="https://raw.githubusercontent.com/Mayank2142/ticket-booking/main/output/playwright/readme/01-home-dark.jpg" alt="CineBook dark-mode home page with movie discovery and event cards" width="100%" />
</a>

**A complete booking experience, backed by an ownership-safe seat-allocation workflow.**

- Searchable movie/live-event discovery, city selection, favourites and recommendations.
- Accessible seat maps, atomic holds, expiry, server-calculated totals and QR tickets.
- FIFO waitlists with single-use offers, cancellation and live inventory through SSE.
- Customer, organiser and administrator workflows, reports and audit history.
- Durable background jobs, retry scheduling and automated API/browser regression tests.

`React` `Vite` `TypeScript` `Node.js` `Prisma` `PostgreSQL` `JWT` `Playwright` `Railway`

**[▶ Live demo](https://ticket-booking-production-dd12.up.railway.app/)** · [Source code](https://github.com/Mayank2142/ticket-booking) · [Architecture & setup](https://github.com/Mayank2142/ticket-booking#architecture)

<sub>Sample inventory and demo accounts—not real paid tickets. Email delivery remains pending HTTPS-provider integration; Railway Trial blocks SMTP.</sub>

---

### 02 · Sentinel AML — explainable, agentic investigation

<a href="https://sentinel-aml-gamma.vercel.app/">
  <img src="https://raw.githubusercontent.com/Mayank2142/Sentinel-AML/main/docs/screenshots/command-center.png" alt="Sentinel AML evidence-based financial investigation command center" width="100%" />
</a>

**Natural-language questions become bounded analytical plans, evidence and human-review workflows.**

- Query-aware orchestration selects relevant tools and explains why others were skipped.
- Rules, statistics, Isolation Forest and graph analysis support explainable risk scoring.
- Governed datasets, model provenance, investigation traces and reviewer audit history.
- Human escalation remains explicit: investigative leads are not regulatory decisions.

**Team project · My documented contribution:** product experience, frontend architecture, UI/UX, visualization and integration.

`React` `TypeScript` `FastAPI` `Python` `DuckDB` `scikit-learn` `NetworkX` `Groq`

**[▶ Live demo](https://sentinel-aml-gamma.vercel.app/)** · [Source code](https://github.com/Mayank2142/Sentinel-AML) · [API docs](https://mayank2142-sentinel-aml-api.hf.space/docs)

**AWS deployment edition:** [Repository](https://github.com/Mayank2142/Anti-Money-Laundering-Detection) · [Live AWS demo](https://sentinel-aml-demo-frontendbucket-aqfdpzq4srwb.s3.ap-south-1.amazonaws.com/index.html#/)

---

### 03 · Darwix AI Chat — resilient multimodal conversations

<a href="https://smart-chat-green.vercel.app/">
  <img src="https://raw.githubusercontent.com/Mayank2142/SmartChat/main/output/playwright/phase-10/desktop-dark.png" alt="Darwix AI Chat desktop interface in dark mode" width="100%" />
</a>

**An accessible Gemini chat experience built around the whole message lifecycle—not just the happy path.**

- Multimodal attachments with server-side model calls that keep API keys out of the browser.
- Cancellation, retry, single-flight requests and stable message identities.
- Persistent/temporary sessions, interrupted-request recovery and bounded history loading.
- Automated interaction, accessibility, persistence and failure-recovery tests.

`React` `TypeScript` `Vite` `Gemini API` `Vitest` `Testing Library` `Vercel`

**[▶ Live demo](https://smart-chat-green.vercel.app/)** · [Source code](https://github.com/Mayank2142/SmartChat) · [Implementation notes](https://github.com/Mayank2142/SmartChat/blob/main/IMPLEMENTATION.md)

### 04 · Smart Operator Assistant — machinery operations co-pilot

Task planning, telemetry, safety alerts, incident handling and cited operator guidance in one prototype. Deterministic safety rules take priority over ML/LLM output; synthetic telemetry is labelled as demonstration data.

`Python` `FastAPI` `PostgreSQL / SQLite` `Document RAG` `Docker`

[Source & local demo](https://github.com/Mayank2142/Smart-Operator-Assistant-for-CAT-Machinery) · [Architecture](https://github.com/Mayank2142/Smart-Operator-Assistant-for-CAT-Machinery/blob/main/docs/ARCHITECTURE.md)

### 05 · Dependency Risk Console — explainable dependency security

DepShield AI combines npm audit/OSV evidence, dependency topology, bounded static reachability, contextual risk, remediation simulation, policy gates and SBOM exports. Scores are project heuristics—not proof of exploitability or a security certification.

`Next.js` `TypeScript` `SQLite` `OSV` `Gemini` `React Flow`

[Source & local demo](https://github.com/Mayank2142/Dependency-Risk-Console) · [Architecture](https://github.com/Mayank2142/Dependency-Risk-Console/blob/main/docs/ARCHITECTURE_V2.md) · [Preserved project provenance](https://github.com/Mayank2142/Dependency-Risk-Console/blob/main/MIGRATION.md)

### 06 · SpreadTheSheets — real-time collaborative spreadsheets

Live multi-user editing, formulas, presence, sharing, version history, in-document chat, charts and CSV export in a collaborative workspace.

`Next.js` `TypeScript` `Firebase` `Firestore`

**[▶ Live demo](https://spreadthesheets.vercel.app/)** · [Source code](https://github.com/Mayank2142/SpreadTheSheets)

## 🧩 More projects

| Project | What it explores | Links |
|---|---|---|
| **Smart Helmet** | ESP32/MPU6050 crash detection, Flutter monitoring, Firebase telemetry and GPS-tagged emergency alerts | [Repository](https://github.com/Mayank2142/Smart_Helmet) · [Documentation](https://github.com/Mayank2142/Smart_Helmet/blob/main/PROJECT_DOCUMENTATION.md) |
| **CampusMate** | Flutter campus tours with Supabase auth, Google Maps, 360° panoramas, audio and 3D previews | [Repository](https://github.com/Mayank2142/Campus-Mate) |
| **Sentient Calendar** | React/Next.js calendar, range selection, daily notes, sticky memos and local persistence | [Live demo](https://sentient-calendar.vercel.app/) · [Repository](https://github.com/Mayank2142/sentient-calendar) |
| **Vivi Alarm** | React productivity dashboard with clocks, weather, alarms and Pomodoro tools | [Live demo](https://vivi-alarm.vercel.app/) · [Repository](https://github.com/Mayank2142/Vivi-Alarm) |
| **Online Voting System** | Voter/candidate registration, voting confirmation and results with Node.js, Express and SQLite | [Repository](https://github.com/Mayank2142/online-voting-system-project) |
| **Emergency Vehicle Detection** | Python project exploring emergency-vehicle detection | [Repository](https://github.com/Mayank2142/Emergency-vehicle-detection) |
| **Portfolio Website** | Personal portfolio and project showcase | [Live site](https://mayank2142.github.io/Portfolio-Website/) · [Repository](https://github.com/Mayank2142/Portfolio-Website) |

**[Browse all public repositories →](https://github.com/Mayank2142?tab=repositories)**

<sub>Featured work is curated rather than an exhaustive list of forks, experiments or private repositories. Local-only projects are labelled instead of given invented deployment links.</sub>

## 👨‍💻 About me

I work across frontend, backend and applied AI. I enjoy engineering problems where details matter: concurrent state changes, role-based access, database consistency, secure model integrations and recovery from partial failure.

- **Currently building:** full-stack products, explainable AI workflows and reliable backend systems.
- **Interested in:** API architecture, distributed state, system design, accessible interfaces and connected applications.
- **Open to:** Software Engineer Intern, Full-Stack, Backend and Applied AI/ML opportunities.
- **Engineering mindset:** **Build → Test → Understand → Improve.**

A polished interface matters. So do the behaviour under invalid input, unavailable services and simultaneous users—and the documentation that makes those tradeoffs clear.

## 💻 Tech stack

Tools represented in my projects—not a list copied from a template.

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

**Frontend & mobile**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend & data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black)

**AI, testing & deployment**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=black)

## 📊 GitHub activity

<p align="center">
  <a href="https://github.com/Mayank2142?tab=repositories"><img src="https://github-readme-stats.vercel.app/api?username=Mayank2142&show_icons=true&theme=tokyonight&hide_border=true" alt="Mayank Gupta's dynamically generated public GitHub statistics" width="49%" /></a>
  <a href="https://github.com/Mayank2142?tab=repositories"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mayank2142&layout=compact&theme=tokyonight&hide_border=true" alt="Languages across Mayank Gupta's public repositories" width="49%" /></a>
</p>

<p align="center">
  <a href="https://github.com/Mayank2142"><img src="https://streak-stats.demolab.com?user=Mayank2142&theme=tokyonight&hide_border=true" alt="Mayank Gupta's dynamically generated GitHub contribution streak" width="70%" /></a>
</p>

<sub>Cards are provided by external services and may occasionally be unavailable. Language proportions describe repository code, not proficiency. GitHub's native contribution calendar is available on my profile; no statistics are hard-coded here.</sub>

### Quality signals from the projects

[![CineBook CI](https://github.com/Mayank2142/ticket-booking/actions/workflows/ci.yml/badge.svg)](https://github.com/Mayank2142/ticket-booking/actions/workflows/ci.yml)
[![SmartChat CI](https://github.com/Mayank2142/SmartChat/actions/workflows/ci.yml/badge.svg)](https://github.com/Mayank2142/SmartChat/actions/workflows/ci.yml)

## 🤝 Let's connect

Interested in building a product, discussing systems or collaborating on applied AI? **[Message me on LinkedIn](https://www.linkedin.com/in/mayank-gupta-14b95428b/).**

[Portfolio](https://mayank2142.github.io/Portfolio-Website/) · [GitHub repositories](https://github.com/Mayank2142?tab=repositories) · [LeetCode](https://leetcode.com/u/Mayank1720/) · [Codolio](https://codolio.com/profile/Mayank1720)

---

<div align="center">

**Thanks for visiting — explore a demo, read the code, and let's build something useful.**

</div>
