# 👋 Hello, World! I'm **Muradov Tehmez**

<p align="center">
  <img src="https://img.shields.io/badge/.NET%208-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 8" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-00599C?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Ethical Hacking" />
</p>

---

<!-- <p align="center">
  <img src="https://i.imgur.com/fqJzW2D.png" width="100%" alt="Profile Banner"/>
</p> -->

Welcome to my GitHub! 🚀 I’m a **C# .NET Developer**, **SQL Server Specialist**, and certified **Ethical Hacker**, passionate about designing **secure, high-performance, and scalable software architectures**.

I’m committed to bridging the gap between **software engineering** and **cybersecurity**, helping organizations in Azerbaijan and beyond to build reliable, secure, and innovative digital infrastructures.

---

## 🧠 About Me

* 🧾 **Full Name:** Muradov Tehmez
* 📍 **Location:** Nakhchivan, Azerbaijan
* 👨‍🏫 **Teaching:** Creator of a 5-month professional **C# & SQL Server course**
* 🥇 **Achievement:** Winner of **StartupFest Nakhchivan**
* 🔐 **Cybersecurity Role:** Active **Ethical Hacker** under NDA with **Qarabug MMC**
* 🌐 **Languages:** Azerbaijani (native), English (fluent), Turkish (fluent)

---

## 🧩 Professional Overview

With 4+ years of software development experience, I focus on building **business automation systems**, **desktop applications**, and **secure backend solutions**.
I’ve contributed to both **private sector** and **government projects**, particularly in HR, Retail, and Data Management fields.

My work philosophy combines **engineering precision**, **security-first coding**, and **user-centric design** — because truly great software must be both powerful and safe.

---

## 🛠️ Tech Stack & Skills

### 💻 Programming Languages

* **C#** – WinForms, OOP, business automation
* **Python** – Django backend, automation scripts
* **SQL** – Query optimization, triggers, procedures, views
* **Java**, **JavaScript**, **HTML5/CSS3**

### ⚙ Frameworks & Platforms

* **.NET Framework / .NET 8** – enterprise app architecture
* **Django** – Python backend framework
* **Entity Framework Core** – ORM, migrations, data layers
* **Microsoft SQL Server** – indexing, security roles, audit trails
* **Zebra ZPL** – Barcode & label generation
* **Arduino** – IoT prototyping
* **Git / GitHub**, **Docker (beginner)**

### 🔒 Cybersecurity Expertise

* **Ethical Hacking** – CVSSv3.1 scoring, exploit validation
* **Penetration Testing** – web, network, and endpoint analysis
* **OWASP Top 10** compliance
* **Wireshark** – traffic sniffing & vulnerability mapping
* **Secure Coding** – token-based auth, salted hashing, HTTPS enforcement

### 📚 Development Principles

* SOLID, KISS, and DRY methodologies
* Multi-layered architecture
* Dependency Injection (DI) and modular design
* CI/CD-ready configuration mindset
* Clean documentation and maintainability focus

---

## 🌟 Featured Projects

### 🏠 **[LuxeHomeEstate](https://luxehomeestate.az)** – Premium Real Estate Platform

