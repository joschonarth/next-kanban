<div align="center">

# 📋 next-kanban

*A simple and focused Kanban board to plan, track and deliver your work.*

<img src="https://img.shields.io/github/last-commit/joschonarth/next-kanban?style=default&logo=git&logoColor=white&color=818cf8&labelColor=#4f46e5" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/joschonarth/next-kanban?style=default&color=818cf8&labelColor=#4f46e5" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/joschonarth/next-kanban?style=default&color=818cf8&labelColor=#4f46e5" alt="repo-language-count">

---

📃 [About](#-about)&nbsp;&nbsp;•&nbsp;&nbsp;
🛠️ [Tech Stack](#️-tech-stack)&nbsp;&nbsp;•&nbsp;&nbsp;
✨ [Features](#-features)&nbsp;&nbsp;•&nbsp;&nbsp;
🚀 [Getting Started](#-getting-started)

</div>

---

<img width="1907" height="933" alt="next-kanban" src="https://github.com/user-attachments/assets/40cb3eda-d6e6-4e5b-895b-33968f78065e" />

---

## 📃 About

**next-kanban** is a full-stack Kanban board application built with Next.js. Organize tasks across four columns — **Backlog**, **To Do**, **In Progress**, and **Done** — with support for liking tasks, leaving comments, and signing in with GitHub. The app features a clean UI with authentication, server-side rendering, and a type-safe API layer.

---

## 🛠️ Tech Stack

- ⚛️ **[Next.js](https://nextjs.org/)** — Full-stack React framework with App Router.
- 🟦 **[TypeScript](https://www.typescriptlang.org/)** — Type safety across the entire codebase.
- 🔥 **[Hono](https://hono.dev/)** — Lightweight web framework for the API layer.
- 🗃️ **[Drizzle ORM](https://orm.drizzle.team/)** — Lightweight, type-safe ORM for TypeScript.
- 🐘 **[PostgreSQL](https://www.postgresql.org/)** — Reliable relational database.
- 🔐 **[Better Auth](https://better-auth.com/)** — Authentication for modern full-stack apps.
- 🐙 **[GitHub OAuth](https://docs.github.com/en/apps/oauth-apps)** — Social login via GitHub.
- 🏝️ **[TanStack Query](https://tanstack.com/query)** — Async state management with caching.
- 💎 **[Zod](https://zod.dev/)** — Runtime schema validation with full type inference.
- 🎨 **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first CSS framework.
- 🧩 **[Radix UI](https://www.radix-ui.com/)** — Accessible, headless UI primitives.
- 📖 **[Scalar](https://scalar.com/)** — Beautiful interactive API documentation.
- 🔍 **[Biome](https://biomejs.dev/)** — Fast, opinionated linter and formatter.

---

## ✨ Features

- [x] 📋 Kanban board with **Backlog**, **To Do**, **In Progress**, and **Done** columns
- [x] ❤️ Like tasks
- [x] 💬 Add and view comments on tasks
- [x] 🔐 Authentication with Better Auth
- [x] 🐙 Sign in with GitHub OAuth
- [x] 🗂️ Full type-safe API with Hono + Zod OpenAPI
- [x] 📖 Interactive API documentation via Scalar

---

## 🚀 Getting Started

### 📋 Prerequisites

- 🟩 [Node.js 18+](https://nodejs.org/)
- 📦 [pnpm](https://pnpm.io/)
- 🐳 [Docker](https://www.docker.com/)

### 🔧 Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/joschonarth/next-kanban.git
    ```

2. Navigate into the project:

    ```bash
    cd next-kanban
    ```

3. Install dependencies:

    ```bash
    pnpm install
    ```

### 🔑 Environment Variables

Copy the example env file and fill in your values:

```bash
cp .env.example .env
```

### 🐳 Database

Start the PostgreSQL container:

```bash
docker compose up -d
```

Apply the database migrations:

```bash
pnpm run db:migrate
```

Optionally seed the database with sample data:

```bash
pnpm run db:seed
```

### ▶️ Running

```bash
pnpm run dev
```

App running at **[http://localhost:3000](http://localhost:3000)**

---

## 📖 API Documentation

With the server running, access the interactive docs powered by Scalar:

- 📚 **[http://localhost:3000/api/docs](http://localhost:3000/api/docs)**

---

## ⭐ Support

If this project was useful to you, consider leaving a ⭐ on GitHub!

---

<div align="center">

Made with ♥ by **[João Otávio Schonarth](https://github.com/joschonarth)**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/joschonarth)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/joschonarth)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:joschonarth@gmail.com)

</div>
