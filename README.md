# issue-insigths-tracker
A mini SaaS portal for tracking file-based issues and structured insights. Built using FastAPI, SvelteKit, PostgreSQL, and Docker. Created as a full-stack engineer coding assignment for DeepLogic AI.

# 🛠️ Issues & Insights Tracker

A lightweight, full-stack SaaS portal to collect, manage, and visualize feedback issues submitted by users.  
Built as a coding assignment for the Full-Stack Engineer role at **DeepLogic AI**.

---

## 🚀 Features

- 🧑‍💼 **Role-based access control**: ADMIN, MAINTAINER, REPORTER
- 🐛 **Issue Tracker**: Create, view, and manage issue reports
- 💾 **File Upload Support** *(Pluggable)*
- 📈 **Dashboard**: Issue severity analytics (planned)
- 🔄 **Realtime Updates**: WebSocket/SSE (planned)
- ⏱️ **Scheduled Worker Job**: Aggregates issue stats (planned)
- 🔐 **Authentication**: Google OAuth / Email-password *(optional)*
- 🧪 **Testing**: 80% coverage planned + E2E test via Playwright
- ☁️ **Dockerized**: One-command run with Docker Compose

---

## 🧰 Tech Stack

| Layer        | Technology                 |
|--------------|----------------------------|
| Frontend     | [SvelteKit](https://kit.svelte.dev), TailwindCSS |
| Backend      | [FastAPI](https://fastapi.tiangolo.com/) |
| Database     | PostgreSQL 15+             |
| ORM          | SQLAlchemy                 |
| Auth         | (JWT/OAuth2-ready)         |
| Worker       | Celery / APScheduler       |
| DevOps       | Docker, Docker Compose     |
| CI/CD        | GitHub Actions (planned)   |

---

## ⚙️ Installation & Running Locally

> Prerequisites:
- Docker & Docker Compose

### 🔧 One-Command Setup

```bash
docker-compose up --build
