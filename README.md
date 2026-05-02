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

## License
See LICENSE file for details.
