# BakeryOS Web

The official BakeryOS landing page. It presents BakeryOS as an Arch Linux based desktop distribution built for a smoother developer experience.

## Requirements

- Node.js `>=22.12.0`
- pnpm

## Getting Started

Install dependencies from this directory:

```bash
pnpm install
```

Start the local development server:

```bash
pnpm dev
```

The site will be available at the local URL printed by Astro, normally `http://localhost:4321`.

## Commands

| Command        | Description                          |
| -------------- | ------------------------------------ |
| `pnpm dev`     | Start the Astro development server   |
| `pnpm build`   | Build the static production site     |
| `pnpm preview` | Preview the production build locally |
| `pnpm astro`   | Run the Astro CLI                    |

## Project Structure

```text
src/
├── assets/                # Screenshots and branding assets
├── components/            # Page sections and shared navigation/footer
├── layouts/               # HTML document layout and metadata
├── pages/                 # Astro pages
└── styles/                # Global design system and responsive styles
```

## Production Build

Create the static site with:

```bash
pnpm build
```

The generated site is written to `dist/` and can be deployed to any static hosting provider.
