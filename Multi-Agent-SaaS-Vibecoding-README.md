# Multi-Agent SaaS Vibecoding System

A reusable AI-agent workflow for building scalable SaaS applications using VS Code, Cursor, Windsurf, Claude, or ChatGPT.

---

# Overview

This system helps you structure AI-assisted development using multiple specialized agents.

Instead of asking one AI to build everything, you split responsibilities across dedicated agents:

- Main Agent → Architecture & orchestration
- Product Agent → Planning
- Database Agent → Schema
- Backend Agent → APIs & business logic
- UI Agent → UX & design
- Frontend Agent → Screens & components
- QA Agent → Testing
- Deploy Agent → Production deployment

This creates:

- Cleaner codebases
- Better scalability
- Faster development
- Less AI chaos
- More production-ready SaaS systems

---

# Recommended Tools

## IDE

- VS Code
- Cursor
- Windsurf

## Stack

- Next.js
- TypeScript
- TailwindCSS
- PostgreSQL
- Prisma
- Redis
- Vercel
- Railway

---

# Project Structure

```txt
project-name/
├── AGENTS.md
├── RULES.md
├── README.md
├── docs/
│   └── project-context.md
├── prompts/
│   ├── main-agent.md
│   ├── product-agent.md
│   ├── ui-agent.md
│   ├── frontend-agent.md
│   ├── backend-agent.md
│   ├── database-agent.md
│   ├── qa-agent.md
│   └── deploy-agent.md
├── apps/
├── packages/
├── services/
└── infrastructure/
```
