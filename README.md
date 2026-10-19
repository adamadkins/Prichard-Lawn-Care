# Prichard Lawn Care & Tree Service

A responsive, static website prototype for Prichard Lawn Care & Tree Service, deployed using Cloudflare Workers Static Assets.

## Deployment

- **Branch:** `main`
- **Static asset directory:** `public/`
- **Cloudflare deploy command:** `npx wrangler deploy`
- **Configuration:** `wrangler.jsonc` at the repository root
- **Build command:** none is required for this static HTML/CSS/JavaScript site

The production site pages are `/`, `/services/`, `/about/`, `/gallery/`, `/careers/`, `/contact/`, `/privacy/`, and `/terms/`.

Changes to `main` should trigger Cloudflare builds when the Cloudflare Git integration is enabled. The Cloudflare **Deployments** tab confirms whether the most recent commit was deployed.

## Important integration notes

- Online payment links point to the designated SwipeSimple payment link.
- Quote and career inquiry forms presently prepare email drafts; they do **not** automatically submit or store data. FormSubmit requires a verified recipient address before enabling delivery.
- Review careers listings, business details and legal policy drafts with the company before launch.
