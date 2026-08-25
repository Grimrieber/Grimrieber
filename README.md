# Stephan Rieber

**Full-Stack ASP.NET Software Engineer** · Lombard, IL

I build and modernize enterprise web applications on the Microsoft stack — currently in .NET 10, Blazor, and EF Core, with eleven years of VB.NET, C#, and MSSQL behind it. I work end to end: schema design and query tuning, through API layers, to the front end, plus the deployment and monitoring around it.

[![Email](https://img.shields.io/badge/Email-stephanr%40spydernetworkinc.com-0A66C2?style=flat-square&logo=maildotru&logoColor=white)](mailto:stephanr@spydernetworkinc.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-stephanrieber-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/stephanrieber)
[![Portfolio](https://img.shields.io/badge/Portfolio-grimrieber.github.io%2FPortfolio-2ea44f?style=flat-square&logo=github&logoColor=white)](https://grimrieber.github.io/Portfolio)

---

## Featured Work

Most of what I build is either client-owned or internal business software, so the source stays private. These are writeups of real systems — architecture, decisions, and outcomes. **Happy to walk through any of them live, including code, in an interview.**

### 🏋️ Apex Coaching — Personal Training Marketplace
`.NET 10` `Blazor Server` `EF Core 10` `ASP.NET Core Identity` `SQL Server` `Stripe Connect`

A full multi-tenant marketplace connecting trainers with clients, with three distinct role-based portals behind a single auth system.

- **Domain model:** Trainer, ClientProfile, Booking, Engagement, ServicePackage, TrainingProgram, Payment, and Lead entities mapped through EF Core with code-first migrations
- **Three portals from one identity system** — Admin (overview, trainer approval, lead pipeline), Trainer (clients, packages, earnings, profile), and Client (booking, program, billing)
- **Stripe Connect marketplace payments** — subscriptions and one-off bookings with the platform fee split per trainer commission rate; simulated checkout when no keys are set
- **Public marketing surface** (pricing, how-it-works, trainer directory, demo) served from the same app with a separate layout
- .NET 10 · 52 source files · EF Core code-first migrations

> Built on the current .NET release with interactive server rendering — the same patterns I'd bring to a modern greenfield project.

---

### 🔍 SEO Optimizer — Site Audit SaaS
`VB.NET` `ASP.NET` `HtmlAgilityPack` `Web API` `SQL Server`

A crawler-driven site auditing tool structured as a subscription product, with the audit engine cleanly separated from billing and reporting.

- **Audit engine** parses live pages via HtmlAgilityPack and scores: HTTPS enforcement, mixed-content detection, meta title/description presence, H1–H3 heading hierarchy, image `alt` coverage, and internal/external link mapping
- **Broken-link detection** with independent request timeouts (5s page / 3s link) so one dead host can't stall a crawl
- **Certificate handling** through `X509Certificate` validation callbacks for HTTPS edge cases
- **Service-layer separation:** `AuditService`, `BillingService`, `ReportService`, `UserService` — each independently testable
- Four-service architecture · live HTTP crawler

---

### 🧰 MultiTool — Multi-App Web Platform
`VB.NET` `ASP.NET WebForms` `Entity Framework` `MSSQL` `PDF Generation`

A single authenticated platform hosting several independent business tools behind shared identity and data access.

- **Complete account system** built from scratch: registration, login, email verification, password reset, and user settings
- **AdventureWorks reporting dashboard** — parameterized queries and aggregations over the sample enterprise schema
- **Resume/Portfolio generator** with server-side PDF output via a dedicated `PDFGenerator` class
- **Calculator suite** for business/financial computations
- Shared EF `MultiToolContext` and master-page layouts across all apps
- Three applications behind one shared account system

---

### 🏢 Enterprise Data Warehouse & Vendor Import *(client work — code private)*
`VB.NET` `ASP.NET` `MSSQL` `ETL`

Vendor data ingestion platform replacing a manual spreadsheet process.

- Configurable **upload → validate → stage → commit** pipeline handling varied vendor file formats
- Vendor management and data-correction screens for non-technical staff
- Reporting dashboard surfacing ingest status and data quality
- Delivered as V1 then rearchitected as V2 after production feedback

---

### 🔐 SAML SSO Billing Portal *(client work — code private)*
`VB.NET` `ASP.NET` `SAML 2.0` `IIS`

Single sign-on integration letting members reach billing preferences through an external identity provider.

- **SAML 2.0 service provider** with metadata endpoint, assertion consumer, and single-logout
- Built in **two variants** — middleware-based and a dependency-free custom implementation — to evaluate the tradeoff between control and maintenance burden
- Custom lightweight logging module for auditing the authentication handshake

---

## Technical Stack

**Languages & Frameworks**
`.NET 10` `C#` `ASP.NET Core` `Blazor` `EF Core` `VB.NET` `ASP.NET MVC` `WebForms` `Web API` `Entity Framework` `JavaScript` `HTML5` `CSS3`

**Data**
`MSSQL` — schema design, stored procedures, triggers, functions, views · Query optimization · `SSRS` reporting · ETL & data warehousing

**Practice & Infrastructure**
`IIS` deployment · `Git` · REST integration · `SAML 2.0` · `Stripe` · Code review · Production debugging · Performance profiling

---

## Background

**Senior Software Developer / Full-Stack VB.NET Developer** — Sirius Business, Lombard IL · *2015–Present*
Refactored legacy VB.NET applications for a **20% page-load improvement**; built Web API endpoints against HTML5/JS front ends; introduced structured code review and production diagnostics that **cut production bugs 25%**; mentored a junior developer to mid-level in 12 months.

**IT Director / DBA / Data Analyst** — Air. Water. Energy, Carol Stream IL · *2016–2023*
Directed IT operations and **reduced system downtime 30%**. Owned MSSQL schema design, stored procedures, and performance tuning; built automated SSRS dashboards for executive reporting.

---

<sub>📫 <a href="mailto:stephanr@spydernetworkinc.com">stephanr@spydernetworkinc.com</a> · Open to full-stack .NET roles</sub>
