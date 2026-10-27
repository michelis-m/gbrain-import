---
type: meeting
title: >-
  Qalzy Klaviyo Operations: Abandoned Cart Funnel Diagnosis & Deliverability
  Fixes
date: '2026-10-12'
---

# Qalzy Klaviyo Operations: Abandoned Cart Funnel Diagnosis & Deliverability Fixes

**Date:** 2026-10-12  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  
**Companies:** [[companies/qalzy]], [[companies/klaviyo]]  

---

## Summary
Operational troubleshooting session between Kostas Koukoravas and Michael Michelis diagnosing the underperformance of Qalzy's Klaviyo abandoned cart email flow. The team identified a critical link redirection flaw, sender name inconsistencies, and template deliverability issues causing low conversion rates.

---

## Key Discussion Points

### 1. Link Redirection Flaw in Abandoned Cart Flow
- **Root Cause Identified:** Clicks in the abandoned cart emails were redirecting users to the general **product landing page (PDP)** instead of sending them directly to their **saved cart / checkout** with pre-populated products and active discount codes.
- **Fix:** Update all CTA buttons to route directly to checkout/cart.

### 2. Sender Identity & Subject Line Alignment
- **Sender Inconsistency:** Email 1 in the flow displayed "Kostas" as the sender, while Email 2 displayed "Dom", despite originating from the exact same domain/inbox.
- **Subject Line Revision:** The current subject line mimicked a transactional checkout receipt rather than an engaging abandoned cart hook.
- **Copy Recommendation:** Update subject line to the industry-standard high-performing format: *"You forgot something in your cart"* with clear 10%–15% promotional incentives placed prominently above the fold.

### 3. Deliverability & Image-Heavy Templates
- **Image Blocking & Spam Risk:** Current email templates consist of 100% large sliced images. Mail clients like Outlook block images by default, and Gmail may clip large image payloads or divert them into the Promotions/Spam tab.
- **Solution:** Rebuild abandoned cart templates into a hybrid format combining HTML live text with supporting visual images to maximize inbox deliverability and readability.
- **Cross-Funnel Consistency:** Align abandoned cart email architecture with the higher-converting abandoned checkout flow.

---

## Action Items
- [ ] **Kostas Koukoravas & Michael Michelis:** Update Klaviyo abandoned cart CTA destinations to redirect directly to cart/checkout.
- [ ] **Kostas Koukoravas & Michael Michelis:** Standardize sender name across flow emails and test revised subject lines (*"You forgot something in your cart"*).
- [ ] **Kostas Koukoravas:** Rebuild email templates into hybrid text/HTML blocks to resolve client image blocking.
