📌 README.md for Monorepo

# Monorepo with Turborepo, Next.js, and NestJS

This is a monorepo setup using **Turborepo**, containing:
- 🏗️ **Frontend**: Next.js + TailwindCSS + React Hook Form
- 🔥 **Backend**: NestJS + PostgreSQL + Drizzle ORM + Zod
- ⚡ **Monorepo Tooling**: Turborepo + Yarn Workspaces

## 🚀 Getting Started

### 1️⃣ Install Dependencies
```sh
yarn install
2️⃣ Run Development Servers
sh
Copy
Edit
yarn turbo run dev --parallel
Or, run frontend/backend separately:

sh
Copy
Edit
yarn turbo run dev --filter=frontend
yarn turbo run dev --filter=backend
📂 Folder Structure
bash
Copy
Edit
monorepo/
│── apps/
│   ├── frontend/   # Next.js (React, Tailwind, React Hook Form)
│   ├── backend/    # NestJS (Drizzle ORM, PostgreSQL, Zod)
│── packages/       # Shared configs, utilities, etc.
│── turbo.json      # Turborepo configuration
│── package.json    # Yarn workspaces configuration
│── README.md       # Project documentation
🛠️ Tech Stack
Frontend: Next.js, TailwindCSS, React Hook Form
Backend: NestJS, PostgreSQL, Drizzle ORM, Zod
Tooling: Yarn Workspaces, Turborepo
🔥 Contributing
Feel free to fork this repo, submit issues, and create pull requests!