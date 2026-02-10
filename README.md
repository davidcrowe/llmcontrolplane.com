# llmcontrolplane.com

Single-page static site defining the "LLM control plane" category. Dark design matching [agenticcontrolplane.com](https://agenticcontrolplane.com).

## Files

- `index.html` — full page with inline CSS, SVG diagram, TechArticle + FAQPage JSON-LD
- `robots.txt` — allows all crawlers
- `sitemap.xml` — single URL entry
- `favicon.svg` — "LCP" mark in indigo on dark background

## Deploy

Static files — no build step. Drop into any static host:

**Cloudflare Pages / Netlify / Vercel:** connect the repo or drag the folder.

**GitHub Pages:** push to `main`, enable Pages in repo settings.

**Manual:** upload the four files to your web root.

## DNS

Point `llmcontrolplane.com` at your host. If currently a 301 redirect, remove the redirect rule and replace with static hosting.

## SEO notes

- Canonical: `https://llmcontrolplane.com/`
- Primary keyword: "LLM control plane"
- Secondary: "MCP control plane", "AI control plane", "agentic control plane"
- Links to pillar page: [what is an agentic control plane?](https://agenticcontrolplane.com/what-is-an-agentic-control-plane)
- Submit to Google Search Console after deploy
