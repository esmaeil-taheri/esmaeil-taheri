# Esmaeil Taheri

**Backend Engineer · Fintech · Distributed Systems · AI**

I build reliable backend systems where **correctness, scalability, and failure handling** matter — from financial ledger and settlement systems to event-driven AI platforms.

My primary stack is **Python, Django, FastAPI, PostgreSQL, Redis, Celery, and Kafka**.

---

## About

Backend Engineer with **3+ years of experience** building and shipping production-oriented systems across fintech, AI, and e-commerce.

My strongest areas are:

* 💰 **Financial systems** — ledger-based wallets, money movement, settlements, KYC, payments
* ⚡ **Distributed & asynchronous systems** — Celery, Kafka, Redis, background processing and retry-safe workflows
* 🏗️ **Backend architecture** — modular monoliths, microservices, clean/domain-oriented architecture
* 🤖 **AI platforms** — unified APIs and asynchronous pipelines for text, image, and video generation
* 🗄️ **Data & consistency** — PostgreSQL, transactional workflows, row-level locking, idempotency and auditability

I particularly enjoy solving the problems that are easy to miss in a happy-path implementation:

**race conditions · duplicate events · failed workers · inconsistent state · concurrent transactions · external service failures**

> **Build it clean. Make it correct. Scale it right.**

---

## Experience

### Backend Engineer — Yara E-Commerce Foundation

**MelliGold Platform · May 2024 – Apr 2026**

**18M+ users · 50K+ daily transactions · Django REST Framework**

Worked on large-scale financial infrastructure involving fiat and gold balances.

* Designed and maintained **ledger-based wallet systems** for fiat and gold assets
* Implemented atomic buy/sell flows using **PostgreSQL transactions and row-level locking**
* Built asynchronous settlement and financial workflows with **Celery**
* Worked on **multi-wallet architecture** and immutable transaction history
* Implemented KYC and identity-verification workflows
* Built secure authentication flows using **OTP / TOTP**
* Worked on payment, settlement, and high-volume transaction processing

---

### Backend Engineer — Sepas Holding

**Opal AI Content Platform · Mar 2025 – Dec 2025 · Part-time / Remote**

**FastAPI · Microservices · Kafka · Celery · Redis**

Built backend infrastructure for an AI content-generation platform.

* Unified multiple AI providers behind a single backend API
* Built event-driven credit/usage processing with **Kafka**
* Implemented asynchronous AI processing pipelines using **Celery + Redis**
* Worked across **PostgreSQL, MongoDB, and MinIO**
* Applied domain-oriented / clean architecture principles to service boundaries
* Designed workflows around long-running and failure-prone AI operations

---

### Backend Engineer — Sigloyland Startup

**Mar 2024 – May 2024 · Full-time**

**Django**

* Built e-commerce backend and order-processing flows
* Implemented store APIs and business logic
* Integrated cryptocurrency payment processing

---

## Selected Projects

### 🥇 Gold Exchange Platform

**Fintech backend for digital gold trading, payments, KYC, wallets, and bank settlement.**

**Django · DRF · PostgreSQL · Redis · Celery · Docker · MinIO**

The system models digital gold trading with financial-style consistency requirements.

Key engineering areas:

* Append-only wallet ledger
* Atomic balance mutations
* `select_for_update()` for concurrent financial operations
* Idempotent payment callbacks
* Async payment and settlement processing
* Gold inventory management with active/locked balances
* KYC state machine
* Bank withdrawal and settlement workflows
* JWT + OTP + TOTP authentication
* Dockerized infrastructure with Nginx, Celery and Redis

**Architecture**

```text
Client
  │
  ▼
Nginx
  │
  ▼
Django REST API
  │
  ├── API Layer
  │
  ├── Service Layer
  │
  ├── Selector Layer
  │
  └── PostgreSQL
       │
       ├── Wallet Ledger
       ├── Transactions
       ├── Payments
       ├── KYC
       └── Settlements

Async Processing
  │
  ├── Celery Worker
  ├── Celery Beat
  └── Redis

External Systems
  ├── Payment Gateway
  ├── Bank Settlement
  ├── Identity Verification
  ├── SMS
  └── MinIO
```

**[View Project →](https://github.com/esmaeil-taheri/Gold-Trading-Paltform)**

---

### ⚙️ FastAPI Starter Kit

**Production-oriented FastAPI foundation for building maintainable backend services.**

**FastAPI · Async SQLAlchemy · PostgreSQL · Docker**

Focus areas:

* Clean / domain-oriented architecture
* Async database access
* Separation of business logic from delivery mechanisms
* Reusable backend structure
* API documentation
* Production-oriented project configuration

**[View Project →](https://github.com/esmaeil-taheri/FastAPI-Starter-Kit)**

---

### 🔄 ERP System — PostgreSQL Sync

Backend service for synchronizing **Odoo contacts, products, and orders** into PostgreSQL.

Focus areas:

* External system integration
* Per-record error handling
* Audit trail
* Reliable synchronization workflows
* PostgreSQL persistence

**[View Project →](https://github.com/esmaeil-taheri/ERP-System--PostgreSQL-Sync)**

---

### 🟢 Go Microservice Question Game

A backend service built with **Go + Echo**, focused on modular service design and layered architecture.

**Go · Echo · REST API · Layered Architecture**

**[View Project →](https://github.com/esmaeil-taheri/Go-Microservice-Question-Game)**

---

## Technical Stack

### Core

`Python` · `Django` · `Django REST Framework` · `FastAPI` · `PostgreSQL` · `Redis`

### Distributed & Async

`Celery` · `Apache Kafka` · `Event-Driven Systems` · `Async Processing`

### Architecture

`Modular Architecture` · `Clean Architecture` · `Domain-Oriented Design` · `Microservices` · `Design Patterns`

### Data & Storage

`PostgreSQL` · `MySQL` · `MongoDB` · `Redis` · `Elasticsearch` · `MinIO`

### Security

`JWT` · `OAuth 2.0` · `OTP` · `TOTP / 2FA`

### Infrastructure

`Docker` · `Docker Compose` · `Nginx` · `Linux` · `GitHub Actions` · `GitLab CI/CD`

### Observability

`Prometheus` · `Grafana`

---

## Engineering Interests

Currently exploring deeper patterns for building reliable distributed systems:

* Event Sourcing
* CQRS
* Transactional Outbox
* Idempotent event processing
* Distributed consistency
* Failure recovery
* Observability and tracing
* High-throughput PostgreSQL systems

---

## What I Like Building

```text
Financial Systems
    ├── Ledgers
    ├── Wallets
    ├── Payments
    └── Settlement

Distributed Systems
    ├── Event-driven workflows
    ├── Async processing
    ├── Retry / idempotency
    └── Failure recovery

AI Platforms
    ├── Provider abstraction
    ├── Usage / credit systems
    ├── Async generation
    └── Event pipelines
```

---

## Let's Connect

**LinkedIn:** [esmaeil-taheri-developer](https://linkedin.com/in/esmaeil-taheri-developer)

**GitHub:** [esmaeil-taheri](https://github.com/esmaeil-taheri)

**Email:** [Esi.taheri@yahoo.com](mailto:Esi.taheri@yahoo.com)