> A production-grade **full-stack real estate platform** built for **Luxe Home Estate MMC** in Baku, Azerbaijan. Live at **[luxehomeestate.az](https://luxehomeestate.az)**.

**Tech Stack:**

* **Next.js 15** (App Router) + **React 19** – server components, server actions, streaming SSR
* **Tailwind CSS v4** – custom design system with dark mode, brand tokens, WCAG-compliant contrast
* **Prisma v6** + **Cloudflare D1** (SQLite) – type-safe ORM with edge-native database
* **Cloudflare Workers** (via OpenNext) – globally distributed serverless deployment
* **Cloudflare R2** – object storage for media assets
* **TypeScript** – end-to-end type safety

**Key Features:**

* 🔍 Advanced property search & filtering — listing type, property type, city/district cascade, price range, area, rooms, renovation status, document status, sorting & pagination
* 🏗️ Residential complex (project) showcase with status tracking
* 📝 Blog / content management system with SEO optimization
* 🤝 Official partnership system — multi-entity partner profiles, RBAC-gated admin CRUD, audit snapshots
* 🔐 Enterprise-grade admin panel — PBKDF2 password hashing, mandatory TOTP 2FA, D1-backed sessions with instant revocation, IP rate limiting, granular RBAC permissions
* 📱 Mobile-first responsive design with progressive disclosure filters
* 🗺️ Interactive map integration (Leaflet)
* ⭐ Favorites system (localStorage + server action)
* 📊 SEO layer — dynamic metadata, JSON-LD structured data (RealEstateAgent, Property, Article, Service, BreadcrumbList), sitemap, robots.txt
* 🌙 Dark mode — CSS custom property override strategy (no `dark:` prefixes), seamless theme switching via `next-themes`
* 📧 Contact form with email notifications (Resend)
* 🔔 Saved search notifications with Cloudflare Workers cron

**Architecture Highlights:**

* All public pages under `(site)` route group with shared Navbar + Footer layout
* Azerbaijani-language URL structure (`/emlaklar`, `/xidmetler`, `/layiheler`, `/blog`, `/elaqe`)
* Centralized domain constants — no hardcoded status strings
* `publicPropertyWhere()` guard ensures drafts and deleted listings never leak
* 40+ auth unit tests, full typecheck + build quality gate
* Staging environment with separate D1 database and Worker deployment

---

### 🌐 **Collabix** – Cloudflare Native Developer Collaboration Platform

> An open-source, ultra-fast collaboration platform for developers, creators, and innovators built entirely on the **Cloudflare Ecosystem**.

**Highlights:**

* Zero-latency architecture using Cloudflare Workers, Pages, and D1 (SQLite)
* Real-time WebSocket communication via Durable Objects
* Integrated project management (Kanban/Sprints) and gamification
* Native R2 Object Storage for secure file sharing
* Advanced RBAC and Zero Trust security principles
* Zero-dependency Vanilla JS frontend for maximum performance

---

### 🏷 **AzAgroPOS** – Retail & Service Management System

> A multi-layered **.NET 8 WinForms** POS platform managing retail & repair operations.

**Highlights:**

* XPrinter & Zebra Printer Integration
* Inventory, sales & debt tracking
* Real-time data analytics
* SQL triggers, views, and stored procedures
* Modern MaterialSkin UI/UX design

---

### 🔄 **360° Evaluation System** – Government HR Solution

> A large-scale **Django-based HR evaluation platform** for institutional performance tracking.

**Core Features:**

* Multi-role RBAC (SuperAdmin, HR, Employee)
* Peer, self, and supervisor evaluation cycles
* Likert-scale survey forms
* Dynamic performance charts (Chart.js)
* Secure JWT authentication, audit logging

---

### 🌍 **Saintstream Platform** – Multimedia & Content Management

> A Django-powered digital platform that delivers multimedia and streaming content.

**Features:**

* Modular REST API
* Dynamic content dashboard
* Admin & user role separation
* Responsive design (HTML, CSS, JS)

---

### 📦 **Barcode Management System** – Inventory Automation

> A full **C# + SQL Server** solution for retail inventory control.

**Capabilities:**

* Product creation, category linking
* ZPL-based barcode generation
* Label printing automation
* Real-time synchronization with database

---

## 🎓 Education & Certifications

* 🎓 **ISCODE Academy Graduate** – Computer Business & Programming
* 🧾 **Microsoft Certified:** SQL Server, C#
* 🧾 **Cisco Certified:** Networking & Security
* 🧾 **Oracle Certified:** Database Foundations

---

## 👨‍🏫 Teaching & Mentorship

I’m passionate about **sharing real-world experience** with future developers.
My **5-month professional course** focuses on:

* Building enterprise-grade apps in **C# .NET**
* Data modeling & optimization in **SQL Server**
* Secure login systems & business logic
* Architecture patterns & deployment workflows

> 🎯 **Goal:** To train developers who write clean, secure, and production-ready code.

---

## 🧭 Vision & Mission

> "My mission is to strengthen Azerbaijan’s software ecosystem by combining technical mastery with security discipline."

I believe in:

* Local innovation with global standards
* Empowering youth through tech education
* Promoting ethical development practices
* Building bridges between **software** and **cybersecurity**

---

## 📬 Contact & Links

<p align="center">
  <a href="https://github.com/tehmezmuradov"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/muradovtahmaz"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:muradoffcode@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

📱 **Phone / Telegram / WhatsApp:** +994 51 871 74 83
🌐 **Website:** [www.tehmez.dev](#) *(Coming soon)*
💼 **Portfolio:** [codersazerbaijan.dev](#)

---

## 💡 Fun Facts

* 🥇 **1st Place Winner** at StartupFest Nakhchivan
* 🔐 Performs **penetration testing** for real clients under NDA
* 👨‍🏫 Trains future developers through structured learning
* ⚙️ Enjoys experimenting with **IoT & embedded systems**
* 🎯 Motto: *“If it’s not secure, it’s not complete.”*

---

## 🤝 Collaboration Opportunities

Open to partnerships and collaborations in:

* 🔹 Enterprise Desktop & Web App Development
* 🔹 Cybersecurity Research & Penetration Testing
* 🔹 IT Education & Mentorship Programs

> 📫 Let’s connect and **build the future of secure software together!** 🚀

<!-- <p align="center">
  <img src="https://i.imgur.com/K3aQ3mT.png" width="100%" alt="Footer Banner"/>
</p> -->
