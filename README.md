# Backend Web Toolbox

A curated bookmark list for building **modern Python back‑end APIs** with **FastAPI**, async runtimes, and production‑grade tooling.

---

## ⚙️ Core Framework & Runtime
| Tool | What it gives you |
|------|-------------------|
| **FastAPI** | High‑performance async web framework with OpenAPI docs out‑of‑the‑box. |
| **Starlette** | Lightweight ASGI toolkit that underpins FastAPI. |
| **Uvicorn [standard]** | Lightning‑fast ASGI server with `uvloop` & `httptools` extras. |
| **Hypercorn** | Alt ASGI server (HTTP/2 + QUIC). |
| **Gunicorn** | Classic WSGI/ASGI process manager (use `-k uvicorn.workers.UvicornWorker`). |

---

## 🛠️ Data Validation & Serialization
- **Pydantic v2** – Type‑safe models, JSON schema, settings management.
- **datamodel‑code‑generator** – Generate Pydantic models from OpenAPI/JSONSchema.
- **marshmallow‑dataclass** – (Alt) Dataclass ↔︎ schema serialization.

---

## 🗄️ Databases & ORM
| Library | Highlights |
|---------|-----------|
| **SQLModel** | SQLAlchemy + Pydantic synth; easy CRUD, sync & async. |
| **SQLAlchemy 2.x** | Battle‑tested ORM/SQL toolkit. |
| **Tortoise‑ORM** | Django‑like async ORM. |
| **encode/databases** | Async database queries w/ transaction & connection pools. |
| **psycopg (v3)** | Modern Postgres driver (sync & async). |
| **asyncpg** | Fastest pure‑async Postgres driver. |

---

## 🔐 Auth & Security
- **fastapi‑users** – Plug‑and‑play user auth (JWT, cookies, OAuth).  
- **python‑jose** – JWT signing & verification.  
- **passlib** – Password hashing algorithms.  
- **Authlib** – OAuth 1 / 2 / OpenID Connect client & server helpers.

---

## 📑 API Documentation & Utils
- **FastAPI’s built‑in docs** – Interactive Swagger & Redoc.
- **fastapi‑pagination** – Drop‑in pagination for list endpoints.
- **fastapi‑filters** – Dynamic filtering & ordering for SQLAlchemy/SQLModel.
- **fastapi‑utils** – Reusable dependencies, CBVs, async tasks.

---

## ⏱️ Background Tasks & Messaging
- **Celery** – Distributed task queue (RabbitMQ/Redis).  
- **Dramatiq** – Simple, Redis‑backed message processor.  
- **RQ** – Lightweight Redis queue.  
- **FastAPI Scheduler** – APScheduler wrapper for cron/interval jobs.  
- **Redis** – In‑memory cache, pub/sub, streams.

---

## 📈 Observability & Logging
- **loguru** – Batteries‑included logging framework.  
- **structlog** – Structured JSON logging.  
- **Prometheus FastAPI Instrumentator** – Automatic metrics.  
- **OpenTelemetry Python** – Traces & metrics exporter.  
- **Sentry SDK** – Error monitoring.

---

## 🧪 Testing & Quality
| Tool | Purpose |
|------|---------|
| **pytest** | Python testing framework. |
| **pytest‑asyncio** | Async test support. |
| **httpx** | Sync & async HTTP client for API tests. |
| **pytest‑cov** | Coverage plugin. |
| **ruff** | Fast Python linter & formatter (replaces flake8 & isort). |
| **mypy** | Static type‑checker. |

---

## 🚀 Containerization & Deployment
- **Docker** – Container images.  
- **docker‑compose** – Local multi‑service orchestration.  
- **Gunicorn + Uvicorn workers** – Production process model.  
- **poetry** – Dependency & packaging manager.  
- **pip‑tools** – Deterministic `requirements.txt`.  
- **Traefik** – Reverse proxy & automatic HTTPS.  
- **Fly.io / Railways.app / Render** – PaaS for FastAPI.  
- **Kubernetes + KEDA** – Autoscaled async workers.

---

## 🔄 CI / CD Helpers
- **actions/setup‑python** – Install CPython in GitHub Actions.  
- **tiangolo/poetry‑actions** – Cache & install dependencies.  
- **docker/build‑push‑action** – Build & push container images.  
- **amondnet/flyctl‑action** – Deploy to Fly.io.  
- **pre‑commit** – Run Ruff, mypy, tests before each commit.

---

### 📜 Licence & Contributions
All listed projects are OSI‑approved (MIT, Apache‑2.0, etc.).

> **How to use:** Fork or copy the list, star the repos you like, and open PRs to suggest new back‑end tools.

---
