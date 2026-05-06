# Coding & Organization Standards

## Repo Naming
- Pattern: `client-<name>-<type>` (e.g., `client-qala-studio`)

## Tech Stack
- Frontend: React / Vite / Next.js
- Styling: Tailwind CSS / Vanilla CSS
- Backend: Node.js / Prisma

## Definition of "Complete"
A project is considered complete only if:
1. It follows the standard folder layout.
2. README.md is fully updated.
3. docs/BRIEF.md and docs/CHANGELOG.md exist.
4. notify-portfolio.yml workflow is active.

## Secret Management
- NEVER commit .env files.
- Use .env.example for templates.
- Use GitHub Secrets for production keys.
