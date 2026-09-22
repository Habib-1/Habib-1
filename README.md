<h1 align="center">Hi 👋, I'm Habibur Rahman Habib</h1>

<h3 align="center">
  Python & Django Backend Developer
</h3>

<p align="center">
  <em>
    Building REST APIs, backend systems and database-driven applications
    with Python & Django.
  </em>
</p>

<p align="center">
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:YOUR_EMAIL">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="YOUR_PORTFOLIO_URL">
    <img src="https://img.shields.io/badge/Portfolio-Visit-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&label=Profile%20Views&color=0e75b6&style=flat" />
</p>

---

## 👨‍💻 About Me

I'm a **Python & Django Backend Developer** focused on building clean,
maintainable and reliable backend applications.

My primary focus is **Django and Django REST Framework**, with hands-on
experience in REST API development, authentication, authorization,
database design, background tasks, API documentation and performance
profiling.

I enjoy solving backend problems and improving the quality and performance
of applications through better architecture, database queries and
engineering practices.

- 🔭 Currently working on **YOUR_CURRENT_PROJECT**
- 🌱 Currently learning **YOUR_CURRENT_LEARNING**
- 💼 Looking for **Junior / Entry-Level Python Django Backend opportunities**
- 📍 Based in **Bangladesh**
- 📫 Email: **YOUR_EMAIL**

---

# ⚙️ Backend Engineering Stack

### Languages & Frameworks

<p>
  <img src="https://skillicons.dev/icons?i=python,django" />
</p>

`Python` `Django` `Django REST Framework`

### Database & Backend Services

<p>
  <img src="https://skillicons.dev/icons?i=postgresql,redis" />
</p>

`PostgreSQL` `Redis` `SQL`

### Async Processing & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=docker" />
</p>

`Celery` `Docker` `Docker Compose`

### API & Development Tools

`JWT` `REST APIs` `OpenAPI` `Swagger`
`drf-spectacular` `Postman` `REST Client`

### Performance

`Django Silk` `Query Profiling` `N+1 Detection`
`Query Optimization`

---

# 🚀 Featured Project

## 💰 Expense Splitter API

<a href="YOUR_EXPENSE_SPLITTER_REPO">
  <img src="https://img.shields.io/badge/View%20Project-Expense%20Splitter-181717?style=for-the-badge&logo=github" />
</a>

A backend-focused expense management and group settlement API built with
**Django REST Framework**.

### Core Features

- 🔐 JWT Authentication
- 👥 Group & Membership Management
- 🛡️ Role-based Permissions
- 💰 Expense Management
- 🧮 Automatic Expense Splitting
- 📊 Per-user Balance Calculation
- 🔄 Settlement Calculation
- 📧 Background Tasks with Celery
- 🐘 PostgreSQL
- 🐳 Docker & Docker Compose
- 📚 OpenAPI / Swagger Documentation
- 🧪 API Testing with Postman
- 🔍 Django Silk Performance Profiling
- ⚡ Database Query Optimization

### Architecture & Technologies

```text
                    ┌──────────────────────┐
                    │      REST Client     │
                    │      / Postman       │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │    Django REST API   │
                    └──────────┬───────────┘
                               │
             ┌─────────────────┼─────────────────┐
             ▼                 ▼                 ▼
       PostgreSQL           Redis             Celery
        Database            Cache          Background Tasks
