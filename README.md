<h1 align="center">Kirti Singh</h1>

<p align="center">
  <strong>Backend Engineer • Python • FastAPI • AI Systems</strong>
</p>

<p align="center">
  <a href="https://github.com/">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:kirtisingh239on@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=flat-square&color=blue" />
</p>

---

## `$ whoami`

```python
kirti@backend:~$ whoami

Computer Science undergraduate focused on backend engineering,
Python, FastAPI, distributed systems and AI-powered applications.

I build systems around:

→ Async APIs
→ PostgreSQL & Redis
→ Background processing
→ Real-time communication
→ Authentication & authorization
→ AI-powered backend pipelines
→ Dockerized deployments
→ Performance & load testing
```

I care less about collecting frameworks and more about understanding what happens when software has to **actually handle traffic, failures, data, and users**.

Currently pursuing a B.Tech in Computer Science at **Invertis University**, with an expected graduation in 2028.

---

## ⚡ What I Build

```text
                         BACKEND SYSTEMS
                              │
            ┌─────────────────┼─────────────────┐
            │                 │                 │
        API LAYER         DATA LAYER       PROCESSING
            │                 │                 │
        FastAPI          PostgreSQL          Celery
        REST APIs        Redis               Async Jobs
        WebSockets       SQLAlchemy          Retries
        Pydantic         Redis Pub/Sub       Background Tasks
            │                 │                 │
            └─────────────────┼─────────────────┘
                              │
                        INFRASTRUCTURE
                              │
                  Docker • Linux • AWS • Git
                              │
                              ▼
                     TEST • LOAD TEST • SHIP
```

---

## 🧰 Tech Stack

### Backend

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi" />
</p>

```text
FastAPI
RESTful API Design
SQLAlchemy 2.0 (Async)
Pydantic v2
WebSockets
Celery
OOP
```

### Databases & Caching

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis" />
</p>

```text
PostgreSQL
MySQL
Redis
Redis Pub/Sub
Database Design
Async Database Access
```

### Authentication & Security

```text
JWT
OAuth2
RBAC
Refresh Tokens
Supabase Authentication
```

### DevOps & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=docker,linux,aws,git,github" />
</p>

```text
Docker
Docker Compose
AWS EC2
AWS S3
AWS IAM
Linux
Git
GitHub
Render
Alembic
```

### Testing & Performance

```text
pytest
k6 Load Testing
Latency Benchmarking
Throughput Testing
Concurrent Connection Testing
Reliability Testing
```

---

# 🚀 Featured Projects

## 🤖 DepositBack

### AI-Powered Tenant Deposit Dispute Platform

> FastAPI • PostgreSQL • Supabase • Gemini API • Docker

An AI-powered backend that analyzes lease agreements and supporting evidence to generate **claim-specific dispute reports and editable legal documents**.

```text
Lease Agreement
       │
       ▼
Document Upload
       │
       ▼
Supabase Storage
       │
       ▼
Gemini Multimodal AI
       │
       ▼
Document Analysis
       │
       ▼
Dispute Report
       │
       ▼
Editable Legal Document
```

### Engineering Highlights

* Built an AI-powered FastAPI backend for automated document analysis
* Integrated **Gemini multimodal AI**
* Implemented **Supabase Auth & Storage**
* Used asynchronous background processing with FastAPI `BackgroundTasks`
* Designed the pipeline to return immediately while document processing continues
* Initial testing achieved approximately **23-second average processing time**
* Achieved **94% initial success rate across 19/20 documents**

---

## 📬 Courier

### Asynchronous Notification Service

> FastAPI • PostgreSQL • Redis • Celery • Docker

A production-style notification backend designed around **reliable asynchronous email delivery**.

```text
API Request
    │
    ▼
Authentication
    │
    ▼
Rate Limiting
    │
    ▼
Redis Queue
    │
    ▼
Celery Worker
    │
    ├──── Success ────► Delivery
    │
    └──── Failure
            │
            ▼
         Retry
            │
            ▼
      Dead Letter Queue
```

### Performance

```text
API Latency       → 70–100 ms
Throughput        → 60–100 req/s
Email Success     → 99.8%
REST APIs         → 12+
```

### Engineering Highlights

* Built 12+ REST APIs for authentication, email delivery, analytics and administration
* Implemented Redis-based rate limiting
* Added asynchronous email processing
* Designed automatic retry mechanisms
* Implemented dead-letter queue recovery
* Load-tested the service to measure throughput, latency and reliability

---

## 🛰️ PollNinja

### Real-Time Polling Platform

> FastAPI • PostgreSQL • Redis • WebSockets

A real-time polling backend designed to synchronize votes and likes across multiple server instances.

```text
                 Client
                   │
                   ▼
              FastAPI API
                   │
          ┌────────┴────────┐
          ▼                 ▼
     PostgreSQL          Redis
                              │
                         Pub / Sub
                              │
               ┌──────────────┼──────────────┐
               ▼              ▼              ▼
           Server 1        Server 2       Server 3
               │              │              │
               └──────────────┼──────────────┘
                              ▼
                         WebSocket
                           Clients
```

### Performance

```text
Concurrent WebSockets → 500+
Average API Latency   → 82 ms
Load Testing          → k6
```

### Engineering Highlights

* Built real-time communication using WebSockets
* Used Redis Pub/Sub for cross-instance event synchronization
* Implemented JWT-secured APIs
* Added polling, voting, likes and authentication functionality
* Tested the system with 500+ concurrent WebSocket connections

---

## 🔗 LinkSnip

### Advanced URL Shortener

> FastAPI • PostgreSQL • Redis • Docker

A production-style URL shortener with authentication, custom redirects, expiration policies and click an

**imkirti-jpg/imkirti-jpg** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
