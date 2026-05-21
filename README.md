# brand-design

AI-powered application from Aurora Market.

## Domain
https://auroramarket.org

## Features
- Premium-only AI tools
- No free tier
- Subscription required

## Deployment (Vercel)
1. Import this repository in Vercel.
2. Framework preset: `Other` (static site).
3. Build command: none.
4. Output directory: `.`
5. Deploy.

## Environment Variables
If backend/payment integrations are enabled, configure values from `.env.example`:
- `NEXT_PUBLIC_APP_URL`
- `NODE_ENV`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `DATABASE_URL`
- `OPENAI_API_KEY`

## CI
`.github/workflows/ci.yml` validates required deployment files and HTML output on every push/pull request. If a `package.json` is added later, it will also run available scripts (`lint`, `check`, `typecheck`, `test`, `build`).

## License
See LICENSE file for details.

## Aurora Ecosystem Positioning
This project is positioned as part of the Aurora ecosystem and is ready for Aurora-aligned workflows and automation.

### No-Key-First Operation
This repository supports a no-key-first setup for local evaluation and onboarding, with optional credentials only for advanced integrations.

<!-- AURORA:README:START -->
## Aurora Rayes alignment

**Aurora Raye Lp Brand Design** is the preferred human-readable product name for generated Aurora Rayes collateral. The repository slug stays unchanged unless a separate rename process is approved.

- Keep README messaging grounded in verified capabilities already present in this repo.
- Prefer no-key-first evaluation and onboarding paths when the repo supports them.
- Keep SELL.md and MARKETING.md aligned with the actual setup, deployment, and feature surface documented here.
<!-- AURORA:README:END -->

