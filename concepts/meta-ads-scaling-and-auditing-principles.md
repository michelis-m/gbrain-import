---
type: concept
title: "Meta Ads Scaling, Auditing, and Algorithmic Principles"
aliases:
  - Meta Ads Principles
  - Meta Ad Optimization Rules
  - Never Turn Off An Ad
---

# Meta Ads Scaling, Auditing, and Algorithmic Principles

A strategic framework on how Meta's ad auction and machine learning algorithms operate, why manual ad-killing harms accounts, and how to properly audit and scale media buying.

Relevant entities: [[companies/qalzy]], [[people/michael-michelis]].

---

## 1. The "Never Turn Off High-Volume Ads" Rule

### Objective Alignment: Highest Volume vs. Cost Caps
- **The Core Conflict:** Over 95% of Meta advertisers optimize campaigns for **Highest Volume** (maximizing conversion volume across the campaign). However, media buyers often manually pause ads based on arbitrary in-platform CPA/ROAS targets that exist only in their heads.
- **Estimated Action Rate (EAR):** Meta optimizes across billions of data points using Estimated Action Rate (Estimated CTR × Estimated CVR). The ad receiving the most spend is the ad Meta has identified as capable of maintaining volume and conversion density.
- **Spend as the Leading Indicator:** Under Highest Volume, the top-spending ad is your true "winner." Sorting and evaluating by in-platform ROAS prioritizes low-spend, low-volume harvesters over high-volume customer acquisition engines.

### The "Hamster Wheel of Decline"
When media buyers manually kill high-spend volume drivers because of in-platform CPA:
1. **Budget Reallocation:** Meta shifts spend down into lower-funnel retargeting ads, catalog/DPA ads, or static promotional offers.
2. **First-Time Impression Ratio (FTIR) Collapses:** Top-of-funnel reach drops sharply, and ad frequency spikes.
3. **Account-Wide Decay:** Because net-new customer acquisition is starved, blended business revenue immediately plummets.
4. **Panic Cycle:** The buyer restarts the paused ads or cuts even more ads, locking the account into constant performance degradation.

### In-Ad ROAS vs. Incremental Business Growth
- As confirmed by Meta data science leads: **The ads inside an ad account with the highest ROAS are usually the least incremental.**
- High-ROAS ads (e.g., catalog ads, coupon statics) often sit near the bottom of the funnel capturing conversions that top-of-funnel ads (e.g., Reels, brand hooks) generated.
- Top-of-funnel ads often show lower in-platform ROAS (e.g., 0.8x) while driving high blended store revenue (e.g., 3.0x blended ROAS).
- Meta's 7-day click / 1-day view attribution window cannot track delayed purchases outside the window or cross-SKU attribution accurately.

### The Only Two Legitimate Reasons to Pause an Ad
1. The featured SKU or product is out of stock.
2. A temporary promo or seasonal offer has ended (which should ideally be housed in a separate promotional campaign).

---

## 2. Demystifying the "Learning Phase"

### Ads are Always Learning
- The belief that an ad set must remain rigidly "out of learning" to succeed is flawed. Target audiences and creatives naturally fatigue over time; the algorithm is in continuous learning mode.
- The 50 optimization events per week threshold is an optimization benchmark, not a hard barrier. Accounts routinely stabilize and profit below 50 conversions.
- Fear of triggering the learning phase paralyzes creative testing. The constant injection of new creative is the primary driver of Meta growth.

### Learning Phase Triggers
- **Campaign Level:** Significant budget shifts (>20%), bid cap / target cost adjustments, bidding strategy shifts.
- **Ad Set Level:** Targeting changes, placement edits, optimization goal changes, pausing for >7 days.
- **Ad Level:** Any edits to creative, copy, headline, or destination URL (ad name edits do NOT reset learning).

### The Real Problem: "Learning Limited" & Account Fragmentation
- **Learning Limited** occurs when an ad set lacks sufficient budget density to optimize properly.
- This is overwhelmingly caused by **Account Fragmentation**: spreading budget too thin across multiple campaigns, ad sets, and individual ads.
- **Fix:** Consolidate account architecture into fewer campaigns/ad sets, test 3–6 active creatives per ad set (or up to 10 in Dynamic Creative Testing), and maintain at least $50+/day per test ad set.

---

## 3. Account Audit & Diagnostic Framework

When auditing a Meta ad account:

1. **Verify Bidding Alignment:**
   - If strict CPA limits are mandatory, use **Cost Caps (Cost Per Result Goal)**. Do not enforce strict CPA limits by manually cutting ads in Highest Volume campaigns.
2. **Audit Structure & Consolidation:**
   - Check campaign/ad set count against total budget. Consolidate to eliminate *Learning Limited* states.
3. **Inspect Top Spenders:**
   - Sort creatives by spend (descending). Verify whether top spenders were recently killed, causing blended performance drops.
4. **Evaluate "Soft" Funnel Health Metrics:**
   - Track **First-Time Impression Ratio (FTIR)**, account frequency, and outbound CTR/CPC alongside blended MER (Total Store Revenue ÷ Total Ad Spend).

---

## See Also
- [[companies/qalzy]]
- [[meetings/2026-09-08_Qalzy_Internal_Meta_Ads_AI_Rules]]
