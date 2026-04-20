# BLOG-WORKFLOW.md — AEO Blog Post Refresh Process
*Read this before starting any blog post refresh. Follow every step in order. Do not skip steps or combine them.*

---

## Session Start — Read These Files First

Before any work begins, read the following reference files in full:

1. **Brand voice:** https://raw.githubusercontent.com/mmenigma/ClaudeAI/main/brand-voice.md
2. **SEO/AEO standards:** https://raw.githubusercontent.com/mmenigma/ClaudeAI/main/seo-aeo-standards.md

**For Cannademy posts only — also read:**
3. **Post-specific refresh plan:** https://raw.githubusercontent.com/mmenigma/ClaudeAI/main/cannademy/cannademy-aeo-refresh-plan.md
   - Do NOT read the entire file. Locate the specific post being worked on by URL slug or title and read only that entry.
   
   - Note: The post URL is in cannademy-aeo-refresh-plan.md for each post entry. Pull it from there and include it in the document header.

Then confirm the following is in the conversation:
- **The existing blog post** — pasted in full or provided as a URL

Do not begin analysis until all reference files are read and the post content is available.

---

## Model

Use **Claude Opus 4.7** for all copywriting steps (Steps 3 and 4). Analysis and structural steps (Steps 1 and 2) may use any available model.

---

## The Non-Negotiable Rule

Do the analytical work BEFORE writing. Every approval gate below is mandatory. Do not combine steps or move to the next step without explicit confirmation from Mitch.

---

## Step 1 — Pre-Write Analysis

Read the existing post in full. Produce a written map covering:

- **Keep as-is:** Content that is accurate, well-written, and in the right place
- **Redundant:** Any sentence or paragraph that repeats a nearby idea
- **Misplaced:** Content that belongs in a different section
- **Missing:** Topics the SEO/AEO standards or post-specific plan call for that aren't present
- **Tone flags:** Any passage that reads dry, academic, or unlike Cheri (see brand-voice.md)
- **Dead links:** Flag every broken or Teachable-era URL with a warning flag
- **Paragraphs over 4 lines:** Flag any that need breaking up

**STOP. Deliver this map. Do not proceed to Step 2 until Mitch confirms.**

---

## Step 2 — Propose the H2 Structure

List every proposed H2 with one sentence describing what that section covers.

Check for:
- All H2s written as questions (see seo-aeo-standards.md Standard 3)
- Overlap between adjacent sections (if two H2s cover the same idea, merge them)
- Logical flow (does each section build on the previous one?)
- Correct count (5 is the SEO sweet spot for list-format posts; always odd numbers)
- Alignment with the post-specific plan in cannademy-aeo-refresh-plan.md (Cannademy posts)

**STOP. Deliver the proposed H2 list. Do not write the draft until Mitch confirms the structure.**

---

## Step 3 — Change Summary for Approval

Before writing a single word of draft, deliver a complete plain-English summary of every planned change:

- What is being removed and why
- What is being added and why
- Which sections are being restructured
- Which links are being replaced or flagged
- Any pricing references that need verification (check brand-voice.md product table)
- Confirmation that the FAQ block meets the minimum 4-question requirement

This is Mitch's last review point before the draft is written. Be specific.

**STOP. Deliver the change summary. Do not write the draft until Mitch confirms.**

---

## Step 4 — Write the Draft

### Model
Use **Claude Opus 4.7** for all writing in this step.

---

### Document Layout

The delivered document has two clearly separated sections:

The document header (top of file, above Section A) must include:
- Post number and title
- Post URL (from cannademy-aeo-refresh-plan.md)
- Site name and draft date

Example:
Post 8 — Long-Term Cannabis Benefits
https://www.cannademy.com/long-term-cannabis-benefits/
AEO Blog Refresh — Cannademy.com | Draft April 2026

**SECTION A — REVIEW NOTES (Do Not Paste Into Page Builder)**

Include here, in this order:
1. Rank Math block (SEO Title, Meta Description, Focus Keyword)
2. Color key (see below)
3. Dead link flags with suggested replacements
4. Editor notes explaining structural decisions
5. Any questions or decisions needing Mitch's input
6. Image prompts (see Step 5)
7. Publishing checklist (from seo-aeo-standards.md)

**SECTION B — CONTENT BLOCK (Paste-Ready)**

Plain text only. No labels, annotations, color codes, or editor notes anywhere inside this block. The entire block from the first word of the title to the last word of the sign-off must be ready to copy directly into the page builder without any cleanup.

---

