# Global Coding Standards

## 1. Naming Conventions
- **Repositories:** Must follow the pattern `client-<name>-<type>` (e.g., `client-qala-studio-react`).
- **Branches:** `feat/`, `fix/`, or `agent/<name>/<task>`.

## 2. Mandatory Repo Checklist
Before a project is "Complete", it must have:
- [ ] `src/` folder with all code.
- [ ] `docs/BRIEF.md`, `docs/DECISIONS.md`, and `docs/CHANGELOG.md`.
- [ ] No secrets in code (use `.env.example`).
- [ ] Working `notify-portfolio.yml` workflow.

## 3. Secret Management
- Use GitHub Secrets for API keys.
- Never commit `.env` files.

## 4. Definition of "Deployed"
A project is considered deployed only when:
1. All tests in `tests/` pass.
2. The live URL is accessible.
3. The `CHANGELOG.md` has been updated with the new version.
4. The Master Portfolio pointer has been updated.
