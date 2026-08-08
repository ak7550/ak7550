# 👋 Hi, I'm Aniket Kumar Ghosh

### Senior Backend Engineer | Node.js • TypeScript • NestJS | Distributed Systems • AI • Cloud

I build backend systems that solve real business problems — from billing and revenue infrastructure to AI-integrated developer tooling, marketplace platforms, and production automation.

Over 4+ years of professional experience, I've worked primarily in the **Node.js and TypeScript ecosystem**, building microservices, REST APIs, event-driven systems, cloud-native services, and distributed backend architectures.

Currently at **NetApp**, where I work across billing infrastructure and the Marketplace Control Tower platform.

---

## 🚀 What I Do

- Design and build scalable **backend and distributed systems**
- Work extensively with **Node.js, TypeScript, NestJS, Fastify and Express**
- Build and operate services on **AWS and Kubernetes**
- Design **event-driven architectures** using Kafka, RabbitMQ and Redis
- Integrate **AI/LLMs into backend systems**, including MCP-based tooling
- Work on **billing, subscription, marketplace and revenue systems**
- Build production systems with strong **observability, resilience and automation**
- Contribute to architecture, HLDs and cross-functional engineering initiatives

---

## 💼 Professional Experience

### NetApp — Software Engineer 3
**Bengaluru, India | July 2026 – Present**

Working on the **Marketplace Control Tower** platform as part of the founding engineering team.

- Designed the HLD and led a cross-functional team of 4 engineers to build and deploy an end-to-end AI chat application using **NestJS, Next.js and the OpenAI SDK**.
- Engineered a **Node.js MCP (Model Context Protocol) server** that exposes production and analytics database data to LLMs, enabling automated root-cause investigation of charging anomalies.
- Upgraded Kubernetes Helm charts and established **Jenkins CI/CD pipelines** to containerize and distribute core licensing microservices across internal Kubernetes clusters.
- Contributed to the architecture and engineering design of Marketplace Control Tower using **Go, Temporal and Dynatrace**.

### NetApp — MTS / Software Engineer II
**BlueXP | Bengaluru, India | September 2023 – July 2026**

Worked on NetApp's licensing, charging and revenue infrastructure.

#### Selected impact

- 💰 **Recovered ~$1M in previously unbilled revenue** in Q1 FY24-25 by designing and shipping a backend back-charging engine in vanilla JavaScript.
- 📉 **Reduced charging errors and production incidents by 12%** by building an automated charging-alert investigation service.
- ⚡ **Reduced manual revenue-loss calculation effort by 52% YoY** by building a self-service revenue-loss calculator.
- 🤖 Led a team of 4 engineers to build an end-to-end **AI chat application for charging investigations**.
- 🔧 Built a **billing-preference API** using Node.js and Fastify, allowing customers to control marketplace subscription routing.
- 📊 Integrated tenancy-v4 data into the platform reporting pipeline to expand SQL-based analytics.
- 🔄 Automated recurring data-integrity checks through TeamCity pipelines.
- 🏗️ Designed and scaled distributed billing systems handling customer transactions across microservices.

### Anchanto — Software Engineer
**Pune, India | June 2022 – September 2023**

Worked on order management, warehouse management and parcel-tracking systems.

- Integrated the Anchanto OMS with **8+ international marketplaces and carriers** across Vietnam, UAE, Korea and Thailand.
- Built asynchronous **REST, SOAP and plugin-based integrations**.
- Supported UAT and go-live activities for 8 integration projects.
- Implemented retry mechanisms, improved logging throughput and restructured schedulers, improving server performance by **28%**.
- Designed and maintained scalable backend systems using the **MERN stack with SQL and NoSQL databases**.

---

# 🛠️ Tech Stack

### Languages & Runtime

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)

### Backend & Frameworks

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat&logo=fastify&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)

### Databases & Messaging

- **PostgreSQL**
- **MySQL**
- **MongoDB**
- **Redis**
- **Apache Kafka**
- **RabbitMQ**

### Cloud & Infrastructure

- **AWS:** RDS, DynamoDB, CloudWatch, Lambda, S3, EC2, ECS, ECR, SQS, EKS
- **Kubernetes**
- **Docker**
- **Helm**
- **Jenkins**
- **TeamCity**
- **GitHub Actions**
- **AWS / Supabase / Vultr / Hetzner**

