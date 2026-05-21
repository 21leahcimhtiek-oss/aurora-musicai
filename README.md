# BeatMind AI

> AI music discovery and playlist curation

## Features
- Personalized playlists
- Mood-based music
- Artist discovery
- Lyrics analysis
- Music journal

## Stack
- Next.js 14 (App Router) + TypeScript
- Tailwind CSS
- OpenAI GPT-4o-mini
- Stripe Subscriptions
- Vercel deployment

## Quick Start

```bash
npm install
cp .env.example .env.local
# Fill in API keys
npm run dev
```

## Environment Variables
Copy `.env.example` to `.env.local` and configure:
- `NEXT_PUBLIC_APP_NAME`
- `NEXT_PUBLIC_APP_URL`
- `OPENAI_API_KEY`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `STRIPE_PRICE_PRO_MONTHLY`
- `STRIPE_PRICE_PRO_YEARLY`
- `DATABASE_URL`

## Commercial Use and Monetization
BeatMind AI is being prepared as an early-access, validation-pending music discovery product for listeners, playlist curators, creators, and music teams. The repository supports free/no-key-first local evaluation before connecting paid APIs or payment providers.

Pricing, feature limits, support levels, and production claims are placeholders until validated with users. No live checkout links, production secrets, or guaranteed recommendation claims are included.

| Plan | Placeholder |
|------|-------------|
| Free / no-key | Local evaluation and playlist workflow review |
| Starter | Individual discovery workflow placeholder |
| Pro | Curator and creator workflow placeholder |
| Enterprise | Team onboarding, integrations, and SLA placeholder |

## Deployment
1. Push your changes to GitHub.
2. Import the repository into Vercel.
3. Add all variables from `.env.example` in Vercel project settings.
4. Confirm build command is `npm run build`.
5. Deploy and verify application health.

## License
MIT (c) 2026 Aurora Rayes LLC

## Aurora Ecosystem Positioning
This repository is part of the Aurora ecosystem: modular open-source building blocks that compose into production-ready AI products and operational systems.

## No-Key-First
Core workflows are designed to run in a no-key-first mode so you can evaluate and develop locally before adding external API keys.

## No-Key-First Note
Default local workflows should work without requiring external API keys; optional integrations can be configured later.

<!-- AURORA:README:START -->
## Aurora Rayes alignment

**Aurora Music AI** is the preferred human-readable product name for generated Aurora Rayes collateral. The repository slug stays unchanged unless a separate rename process is approved.

- Keep README messaging grounded in verified capabilities already present in this repo.
- Prefer no-key-first evaluation and onboarding paths when the repo supports them.
- Keep SELL.md and MARKETING.md aligned with the actual setup, deployment, and feature surface documented here.
<!-- AURORA:README:END -->

