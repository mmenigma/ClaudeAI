# BLOG-WORKFLOW.md — AEO Blog Post Refresh Process
*Read this before starting any blog post refresh. Follow every step in order. Do not skip steps or combine them.*

---

## Session Start — What to Provide

Before any work begins, confirm the following are in the conversation:

1. **The existing blog post** — paste the full text or URL
2. **The AEO refresh plan** — upload `cannademy-aeo-refresh-plan.md.pdf` as an attachment
3. **Brand voice reference** — `brand-voice.md` is at https://github.com/mmenigma/ClaudeAI/blob/main/brand-voice.md. Read it before writing a single word.

Do not proceed if any of these are missing. Ask for them first.

---

## The Non-Negotiable Rule

Do the analytical work BEFORE writing. Every approval gate below is mandatory. Do not combine steps or move to the next step without explicit confirmation.

---

## Step 1 — Pre-Write Analysis

Read the existing post in full. Produce a written map covering:

- **Keep as-is:** Content that is accurate, well-written, and in the right place
- **Redundant:** Any sentence or paragraph that repeats a nearby idea
- **Misplaced:** Content that belongs in a different section
- **Missing:** Topics the AEO plan calls for that aren't in the existing post
- **Tone flags:** Any passage that reads dry, academic, or unlike Cheri (see brand-voice.md)
- **Dead links:** Flag every broken or Teachable-era URL with ⚠️

**→ STOP. Deliver this map. Do not proceed to Step 2 until Mitch confirms.**

---

## Step 2 — Propose the H2 Structure

List every proposed H2 with one sentence describing what that section covers.

Check for:
- Overlap between adjacent sections (if two H2s cover the same idea, merge them)
- Logical flow (does each section build on the previous one?)
- Correct count (5 is the SEO sweet spot for list-format posts; always odd numbers)
- Alignment with what the AEO plan specifies for this post

**→ STOP. Deliver the proposed H2 list. Do not write the draft until Mitch confirms the structure.**

---

## Step 3 — Change Summary for Approval

Before writing a single word of draft, deliver a complete plain-English summary of every change planned:

- What is being removed and why
- What is being added and why
- Which sections are being restructured
- Any links being replaced or flagged
- Any pricing references that need verification against brand-voice.md

This is Mitch's last review point before the draft is written. Be specific — "tightening the intro" is not sufficient. State exactly what changes.

**→ STOP. Deliver the change summary. Do not write the draft until Mitch confirms.**

---

## Step 4 — Write the Draft

### Document Layout

The delivered document has two clearly separated sections:

---

**SECTION A — REVIEW NOTES (Do Not Paste Into Page Builder)**

Include here:
- Color key (see below)
- All dead link flags with ⚠️ and suggested replacements
- Editor notes explaining structural decisions
- Any questions or decisions that need Mitch's input
- Publishing checklist (see bottom of this document)

---

**SECTION B — CONTENT BLOCK (Paste-Ready)**

Plain text only. No labels, annotations, color codes, or editor notes anywhere inside this block. The entire block from the first word of the title to the last word of the sign-off should be ready to copy directly into the page builder without any cleanup.

---

### Color Coding (Section A reference only — never inside Section B)

- **BLACK** = Cheri's existing content, kept or lightly polished
- **BLUE** = New AEO additions (answer-first paragraphs, FAQ, new sections)
- **GRAY ITALIC** = Structural notes (Section A only)

---

### AEO Answer-First Paragraph — Required Format

Every H2 section must open with an AEO answer-first paragraph immediately after the heading. This is what AI engines scrape. Follow this format exactly:

**What it is:**
2–3 sentences that directly answer the implied question in the H2. Opens with the answer, not a setup. No "In this section..." or "There are many ways to..." openers.

**Voice:**
Plain language. Cheri's warmth. No clinical terms unless immediately defined in plain language.

**Format:**
```
[H2 Heading]

Direct answer sentence in plain language. One more sentence expanding the key point. Optional third sentence only if it adds new information, not restatement.

[Cheri's existing content continues below]
```

**Example:**
```
## Why Edibles Hit Differently Than Smoked Cannabis

When you eat an edible, your liver converts THC into a stronger compound — which is why the effects hit harder, take longer to kick in, and last significantly longer than smoking. Most people are caught off guard the first time, and that's completely normal.

[Cheri's existing content on edibles effects follows here...]
```

---

### Every H2 Section Must Include

1. AEO answer-first paragraph (2–3 sentences, format above)
2. Cheri's existing content below that, with redundant sentences removed
3. A human moment before any technical explanation (see brand-voice.md — Warmth Before Technical Content)

### Structural Rules

- Closing/wrap-up sentences belong AFTER the last point, not inside any individual section
- CTAs belong at the end of the post and in the "Ready to Go Deeper?" section — not scattered through body copy unless they exist in Cheri's original
- FAQ belongs after all body content, before Related Posts
- Related Posts belong at the bottom
- Sign-off matches content type (see brand-voice.md — Sign-Offs)

