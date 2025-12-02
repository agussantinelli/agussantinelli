<h1 align="center">👋 Hey, I'm Agustín Santinelli</h1>

<p align="center">
  Third-year <strong>Systems Engineering</strong> student from Rosario, Argentina.<br/>
  Passionate about <strong>software engineering</strong>, <strong>clean architectures</strong>, and <strong>data-driven apps</strong>.
</p>

<p align="center">
  <a href="mailto:agustinsantinelli@gmail.com">
    <img src="https://img.shields.io/badge/Email-agustinsantinelli%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/agustin-santinelli-a60639300" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/agussantinelli" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-agussantinelli-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 🧑‍💻 About me

- 🎓 Third-year **Systems Engineering** student at **UTN-FRRO**.  
- 🌍 Based in **Rosario, Argentina**.  
- 💬 I enjoy working on **full-stack projects**, mixing **TypeScript**, **.NET**, **Node.js**, SQL and modern frontend frameworks.  
- 🧠 Comfortable switching between **academic projects** and **production-like architectures** (layered design, DTOs, services, testing).  
- 🚀 Currently building projects around:
  - financial dashboards,
  - ticketing systems,
  - inventory and reporting tools,
  - and sports / NBA stats platforms.

---

## 🛠 Tech stack & skills

### Languages
- **TypeScript**, **JavaScript**
- **C#**, **Java**
- **Python**
- **SQL**
- (also some **Smalltalk** from university 😊)

### Backend & APIs
- **Node.js**, **Express.js**
- **ASP.NET Core Web API**
- **.NET 8 / .NET Framework**
- REST API design, DTOs, domain services, layered architectures

### Frontend
- **React**, **Next.js**
- **Blazor WebAssembly**
- Classic **Java Servlets + JSP + JSTL**
- HTML5, CSS3

### Databases & Data Access
- **SQL Server**, **MySQL**, **PostgreSQL**
- **Entity Framework Core**
- Custom **JDBC** DAO layer
- Query optimization, reporting queries (ADO.NET, raw SQL)

### Tools, Dev & Testing
- **Git & GitHub**
- **Maven**, **npm**
- **Jest**, **Vitest**, **Playwright**, **Supertest**
- Swagger / OpenAPI, Postman

### Other
- Stripe & MercadoPago integrations  
- JWT authentication, role-based authorization  
- Report generation (PDF, charts) with tools like **PDFsharp** and **ScottPlot**

---

## 📊 GitHub stats

<p align="center">
  <img 
    src="https://github-readme-stats.vercel.app/api?username=agussantinelli&show_icons=true&theme=radical&hide_border=true" 
    alt="My GitHub stats" 
  />
</p>

<p align="center">
  <img 
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=agussantinelli&layout=compact&theme=radical&hide_border=true" 
    alt="Top languages" 
  />
</p>

---

## 🧩 Highlighted projects

### 🧮 FinanzApp – Personal Finance Dashboard
<p>
A full personal finance platform focused on the Argentinian context.  
It combines a modern Next.js frontend with an ASP.NET Core 8 backend, integrating multiple data sources (dollar quotes, crypto, CEDEARs, local/US stocks) into a single dashboard with caching, DTOs and a clean architecture.
</p>

<ul>
  <li>🖥 Frontend: Next.js + Material UI, dark / neon green theme.</li>
  <li>⚙️ Backend: ASP.NET Core 8 Web API + EF Core + SQL Server/PostgreSQL.</li>
  <li>📊 Features: asset tracking, quotes aggregation, and domain-driven design.</li>
</ul>

<p>
  <a href="https://github.com/agussantinelli/FinanzApp-FrontEnd" target="_blank">🔗 Frontend repo</a> •
  <a href="https://github.com/agussantinelli/FinanzApp-BackEnd" target="_blank">🔗 Backend repo</a>
</p>

---

### 🎮 BuyJugador – Gaming Inventory & Sales System
<p>
Academic project for UTN (IDE course): a multi-client inventory and sales system for a gaming hardware store.  
The solution includes a Blazor WebAssembly web client, a WinForms desktop client, and an ASP.NET Core Web API, all sharing the same domain model and database.
</p>

