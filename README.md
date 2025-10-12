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
1) Paste a product URL in the web app (built with Lovable).
2) Firecrawl fetches and structures the product page: title, price, description, gallery, brand cues.
3) OpenAI 4o mini reads this data and infers audience, tone, benefits, objections, and CTAs.
4) We normalize images: crop/resize to vertical, clean artifacts, and pick a key “hero” frame.
5) The LLM composes prompt templates for four formats: review, unboxing, how to, teaser.
6) We generate “product + avatar” stills with Gemini Flash Image 2.5 (“Nano Banana”) on Runware.
7) We animate them into short vertical videos with Veo 3 / Kling, then add subtitles and CTA.
8) The app returns a ready UGC kit: 4 videos, 4 images, plus captions and hashtags — all on brand.
9) **All of this is fully automated under the hood.**

## Exports (samples)
See `/exports` for Firecrawl sample, n8n workflow, and prompt templates.

## Roadmap
Batch by sitemap • personas • multilingual • Ads export.

## Contact
Valery — <email / Telegram>
