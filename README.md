<h1 align="center">Hi, I'm Kirti Singh 👋</h1>

<p align="center">
  <strong>Backend Engineer • Python • FastAPI • AI Systems</strong>
</p>

<p align="center">
  <a href="https://github.com/imkirti-jpg">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/kirti-singh-012627323/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:kirtisingh239on@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>


<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Building+backend+systems+that+don't+fall+over;FastAPI+%2B+PostgreSQL+%2B+Redis+%2B+Docker;Async+APIs+%7C+AI+pipelines+%7C+Real-time+systems;Currently+shipping+%E2%80%94+DepositBack+%2F+Courier+%2F+PollNinja" />
</p>

---

## `$ whoami`

```python
kirti@backend:~$ whoami

Computer Science undergraduate focused on backend engineering,
distributed systems, and AI-powered applications.

I build systems around:

  → Async APIs
  → PostgreSQL & Redis
  → Background job processing
  → Real-time communication (WebSockets)
  → Authentication & authorization
  → AI-powered backend pipelines
  → Dockerized deployments
  → Performance & load testing
```

I care less about collecting frameworks and more about understanding what happens when software has to **actually handle traffic, failures, data, and users.**

🎓 Currently pursuing a **B.Tech in Computer Science** at **Invertis University** — Class of 2028.

---

## ⚡ What I Build

```text
                          BACKEND SYSTEMS
                                │
             ┌──────────────────┼──────────────────┐
             │                  │                  │
         API LAYER          DATA LAYER         PROCESSING
             │                  │                  │
         FastAPI            PostgreSQL           Celery
         REST APIs          Redis                Async Jobs
         WebSockets         SQLAlchemy 2.0       Retries
         Pydantic v2        Redis Pub/Sub        Background Tasks
             │                  │                  │
             └──────────────────┼──────────────────┘
                                │
                         INFRASTRUCTURE
                                │
                   Docker • Linux • AWS • Git
                                │
                                ▼
                      TEST → LOAD TEST → SHIP
```

---

## 🧰 Tech Stack

### Backend
<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,redis" />
</p>

```text
FastAPI · RESTful API Design · SQLAlchemy 2.0 (Async)
Pydantic v2 · WebSockets · Celery · OOP
```

### Databases & Caching
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis" />
</p>

```text
PostgreSQL · MySQL · Redis · Redis Pub/Sub
Database Design · Async Database Access
```

### Authentication & Security
```text
JWT · OAuth2 · RBAC · Refresh Tokens · Supabase Auth
```

### DevOps & Infrastructure
<p>
  <img src="https://skillicons.dev/icons?i=docker,linux,aws,git,github" />
</p>

```text
Docker · Docker Compose · AWS EC2 · AWS S3 · AWS IAM
Linux · Git · GitHub · Render · Alembic
```

### Testing & Performance
```text
pytest · k6 Load Testing · Latency Benchmarking
Throughput Testing · Concurrent Connection Testing · Reliability Testing
```

---

## 🚀 Featured Projects

### 🤖 DepositBack — AI-Powered Tenant Deposit Dispute Platform
> `FastAPI` · `PostgreSQL` · `Supabase` · `Gemini API` · `Docker`

An AI-powered backend that analyzes lease agreements and supporting evidence to generate **claim-specific dispute reports and editable legal documents.**

```text
Lease Agreement → Document Upload → Supabase Storage
      → Gemini Multimodal AI → Document Analysis
      → Dispute Report → Editable Legal Document
```

**Engineering Highlights**
- Built an AI-powered FastAPI backend for automated document analysis
- Integrated **Gemini multimodal AI** for lease and evidence parsing
- Implemented **Supabase Auth & Storage** for secure document handling
- Used asynchronous background processing via FastAPI `BackgroundTasks` so the API returns immediately while processing continues
- Achieved an average processing time of **~23 seconds**
- Hit a **94% success rate across 19/20 test documents** in initial testing

---

### 📬 Courier — Asynchronous Notification Service
> `FastAPI` · `PostgreSQL` · `Redis` · `Celery` · `Docker`

A production-style notification backend built around **reliable asynchronous email delivery.**

```text
API Request → Auth → Rate Limiting → Redis Queue → Celery Worker
                                          ├── Success → Delivery
                                          └── Failure → Retry → Dead Letter Queue
```

| Metric | Result |
|---|---|
| API Latency | 70–100 ms |
| Throughput | 60–100 req/s |
| Email Success Rate | 99.8% |
| REST APIs | 12+ |

**Engineering Highlights**
- Built 12+ REST APIs for auth, email delivery, analytics, and admin functions
- Implemented Redis-based rate limiting
- Added asynchronous email processing with automatic retries
- Designed dead-letter queue recovery for failed deliveries
- Load-tested the service for throughput, latency, and reliability

---

### 🛰️ PollNinja — Real-Time Polling Platform
> `FastAPI` · `PostgreSQL` · `Redis` · `WebSockets`

A real-time polling backend that synchronizes votes and likes across multiple server instances.

```text
Client → FastAPI API → PostgreSQL
                     → Redis Pub/Sub → Server 1 / Server 2 / Server 3
                                              → WebSocket Clients
```

| Metric | Result |
|---|---|
| Concurrent WebSockets | 500+ |
| Average API Latency | 82 ms |
| Load Testing | k6 |

**Engineering Highlights**
- Built real-time communication using WebSockets
- Used Redis Pub/Sub for cross-instance event synchronization
- Implemented JWT-secured APIs
- Added polling, voting, likes, and authentication functionality
- Tested the system with 500+ concurrent WebSocket connections

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=tokyo-night&hide_border=true" />
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg" />
</p>

<p align="center">
  <em>💡 Currently exploring: distributed systems, AI-powered backend pipelines, and making things fast under load.</em>
</p>

<p align="center">📫 Reach me at <a href="mailto:kirtisingh239on@gmail.com">kirtisingh239on@gmail.com</a></p>
