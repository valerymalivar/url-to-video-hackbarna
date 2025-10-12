# url-to-video-hackbarna
From product URL to UGC kit in 1 min (4 imgs, 4 vids, captions, brand-aware).

**Live demo:** https://mysynt.io
**Login (demo):** Click **“Continue with Google”** or signup via email.  
**Note:** Built entirely on **Lovable** (no separate GitHub codebase). 

## Problem
Brands and sellers need lots of short UGC across SKUs, but most lack in-house production/marketing and big budgets. So they either juggle GenAI point tools (prompting, editing, subtitling, brand fit) which demands time, expertise, and taste, or run traditional shoots that are slow, expensive, and hard to scale.

## Solution
Paste a product URL and get a ready UGC kit automatically. We crawl the page, extract benefits, specs and brand cues, choose a persona and tone, generate prompts, and produce an on brand kit with 4 vertical videos and 4 images with captions and hashtags. Realistic UGC avatars showcase your product.

## Why it wasn’t possible 12 months ago
- **Team leverage.** Two makers with product + design backgrounds, no in-house engineers, can now ship in a weekend with Lovable. A year ago we’d need a full-stack team and weeks.
- **Models matured.** Production-quality gen video/images and controllable presenters only became viable recently (Nano Banana, Veo 3, Sora 2).
- **Web → structured.** Reliable HTML ingest + LLM extraction now pull benefits/specs/brand cues from messy PDPs automatically.
- **Speed & cost.** Inference is fast and affordable enough for batch UGC; last year it was too slow and too expensive.

## How it works
Firecrawl ingest → LLM extraction → prompt templates (review / unboxing / how-to / teaser) → FFmpeg assemble → subtitles & brand colors.  
Orchestration: n8n + cached assets.

## Exports (samples)
See `/exports` for Firecrawl sample, n8n workflow, and prompt templates.

## Roadmap
Batch by sitemap • personas • multilingual • Ads export.

## Contact
Valery — <email / Telegram>
