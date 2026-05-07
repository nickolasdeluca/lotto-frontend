# Mega Sena Generator

A modern, dark-mode static web app to generate random Mega Sena lottery combinations.

Built with [Astro](https://astro.build) + [Bun](https://bun.sh). Deployed on [Vercel](https://vercel.com).

## Features

- Generate 1–10 games per turn
- 6–9 numbers per game (01–60), sorted ascending
- Cryptographically secure randomness via `crypto.getRandomValues`
- Zero server-side function invocations — fully static
- Dark mode, responsive design

## Tech Stack

- **Framework**: Astro (static output)
- **Runtime / Package Manager**: Bun
- **Hosting**: Vercel

## Getting Started

```bash
bun install
bun run dev      # development server
bun run build    # production build → dist/
bun run preview  # preview production build
```

## Deployment

Import the repository into Vercel. The `vercel.json` is already configured for Astro static builds.
