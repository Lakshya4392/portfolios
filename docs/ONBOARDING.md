# Onboarding Guide

## 1. Cloning the Portfolio
Use the recursive clone command to get everything:
```bash
git clone --recurse-submodules https://github.com/Lakshya4392/portfolios.git
```

## 2. Getting Access
- Request access to the GitHub Organization.
- Set up your SSH keys.
- Get the `PORTFOLIO_PAT` from the admin for local testing.

## 3. Making Your First Contribution
1. Choose a client in `clients/`.
2. Create a branch: `git checkout -b feat/your-task`.
3. Make changes and commit with prefix: `[client-name] feat: <message>`.
4. Push and wait for the automation to update the Hub.
