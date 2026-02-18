# NERVOPS

A MAGI-inspired static portfolio site for the NervOps multi-agent AI system.

## Stack

- Astro 4 (static output)
- GSAP (boot animation, scroll reveals, stat count-up)
- Pure Astro + HTML/CSS (no UI framework)

## Local Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Build output is generated in `dist/`.

## Deploy to Cloudflare Pages

1. Push this repo to GitHub.
2. In Cloudflare Pages, click **Create a project** and connect `stephenreynolds/nervops`.
3. Configure build settings:
   - **Framework preset:** Astro (or None)
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Deploy. Cloudflare Pages will build and publish automatically.

## Sections

- System Boot Hero
- System Overview + animated counters
- Neural Cores (Balthasar / Melchior / Casper)
- Active Deployments
- Command Interface

## Disclaimer

NervOps is not affiliated with GAINAX, khara, or the official Evangelion franchise.
