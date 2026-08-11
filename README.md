# Hey, I'm Vishal 👋

### Software Engineer | Backend & Distributed Systems | AI Engineer

I build backend systems with a focus on **scalability, reliability, performance, and clean engineering**.

I'm particularly interested in understanding what happens when a system goes from:

```text
10 requests
      ↓
10,000 requests
      ↓
1,000,000 requests
```

—not just making the API work, but understanding **latency, caching, databases, queues, failures, observability, and trade-offs**.

---

## 🧑‍💻 About Me

* 🎯 **Open to Software Engineering opportunities — Backend / SDE-1**
* 🛠️ Strongest in **JavaScript / TypeScript**
* 🚀 Building production-style backend systems
* 🧠 Learning and applying **Distributed Systems & System Design**
* 🗄️ Working with **PostgreSQL & Redis**
* ⚡ Exploring **Kafka, ClickHouse & event-driven architectures**
* ☁️ Exploring **AWS, Docker & Terraform**
* 📊 Interested in **performance engineering and observability**
* 🧪 I like testing systems under load instead of assuming they scale
* 🤝 Open to connecting with engineers, founders, and teams building interesting backend products

---

## ⚙️ Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=typescript,javascript,python" />
</p>

**TypeScript · JavaScript · Python**

### Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,nextjs,restapi" />
</p>

**Node.js · Express · Next.js · REST APIs**

### Databases & Data

<p>
  <img src="https://skillicons.dev/icons?i=postgresql,redis,kafka,clickhouse" />
</p>

**PostgreSQL · Redis · Kafka · ClickHouse**

### API & Documentation

<p>
  <img src="https://skillicons.dev/icons?i=openapi,scalar" />
</p>

**OpenAPI · Scalar**

### Testing & Performance

<p>
  <img src="https://skillicons.dev/icons?i=vitest,supertest,playwright,autocannon,k6" />
</p>

**Vitest · Supertest · Playwright · Testcontainers · Autocannon · k6**

### Cloud & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,terraform,githubactions" />
</p>

**AWS · Docker · Terraform · GitHub Actions**

### Observability

<p>
  <img src="https://skillicons.dev/icons?i=opentelemetry,prometheus,grafana,sentry" />
</p>

**OpenTelemetry · Prometheus · Grafana · Sentry**

---

# 🚀 Featured Project

## 🔗 LinkPulse

**Distributed Link Infrastructure & Traffic Analytics Platform**

A production-oriented link platform designed around **low-latency redirects and asynchronous analytics**.

### Architecture

```text
                         LinkPulse
                            │
                            ▼
                  Express + TypeScript
                            │
                ┌───────────┴───────────┐
                │                       │
                ▼                       ▼
             Redis                 PostgreSQL
                │                       │
                └───────────┬───────────┘
                            │
                       Redirect
                            │
                            ▼
                          Kafka
                            │
                            ▼
                    Analytics Workers
                            │
                            ▼
                       ClickHouse
                            │
                            ▼
                    Analytics Dashboard
```

### Engineering Highlights

* ⚡ Redis cache-aside link resolution
* 📊 Kafka-based asynchronous analytics
* 🗄️ PostgreSQL transactional storage
* 📈 ClickHouse analytical workloads
* 🌍 Intelligent traffic routing
* 🔐 Multi-tenancy + RBAC
* 🛡️ Rate limiting & abuse protection
* 🔑 API key authentication
* 🌐 Custom domains
* 📖 OpenAPI + Scalar API documentation
* 📡 OpenTelemetry distributed tracing
* 🐛 Sentry error tracking
* 📊 Prometheus + Grafana monitoring
* ⚡ Autocannon HTTP benchmarking
* 🧪 k6 load testing
* 🐳 Docker
* ☁️ AWS + Terraform

**Repository:** `LinkPulse`

---

# 🧠 What I'm Currently Learning

### Backend Engineering