### Observability

- Dynatrace
- Grafana
- Kibana
- Signoz

---

# 🚀 Selected Projects

## Multi-Broker Algorithmic Trading Automation

A production-grade autonomous trading platform designed around a broker-agnostic architecture.

**Status:** Daily live trading | Production

### Highlights

- Receives **TradingView webhooks and WhatsApp/Telegram signals**.
- Evaluates trading strategies against live and historical market data.
- Executes orders across multiple brokers.
- Uses a **Factory pattern and broker-agnostic interfaces** for plug-and-play broker integrations.
- Currently live with Dhaan, with architecture ready for Angel, Fyers and Zerodha.
- Implements technical indicators including **RSI, Bollinger Bands, VWAP, gap-up and candle patterns**.
- Two-tier strategy filtering and conflict-resolution system.
- Production resilience through:
  - Exponential-backoff retries
  - Broker-level trading locks
  - Global kill switches
  - Encrypted credential storage
  - Scheduled background jobs
  - Structured logging and error tracking
- Dockerized deployment with **GitHub Actions CI/CD**, automated deployment, health checks and rollback.
- Uses **NestJS, TypeScript, MySQL, TypeORM, Redis, Docker and cron scheduling**.

---

# 🤖 AI & MCP Engineering

One of the areas I'm particularly interested in is using AI as an engineering multiplier rather than simply adding an LLM API to an application.

### MCP Server for Billing Investigation

Built a **Node.js MCP server** that gives LLMs controlled access to production and analytics data, enabling automated investigation of billing anomalies and reducing manual log-diving.

### AI Charging Investigation Chat

Led a 4-engineer team through the HLD, implementation and deployment of an AI chat application using:

- NestJS
- Next.js
- OpenAI SDK
- Internal infrastructure
- GitHub Actions CI/CD

---

# 🌟 Open Source

## Postiz — Short.io Integration

Contributed to **Postiz**, an AI-driven social media scheduling platform with 35K+ GitHub stars.

**PR #564 — Merged**

Implemented a new **Short.io link-shortening provider** within Postiz's multi-provider architecture.

### Contribution included

- Provider-pattern implementation using NestJS
- Short.io REST API integration
- URL shortening and expansion
- Link statistics retrieval
- Recursive pagination for bulk analytics
- Authentication and production-grade error handling
- Response mapping and integration with the existing provider architecture

---

# 📊 Engineering Impact

| Metric | Impact |
|---|---:|
| Revenue recovered | **~$1M** |
| Reduction in manual revenue-loss calculation | **52% YoY** |
| Reduction in charging errors / production issues | **12%** |
| Backend/server performance improvement | **28%** |
| International marketplace/carrier integrations | **8+** |
| AI application team led | **4 engineers** |

---

# 🎓 Education

### Jadavpur University
**Bachelor of Engineering — Information Technology**

2018 – 2022  
CGPA: **8.7**

---

# 🌐 Find Me Online

- 💼 **LinkedIn:** [linkedin.com/in/aniket-kumar-ghosh-6ba368140](https://www.linkedin.com/in/aniket-kumar-ghosh-6ba368140)
- 💻 **GitHub:** [github.com/ak7550](https://github.com/ak7550)
- 🧠 **LeetCode:** [leetcode.com/ak7550](https://leetcode.com/ak7550)
- 🏆 **HackerRank:** [hackerrank.com/ghoshaniketkuma1](https://www.hackerrank.com/ghoshaniketkuma1)
- 💬 **Stack Overflow:** [stackoverflow.com/users/8178112/a-k](https://stackoverflow.com/users/8178112/a-k)
- 🌍 **Portfolio:** [ak7550.github.io/portfolio-website-in-next](https://ak7550.github.io/portfolio-website-in-next/)

---

## 💡 What I'm Interested In

I'm particularly interested in engineering problems involving:

**Distributed Systems · Backend Architecture · AI/LLM Infrastructure · MCP · Cloud-Native Systems · Financial & Billing Systems · Developer Infrastructure · Automation**

I'm open to **backend-heavy and full-stack engineering opportunities in India and internationally**.

---

> **Build systems that are reliable enough for production, simple enough to maintain, and useful enough to matter.**
