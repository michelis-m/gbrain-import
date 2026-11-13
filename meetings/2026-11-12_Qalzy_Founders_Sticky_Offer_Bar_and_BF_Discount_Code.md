---
type: meeting
title: >-
  Qalzy Founders Sync: Sticky Header Offer Bar Behavior & BF Discount Code
  Testing
date: '2026-11-12'
---

# Qalzy Founders Sync: Sticky Header Offer Bar Behavior & BF Discount Code Testing

**Date:** 2026-11-12  
**Attendees:** [[people/kostas-koukoravas]], [[people/michael-michelis]]  

---

## Summary
Brief technical sync between [[people/michael-michelis]] and [[people/kostas-koukoravas]] to review Black Friday storefront promotional elements, resolving mobile sticky header behavior and troubleshooting an incognito session cookie bug affecting discount code application.

---

## Key Discussion Points

### 1. Sticky Header & Promotional Banner Behavior
- Discussed mobile UX on whether the Black Friday promotional offer bar should remain sticky on scroll alongside the navigation header.
- [[people/kostas-koukoravas]] confirmed the intended design: the main navigation header stays sticky, but the promotional offer bar scrolls away to prevent covering half the mobile viewport screen.
- [[people/michael-michelis]] agreed that keeping the offer bar persistent on mobile would take up excessive screen real estate.

### 2. Discount Code Checkout Glitch (BF20D vs. BF10)
- [[people/michael-michelis]] observed an anomaly during testing where entering discount code `BF20D` was incorrectly applying `BF10` at checkout.
- [[people/kostas-koukoravas]] noted that `BF20D` functioned properly on his end and diagnosed the issue as residual browser session cookies persisting across shared incognito windows in Chrome.
- After fully closing all incognito windows and opening a clean session, the issue resolved and `BF20D` applied properly.

### 3. Launching 50/50 Split Test
- With the checkout discount code validated, [[people/michael-michelis]] confirmed proceeding to push the promotional program live.
- Agreed to execute a 50/50 offer test structure.

---

## Action Items & Next Steps
- **[[people/michael-michelis]]:** Push the Black Friday promotional offer live with the 50/50 test configuration.
- **[[people/kostas-koukoravas]]:** Monitor incoming checkout events and conversion tracking across variants.
