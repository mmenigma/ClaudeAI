# PROGRESS.md — Current Status & Active Tasks
*Updated: April 15, 2026*

---

## Active Project: 90-Day Marketing Plan
**Goal:** Generate consistent premium course sales (CCHC + DMC)
**Plan document:** cannademy-90-day-marketing-plan.md
**Start date:** March 2026

---

## Week 1 Checklist

- [x] Fix dosing calculator lead magnet page — replaced "coming soon" waitlist with live DMC offer *(done March 2026)* ✅
- [x] Dosing calculator page copy fixed ✅
- [x] 4-email reactivation campaign drafted — pending Cheri proof and email verification ✅
- [x] Full .md file kit created and uploaded to Cowork project folder ✅
- [x] 90-day marketing plan finalized (updated for HeyGen + platform realities) ✅
- [ ] Email 9 DMC waitlist subscribers — notify course is live, link to DMC sales page
- [x] Run email verification on ~6,378 raw contacts (expect ~10% dropoff → ~5,740 deliverable)
- [x] Segment verified list into: calculator owners (~1,370) vs freebie only (~4,370)
- [x] Draft 3-email reactivation campaign — IN PROGRESS (see CAMPAIGNS.md)
- [x] Load reactivation emails into CCM and schedule
- [ ] Upgrade recipe CTA blocks on top 20 cannabischeri.com recipes
- [ ] Orient in CCM Social Planner — schedule first post batch
- [ ] Write first 2 HeyGen YouTube video scripts

---

## Email Campaign Status
See CAMPAIGNS.md for full details.

**Reactivation Campaign (4 emails total):**
- Email 1 (both segments): DRAFTED — needs Cheri proof
- Email 2 (both segments): DRAFTED — needs Cheri proof
- Email 3A (calc owners → DMC/CCHC pitch): NOT STARTED
- Email 3B (freebie only → $5 calc pitch): NOT STARTED
- Status: Waiting on email verification before sending

---

## Sales Status (as of March 2026)
- Premium course sales in past 60 days: **0**
- CCHC funnel: ~20 people total, ~8 currently active
- Free course funnel: Live and capturing leads

---

## Platform Status
| Platform | Status | Priority |
|----------|--------|----------|
| Email list | Reactivation campaign in progress | 🔴 #1 |
| YouTube (30k subs) | Inactive — no recent posts | 🔴 #1 ongoing |
| Facebook | Active | 🟠 Month 1 |
| Pinterest | Active | 🟠 Month 1 |
| Instagram | Dormant | 🟡 Month 2 |
| TikTok | Brand new | 🟡 Month 2-3 |

---

## Completed Work (Pre-Marketing Plan)

### WordPress / WooCommerce (cannademy.com)
- ✅ Add-to-cart → direct checkout URL implemented
- ✅ Cart widget added to checkout page
- ✅ CSS coupon form display fix
- ✅ Cart-clearing bug fixed (caused by quicklink prefetch snippet)
- ✅ Staging login fix (wp-config.php cookie/URL constants)
- ✅ Snippet audit: 7 deleted, 4 cleaned, 2 flagged for later testing
- ✅ WP Rocket conflicts identified — slated for removal
- ✅ App redirect plugin modified (privacy policy exception added)

### Student Migration
- ✅ Existing students remain on Teachable
- ✅ New students onboard to WordPress/WooCommerce/Thrive Apprentice
- ✅ Soft launch completed

### Email List Migration
- ✅ Merged Teachable + Kit.com lists (~9,900+ raw contacts)
- ✅ Deduplicated, consolidated tags, parsed names, added date-joined fields
- ✅ Migrated to ContentCreator.com (CCM)

### 7-Agent Marketing System
- ✅ System designed (Research, SEO, Sales Page, Email Funnel, Social Media, Critic, CRO)
- ✅ cannademy-context.md foundation file created
- ⬜ Individual agent files — not yet built

---

## Next Up (Days 8-30)
- HeyGen video workflow launch (2 videos/week)
- cannabischeri.com recipe CTA upgrade
- CCHC sales page CRO optimization
- CCHC email funnel audit (open/click rates in CCM)

---

## AEO Blog Refresh — Active Project
*Started: April 7, 2026*
**Reference doc:** traffic building/cannademy-aeo-refresh-plan.md.pdf
**Output folder:** traffic building/

### Workflow (established April 7, 2026)
For each post:
1. Claude reads the AEO plan section for that post (from the PDF)
2. Claude fetches the live post via Chrome browser tab using **innerHTML** (not innerText) to capture Cheri's original hyperlinks
3. Claude writes a revised Word doc with:
   - **Blue text** = new answer-first lead paragraphs (AEO additions)
   - **Black text** = Cheri's existing content, kept or lightly polished — **with all original links preserved as clickable hyperlinks**
   - **Gray italic** = editor notes explaining trims
4. Mitch pastes revisions into WordPress, applies sitewide fixes (byline, date, schema)

**IMPORTANT:** Always scrape with innerHTML and parse anchor tags so Cheri's links are preserved in the Word doc. Using innerText strips all links (learned from Post 1 — Mitch had to re-add them manually).

### Key AEO principle
Each H2 gets a 2-3 sentence direct answer prepended ABOVE Cheri's existing content. This is what AI engines scrape. Existing content stays — redundant openers are trimmed.

### Sitewide fixes (apply to every post)
- Byline: "By Cheri Sicard, Cannabis Author & Educator"
- Update "Last Updated" date on publish
- Add FAQ schema (JSON-LD) via Code Snippets or Rank Math
- Add Article schema with dateModified
- Every post links to at least one course + one related post

### Post Status
| # | Post | Status | Output file |
|---|------|--------|-------------|
| 1 | What Are Cannabis Edibles? | ✅ Done | post1-what-are-edibles-revised.docx |
| 2 | Dosing Homemade Edibles | ✅ Done | post2-dosing-homemade-edibles-revised.docx |
| 3 | How to Make Edibles Work Better | ✅ Done | post3-how-to-make-edibles-work-better-revised.docx |
| 4 | Edibles Tolerance | ✅ Done | post4-edibles-tolerance-revised.docx |
| 5 | How NOT to Waste Money Making Edibles | ✅ Done | post5-waste-money-making-edibles-revised.docx |
| 6 | Edibles Dosage Calculator | ✅ Done | post6-edibles-dosage-calculator-revised.docx |
| 7 | DIY Cannabis Cookbook | ✅ Done | post7-diy-cannabis-cookbook-revised.docx |
| 8 | Long Term Cannabis Benefits | ✅ Done | post8-long-term-cannabis-benefits-revised.docx |
| 9 | Who Can/Cannot Benefit from Topical Cannabis | ✅ Done | post9-topicals-revised.docx |
| 9 | Who Can/Cannot Benefit from Topical Cannabis | | ✅ Done | — |
| 10 | Online Cannabis Education vs. Cannabis Universities | ✅ Done | post10-complete.docx |
| 11 | Cannabis Topicals Won't Get You High — And Other Myths Worth Busting | ✅ Done |           Post-11-Cannabis-Topicals-Myth-Busting-Refresh.docx |
| 12–15 | Tier 3 posts | ✅ Done | Do last | — |
