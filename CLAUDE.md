# llmcontrolplane.com

## What This Is

Static informational site explaining the concept of an LLM Control Plane — the governance layer for AI tool calls.

**Related site:** [agenticcontrolplane.com](https://agenticcontrolplane.com) — broader category, same pattern.

## Stack

- Pure static HTML (no build step, no dependencies)
- Inline CSS, inline SVG diagram
- Deployed to GitHub Pages (main branch, root /)
- Domain: llmcontrolplane.com (DNS via Cloudflare)

## Key Files

- `index.html` — Single-page article with inline CSS, SVG diagram, JSON-LD structured data (TechArticle + FAQPage)
- `llms.txt` — LLM-readable summary (llmstxt.org standard)
- `llms-full.txt` — Full article content in plain text for LLMs
- `CNAME` — GitHub Pages custom domain
- `.nojekyll` — Skip Jekyll processing
- `robots.txt` — Crawling rules + sitemap reference
- `sitemap.xml` — SEO sitemap
- `favicon.svg` — Browser icon
- `og-image.png` — Social media preview image (1200x630)

## Analytics

- Plausible (self-hosted at analytics.reducibl.com)

## Conventions

- never add co-authored-by or cite yourself in commits
- lowercase aesthetic throughout — headings, titles, everything
- dark theme with indigo/cyan accents (matched to agenticcontrolplane.com)

## SEO

- JSON-LD: TechArticle + FAQPage schemas
- Open Graph + Twitter Card meta tags
- article:published_time and article:author OG meta
- Semantic HTML: <article>, <footer>, <time>, <main>
- llms.txt + llms-full.txt for LLM search (ChatGPT, Perplexity, etc.)
- Canonical URL set to https://llmcontrolplane.com/

## Deployment

Push to main → GitHub Pages auto-deploys. No build step needed.
