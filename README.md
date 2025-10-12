# url-to-video-hackbarna
From product URL to UGC kit in 1 min (4 imgs, 4 vids, captions, brand-aware).

**Live demo:** https://mysynt.io
**Login (demo):** Click **“Continue with Google”** or signup via email.  
**Note:** Built entirely on **Lovable** (no separate GitHub codebase). 

## What it does
Paste a product URL → we ingest HTML (incl. gallery), extract benefits/CTAs/brand palette → generate 4 UGC scripts → render 4 vertical videos (captions, logo, CTA).

## How it works
Firecrawl ingest → LLM extraction → prompt templates (review / unboxing / how-to / teaser) → FFmpeg assemble → subtitles & brand colors.  
Orchestration: n8n + cached assets.

## Exports (samples)
See `/exports` for Firecrawl sample, n8n workflow, and prompt templates.

## Roadmap
Batch by sitemap • personas • multilingual • Ads export.

## Contact
Valery — <email / Telegram>
