# seo-aeo-standards.md — SEO/AEO Content Standards
*Applies to ALL content on Cannademy.com and cannabischeri.com. Read this alongside brand-voice.md before writing any post.*

---

## What This Document Covers

These are the baseline SEO and Answer Engine Optimization (AEO) standards that every blog post on both sites must meet. AEO is the practice of writing content so that AI engines (ChatGPT, Perplexity, Google AI Overviews, Claude) can find, understand, and cite it accurately. Posts that follow these standards rank better in traditional search AND get cited more frequently by AI platforms.

---

## Standard 1 — Byline

Every published post uses this exact byline:

> **By Cheri Sicard, Cannabis Author & Educator**

Never use "By Cannademy Staff Writer" or any generic attribution. This applies to both sites.

---

## Standard 2 — Date Freshness

- Every post must display a visible **"Updated [Month Year]"** note at the top
- Update the WordPress **Last Modified** date when publishing changes
- Add or update `dateModified` in Article schema JSON-LD (via Rank Math per-post or Code Snippets plugin)

---

## Standard 3 — H2 Question Format

H2 headings perform significantly better for AEO when written as questions rather than statements. AI engines match question-format headings directly to user queries.

**Rules:**
- Rewrite declarative H2s as questions wherever natural: "Dosing Homemade Edibles" → "How Do You Dose Homemade Edibles?"
- Check for overlap between adjacent H2s — if two headings cover the same idea, merge them
- For list-format posts, 5 points is the SEO sweet spot; always use odd numbers
- Each section must build logically on the previous one

**Example:**
- ❌ "Effects of Edibles"
- ✅ "What Effects Do Cannabis Edibles Produce?"

---

## Standard 4 — AEO Answer-First Paragraph

Every H2 section must open with an AEO answer-first paragraph immediately after the heading. This is the content AI engines scrape and cite.

**Format:**
2–3 sentences that directly answer the implied question in the H2. Opens with the answer — never with a setup phrase like "In this section..." or "There are many ways to..."

**Voice:**
Plain language. Cheri's warmth. No clinical terms unless immediately defined in plain language. See brand-voice.md for full voice rules.

**Structure:**
```
[H2 Heading — written as a question]

Direct answer sentence in plain language. One more sentence 
expanding the key point. Optional third sentence only if it 
adds new information — not a restatement.

[Cheri's existing or new content continues below]
```

**Example:**
```
## Why Do Edibles Hit Differently Than Smoked Cannabis?

When you eat an edible, your liver converts THC into a stronger 
compound — which is why the effects hit harder, take longer to 
kick in, and last significantly longer than smoking. Most people 
are caught off guard the first time, and that's completely normal.

[Remaining section content follows...]
```

---

## Standard 5 — Paragraph Length

No paragraph in the body of a post should exceed 4 lines. If a paragraph runs longer, break it. Long paragraphs suppress AEO extraction and hurt readability on mobile.

---

## Standard 6 — FAQ Block

Every post must include a FAQ block. Place it after all body content and before Related Posts.

**Format:**
```
## Frequently Asked Questions

**Q: [Question written the way someone would actually ask it]**
[2–4 sentence direct answer. Plain language. Cheri's voice.]

**Q: [Next question]**
[Answer]
```

**Rules:**
- Minimum 4 questions per post; 6 is ideal
- Questions must match real search queries — write them as a person would type or speak them
- Each answer must be self-contained — it should make sense if read without any surrounding content
- Never answer a question with "it depends" without immediately explaining what it depends on
- FAQ schema must be enabled (see Publishing Checklist)

---

## Standard 7 — Internal Linking

Every post must include:
- At least **one link to a Cannademy course** relevant to the post topic
- At least **one link to a related post** on either Cannademy.com or cannabischeri.com

Place links naturally within body content. Do not stack all links at the bottom.

---

## Standard 8 — FAQ Schema

FAQ schema tells search engines and AI platforms that your FAQ block contains structured Q&A content, dramatically increasing the chance of citation.

**How to enable:**
- Turn on FAQ schema per-post in Rank Math settings
- Verify the FAQ block is formatted correctly (Q: label followed by answer paragraph)

---

## Publishing Checklist

Run through this for every post before publishing.

**Before publishing:**
- [ ] Byline updated to "By Cheri Sicard, Cannabis Author & Educator"
- [ ] "Updated [Month Year]" note visible at top of post
- [ ] All H2s reviewed for question format
- [ ] Every H2 has an AEO answer-first paragraph (2–3 sentences)
- [ ] No paragraph longer than 4 lines
- [ ] FAQ block present (minimum 4 questions, ideally 6)
- [ ] At least one course link included
- [ ] At least one related post link included
- [ ] All internal links verified as live
- [ ] All Teachable-era URLs replaced or flagged
- [ ] No Google Drive links anywhere
- [ ] Rank Math: SEO title set (55–60 characters)
- [ ] Rank Math: Meta description set (150–155 characters, question or benefit focused)
- [ ] Rank Math: Focus keyword set
- [ ] FAQ schema enabled in Rank Math
- [ ] Article schema dateModified updated
- [ ] Featured image uploaded with descriptive alt text

**After publishing:**
- [ ] Request re-index via Google Search Console

---

## What This Document Does NOT Cover

- **Voice and tone rules** → brand-voice.md
- **Cannademy-specific post refresh plans** → cannademy-aeo-refresh-plan.md
- **Blog post production workflow steps** → BLOG-WORKFLOW.md
- **Product pricing** → brand-voice.md
- **Error history** → ERRORS.md

---

*Source of truth for SEO/AEO standards across Cannademy.com and cannabischeri.com.*
*Update this file when standards change — never duplicate these rules in individual workflow files.*
