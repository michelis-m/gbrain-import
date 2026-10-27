---
type: meeting
title: >-
  Qalzy Operations: Klaviyo Abandoned Cart Filter Overhaul, Purchase Velocity,
  and Landing Page UX
date: '2026-10-13'
---

# Qalzy Operations: Klaviyo Abandoned Cart Filter Overhaul, Purchase Velocity, and Landing Page UX

**Date:** 2026-10-13  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  
**Companies:** [[companies/qalzy]]  

---

## Summary
Kostas Koukoravas detailed crucial fixes to Klaviyo email flow triggers that previously suppressed abandoned cart emails for ~50% of high-intent shoppers, analyzed customer purchasing velocity patterns, and evaluated landing page UX patterns for the "How It Works" step-by-step section using Microsoft Clarity heatmap data.

---

## Key Discussion Points

### 1. Klaviyo Email Flow Logic & Filter Resolution
- **Flow Suppression Root Cause:** The previous Klaviyo configuration had two conflicting profile filters that excluded shoppers who browsed or added other products. Because high-intent shoppers routinely browsed accessories and add-on items, roughly 50% of visitors were being disqualified from entering any flow.
- **Filter Simplification:**
  - Excluded only users who actually completed checkout or placed an order.
  - Updated the add-to-cart condition from *"added to cart 0 times overall"* to *"added to cart 0 times in the last 7 days"*, allowing returning prospective buyers to re-enter flows.
  - Removed an erroneous filter that excluded users if they viewed a product again after starting the flow.
- **Discount Messaging & Visibility:**
  - Preserved a 15% discount incentive on the second follow-up email.
  - Updated subject lines (e.g., *"Still thinking about Qalzy? [left off with 10% off]"*) and revised preview text so discount incentives are clearly visible in the mobile inbox preview without requiring scrolling.
- **Customer Purchase Velocity Analysis:**
  - Data indicates that the majority of Qalzy sales are impulse purchases occurring within the first 15 minutes of site visits, dropping sharply between 15 and 60 minutes, with minimal volume in subsequent windows.
  - Agreed to maintain the first email trigger at 2 hours (avoiding automated suggestions to send at 1 hour, which risks discounting shoppers who would have purchased at full price).
- **Destination URL Strategy:** Cart abandonment links will direct users to the product display page (PDP) rather than the standalone cart page, because the main cart template lacks the accessory upsell modules present in the slideout drawer, protecting Average Order Value (AOV).

### 2. Landing Page UX: "How It Works" & Demo Media
- **Full Meal Demo Asset:** Reviewed a new animated demo demonstrating weighing and scanning an entire mixed meal. Discussed overlaying the mobile app interface to display recognized macros and nutrient breakdowns upon scan completion.
- **Scroll Locking vs. Flowing UX:** Considered implementing Apple-style sticky scroll locking for the 3-step *"How It Works"* section. Decided against scroll locks because artificial scroll resistance risks fatiguing mobile shoppers and reducing overall scroll depth.
- **Clarity Heatmap Interaction:** Microsoft Clarity mobile heatmaps show ~4% click-through on step images. Agreed to make the step images clickable to advance to the next step, while maintaining clear button outlines for readability.

---

## Action Items
- [ ] **Kostas Koukoravas:** Track deliverability, open rates, and attributed revenue following the Klaviyo flow filter adjustments.
- [ ] **Michael Michelis:** Overlay the mobile app nutrient/macro UI onto the mixed meal demo video asset.
- [ ] **Michael Michelis & Kostas Koukoravas:** Implement click-to-advance navigation on "How It Works" step images without sticky scroll locking.
