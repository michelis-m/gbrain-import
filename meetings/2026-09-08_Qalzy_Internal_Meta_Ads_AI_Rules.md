# Qalzy Internal Meta Ads AI Rules Engine & Scaling Sync

**Date:** 2026-09-08  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  
**Companies:** [[companies/qalzy]]

## Summary
Internal working session between [[people/kostas-koukoravas]] and [[people/michael-michelis]]. Kostas presented an AI-generated data analysis model and interactive rule engine (built in HTML/artifacts) trained on Qalzy's historical Meta ad metrics to automate scaling and ad cut-off decisions based on statistically verified thresholds.

## Key Discussion Points & Rule Architecture

### 1. Statistical Rule Engine Overview
- Built to eliminate emotional/subjective ad killing and replace manual guesswork with statistical gates aligned with Qalzy's gross margin, target CPA ($91 breakeven CPA target), and average order value ($199–$254).
- **Gate 1: Landing Page Integrity:** Evaluates landing page views relative to outbound clicks. If the ratio is below 80%, the traffic quality is compromised and the ad is flagged/killed.
- **Gate 2: Cost Per Add-to-Cart (ATC) as Primary Leading Indicator:**
  - Because Qalzy's purchasing cycle can take up to 2–3 weeks, purchases alone lag too significantly for fast day-to-day decisions.
  - Cost per ATC emerged as the strongest predictive metric of downstream ROAS.
  - **Kill Line:** Hard kill threshold set at **$64 cost per cart**.

### 2. Decision Tree & Threshold Gates
- **Under 0.5x Spend Threshold:** Let the ad run; insufficient data to draw conclusions.
- **At 1.0x Spend Threshold with 0 ATCs:** Immediate shutoff. Specific recommendation: Kill the "Founder Video" ad and static ads currently consuming budget without carts.
- **At 2.0x Spend Threshold:** Shut off if ATC efficiency is below target threshold, even if isolated sporadic purchases occurred.
- **At 3.0x Spend Threshold with 0 Purchases:** Shut off immediately regardless of soft metrics.
- **Low-Correlation Metrics to Ignore:** Statistical analysis indicated that CTR, CPM, video hold rate, and basic landing page views show low direct correlation to net revenue efficiency; decisions should strictly follow the ATC efficiency gates.

### 3. Scaling Strategy
- Immediate scaling recommended for self-made UGC ads that passed all integrity and ATC efficiency gates.
- Scaling budget adjustments should be calculated via spend response curves rather than blunt percentage increases.

## Action Items & Next Steps
- [ ] [[people/kostas-koukoravas]] to implement an automated rule check/cron job sending weekly ad audits to a dedicated Slack channel (`meta-related`).
- [ ] Pause the underperforming Founder video and static ads that breached the 1x threshold without ATCs.
- [ ] Scale winning self-made ad creatives according to the spend response curve recommendations.

## See Also
- [[concepts/meta-ads-scaling-and-auditing-principles]]
