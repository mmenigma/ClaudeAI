# CLAUDE.md — Cannademy.com
*Read the root `brand-voice.md` and `ERRORS.md` first. Then read this file and the files it references.*

---

## Read Order for Cannademy Tasks

1. `../brand-voice.md` — voice, compliance, pricing (shared)
2. `../ERRORS.md` — mistakes log (shared)
3. **This file** — Cannademy-specific context
4. `PRODUCTS.md` — full product catalog and funnel architecture
5. The task-specific file:
   - Blog post refresh → `BLOG-WORKFLOW.md` + relevant skill in `../skills/ai-seo/`
   - Email campaign → `CAMPAIGNS.md` + `../skills/email-sequence/`
   - Sales page work → `../skills/page-cro/`
   - Any content task → `../skills/copywriting/`
6. `PROGRESS.md` — check current status before starting, update before ending

---

## The Business

**Cannademy.com** is an online cannabis education platform.
- **Owner:** Mitch
- **Co-owner / Instructor / Face of Brand:** Cheri Sicard
- **Business entity:** Z-Dog Media LLC
- **Sister site:** cannabischeri.com (cannabis cooking blog — ~6,000 active users/month, feeds traffic to Cannademy)

---

## Tech Stack (summary)

| Component | Tool |
|-----------|------|
| CMS | WordPress |
| E-commerce | WooCommerce (PayPal only — cannabis restriction) |
| Course delivery | Thrive Apprentice |
| Page builder | Thrive Architect |
| SEO | RankMath Pro |
| Hosting | SiteGround + SiteGround Optimizer (NOT WP Rocket) |
| Email / CRM | ContentCreator.com (CCM) |
| Video hosting | Bunny.net |
| AI video | HeyGen (Cheri avatar approved for YouTube) |
| Bot protection | Cloudflare Turnstile |
| Custom code | Code Snippets plugin |

See `STACK.md` for full technical details, known plugin issues, and wp-config notes.

---

## Thrive Architect — Special Handling

Standard CSS selectors (`article`, `.entry-content`, `main`) return little or no content on Thrive-built pages. Known workarounds:

- **Reliable selector:** `.thrv_text_element`
- **Extraction limit:** 600 characters per chunk (security filter blocks larger extractions containing URLs)
- **Base64 does NOT bypass** the filter
- **web_fetch returns incomplete content** — never rely solely on it for Thrive page reviews
- **Fallback:** Mitch pastes content as markdown with links in `[text](url)` format

---

## Active Platforms

| Platform | Status | Notes |
|----------|--------|-------|
| YouTube | 30,000 subscribers | Top content: potency, dosing, decarb |
| Facebook | Active | Established audience |
| Pinterest | Active | Strong SEO value |
| Instagram | Dormant | Needs reactivation |
| TikTok | Brand new | Starting from zero |
| Email (CCM) | Active | ~5,740 verified contacts |

---

## Email List Segments

| Segment | Verified Count | Purchase History |
|---------|---------------|-----------------|
| Calculator owners, no course | ~1,370 | Bought $5 calc — warm buyers |
| No calculators, no course | ~4,370 | Nothing — start with $5 pitch |

---

## Content Rules (Cannademy-specific)

- YouTube teases course lessons — **NEVER gives full lesson content free**
- CTA pattern for videos: "Get the full lesson + [feature] inside [course name]"
- Short-form (TikTok/Reels) requires **separate scripts** from YouTube — never repurposed cuts
- HeyGen AI avatar for YouTube only — not TikTok/Reels (authenticity matters there)
- One topic brief can produce: 1 YouTube script + 2-3 separate short-form scripts
- HeyGen script length: 300-400 words for 2-3 minute video

---

## Session Rules

1. Read all files in the read order above before starting work
2. Log any errors to `../ERRORS.md`
3. Log any strategic decisions to `DECISIONS.md`
4. Update `PROGRESS.md` before ending session
5. Verify all product pricing against `../brand-voice.md` before delivering any content
6. Never link to Teachable — all Teachable URLs must be replaced with cannademy.com equivalents or flagged as `[PLACEHOLDER]`

---

## Key Reference Files in This Folder

| File | What It Covers |
|------|---------------|
| `PRODUCTS.md` | Full product catalog, pricing, funnel architecture |
| `CAMPAIGNS.md` | Email campaign history, status, segments |
| `DECISIONS.md` | Strategic decisions log — do not relitigate without new info |
| `PROGRESS.md` | Current project status and active tasks |
| `STACK.md` | Full technical environment details |
| `BLOG-WORKFLOW.md` | Step-by-step AEO blog post refresh process |
