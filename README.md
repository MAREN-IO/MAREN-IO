<!-- ====== HERO ====== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=210&text=Backend%20Developer%20Portfolio&fontAlign=50&fontAlignY=40&color=gradient" />
</p>

<p align="center">
  <b>Backend Developer</b> focused on building <b>production-ready APIs</b>: auth, databases, testing, CI/CD, observability, and deployment.
</p>

<p align="center">
  <!-- ====== QUICK BUTTONS ====== -->
  <a href="#projects"><img src="https://img.shields.io/badge/Projects-Explore-blue?style=for-the-badge" /></a>
  <a href="#stack"><img src="https://img.shields.io/badge/Stack-FastAPI%20%7C%20Postgres%20%7C%20Docker-0a7?style=for-the-badge" /></a>
  <a href="#proof"><img src="https://img.shields.io/badge/Proof-CI%2FCD%20%7C%20Tests%20%7C%20Deploy-black?style=for-the-badge" /></a>
  <a href="#contact"><img src="https://img.shields.io/badge/Contact-LinkedIn-5865F2?style=for-the-badge" /></a>
</p>

<hr />

<!-- ====== BADGES ====== -->
<p align="center">
  <img src="https://img.shields.io/badge/Role-Backend%20Developer-informational" />
  <img src="https://img.shields.io/badge/Focus-APIs%20%7C%20Databases%20%7C%20Testing-success" />
  <img src="https://img.shields.io/badge/Delivery-Docker%20%7C%20CI%2FCD%20%7C%20Deploy-blueviolet" />
  <img src="https://img.shields.io/badge/Status-Actively%20Building-yellow" />
</p>

---

## Why me (30-second scan)
- **Production mindset:** clean architecture, validation, error handling, and structured logging
- **Quality:** unit + integration tests, coverage targets, and CI gates
- **Delivery:** Dockerized services with repeatable deployments
- **Operations:** metrics, tracing-ready patterns, and pragmatic observability

---

## Projects
> Each project is built as if it were going to production: requirements → design → implementation → tests → CI/CD → deploy.

### 1) Core API — Auth + RBAC + Postgres (Flagship)
**What it shows:** REST API design, auth (JWT), RBAC, migrations, testing strategy, CI/CD, deployment.  
- Repo: `LINK_HERE`
- Live demo: `LINK_HERE`
- Docs (OpenAPI/Swagger): `LINK_HERE`

**Highlights**
- JWT auth + role-based access control (RBAC)
- Postgres schema + migrations
- Test pyramid (unit/integration) + coverage reporting
- GitHub Actions: lint → tests → build → deploy

---

### 2) Async Jobs / Events — Background workers
**What it shows:** scalable backend patterns (queues, background processing), resilience, idempotency.  
- Repo: `LINK_HERE`
- Demo: `LINK_HERE`

**Highlights**
- Job queues, retries, dead-letter strategy (documented)
- Idempotency keys + safe reprocessing
- Structured logs + job tracing fields

---

### 3) Observability Pack — Logs + Metrics + Health checks
**What it shows:** professional operations: health endpoints, metrics, dashboards-ready output.  
- Repo: `LINK_HERE`

**Highlights**
- Health checks (liveness/readiness)
- Metrics-friendly endpoints and logging conventions
- Incident-style runbook (basic)

---

## Stack
<p align="center">
  <img src="https://img.shields.io/badge/Python-FastAPI-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Database-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Containers-Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/CI/CD-GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white" />
</p>

**Backend fundamentals**
- RESTful APIs, pagination, filtering, validation
- AuthN/AuthZ (JWT, RBAC), secure defaults
- DB design: indexes, constraints, migrations
- Testing: unit + integration, fixtures, test containers
- CI/CD: lint + tests + build + deploy
- Observability: logs, metrics, health checks

---

## Proof
### CI/CD checklist
- [ ] Linting + formatting
- [ ] Unit + Integration tests
- [ ] Coverage report
- [ ] Docker build
- [ ] Deploy pipeline

### Quality gates (target)
- Unit tests for business logic
- Integration tests for DB/API routes
- Coverage target: **80%+** (adjust as needed)

---

## Progress dashboard (visual)
> These SVG charts render directly on GitHub.

### Skills radar (static)
<svg width="720" height="260" viewBox="0 0 720 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Skill bars">
  <style>
    .title{font:700 18px system-ui,Segoe UI,Roboto; fill:#111}
    .label{font:600 12px system-ui,Segoe UI,Roboto; fill:#333}
    .bg{fill:#eef2ff}
    .bar{fill:#4f46e5}
  </style>
  <text x="12" y="28" class="title">Backend Skill Snapshot</text>

  <!-- Row 1 -->
  <text x="12" y="70" class="label">API Design</text>
  <rect x="130" y="56" width="560" height="16" rx="8" class="bg"/>
  <rect x="130" y="56" width="420" height="16" rx="8" class="bar"/>

  <!-- Row 2 -->
  <text x="12" y="104" class="label">Databases (Postgres)</text>
  <rect x="130" y="90" width="560" height="16" rx="8" class="bg"/>
  <rect x="130" y="90" width="380" height="16" rx="8" class="bar"/>

  <!-- Row 3 -->
  <text x="12" y="138" class="label">Testing</text>
  <rect x="130" y="124" width="560" height="16" rx="8" class="bg"/>
  <rect x="130" y="124" width="340" height="16" rx="8" class="bar"/>

  <!-- Row 4 -->
  <text x="12" y="172" class="label">CI/CD & Delivery</text>
  <rect x="130" y="158" width="560" height="16" rx="8" class="bg"/>
  <rect x="130" y="158" width="320" height="16" rx="8" class="bar"/>

  <!-- Row 5 -->
  <text x="12" y="206" class="label">Observability</text>
  <rect x="130" y="192" width="560" height="16" rx="8" class="bg"/>
  <rect x="130" y="192" width="260" height="16" rx="8" class="bar"/>

  <text x="12" y="244" class="label">Update the bar widths as you progress (0–560).</text>
</svg>

---

## What recruiters usually care about (and where to look)
- **Architecture & decisions:** see each project README → “Architecture” + “Tradeoffs”
- **Testing & quality:** `tests/` + CI checks in Actions
- **Delivery:** Dockerfile + pipeline + live deploy link
- **Communication:** concise docs, clear setup, reproducible runs

---

## Local setup (template)
```bash
# clone
git clone YOUR_REPO_URL
cd YOUR_REPO

# create venv
python -m venv .venv
source .venv/bin/activate

# install
pip install -r requirements.txt

# run
uvicorn app.main:app --reload


<!--
**MAREN-IO/MAREN-IO** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