---

## Step 5 — Image Prompts for Gemini

After the draft is complete, generate image prompts for Gemini. These go in Section A (review notes) — not in the paste-ready content block.

### Model guidance
- **Gemini 3.1 Pro** — use for featured/hero images (higher quality, slower)
- **Gemini 3.1 Flash Lite** — use for in-post images and Pinterest pins (faster, lower cost)

### Style baseline for all prompts
Professional cannabis food photography. Warm natural lighting. Appetizing and inviting. No text overlaid. No people. No cannabis leaves, plants, or raw flower — focus on finished food and drink products only. No drug paraphernalia.

### Required outputs per post

```
## IMAGE PROMPTS — Gemini Generation

**Featured Image — 16:9 landscape (Gemini Pro)**
[Prompt]

**In-Post Image 1 — tied to [Section Name] — 4:3 (Gemini Flash Lite)**
[Prompt]

**In-Post Image 2 — tied to [Section Name] — 4:3 (Gemini Flash Lite)**
[Prompt]

**Pinterest Pin 1 — 2:3 portrait, 1000x1500px (Gemini Flash Lite)**
[Prompt]

**Pinterest Pin 2 — 2:3 portrait, 1000x1500px (Gemini Flash Lite)**
[Prompt]

**Pinterest Pin 3 — 2:3 portrait, 1000x1500px (Gemini Flash Lite)**
[Prompt]
```

Each prompt should specify: subject, food styling details, lighting, mood, background, aspect ratio, and end with "no text"

---
Read the image prompt standards file before generating any images or Pinterest pins:
https://raw.githubusercontent.com/mmenigma/ClaudeAI/refs/heads/main/image-prompts.md
Generate all image prompts following the rules in that file. Place all prompts in Section A only — never in Section B.

## Step 6 — Pre-Delivery Self-Check

Read the complete draft top to bottom as a reader — not a writer — before delivering. Check every item. Do not deliver until all boxes are confirmed.

**Content**
- [ ] Every H2 opens with a 2–3 sentence AEO answer-first paragraph in Cheri's voice
- [ ] No redundant sentences between adjacent paragraphs
- [ ] No two H2 sections covering the same idea
- [ ] Closing/wrap-up statements are after the last point, not inside a section
- [ ] All content from the AEO plan has been incorporated
- [ ] Mango/myrcene tip included where fat absorption is discussed (edibles posts)

**Links**
- [ ] All Teachable URLs replaced with cannademy.com equivalents or flagged ⚠️
- [ ] All dead links flagged in Section A — not inline in the content block
- [ ] No Google Drive links anywhere in the document

**Voice**
- [ ] No dry, textbook-style openings to technical sections
- [ ] No over-explained paragraphs (make the point, stop)
- [ ] Reads like Cheri — not a Wikipedia editor or AI assistant
- [ ] All cannabis terminology follows brand-voice.md rules (THCa → THC, not "activates")

**Pricing — verify against brand-voice.md before every post**
- Free Dosing Class: $0
- Dosing Calculator: $5
- Cannabis Dosing Mastery (DMC): $59 (NOT $39)
- Cannabis Cooking for Home Cooks (CCHC): $89 funnel / $149 full price
- Cannabis Gummies Course: $59
- DIY Cannabis Topicals & Skincare: TBD

**Document layout**
- [ ] Section A contains all notes, flags, color key, and image prompts
- [ ] Section B is clean — no annotations anywhere inside the content block
- [ ] Rank Math snippet block at top of Section A (SEO Title, Meta Description, Focus Keyword)
- [ ] Byline in content: "By Cheri Sicard, Cannabis Author & Educator"
- [ ] "Updated [Month Year]" badge noted
- [ ] FAQ schema reminder in Section A
- [ ] Image prompts complete in Section A

---

## Publishing Checklist (Section A — included with every delivery)

- [ ] Rank Math: SEO title, meta description, focus keyword set
- [ ] Featured image uploaded and alt text written
- [ ] FAQ schema block added
- [ ] All internal links verified as live
- [ ] "Updated [Month Year]" badge applied
- [ ] Post scheduled or published

---

## Known Errors — Never Repeat

See ERRORS.md for full details.

- **Never link to Google Drive** — check all hyperlinks before delivering
- **Never duplicate a sentence** — if new AEO content makes an existing sentence redundant, remove the existing sentence and note it in Section A
- **Never write 3 of 5 points covering the same idea** — map the H2s in Step 2
- **Cannabis Dosing Mastery is $59** — earlier docs had this wrong at $39
- **THCa → THC, CBDa → CBD** — use precise conversion language always
- **Decarboxylation** converts THCa and CBDa — never describe it as "activating" cannabis
- **Never recommend Ardent products** — affiliate program has deteriorated

---

*Document prepared for Cannademy.com | AEO Blog Refresh Workflow*
*Voice rules → brand-voice.md | Product pricing → brand-voice.md | Error history → ERRORS.md*
