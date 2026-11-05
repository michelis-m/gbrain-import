---
type: meeting
title: >-
  Qalzy Founders Sync: CES 2027 Booth Specs, Print Quotes & Black Friday
  Lifetime Backend Architecture
date: '2026-11-05'
---

# Qalzy Founders Sync: CES 2027 Booth Specs, Print Quotes & Black Friday Lifetime Backend Architecture

**Date:** 2026-11-05  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  

---

## Summary
Strategic alignment between [[people/michael-michelis]] and [[people/kostas-koukoravas]] evaluating CES 2027 Eureka Park booth specifications and electrical requirements, reviewing print quotes for bilingual event collateral, designing a frictionless backend webhook architecture for the Black Friday Lifetime Subscription promotion, and reviewing dual US/UK tax structuring advisory needs.

---

## Key Discussion Points

### 1. CES 2027 Eureka Park Booth Logistics
- **Booth Structure & Wall Panels:**
  - Reviewed CTA booth documentation and floor plan guidelines.
  - Uncertainty regarding default side partition wall coloring (whether standard walls are white panels with black frames or solid white). Custom printed graphic panel upgrades from official contractors are prohibitively expensive.
  - Michael sent an inquiry to CTA Exhibitor Support (`exhibitorsupport@cta.tech`) requesting written confirmation of wall panel specs and whether external Wi-Fi routers can be deployed inside the booth.
  - Flagged that electrical/power drops are expensive optional add-ons that must be planned carefully.
- **Print Collateral Quotes (Athens):**
  - Michael requested quotes from local Greek commercial printers for 4-page US Letter bi-fold product brochures to distribute at CES.
  - Received quote from **Pallis Printing** (`typography.pallis@gmail.com`):
    - 170g velvet/matt: **205€ + VAT**
    - 250g velvet/matt: **225€ + VAT**
    - Turnaround time: 4–6 working days (digital printing).

### 2. Black Friday Lifetime Subscription: Backend Webhook Architecture
- Evaluated implementation mechanisms for the Black Friday / Cyber Monday "Free Lifetime Subscription" promotion without creating customer friction or violating mobile app store guidelines.
- **App Store Constraint:** Apple previously rejected in-app promo code redemption fields, and maintaining coupon UX in-app introduces unnecessary rejection risks.
- **Backend Architecture Solution:**
  - Bypasses promo codes completely via automated backend mapping.
  - When an order is placed on Shopify during the BFCM promotion window, an automated webhook captures the order email and writes it to a designated entitlement collection in the database.
  - When the customer receives the physical scale, downloads the Qalzy mobile app, and signs up / connects their device using that same email, the backend instantly provisions Lifetime Premium access.
  - Eliminates support tickets, prevents leakages, and complies fully with app store guidelines.

### 3. Corporate Structuring & Dual US/UK Tax Advisory
- Kostas followed up on inquiries with international tax advisors regarding the proposed US C-Corp subsidiary vs LLC structure.
- Several US-based CPAs contacted only advise on US domestic tax rules; Qalzy specifically requires dual-qualified advisors who understand UK HMRC treatment of US LLCs (to eliminate the severe 70% hybrid mismatch double-tax trap). Kostas is continuing outreach to specialized cross-border advisory firms.

---

## Action Items & Next Steps
- **[[people/michael-michelis]]:** Await CTA Exhibitor Support response regarding booth wall panel frames and router policies.
- **[[people/michael-michelis]]:** Finalize brochure print order with Pallis Printing (250g weight preferred for trade show durability).
- **[[people/kostas-koukoravas]]:** Architect the Shopify order webhook and database mapping to auto-grant Lifetime Premium access for BFCM email registrations.
- **[[people/kostas-koukoravas]]:** Continue screening dual UK/US corporate tax advisors for C-Corp subsidiary formation.
