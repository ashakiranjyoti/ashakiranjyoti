# Hi, I'm Ashakiran Jyoti 👋

**QA Automation Engineer** — Playwright (JavaScript) · Manual Testing · GitLab CI

---

## About Me

I'm a QA Automation Engineer with 2+ years of experience testing web applications. I have worked on two live systems — a government IoT/SCADA monitoring platform for municipal water infrastructure (confidential client), and an internal enterprise inventory management system.

My work covers the full testing lifecycle: writing and executing manual test cases, building Playwright automation frameworks using Page Object Model, raising and tracking bugs, and working within Agile/Scrum teams. I work with Git and GitLab CI daily as part of my workflow.

---

## Tech Stack

**Test Automation:** Playwright (JavaScript), Page Object Model (POM), Data-Driven Testing, End-to-End Testing  
**Manual Testing:** Functional, Regression, Smoke, Exploratory, Boundary Value Analysis, Negative Testing  
**API Testing:** Playwright Request Context, Postman (REST API validation)  
**CI/CD & Version Control:** Git, GitLab, GitLab CI (internal), GitHub Actions  
**Databases:** MySQL, MS SQL Server (SQL queries for test data verification)  
**Tools:** VS Code, npm, Playwright Trace Viewer, Excel (test documentation)  
**Domain Knowledge:** IoT/SCADA systems, real-time data testing, role-based access control

---

## Professional Experience

**QA Automation Engineer — Modern Communication Technology, Pune** *(June 2024 – Present)*

**Project 1 — Government IoT/SCADA Monitoring Platform** *(Confidential Client)*
- Tested a real-time web application monitoring municipal water infrastructure — live sensor data from pump stations, OHT levels, valve states, and zone-level reporting for field operators
- Designed and executed **150+ manual test cases** covering role-based access (Admin, Full Control, View-Only), live dashboard, satellite map, device configuration, reports, and alert management
- Built a **Playwright automation suite** (JavaScript, POM) for login flows, role-based visibility, dashboard filters, report date validation, and device CRUD with conditional field logic
- Found **6 high-severity bugs** — including OHT percentage calculating incorrectly for remote station types, location filter silently dropping across modules, and map navigation passing wrong station ID to control screen
- Worked within an internal **GitLab CI pipeline** — pushed scripts via Git merge requests, debugged CI failures by reading job logs, fixed timing issues using `waitForResponse()` over arbitrary waits

**Project 2 — Internal Inventory Management System**
- Performed manual and automation QA for an inventory platform covering inward/outward stock flows, shortage detection, supplier management, and reporting across a 3-level product hierarchy
- Wrote and executed **120+ test cases**; cross-verified live stock calculations via SQL queries against UI-displayed values
- Found a **critical data integrity bug** — outward module had no server-side quantity validation, stock could go negative; also found cascading dropdown reset failure causing mismatched database records
- Built Playwright regression suite covering boundary value flows, shortage threshold tests, and master data CRUD

**Technical Intern — QA · ITJOBXS** *(October 2023 – May 2024)*
- Executed manual functional and regression testing; documented test cases in Excel and tracked bugs through resolution
- Wrote foundational Playwright scripts for login validation; performed REST API testing via Playwright request context

---

## Public Projects

### [SauceDemo E-Commerce — Playwright Automation Framework](https://github.com/ashakiranjyoti/saucedemo-playwright)
End-to-end Playwright framework (JavaScript, POM) automating the complete purchase journey across 5 user types using data-driven testing. Integrated with **GitHub Actions** CI for execution on every push.

`Playwright` `JavaScript` `POM` `GitHub Actions` `Data-Driven Testing`

---

## Education

**B.Tech — Computer Science & Engineering**  
Dr. Babasaheb Ambedkar Technological University, Lonere · 2019–2023 · CGPA: 8.33/10

---

## Contact

📧 ashakirandjoti5501@gmail.com  
📍 Pune, Maharashtra, India  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/ashakiran-jyoti-b3489b252)
