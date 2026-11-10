---
type: meeting
title: >-
  Qalzy Founders Sync: Operations, Creator Demographics, Figma BFCM Page &
  Subscription Cohort Analysis
date: '2026-11-10'
---

# Qalzy Founders Sync: Operations, Creator Demographics, Figma BFCM Page & Subscription Cohort Analysis

**Date:** 2026-11-10  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  

---

## Summary
Founders operational sync between [[people/michael-michelis]] and [[people/kostas-koukoravas]] covering administrative and vendor account resolutions, creator audience demographic vetting, real-time Figma UI design iterations for the Black Friday sales funnel, copywriting for complex meal tracking, and an empirical analysis of 30-day subscription acquisition data.

---

## Key Discussion Points

### 1. Operations & Account Communications
- Addressed operational frustration regarding extensive email exchanges over an outstanding balance that could have been resolved instantly by direct phone communication. Emphasized prioritizing direct resolution over passive messaging.

### 2. Influencer Demographic Vetting
- Reviewed an influencer pitch featuring food plate presentations to enhance visual diversity.
- Audience demographic audit revealed 40% of the creator's followers were based in India and only 30% in the United States.
- Decided to pass on the partnership to protect marketing ROI, focusing strictly on creators with predominantly US-based audiences.
- Confirmed proceeding with an alternate US-based creator.

### 3. Black Friday Landing Page Design Iterations (Figma)
- Conducted live collaborative design in Figma on the Black Friday promotional header:
  - Addressed countdown timer placement and contrast.
  - Evaluated button styling for the "Black Friday" badge; removed excessive borders to prevent users from treating the badge as an inactive or confusing button.
  - Ensured the banner cleanly triggers an add-to-cart action or smoothly scrolls to the bundle section on mobile viewports.

### 4. "Track Complex Meals" Section & Copywriting
- Refined messaging for the landing page feature demonstrating multi-ingredient meal logging:
  - Simplified verbose copy (*"See how Qalzy tracks complex meals"*) into crisp, benefit-focused headlines: *"Multiple ingredients, no problem"* and *"Track step-by-step or track in one tap"*.
  - Agreed to display colorful UI breakdowns across varied global cuisines to provide strong social proof for home cooks and meal preppers.

### 5. 30-Day App Subscription Acquisition Breakdown
- [[people/kostas-koukoravas]] analyzed subscription creation data for the past 30 days (2026-10-11 to 2026-11-10):
  - **Total Subscriptions Created:** 241
  - **Scale Owners:** 166 (69%)
  - **Non-Scale Users:** 75 (31%)
- [[people/michael-michelis]] noted that `created_at` timestamps include users entering the initial 30-day free trial period.
- Identified the need to cross-reference `trial_end_date` to isolate paid active retention from active trial cohorts.

---

## Action Items & Next Steps
- **[[people/michael-michelis]]:** Implement approved Figma typography and button styles on the Shopify Black Friday staging theme; proceed with US-based creator collaboration.
- **[[people/kostas-koukoravas]]:** Query database to separate paid active subscriptions from ongoing 30-day free trials.
