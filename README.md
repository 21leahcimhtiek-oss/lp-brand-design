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
