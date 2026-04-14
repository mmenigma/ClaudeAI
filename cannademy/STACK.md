# STACK.md — Technical Environment
*Cannademy.com and cannabischeri.com technical details*

---

## cannademy.com

| Component | Details |
|-----------|---------|
| Platform | WordPress |
| E-commerce | WooCommerce |
| Course delivery | Thrive Apprentice |
| SEO plugin | RankMath |
| Hosting | SiteGround |
| Staging URL | staging2.cannademy.com |
| Old platform | Teachable (existing students remain there) |

### Known Plugin Notes
- **WP Rocket:** Has conflicts — slated for removal, replace with SiteGround Speed Optimizer
- **Quicklink prefetch:** REMOVED — was causing cart-clearing bug by pre-fetching remove-item URLs
- **App redirect plugin:** Modified to allow privacy policy page — all other non-admin visitors redirected to app.cannademy.com/download-app/

### Snippet Audit (completed pre-March 2026)
- 7 snippets deleted (outdated/broken/redundant)
- 4 snippets cleaned and kept
- 2 snippets flagged for later testing (jQuery migrate + Thrive Leads fix)

### wp-config.php Notes (staging)
Added to fix login loop:
```php
define('WP_HOME', 'https://staging2.cannademy.com');
define('WP_SITEURL', 'https://staging2.cannademy.com');
define('COOKIE_DOMAIN', '');
define('DISABLE_WP_CRON', true);
```

---

## cannabischeri.com

| Component | Details |
|-----------|---------|
| Platform | WordPress |
| Traffic | ~6,000 active users/month |
| SEO | RankMath |
| Hotlinking protection | Configured |

### Content Notes
- Every recipe page has dosing calculator lead magnet CTA in "Notes" section
- Top 20 recipes need upgraded CTA blocks (planned Week 1)
- Natural feeder site to Cannademy — 4x the traffic of cannademy.com

---

## ContentCreator.com (CCM)

| Feature | Status |
|---------|--------|
| Email marketing | Active |
| Social media scheduling | Active — all 5 platforms connected |
| Social Planner | Configured — Instagram, Facebook, YouTube, TikTok, Pinterest |
| Workflow automations | Active — CCHC funnel running |
| Contact segments | Configured |

**Social Planner workflow:**
1. Claude generates post batch
2. Mitch reviews and loads into Post Builder
3. Select platforms, set schedule
4. CCM publishes automatically

---

## HeyGen
- Cheri's AI avatar: **APPROVED** (Cheri reviewed and approved March 2026)
- Best use: YouTube videos (educational, under 5 min)
- Not recommended for TikTok/Reels (authenticity more important there)
- Script length for HeyGen: 300-400 words for a 2-3 minute video

---

## Mitch's Hardware
- MacBook Air
- Windows 11 PC (AMD Ryzen)
- Preference: GUI interfaces over command-line tools
