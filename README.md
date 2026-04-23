# Hi, I'm Ashakiran Jyoti 👋

**Junior QA Engineer** — Manual Testing · Playwright (JS & TS) · GitLab CI

---

## About Me

Junior QA Engineer with 2+ years of experience on two live production systems — **AMRUT 2.0**, a Government of India SCADA dashboard monitoring municipal water infrastructure across Indian cities, and an **Inventory Management System** for a manufacturing organisation.

I work under a Senior QA Lead in a cross-functional Agile/Scrum team. My day-to-day covers the full testing lifecycle: writing and executing manual test cases in Excel, raising detailed bug reports in GitLab, building Playwright automation scripts in JavaScript (POM framework), and participating in all Scrum ceremonies.

---

## Tech Stack

**Test Automation:** Playwright (JavaScript · TypeScript), Page Object Model, Data-Driven Testing, Custom Fixtures, Allure Reports  
**Manual Testing:** Functional, Regression, Smoke, Sanity, Exploratory, Boundary Value Analysis, Equivalence Partitioning, RBAC Testing  
**API Testing:** Playwright Request Context, Postman (REST API validation), Schema Validation, Multi-env Config  
**CI/CD & Version Control:** Git, GitHub, GitLab, GitLab CI, GitHub Actions  
**Databases:** MySQL, MS SQL Server  
**Tools:** VS Code, Playwright Trace Viewer, Excel (test documentation)  
**AI Workflow:** GitHub Copilot, Cursor AI, Windsurf, Claude, ChatGPT (sanitized prompts only — no real project data)

---

## Professional Experience

**Junior QA Engineer — Modern Communication Technology (MCOM), Pune** *(June 2024 – Present)*

**AMRUT 2.0 — Government of India SCADA Dashboard**
- Tested a live real-time web application monitoring water supply across Indian cities — 50+ pumping stations, live sensor data every 15–60 seconds, remote pump/valve controls, RBAC for field engineers and officers
- Wrote and executed **150+ manual test cases** across 8 modules covering functional, regression, RBAC, integration, and exploratory testing
- Built **50+ Playwright JS automation scripts** (POM) covering login flows, role-based visibility, dashboard filters, report exports, and device CRUD
- Found **critical security bug** — View-Only users could see SCADA control buttons (RBAC failure)
- Designed a real-time test protocol with the developer: inserting known sensor values so assertions were stable on live-updating dashboards
- Worked within **GitLab CI pipeline** — strict Merge Request process, Senior QA Lead reviewed all scripts before merge

**Inventory Management System — Manufacturing ERP** *(Internal)*
- Performed manual and automation QA across 7 modules: inward/outward stock, shortage detection, supplier management, 3-level product hierarchy, PDF/Excel reports
- Wrote and executed **150+ manual test cases**; cross-verified stock calculations via SQL queries against UI values
- Found **critical data integrity bug** — outward module had no server-side quantity validation, stock could go negative (caught via Boundary Value Analysis at qty = available + 1) — **blocked the release**
- Built **60+ Playwright JS regression scripts** covering boundary value flows, AJAX cascade dropdowns (`waitForResponse`), shortage thresholds, and master data CRUD

**Technical Intern — QA · IT JOBXS** *(October 2023 – May 2024)*
- Tested security features: bot detection, spam prevention, Google reCAPTCHA integration end-to-end
- Wrote test cases, executed functional testing, reported defects with developer collaboration

---

## Key Achievements

| Metric | Detail |
|---|---|
| 300+ test cases | Across 3 projects — Excel suites covering all STLC phases |
| 160+ automated tests | Playwright JS — login, RBAC, stock, SCADA, reports |
| 15+ critical bugs | Including RBAC security flaw & negative-stock bug before release |
| 70% regression time saved | 4–5 days/sprint → under 1 day via automation |

---

## Public Projects

### [DemoBlaze — E2E Playwright Framework (TypeScript)](https://github.com/ashakiranjyoti/demoblaze_playwright_ts)
Typed POM framework with Allure reports auto-published to GitHub Pages on every CI push. Covers login, products, cart, checkout — smoke + regression tagged suites, externalized test data.  
📊 [Live Test Report](https://ashakiranjyoti.github.io/demoblaze_playwright_ts/)

`Playwright` `TypeScript` `POM` `Allure` `GitHub Actions`

---

### [SauceDemo — Cross-Browser Playwright Framework (TypeScript)](https://github.com/ashakiranjyoti/saucedemo-playwright-ts)
Cross-browser framework (Chromium / Firefox / WebKit), typed page objects, externalized test data (JSON), CI with retries, screenshot + video on failure.

`Playwright` `TypeScript` `Cross-Browser` `GitHub Actions` `Data-Driven`

---

### [ReqRes REST API Framework (TypeScript)](https://github.com/ashakiranjyoti/REQRES_API-TS)
Typed API test framework with multi-environment config (DEV/QA switchable via env var), reusable typed assertion helpers. Covers GET, POST, PUT, DELETE with schema validation and negative testing.

`Playwright Request Context` `TypeScript` `Multi-env` `Schema Validation` `GitHub Actions`

---

### [Site Track System — Playwright Automation (JavaScript)](https://github.com/ashakiranjyoti/SITE_TRACK_SYSTEM)
60+ automated scripts covering a 3-level role-based field operations hierarchy (Sites → Tubewells → LCS), media upload edge cases, audit trails, and CRUD workflows.

`Playwright` `JavaScript` `POM` `CRUD` `Security Testing`

---

## Education

**B.Tech — Computer Science & Engineering**  
Dr. Babasaheb Ambedkar Technological University, Lonere · 2019–2023 · CGPA: 8.33/10

---

## Contact

📧 ashakirandjoti5501@gmail.com  
📍 Pune, Maharashtra, India  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/ashakiran-jyoti-b3489b252)  
[![GitHub](https://img.shields.io/badge/GitHub-ashakiranjyoti-333?style=flat&logo=github)](https://github.com/ashakiranjyoti)
