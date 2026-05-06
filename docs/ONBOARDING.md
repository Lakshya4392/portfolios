# Developer Onboarding

## Getting Started
1. Clone the master repo: `git clone --recurse-submodules <portfolio-url>`
2. Run `git submodule update --init --recursive` to fetch all client projects.

## Credentials
- Request access to the organization's GitHub secrets.
- Copy .env.example to .env in each client folder.

## Making Changes
- Create a new branch: `agent/<name>/<feature>`.
- Use worktrees for parallel work.
- Always update CHANGELOG.md before PR.
