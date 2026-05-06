# Antigravity Master Portfolio Hub

Welcome to the single source of truth for all Antigravity client projects.

## 📁 Repository Structure
- `clients/`: Every client project is linked here as a **Git Submodule**.
- `docs/`: Global Governance docs (Vision, Standards, Tech Stack).
- `artifacts/`: Proposals, pitch decks, and design assets.

## 🚀 Getting Started (How to Clone)
To get all projects at once, use:
```bash
git clone --recurse-submodules https://github.com/Lakshya4392/portfolios.git
```
If you already cloned it and the folders are empty:
```bash
git submodule update --init --recursive
```

## 🛠️ Developer Guide: What are Submodules?
Submodules are like "live links" to other repositories. 
- **The Hub** (`portfolios`) keeps track of which version (commit) each client is on.
- **The Spokes** (Individual repos) hold the actual code.

### How to add a new client:
1. `cd clients`
2. `git submodule add <REPO_URL> <CLIENT_NAME>`
3. `git commit -m "add <CLIENT_NAME> to portfolio"`
4. `git push origin main`

## 🤖 Automation
This hub is powered by GitHub Actions. When you push to any client repo, the **notify-portfolio** workflow automatically updates the pointer here. No manual sync required!

---
*Verified by AG Brain — Standardized Infrastructure v1.0*
