# Modern Next.js + FastAPI Template

A clean, modern, full-stack template with Next.js 16, FastAPI, Tailwind CSS 4, and shadcn/ui.

<img src="public/image.png" alt="Modern Next.js + FastAPI Template" width="auto">

## Tech Stack

**Frontend:** Next.js 16 (Turbopack) · Tailwind CSS 4 · shadcn/ui · Lucide React · Sonner · Motion (Framer Motion)
**Backend:** FastAPI · Python 3.13+  
**Linting:** Ruff (Python) · ESLint (TypeScript)  
**Package Managers:** pnpm (TypeScript) · uv (Python)

## Prerequisites

- [pnpm](https://pnpm.io/installation) — fast Node.js package manager
- [uv](https://docs.astral.sh/uv/getting-started/installation/) — fast Python package manager

## Quick Start

```bash
# Install dependencies
pnpm install && uv sync

# Run frontend (localhost:3000)
pnpm dev

# Run backend (localhost:8000)
uv run fastapi dev backend/main.py
```

## Project Structure

```
app/            -> Next.js frontend
backend/        -> FastAPI backend
components/ui/  -> shadcn/ui components
```

## Commands

```bash
# Add shadcn component (from root directory)
pnpm dlx shadcn@latest add button

# Linting and formatting
uv run ruff check --fix backend/
uv run ruff format backend/
pnpm run lint --fix
```

## Licence

[MIT License](LICENSE)
