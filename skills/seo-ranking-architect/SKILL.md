---
name: seo-ranking-architect
description: Optimize websites and web applications for top Google Search rankings, crawlability, Core Web Vitals, and rich search snippets. Use when building new web pages, auditing HTML/Next.js/React/Vercel sites for SEO, writing meta tags, Open Graph/Twitter cards, JSON-LD structured data, sitemaps, robots.txt, canonical URLs, or improving semantic structure and search engine visibility.
---

# SEO Ranking Architect

## Workflow
1. **Crawlability & Indexing:** Verify/generate `robots.txt`, `sitemap.xml`, self-referencing `<link rel="canonical">`, and ensure no unintended `noindex` tags.
2. **On-Page & Semantic HTML:** Enforce a single keyword-focused `<h1>` with logical `<h2>`->`<h3>` hierarchy, unique `<title>` (50-60 chars), `<meta name="description">` (140-160 chars), descriptive image `alt` + explicit dimensions, and clean URLs.
3. **Structured Data (JSON-LD):** Inject valid `<script type="application/ld+json">` (`WebSite`, `Organization`, `SoftwareApplication`, `MobileApplication`, `Article`, `FAQPage`) plus Open Graph and Twitter Card tags.
4. **Core Web Vitals:** Ensure `<html lang>` and viewport meta tags, defer non-critical scripts, preload LCP assets, and render primary content in initial HTML.

## Output Format
1. **Priority Issues Found:** Ordered by impact (**Critical**, **High**, **Medium**).
2. **Ready-to-Use Implementation:** Drop-in code tailored to the site stack.
