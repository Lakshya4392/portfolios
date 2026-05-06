# Master Portfolio Hub

This is the central hub for all client website projects.

## Structure
- `clients/`: Git submodules for each client project.
- `docs/`: Global vision, standards, and onboarding guides.
- `artifacts/`: Proposals and high-level design assets.

## How to Clone
`git clone --recurse-submodules https://github.com/Lakshya4392/portfolios.git`

## Automation
Every client repo is equipped with a `notify-portfolio.yml` workflow that automatically updates its submodule pointer here on every push to main.