### Color Coding (Section A reference only — never inside Section B)

- BLACK = Cheri's existing content, kept or lightly polished
- BLUE = New AEO additions (answer-first paragraphs, FAQ block, new sections)
- GRAY ITALIC = Structural notes (Section A only)

---

### AEO Answer-First Paragraph — Required Format

Every H2 section must open with an AEO answer-first paragraph immediately after the heading.

Rules:
- 2-3 sentences maximum
- Opens with the answer — never "In this section..." or "There are many ways to..."
- Plain language — no clinical terms unless immediately defined
- Cheri's voice — see brand-voice.md for full voice rules

Example:

## Why Do Edibles Hit Differently Than Smoked Cannabis?

When you eat an edible, your liver converts THC into a stronger compound — which is why the effects hit harder, take longer to kick in, and last significantly longer than smoking. Most people are caught off guard the first time, and that's completely normal.

[Section content continues here...]

---

### Structural Rules

- Closing/wrap-up sentences belong AFTER the last point, not inside any individual section
- CTAs belong at the end of the post and in the "Ready to Go Deeper?" section — not scattered through body copy unless they exist in Cheri's original
- FAQ block belongs after all body content, before Related Posts
- Related Posts belong at the bottom
- Sign-off matches content type (see brand-voice.md Sign-Offs)
- No paragraph longer than 4 lines anywhere in the post
- Output format: Always deliver as .docx. Never deliver as .md. The .docx format is required for color coding in Section A to render correctly.
---

## Step 5 — Image Prompts for Gemini

Read the image prompt standards file before generating any images or Pinterest pins:
https://raw.githubusercontent.com/mmenigma/ClaudeAI/refs/heads/main/image-prompts.md
Generate all image prompts following the rules in that file. Place all prompts in Section A only — never in Section B.

## Step 6 — Pre-Delivery Self-Check

Read the complete draft top to bottom as a reader before delivering. Do not deliver until every item is confirmed.

Content
- Every H2 is written as a question
- Every H2 opens with a 2-3 sentence AEO answer-first paragraph in Cheri's voice
- No paragraph longer than 4 lines
- No redundant sentences between adjacent paragraphs
- No two H2 sections covering the same idea
- Closing/wrap-up statements are after the last point, not inside a section
- FAQ block present with minimum 4 questions (ideally 6)
- FAQ answers are self-contained and written as a real person would ask them
- Mango/myrcene tip included where fat absorption is discussed (edibles posts)
- Medical disclaimer included where health benefits are discussed

Links
- At least one Cannademy course link included
- At least one related post link included
- All internal links verified as live
- All Teachable-era URLs replaced or flagged in Section A
- No Google Drive links anywhere in the document

Voice
- No dry, textbook-style openings to technical sections
- No over-explained paragraphs (make the point, stop)
- Reads like Cheri — not a Wikipedia editor or AI assistant
- THCa to THC, CBDa to CBD language used correctly (never "activates")
- No Ardent product or brand mentions

Pricing — verify against brand-voice.md before every post
- Free Dosing Class: $0
- Dosing Calculator: $5
- Cannabis Dosing Mastery (DMC): $59 (NOT $39)
- Cannabis Cooking for Home Cooks (CCHC): $89 funnel / $149 full price
- Cannabis Gummies Course: $59
- DIY Cannabis Topicals & Skincare: TBD

Document layout
- Section A contains all notes, flags, color key, Rank Math block, and image prompts
- Section B is completely clean — zero annotations inside the content block
- Byline in content block: "By Cheri Sicard, Cannabis Author & Educator"
- "Updated [Month Year]" note present in content block
- FAQ schema reminder in Section A
- Publishing checklist included in Section A (from seo-aeo-standards.md)

---

## Known Errors — Never Repeat

See ERRORS.md for full details.

- Never link to Google Drive
- Never duplicate a sentence — note removals in Section A
- Never write 3 of 5 points covering the same idea — map H2s in Step 2
- Cannabis Dosing Mastery is $59 — earlier docs had this wrong at $39
- THCa to THC, CBDa to CBD — use precise conversion language always
- Decarboxylation converts THCa and CBDa — never describe it as "activating" cannabis
- Never mention Ardent — affiliate program has deteriorated, do not reference the brand

---

Document prepared for Cannademy.com | AEO Blog Refresh Workflow
Voice rules: brand-voice.md | SEO/AEO standards: seo-aeo-standards.md
Cannademy post plans: cannademy-aeo-refresh-plan.md | Error history: ERRORS.md
