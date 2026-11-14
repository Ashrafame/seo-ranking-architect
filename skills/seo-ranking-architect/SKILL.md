---
name: seo-ranking-architect
description: Optimize websites and web applications for top Google Search rankings, crawlability, Core Web Vitals, and rich search snippets. Use when building new web pages, auditing HTML/Next.js/React/Vercel sites for SEO, writing meta tags, Open Graph/Twitter cards, JSON-LD structured data, sitemaps, robots.txt, canonical URLs, or improving semantic structure and search engine visibility.
---

# SEO Ranking Architect

Optimize websites for maximum Google Search visibility, clean crawlability, fast Core Web Vitals, and high click-through rates from search results.

## When to Use
- Building or launching a new website, landing page, or web application.
- Auditing an existing site (static HTML, React, Next.js, or Vercel-hosted) for technical and on-page SEO issues.
- Generating or fixing `<title>`, meta descriptions, canonical links, Open Graph tags, `robots.txt`, `sitemap.xml`, or JSON-LD structured data.
- Improving page hierarchy, internal linking, image alt attributes, or Core Web Vitals performance.

## Audit & Optimization Workflow
### 1. Crawlability & Indexing Foundations
- Verify a valid `robots.txt` exists allowing public pages and pointing to `sitemap.xml`.
- Generate or verify XML `sitemap.xml` listing all canonical indexable URLs with `<loc>` and `<lastmod>`.
- Ensure every indexable page includes self-referencing `<link rel="canonical" href="...">` and no accidental `noindex` tags.

### 2. On-Page & Semantic HTML Structure
- Enforce a single keyword-focused `<h1>` per page followed by a logical `<h2>` -> `<h3>` hierarchy.
- Craft unique `<title>` tags (50-60 chars) and `<meta name="description">` tags (140-160 chars) for high CTR.
- Ensure meaningful `<img>` elements have descriptive `alt` text, explicit `width`/`height` dimensions, and modern formats (WebP/AVIF).

### 3. Rich Snippets & Structured Data (JSON-LD)
- Inject valid `<script type="application/ld+json">` schema markup (`WebSite`, `Organization`, `SoftwareApplication`, `MobileApplication`, `Article`, `FAQPage`, `Product`).
- Add complete Open Graph (`og:title`, `og:description`, `og:image`, `og:url`, `og:type`) and Twitter Card metadata.

### 4. Technical Performance & Core Web Vitals
- Ensure `<html lang="...">` and viewport meta tags are set, eliminate render-blocking scripts, preload LCP hero assets, and ensure critical content renders in initial HTML (SSR/SSG).

## Output Format
1. **Priority Issues Found:** Ordered by ranking impact (**Critical**, **High**, **Medium**).
2. **Ready-to-Use Implementation:** Drop-in code for meta tags, JSON-LD schema, `sitemap.xml`, `robots.txt`, and semantic HTML fixes.

## Gotchas
- Never stuff keywords; write natural, user-first titles and headings.
- Ensure JSON-LD URLs are absolute (`https://...`) and match schema.org specs.
