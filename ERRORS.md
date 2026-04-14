# ERRORS.md — Mistakes Log
*What went wrong, why, and how it was fixed. Do not repeat these mistakes.*

---

## Content / Copy Errors

**[March 2026] Incorrect decarboxylation explanation**
- WRONG: "Skip it and your edibles will be weak or completely ineffective. Overdo it and you lose potency."
- CORRECT (Cheri's language): "Decarboxylation — or decarbing — is the process of transforming the THCa and CBDa in your cannabis into THC and CBD before you cook with it."
- Rule: Always use precise cannabis chemistry language. THCa → THC, CBDa → CBD.

**[March 2026] Wrong explanation for uneven brownie dosing**
- WRONG: Described the problem as batch-to-batch variation in potency.
- CORRECT: The primary cause of uneven dosing WITHIN a single batch is:
  1. Cannabis infusion not stirred thoroughly into batter → hot spots
  2. Edge brownies bake at slightly higher temp → more THCa converts → stronger
  3. Person doesn't know their personal tolerance (biggest factor)
- Rule: Dosing problems within a single batch = technique issues, not calculation issues.

**[March 2026] One video script does not work for all 3 platforms**
- WRONG: Assumed YouTube script could be repurposed for TikTok and Instagram Reels.
- CORRECT: Each platform needs its own script.
  - YouTube: 5-8 min educational, structured, 600-900 words
  - TikTok/Reels: 60-90 sec, entertainment-first, 100-150 words, 2-second hook required
- Rule: Always write separate scripts per platform format.

**[March 2026] Dosing calculator lead magnet had dead-end "coming soon" copy**
- The page was collecting waitlist emails for the DMC — which was already live.
- Fix: Replaced with direct CTA to live DMC sales page.
- Rule: Always verify product status before writing CTAs. Never assume "coming soon" is accurate.

**[April 2026]
- Cannabis Dosing Mastery in some docs is priced at $39, this is an error, the price for this course is $59.

---

## Technical Errors

**[Pre-2026] Staging site login loop**
- Cause: www vs non-www URL mismatch in WordPress config + missing cookie domain constants
- Fix: Added WP_HOME, WP_SITEURL, and COOKIE_DOMAIN (set to empty string) to wp-config.php
- Also disabled WP_CRON on staging (no server cron configured)

**[Pre-2026] Cart-clearing bug on cannademy.com**
- Cause: Quicklink prefetch snippet was pre-fetching "remove item from cart" URLs
- Fix: Removed the quicklink prefetch snippet entirely
- Rule: Never add link prefetch scripts to WooCommerce sites without testing cart behavior first.

**[Pre-2026] Teachable admin redirect issue**
- Cause: Cached custom domain configuration
- Fix: Cleared cache and reconfigured domain settings

---

## Strategic Errors (Assumptions That Were Wrong)

**[March 2026] Assumed 5,500 untouched subscribers — actual count is 6,378**
- After proper segmentation: 1,525 calc owners + 4,853 freebie only = 6,378 total
- Always verify list sizes before writing revenue projections.

**[March 2026] Assumed TikTok/IG were established platforms**
- Reality: TikTok is brand new. Instagram dormant 1+ year, no Reels history.
- These are Month 2-3 priorities, not Week 1.

**[March 2026] Assumed 20% of untouched list were pure freebie subscribers**
- Reality: ~20% have purchased the $5 app — they are warm buyers, not cold leads.
- Always segment by purchase history before writing email strategy.
