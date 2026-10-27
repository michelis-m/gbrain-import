---
type: meeting
title: Intelistyle Standup & Qalzy Operations
date: '2026-10-19'
---

# Intelistyle Standup & Qalzy Operations

**Date:** 2026-10-19  
**Attendees:** [[people/john-karunungan]], [[people/michael-michelis]], [[people/kostas-koukoravas]]  
**Companies:** [[companies/intelistyle]], [[companies/qalzy]]  

---

## Summary
The session began with the daily Intelistyle operational standup with John Karunungan reviewing client image QA workflows. Following John's update, Michael Michelis and Kostas Koukoravas discussed Intelistyle client contract management (Decuba exceeding outfit quotas), CES 2027 pitch opportunities, Qalzy technical customer support escalations, CRO architecture for the ongoing Absolutely A/B test, US 3PL fulfillment transition planning, and Q4 seasonal creative strategy (Thanksgiving and Christmas angles).

---

## Key Discussion Points

### 1. Intelistyle Client Operations & Decuba Quota
- **Daily Operations:** [[people/john-karunungan]] reported completing image quality verification for Epicure and Guess on Friday, as well as Guess Shop the Look. Today's focus includes image quality checks for Epicure, Guess, and Decuba, followed by Decuba Shop the Look.
- **Decuba Quota Exhaustion:** Decuba has reached their contracted outfit limit.
- **Billing Strategy & Contract Terms:** Kostas and Michael evaluated whether to charge on a pay-as-you-go basis or offer a discounted package through year-end.
- **Operational Decision:** Rather than billing automatically without warning, Kostas recommended pausing processing immediately and sending a notification: *"You have now hit your quota. New outfits are not being processed. If you would like to continue, please let us know if you'd like to continue paying as you go at a price of X, or buy a package at Y."*

### 2. CES 2027 & Eureka Park Stage Pitch
- **Pitch Invitation:** Kostas noted that Qalzy received an invitation to apply/pitch on the Eureka Park stage at CES 2027, featuring a 5,000 grand prize winner.
- **Eligibility & Deadlines:** Michael noted previous research showing Eureka Park pitch deadlines had closed, but questioned whether the invitation opens a separate track or late-stage startup opportunity.
- **VIP Tours:** Michael highlighted that exhibitors can apply through the CES dashboard to be featured on curated VIP tours showcasing innovative hardware products.

### 3. Customer Support, Hardware & Connectivity
- **Wi-Fi Connectivity Issues:** Discussion around customer tickets where customers have dual-band 2.4 GHz / 5 GHz routers sharing the same SSID/band. The scale struggles to connect under certain combined configurations.
- **Firmware & Protocol Risk:** Kostas noted that modifying the BLE / Wi-Fi onboarding protocol between the scale and mobile app introduces high firmware risk that should not be touched right now.
- **Support Inquiries:** Other user queries involved nutritional accuracy for protein items and resting heart rate monitoring expectations.

### 4. Absolutely A/B Test Architecture & CRO
- **Redirect Latency & Bias:** Michael raised concerns that the ongoing Absolutely A/B test (evaluating the black scale variant) relies on URL redirects, which creates an artificial dropoff (~10% traffic discrepancy) and may inflate bounce rates.
- **Theme-Level Architecture:** Michael proposed converting the test setup from URL redirects to theme-level liquid/variable rendering so traffic split remains perfectly balanced without redirect delays.
- **Revenue Volatility:** Noted that while revenue/profit per visitor metrics are volatile (+32% swings on small sample sizes), ensuring tracking integrity is critical.

### 5. Supply Chain, Logistics & US Warehouse Transition
- **Customer Shipping Friction:** Customer complaints regarding USPS last-mile tracking delays highlighted the friction of shipping direct from China.
- **Portless vs. US Warehouse Buffer:** Discussion on allocating inventory between China (Portless) and US 3PL (ShipBots) ahead of peak season. Michael and Kostas emphasized avoiding stockouts during January (historically the highest-volume month driven by New Year resolutions and fitness demand).
- **Inventory Depletion:** Carrying cases and White scale SKUs are running low; need to manufacture and replenish in parallel.
- **Corporate & Tax Administration:** Kostas flagged a discrepancy in US IRS filing dates/periods to review.

### 6. Creative Strategy & Seasonal Q4 Content (Thanksgiving & Holidays)
- **High-Calorie Hook Creatives:** Visuals of recognizable American comfort foods (Mac & Cheese, Big Mac, KFC) consistently deliver stronger scroll-stopping thumbstop rates. Kostas is testing an oven-baked Mac & Cheese creative.
- **Holiday Timeline:** Halloween is deemed a lost cause due to 10–12 day lead times. The creative pipeline will pivot immediately to Thanksgiving.
- **Thanksgiving Content Angles:**
  - Classic holiday dessert calorie comparisons: Pumpkin Pie vs. Pecan Pie vs. Apple Pie (*"Which dessert has more calories?"*).
  - Thanksgiving plate comparison / smart swaps: 1,500 kcal traditional plate vs. 700 kcal plate (mashed potatoes, turkey, gravy portion control).
- **Creator Execution:** Producing recipe videos internally is excessively time-consuming; agreed to recruit food/cooking influencers to film recipe demonstrations.
- **Christmas Angle:** Frame holiday marketing around gifting urgency: *"Order now because shipping takes 15 days — the ultimate Christmas health gift."*

### 7. Customer Service Chatbot (Fin AI) & 9to5Mac Reviewer
- **Fin AI Performance:** Reviewed recent chatbot resolutions; noted instances where the bot properly clarified that scale hardware works without a mandatory app subscription.
- **9to5Mac Review Onboarding:** [[people/ben-lovejoy]] successfully paired his scale and confirmed the app receives weight/nutrition data after Michael explained the Basic plan does not require a paid subscription.

### 8. Personal & General Discussion
- **Personal Updates:** Kostas has a property viewing at 16:30 today and will have lighter availability next week. Michael's father is scheduled for a routine catheter ablation for cardiac arrhythmia (2–3 days in hospital, followed by 1 week rest); Liam had a fever over the weekend.
- **AI Ecosystem & API Economics:** Discussed AI platform token burn, high developer API pricing (e.g. Anthropic Claude boost/credit consumption), and the long-term industry necessity of lightweight open-source models running locally on standard 16GB hardware.

---

## Action Items & Commitments
- **[[people/michael-michelis]]:**
  - Confirmed 9to5Mac reviewer [[people/ben-lovejoy]] is onboarded on the Basic plan and receiving live scale data.
  - Re-architect Absolutely A/B test at theme level to remove redirect latency.
  - Outreach to food/cooking creators for Thanksgiving recipe and calorie-comparison video assets.
- **[[people/kostas-koukoravas]]:**
  - Contact Decuba regarding exhausted quota, pausing new outfit processing and offering pay-as-you-go (/outfit) vs. bulk package terms.
  - Coordinate receiving timelines with ShipBots and Portless for US warehouse inventory transition.
  - Investigate the US IRS corporate filing date discrepancy.

---

## Key Decisions
- **Decuba Account Management:** Immediately notify Decuba that their quota is exhausted and suspend processing pending contract extension or overage agreement.
- **A/B Testing Standard:** Migrate Shopify split tests from URL redirects to theme-level variables to preserve UX speed and tracking accuracy.
- **Holiday Ad Focus:** Skip Halloween; focus immediate creative production on Thanksgiving food comparisons and Christmas gifting with explicit 15-day delivery messaging.