<ul>
  <li>🌐 Blazor WASM frontend with dashboards and low-stock alerts.</li>
  <li>🪟 WinForms desktop app for back-office workflows and reporting.</li>
  <li>🧱 Clean layered architecture (Domain, Data, Services, API, Clients).</li>
  <li>📈 Reports with ScottPlot (charts) + PDFsharp (PDF export).</li>
</ul>

<p>
  <a href="https://github.com/agussantinelli/ProyectoIDE-BuyJugador" target="_blank">🔗 Main repository</a>
</p>

---

### 🎫 TicketApp – Event Ticketing Platform (Venta de Entradas)
<p>
Full ticketing platform for events, with seat maps, role-based flows (user, organiser, admin), and online payments.  
The system is split into a React + TypeScript frontend and a Node.js + Express + Prisma backend with MySQL.
</p>

<ul>
  <li>🧭 Frontend: React (Vite), Context API, protected routes, Stripe & MercadoPago integration, PDF ticket generation.</li>
  <li>🗄 Backend: Node.js + Express + Prisma ORM, JWT auth, role protection, webhooks for Stripe/MercadoPago.</li>
  <li>🧪 Testing: Vitest + Playwright on the frontend, Jest + Supertest on the backend.</li>
</ul>

<p>
  <a href="https://github.com/valenpeppi/FrontEnd-Venta-de-Entradas" target="_blank">🔗 Frontend repo (team)</a> •
  <a href="https://github.com/valenpeppi/BackEnd-Venta-de-Entradas" target="_blank">🔗 Backend repo (team)</a>
</p>

---

### 💰 ImpulsaMe – Java Crowdfunding Platform
<p>
Crowdfunding web application built with “classic” Java web technologies.  
Users can create, discover and fund projects. Admins moderate content, approve projects and manage the platform.  
Includes Stripe payments in ARS and role-based access control.
</p>

<ul>
  <li>🌐 Web: Java Servlets + JSP + JSTL, running on Apache Tomcat.</li>
  <li>🗄 Persistence: MySQL + custom JDBC DAO layer.</li>
  <li>🧱 Architecture: three-tier (Presentation – Control – Data Access).</li>
  <li>💳 Payments: Stripe Checkout integration, UUID-based tracking for payment attempts.</li>
</ul>

<p>
  <a href="https://github.com/martin-ratti/ProyectoJava-Crowdfunding" target="_blank">🔗 Project repository (team)</a>
</p>

---

### 🏀 Promiedos NBA (Work in progress)
<p>
A long-term idea: a modern stats and info platform for the NBA, fully in Spanish.  
The goal is to provide live scores, advanced player stats (PPG, APG, BPG, SPG, stocks), historical data (MVPs, All-Star, Hall of Fame), and rich static pages for each franchise, including history, arena photos and cultural background.
</p>

<ul>
  <li>Frontend (planned): <strong>Astro + TypeScript</strong>, modern UI, SEO-friendly.</li>
  <li>Backend (planned): <strong>Node.js + Express + MySQL</strong>, designed to later extend to other leagues (EuroLeague, ACB, LNB, G League, Olympics, etc.).</li>
</ul>

<p>
  <a href="https://github.com/agussantinelli/Promiedos-NBA-FrontEnd" target="_blank">🔗 Promiedos NBA FrontEnd</a> •
  <a href="https://github.com/agussantinelli/Promiedos-NBA-BackEnd" target="_blank">🔗 Promiedos NBA BackEnd</a>
</p>

---

## 🤝 Let’s connect

If you’re working on backend-heavy systems, financial apps, sports data, or full-stack projects with TypeScript / .NET / Java,  
feel free to reach out — I’m always open to learning, collaborating and contributing.

- 📧 Email: **agustinsantinelli@gmail.com**  
- 💼 LinkedIn: [linkedin.com/in/agustin-santinelli-a60639300](https://www.linkedin.com/in/agustin-santinelli-a60639300)
