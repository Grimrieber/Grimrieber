# Stephan Rieber

**Full-Stack ASP.NET Software Engineer** · Lombard, IL

I build and modernize enterprise web applications on the Microsoft stack — currently in .NET 10, Blazor, and EF Core, with eleven years of VB.NET, C#, and MSSQL behind it. I work end to end: schema design and query tuning, through API layers, to the front end, plus the deployment and monitoring around it.

[![Portfolio](https://img.shields.io/badge/Portfolio-grimrieber.github.io-2ea44f?style=flat-square&logo=github&logoColor=white)](https://grimrieber.github.io/Portfolio/)
[![Email](https://img.shields.io/badge/Email-stephanr%40spydernetworkinc.com-0A66C2?style=flat-square&logo=maildotru&logoColor=white)](mailto:stephanr@spydernetworkinc.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-stephanrieber-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/stephanrieber)

---

## Projects

Every repository below builds and runs. Each README states plainly what works, what needs setup, and what isn't built — no repo claims more than it does.

### [ApexCoaching](https://github.com/Grimrieber/ApexCoaching) — personal-training marketplace
`.NET 10` `Blazor Server` `EF Core 10` `ASP.NET Core Identity` `SQL Server` `Stripe Connect`

Twelve-entity domain model behind three role-scoped portals — admin, trainer, and client — sharing one identity system. Stripe Connect handles split payments with a platform commission per trainer; with no keys configured it falls back to simulated checkout so every flow stays walkable. Public marketing site, trainer directory, and a contact form that feeds the admin lead pipeline.

*All three portals verified working end to end against seeded data.*

### [SEOOptimizer](https://github.com/Grimrieber/SEOOptimizer) — site auditing tool
`VB.NET` `HtmlAgilityPack` `ASP.NET Web API` `SQL Server`

A real crawler: HTTPS and mixed-content checks, meta and heading analysis, image `alt` coverage, internal link mapping, and broken-link detection with separate 5s/3s timeout budgets so one dead host can't stall a crawl. X509 validation callbacks keep it alive against real-world HTTPS. Audit, report, billing, and user concerns split into independent services.

*Verified by running a live audit and checking the results.*

### [MultiTool](https://github.com/Grimrieber/MultiTool) — multi-app platform
`VB.NET` `ASP.NET WebForms` `Entity Framework` `MSSQL`

Several business tools behind one hand-built account system — registration, email verification, expiring password-reset tokens. Includes an AdventureWorks reporting dashboard with an embedded RDLC report and a server-side PDF generator.

### [OnlineShop](https://github.com/Grimrieber/OnlineShop) — multi-vendor marketplace
`VB.NET` `Entity Framework` `SQL Server`

Seventeen tables covering shops, products, categories, cart, orders, payments, reviews, and favourites — plus two-tier messaging (buyer↔seller threads and shop-level enquiries) and product view tracking.

### [FoodRecipes](https://github.com/Grimrieber/FoodRecipes) — recipe manager
`VB.NET` `T-SQL`

The database work is the point: tables, views, and stored procedures written by hand and kept in source, with nutrition reference data and a Python importer.

### Also public

[Gamba](https://github.com/Grimrieber/Gamba) · [CouponApp](https://github.com/Grimrieber/CouponApp) · [TinyTools](https://github.com/Grimrieber/TinyTools) — smaller projects, honestly labelled in their READMEs.

[PythonFoundations](https://github.com/Grimrieber/PythonFoundations) — learning Python from scratch in 2023, twelve exercises in the order written.

### Client work — described, not published

**Enterprise data warehouse** (VB.NET · MSSQL · ETL) — configurable vendor ingest pipeline, upload through validate, stage, and commit; rebuilt as V2 after production feedback.

**SAML 2.0 SSO billing portal** (VB.NET · IIS) — service provider with metadata endpoint and single logout, built twice (middleware and dependency-free) to compare control against maintenance cost.

Source stays private. Happy to walk through either in an interview.

---

## Technical Stack

**Languages & frameworks** — `.NET 10` `C#` `ASP.NET Core` `Blazor` `EF Core` `VB.NET` `ASP.NET MVC` `WebForms` `Web API` `JavaScript` `HTML5` `CSS3`

**Data** — `MSSQL` schema design, stored procedures, triggers, views, functions · query optimization · `SSRS` · ETL & data warehousing

**Practice & infrastructure** — `IIS` deployment · `Git` · REST & OData integration · `SAML 2.0` · `Stripe` · code review · production debugging · performance profiling

---

## Background

**Senior Software Developer / Full-Stack VB.NET Developer** — Sirius Business, Lombard IL · *2015–Present*
Refactored legacy VB.NET applications for a **20% page-load improvement**; built Web API endpoints against HTML5/JavaScript front ends; introduced structured code review and production diagnostics that **cut production bugs 25%**; mentored a junior developer to mid-level in 12 months.

**IT Director / DBA / Data Analyst** — Air. Water. Energy, Carol Stream IL · *2016–2023*
Directed IT operations and **reduced system downtime 30%**. Owned MSSQL schema design, stored procedures, and performance tuning; built automated SSRS dashboards for executive reporting.

---

<sub>📫 <a href="mailto:stephanr@spydernetworkinc.com">stephanr@spydernetworkinc.com</a> · Open to full-stack .NET roles</sub>
