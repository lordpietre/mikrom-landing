# Mikrom Landing

[![Build & Deploy](https://github.com/spluca/mikrom-landing/actions/workflows/deploy.yml/badge.svg)](https://github.com/spluca/mikrom-landing/actions/workflows/deploy.yml)

Marketing and landing page for [Mikrom](https://www.mikrom.es), a microservices platform for Firecracker microVMs.

Built with **Astro 5** and deployed to **Cloudflare Workers**.

## Project Structure

```text
/
├── public/             # Static files (favicons)
├── src/
│   ├── assets/         # Images/SVGs processed by Astro
│   ├── components/     # Reusable Astro components
│   ├── layouts/        # Page layout wrappers
│   └── pages/          # File-based routing
├── astro.config.mjs    # Astro config (Cloudflare adapter)
└── wrangler.jsonc      # Cloudflare Workers config
```

## Commands

| Command        | Action                                      |
| :------------- | :------------------------------------------ |
| `pnpm install` | Install dependencies                        |
| `pnpm dev`     | Start dev server at `localhost:4321`         |
| `pnpm build`   | Build production site to `./dist/`           |
| `pnpm preview` | Preview production build locally             |