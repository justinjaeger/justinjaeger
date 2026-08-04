### Hi, I'm Justin 👋

Full-stack engineer spanning founder, startup, and consulting roles. I took a side project from nights-and-weekends to a full-time venture with a user base that topped an industry-backed competitor.

---

### 🏆 Award Expert — Founder & Solo Engineer (2023–present)

A full-stack social platform (iOS, Android, web) for awards-prediction enthusiasts — log predictions, discuss and compare them, and compete on leaderboards.

- **13.6k** peak-season active users, **62%** YoY retention, subscription-powered revenue
- Became the largest user base for a platform of its kind, **topping industry-backed competitor GoldDerby**
- Partnered with **Next Best Picture**, a leading independent awards site, to replace their prediction pages with Award Expert's user-generated data

**Stack:** React Native + TypeScript (iOS/Android) · Next.js + React (web) · Node.js + Express · MongoDB · AWS

**Engineering highlights:**
- Zero-latency tab switching and 60fps scrolling on image-heavy, 300+ item lists — tabs mounted simultaneously, animation driven on the UI thread, virtualized scrolling for minimal JS-compute
- Pre-aggregated frequently-read prediction stats and cached third-party movie-API data to avoid expensive on-demand computation and insulate the app from external throttles/downtime
- Modeled the movie store as single-document-per-year instead of normalized collections, cutting query times 2x for large (100+ item) lists
- Discriminated-union TypeScript models to safely branch on type without permissive optional fields
- Split a widely-consumed data store into separate read/write contexts across 20+ query hooks, cutting unnecessary re-renders

📱 [App Store](https://apps.apple.com/us/app/award-expert/id6446135720) · [Play Store](https://play.google.com/store/apps/details?id=com.awardspredictionapp&hl=en_US)

---

### 💼 SimplyWise — Software Engineer (2021–2025)

Joined as the second full-time engineer at a seed-stage startup, building mobile and web apps that help small business owners organize financial documents, track spending, and ease tax season — in a fast-paced, ship-often environment as the company grew to profitability.

**Stack:** React Native + TypeScript · Python + Django · React + TypeScript

**Engineering highlights:**
- Built an in-house, Excel-like spreadsheet in React handling 1,000+ document sets — row virtualization to skip off-screen render cost, Web Workers to prefetch high-res images ahead of scroll, eliminating jank
- Led "split receipt" end-to-end: Figma mockups → data migration → backfill script, letting users itemize a single receipt across multiple tax categories with self-balancing reconciliation
- Built a custom navigator on React Navigation's low-level `useNavigationBuilder` hook for a branded onboarding flow with independently animated slide-in/out screens

---

### 🛠️ Also

**Senior Resources and Benefits** — Software Consultant (2026, freelance): built and deployed a full-stack Next.js retirement-planning app, compressing an estimated 2–3 month timeline to under 80 hours using agentic coding tools, delivered under budget.

---

### Tech I work with

**Frontend:** React Native · React · TypeScript · Next.js (SSR/SEO) · Redux · React Query · Figma
**Backend:** Node.js · Express · MongoDB · Python · Django · SQL · REST APIs · OAuth/JWT
**Tooling:** AWS (EC2, S3, Lambda) · Agentic coding (Claude Code) · Vercel · Xcode · Fastlane

---

📫 [LinkedIn](https://linkedin.com/in/justin-jaeger) · jjustinjaeger@gmail.com