```text
TypeScript
    ↓
Node.js / Express
    ↓
PostgreSQL
    ↓
Redis
    ↓
Kafka
    ↓
ClickHouse
```

### System Design

Currently focusing on:

* caching strategies
* database indexing
* database transactions
* connection pooling
* message queues
* event-driven architecture
* idempotency
* rate limiting
* horizontal scaling
* consistency models
* failure handling
* observability
* load testing

---

# 📈 How I Approach Engineering

I don't want my projects to be:

```text
Build CRUD
      ↓
Push to GitHub
      ↓
Done
```

I prefer:

```text
Build
  ↓
Measure
  ↓
Find Bottleneck
  ↓
Understand Why
  ↓
Optimize
  ↓
Load Test
  ↓
Introduce Failure
  ↓
Observe
  ↓
Document Trade-offs
```

That's the engineering mindset I'm trying to develop.

---

# 🔬 Engineering Experiments

I enjoy turning architectural decisions into measurable experiments.

### Example

**Question:**

> Does Redis actually improve redirect performance?

Instead of assuming:

```text
PostgreSQL → slow
Redis → fast
```

I benchmark:

```text
Scenario A
PostgreSQL only

vs.

Scenario B
Redis warm cache

vs.

Scenario C
Redis cold cache
```

Using:

```text
Autocannon
    +
k6
    +
Prometheus
    +
Grafana
```

And compare:

```text
p50
p95
p99
RPS
CPU
Memory
Database load
Cache hit rate
Error rate
```

The numbers matter more than the assumption.

---

# 🏗️ Architecture > Buzzwords

I don't want to add technologies just because they look good on a resume.

For example:

```text
Kafka
```

should exist because there is a real asynchronous/event-driven workload.

```text
Redis
```

should exist because there is a caching/performance problem.

```text
ClickHouse
```

should exist because analytical workloads shouldn't unnecessarily compete with transactional workloads.

```text
Terraform
```

should exist because infrastructure should be reproducible.

```text
OpenTelemetry
```

should exist because distributed systems need visibility across service boundaries.

My goal is to understand **why a technology belongs in a system**, not just how to use it.

---

# 📚 Currently Exploring

* Distributed Systems
* System Design
* Backend Performance
* Database Internals
* Event-Driven Architecture
* Cloud Infrastructure
* Observability
* Reliability Engineering
* Security

---

# 📊 GitHub Stats

<!-- Add GitHub stats after building meaningful repository activity. -->

---

# 📫 Let's Connect

I'm currently **open to Backend / SDE-1 Software Engineering opportunities**.

I'm especially interested in teams working on:

* Backend systems
* Distributed systems
* Infrastructure
* Developer tools
* Developer platforms
* High-scale applications
* Performance engineering

### Connect with me

<div align="center">
<a href="mailto:v1shalgupta35264@gmail.com"> <img src="https://img.shields.io/badge/Gmail-v1shalgupta35264%40gmail.com-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" /> </a>
<a href="https://www.linkedin.com/in/vishal-gupta/"> <img src="https://img.shields.io/badge/LinkedIn-Vishal%20Gupta-6366F1?style=for-the-badge&logo=linkedin&logoColor=white" /> </a>
<a href="https://github.com/vishalgupta-02"> <img src="https://img.shields.io/badge/GitHub-vishalgupta--02-4F46E5?style=for-the-badge&logo=github&logoColor=white" /> </a>
<a href="https://vishalbuild.tech"> <img src="https://img.shields.io/badge/Portfolio-vishalbuild.tech-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white" /> </a>
</div>

---

## ⚡ A little about how I build

```text
Curiosity
    +
Engineering
    +
Measurement
    +
Failure
    +
Iteration
    =
Better Systems
```

### Building systems that don't just work — understanding why they work.
<div align="center">  
      <img src="https://capsule-render.vercel.app/api?type=waving&color=0:312E81,50:6D28D9,100:8B5CF6&height=120&section=footer" />
</div>
