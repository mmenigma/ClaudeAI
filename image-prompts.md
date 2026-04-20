# image-prompts.md — Image Generation & Pinterest Pin Standards
*Read this file whenever generating images or Pinterest pins for Cannademy.com or cannabischeri.com posts.*

---

## Overview

This file governs all image prompt generation for blog posts across both sites. It covers:
- Featured images and in-post images (for Gemini generation)
- Pinterest pins (image prompts + text overlays + pin descriptions)

All image prompts are placed in **Section A only** of the delivered post document. They are never inside Section B.

---

## Model Selection

| Image type | Model |
|---|---|
| Featured/hero image | Gemini 3.1 Pro (higher quality) |
| In-post images | Gemini 3.1 Flash Lite (faster, lower cost) |
| Pinterest pins | Gemini 3.1 Flash Lite (faster, lower cost) |

---

## Cannabis Content Rule

People, cannabis leaves, cannabis plants, and raw cannabis flower may be included when they strengthen the image concept. Finished food and wellness products are always acceptable.

## On composition:

Single-subject images leave too much dead space in the 1500px tall format — always compose with multiple elements (hero food + supporting items like jars, ingredients, utensils, garnishes, or a second food item) to fill the vertical space naturally
Aim for a kitchen, or table setting scene, not a product shot

## On food variety:

gummy worms, gummy cannabis leaves, gummies shapes, brownies of diffrent varieties-not just chocolate, cookies, rice crispy treats, pasta, sauces, soups, salad dressings, hot beverages, pizza
No more than one brownie image per post, and avoid brownies entirely when other foods are equally relevant to the topic

## On infusion
When ever depicting the actual infusion or topical it needs to have a green or light green tint so it's known to be infused with cannabis.

---

## Style Palette — Assign a DIFFERENT Style to Each Image in the Post

Do not repeat the same style twice within a single post. Track which styles have been used in recent posts and avoid repeating across consecutive posts.

| Style | Lighting | Mood |
|---|---|---|
| Warm golden hour | Soft directional side light, amber tones | Cozy, homey, abundant |
| Cool bright studio | Diffused overhead daylight, crisp neutral shadows | Clean, modern, editorial |
| Moody dark | Dramatic single-source side light, deep shadows | Sophisticated, artisan |
| Airy minimal | Pale even light, minimal props, lots of negative space | Calm, spa-like, serene |
| Rustic farmhouse | Soft natural window light, textured surfaces | Approachable, handmade, wholesome |
| Modern clean | Bright overhead, geometric arrangements, graphic shadows | Precise, contemporary |
| Cozy evening | Warm lamp or candlelight glow, soft shadow | Intimate, relaxed, personal |
| Bright outdoor | Natural open shade or dappled sunlight | Fresh, energetic, lifestyle |

---

## Surface and Background Palette — Vary Across Images

Never use the same surface in two images within the same post.

**Light surfaces:** white marble, pale limestone, light ash wood, parchment paper, cream linen, white ceramic tile, bleached oak

**Mid-tone surfaces:** butcher block, natural pine, terracotta tile, sage linen, unbleached cotton, warm concrete

**Dark surfaces:** dark walnut, slate, charcoal concrete, black granite, deep espresso wood, aged cast iron

**Textile/soft surfaces:** folded linen towel, knit throw, raw cotton cloth, woven rattan tray, weathered burlap

---

## Pinterest Pins — Keyword and Description Rules

Pinterest is a search engine. Every pin must be optimized for how people actually search, not just written to sound compelling.

### Text Overlay (the headline on the image)

- Lead with the primary search keyword phrase — write it the way someone would type it into Pinterest search
- Example: **"How to Make Edibles Without Wasting Cannabis"** not **"Stop Wasting Cannabis on Weak Edibles"**
- 6–10 words maximum — must be legible at thumbnail size
- Each of the three pins per post should target a different keyword angle on the same post topic

### Pin Description (entered in Pinterest when uploading — not on the image)

- 150–300 characters
- Open with the primary keyword phrase naturally in the first sentence
- Read like a mini intro to the post, not a caption
- Include 2–3 related keyword phrases worked in naturally
- End with a soft CTA: "Get the full guide at Cannademy.com" or similar
- No hashtags — keyword phrases significantly outperform hashtags

**Example — post about dosing homemade edibles:**

> Text overlay: How to Dose Homemade Edibles (Step-by-Step)
>
> Description: Learn how to dose homemade edibles accurately every time — even without a lab test. This step-by-step guide covers the dosing formula, decarb variables, and how to calculate mg per serving for any recipe. Full guide at Cannademy.com.

---

## Pinterest Pins — Scheduling Notes

- Pinterest pins are posted to Pinterest only — they are NOT embedded in the blog post
- Space pin uploads out over separate days or weeks via CCM — do not upload all three at once
- Each pin links back to the blog post URL

---

## Required Output Format

```
IMAGE PROMPTS — Gemini Generation

Styles used: [list style name assigned to each image — no repeats within post]

Featured Image — 16:9 landscape (Gemini 3.1 Pro)
Style: [style name from palette]
Surface/background: [surface from palette]
[Prompt — include: subject, food styling details, specific lighting from chosen style,
mood, surface/background detail, aspect ratio, "no text"]

In-Post Image 1 — tied to [Section Name] — 4:3 (Gemini Flash Lite)
Style: [style name — must differ from featured image]
Surface/background: [surface — must differ from featured image]
[Prompt — "no text"]

In-Post Image 2 — tied to [Section Name] — 4:3 (Gemini Flash Lite)
Style: [style name — must differ from images above]
Surface/background: [surface — must differ from images above]
[Prompt — "no text"]

Pinterest Pin 1 — 2:3 portrait, 1000px x 1500px (Gemini Flash Lite)
Style: [style name]
Surface/background: [surface]

Image prompt: [Prompt — include: subject, food styling, lighting from chosen style,
"leave clean space at top or bottom for text overlay, no text"]
Text overlay: [Keyword-led headline — 6–10 words, written as a search query]

Pin description: [150–300 characters, opens with primary keyword phrase, includes
2–3 related keywords naturally, ends with soft CTA to Cannademy.com]

Pinterest Pin 2 — 2:3 portrait, 1000px x 1500px (Gemini Flash Lite)
Style: [style name — must differ from Pin 1]
Surface/background: [surface — must differ from Pin 1]

Image prompt: [Prompt]Text overlay: [Different keyword angle from Pin 1]

Pin description: [150–300 characters, different keyword angle from Pin 1]

Pinterest Pin 3 — 2:3 portrait, 1000px x 1500px (Gemini Flash Lite)
Style: [style name — must differ from Pins 1 and 2]
Surface/background: [surface — must differ from Pins 1 and 2]

Image prompt: [Prompt]
Text overlay: [Different keyword angle from Pins 1 and 2]

Pin description: [150–300 characters, different keyword angle from Pins 1 and 2]
```
*Applies to Cannademy.com and cannabischeri.com*
*Voice rules: brand-voice.md | SEO/AEO standards: seo-aeo-standards.md*
*Blog post workflow: BLOG-WORKFLOW.md*
