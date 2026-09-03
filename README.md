<div align="center">

# Ngo Nhat Huy

### Full Stack Developer · Backend · Enterprise Integration

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono\&size=16\&pause=1000\&color=4ADE80\&center=true\&vCenter=true\&width=700\&lines=Full+Stack+Developer+with+Backend+Focus;NestJS+%7C+Angular+%7C+React+%7C+PostgreSQL;SAP+%E2%86%94+E-Sourcing+Enterprise+Integration;Logistics+%7C+Procurement+%7C+Warehouse+Systems;Learning+System+Design+%7C+DevOps+%7C+Cloud)](https://git.io/typing-svg)

<br/>

[![Email](https://img.shields.io/badge/ngonhathuy6878%40gmail.com-EA4335?style=flat-square\&logo=gmail\&logoColor=white)](mailto:ngonhathuy6878@gmail.com)
[![Location](https://img.shields.io/badge/Ho_Chi_Minh_City-Vietnam-red?style=flat-square\&logo=googlemaps\&logoColor=white)](https://maps.google.com/?q=Ho+Chi+Minh+City)
[![GitHub](https://img.shields.io/badge/GitHub-nnh2x-181717?style=flat-square\&logo=github)](https://github.com/nnh2x)
![Profile Views](https://komarev.com/ghpvc/?username=nnh2x\&style=flat-square\&color=4ade80\&label=profile+views)

</div>

---

## 👨‍💻 About Me

```typescript
const huy = {
  role: "Full Stack Developer",

  focus: [
    "Backend Development",
    "Enterprise Integration",
    "System Design",
    "Database Performance",
  ],

  domains: [
    "Procurement / E-Sourcing",
    "Logistics",
    "Warehouse Management",
    "Order Management",
  ],

  technologies: {
    backend: ["NestJS", "Node.js", ".NET"],
    frontend: ["Angular", "ReactJS", "React Native"],
    database: ["PostgreSQL", "MySQL", "Redis"],
    infrastructure: ["Docker", "AWS", "Linux"],
    observability: ["Grafana", "Loki", "Promtail"],
  },

  currentlyLearning: [
    "DevOps",
    "Linux & Networking",
    "AWS / Azure",
    "Distributed Systems",
    "Microservices Integration",
  ],

  engineeringInterests: [
    "Reliable enterprise integrations",
    "Database optimization",
    "Scalable backend systems",
    "Clean and maintainable code",
  ],
};
```

I am a **Full Stack Developer with a strong interest in backend engineering and enterprise systems**.

My work has mainly focused on business-critical platforms in **Logistics, Warehouse Management and Procurement**, where systems need to exchange data reliably across multiple services and external platforms.

Recently, I have been working deeply with **SAP ↔ E-Sourcing integration**, including procurement flows such as:

```text
PR → RFQ / RFP → Quotation → Vendor Selection → PO
```

Beyond feature development, I am actively improving my knowledge of **system design, database architecture, distributed systems, DevOps and cloud infrastructure**.

---

# 🚀 Current Project

## Procurement / E-Sourcing Platform

**Full Stack Developer · Dec 2025 → Present**

Enterprise procurement platform integrated with SAP.

```text
SAP
 │
 ▼
Purchase Requisition
 │
 ▼
RFQ / RFP
 │
 ▼
Supplier Quotation
 │
 ▼
Vendor Evaluation
 │
 ▼
Purchase Order
 │
 ▼
SAP
```

### Main responsibilities

* Develop and maintain **Purchase Requisition (PR)** workflows
* Build **RFQ / RFP** sourcing processes
* Develop supplier invitation and quotation workflows
* Build supplier-facing portal features
* Implement Master Data management
* Design REST APIs for frontend and external integrations
* Integrate procurement data between **SAP and E-Sourcing**
* Handle synchronization of PR, PR Item, PO and purchasing quantities
* Handle PO quantity changes and item cancellation scenarios
* Build integration request logging and troubleshooting mechanisms
* Optimize PostgreSQL queries and high-volume tables
* Implement email integration for procurement document processing

### SAP Integration

Typical integration flow:

```text
SAP
 │
 │ IDoc / Integration Data
 ▼
E-Sourcing
 │
 ├── Purchase Requisition
 ├── PR Item
 ├── Open Quantity
 ├── Ordered Quantity
 ├── Vendor
 └── Purchase Order
```

Example quantity synchronization:

```text
PR Quantity       = 100
Ordered Quantity  = 60
Open Quantity     = 40
```

When PO quantities change or PO items are cancelled, procurement quantities are synchronized again so E-Sourcing reflects the latest SAP state.

### Tech Stack

`NestJS` `PostgreSQL` `Angular` `ReactJS` `AWS` `Docker`

---

# 💼 Experience

## NDS Vietnam JSC

### Full Stack Developer

**Jun 2024 → Jun 2026**

Worked on logistics platforms supporting order management, delivery planning and real-time transportation operations.

```text
Order
  ↓
Delivery Planning
  ↓
Trip
  ↓
Driver
  ↓
Tracking
  ↓
Delivery Result
```

### Responsibilities

* Developed backend services using **NestJS**
* Built administrative applications using **Angular**
* Developed mobile features using **React Native**
* Designed and maintained RESTful APIs
* Integrated external systems including:

  * OMS
  * GPS providers
  * Banking services
  * Loyalty platforms
* Developed order and delivery trip management features
* Worked with PostgreSQL and MySQL databases
* Investigated query performance and connection issues
* Implemented backend logging and monitoring
* Used **Loki + Promtail + Grafana** for centralized logs
* Worked with Redis for caching and application data
* Participated in Agile/Scrum development using Jira and Git

### Tech Stack

`NestJS` `Angular` `React Native` `PostgreSQL` `MySQL` `Redis` `.NET` `Grafana` `Loki`

---

## Smartlog

### Developer

**Mar 2023 → Apr 2024**

Worked on Warehouse Management System features for inventory and logistics operations.

### Main features

* Inventory management
* Inbound / outbound operations
* Inventory tracking
* Stock monitoring
* Expiry alerts
* Shipment management
* Delivery status tracking
* Logistics reporting

### Tech Stack

`NestJS` `PostgreSQL` `Angular`

---

# 🧩 Systems & Domain Knowledge

During my work, I have had the opportunity to work with and study enterprise system relationships such as:

```text
                 ┌───────────┐
                 │    ERP    │
                 │    SAP    │
                 └─────┬─────┘
                       │
              Master / Business Data
                       │
       ┌───────────────┼───────────────┐
       │               │               │
       ▼               ▼               ▼
      OMS             WMS             TMS
 Order Mgmt      Warehouse Mgmt   Transport Mgmt
       │               │               │
       └───────────────┼───────────────┘
                       │
                       ▼
                Business Workflow
```

Areas I am particularly interested in:

* OMS / WMS / TMS integration
* Master Data Management
* ERP integration
* API-based system integration
* Transaction consistency
* Event-driven architecture
* Outbox Pattern
* Retry mechanisms
* Idempotency
* Distributed transaction handling
* Integration logging and observability

---

# 🛠 Tech Stack

<div align="center">

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge\&logo=dotnet\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)

### Backend

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge\&logo=nestjs\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge\&logo=dotnet\&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge\&logo=jest\&logoColor=white)

### Frontend

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge\&logo=angular\&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge\&logo=react\&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge\&logo=react\&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge\&logo=tailwindcss\&logoColor=white)

### Database & Cache

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge\&logo=redis\&logoColor=white)

### Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)

### Monitoring

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge\&logo=grafana\&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-2C3239?style=for-the-badge\&logo=grafana\&logoColor=white)

### Development Tools

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge\&logo=jira\&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge\&logo=postman\&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=for-the-badge\&logo=typeorm\&logoColor=white)

</div>

---

# 🗄 Database Engineering

PostgreSQL is one of the areas I spend significant time working with.

Topics I regularly deal with include:

```text
Query Optimization
      │
      ├── Index
      ├── Execution Plan
      ├── Pagination
      └── Large Dataset Queries

Connection Management
      │
      ├── Connection Pool
      ├── pg_stat_activity
      └── Connection Limits

Data Integrity
      │
      ├── Foreign Keys
      ├── Transactions
      ├── Constraints
      └── Database Migrations
```

I am particularly interested in designing database schemas that remain maintainable as systems and business rules grow.

---

# 🔌 Enterprise Integration

A major part of my recent work involves communication between independent systems.

Some problems I have worked with or studied include:

```text
Service A
   │
   ▼
REST API
   │
   ▼
Service B
   │
   ├── Success
   │
   └── Failure
          │
          ▼
        Retry
          │
          ├── Idempotency
          ├── Outbox
          └── Logging
```

Key areas:

`REST API` · `SAP Integration` · `IDoc` · `Retry` · `Outbox Pattern` · `Idempotency` · `Integration Logs`

---

# 📧 External Platform Integration

Besides traditional business-system integration, I have also worked with external services such as:

```text
Application
    │
    ├── Google OAuth
    │      └── Gmail API
    │
    ├── Microsoft OAuth
    │      └── Microsoft Graph
    │
    ├── GPS Providers
    │
    ├── Banking APIs
    │
    └── Loyalty Platforms
```

These integrations involve authentication, callback handling, token management, synchronization and error tracking.

---

# 📚 Currently Learning

My current learning path focuses on moving deeper from application development into backend and infrastructure engineering.

```text
Full Stack
   │
   ▼
Backend Engineering
   │
   ├── System Design
   ├── PostgreSQL
   ├── Distributed Systems
   └── Integration Architecture
   │
   ▼
DevOps
   │
   ├── Linux
   ├── Networking
   ├── Docker
   ├── CI/CD
   ├── AWS
   └── Azure
```

Current topics:

`Linux` · `Networking` · `Docker` · `AWS` · `Azure` · `CI/CD` · `Microservices` · `Distributed Systems`

---

# 🎯 Engineering Goals

```text
Write better code
      ↓
Understand the system
      ↓
Understand infrastructure
      ↓
Design reliable systems
      ↓
Build scalable software
```

My goal is not only to implement features, but to better understand:

* why systems are designed in a certain way,
* how data flows between services,
* how failures should be handled,
* how databases behave under load,
* and how applications run in production.

---

# 📊 GitHub Stats

<div align="center">

[![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nnh2x\&theme=tokyonight)](https://github.com/nnh2x)

[![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=nnh2x\&theme=tokyonight)](https://github.com/nnh2x)
 
[![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=nnh2x\&theme=tokyonight)](https://github.com/nnh2x)

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=nnh2x\&theme=tokyo-night\&hide_border=true\&area=true)](https://github.com/nnh2x)

![Followers](https://img.shields.io/github/followers/nnh2x?style=flat-square\&color=3b82f6\&label=Followers)

</div>

---

# 🎓 Education

**Information Technology**
Ho Chi Minh City, Vietnam

---

# 📬 Contact

<div align="center">

### Let's Connect

[![Email](https://img.shields.io/badge/Email-ngonhathuy6878%40gmail.com-EA4335?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:ngonhathuy6878@gmail.com)

[![GitHub](https://img.shields.io/badge/GitHub-nnh2x-181717?style=for-the-badge\&logo=github)](https://github.com/nnh2x)

<br/>

> *"First, solve the problem. Then, write the code."*

</div>
