---
type: meeting
title: >-
  Qalzy Morning Sync: Headline A/B Test Results, App Bug Investigation & US
  Entity Structuring Friction
date: '2026-11-06'
---

# Qalzy Morning Sync: Headline A/B Test Results, App Bug Investigation & US Entity Structuring Friction

**Date:** 2026-11-06  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  

---

## Summary
Morning sync between [[people/michael-michelis]] and [[people/kostas-koukoravas]] covering iOS app support investigation into customer-reported keyboard and event capture failures, ad creative sales performance across Meta (Oatmeal ad holding #1 spot), detailed breakdown of the headline Absolutely A/B test (tied conversion rates between "World's First AI Scale" and "World's Most Accurate AI Calorie Counter"), rollout plan for the subscription pricing A/B test, severe operational/customs friction identified with US corporate structuring under Doola, and review of upcoming Black Friday page assets.

---

## Key Discussion Points

### 1. App Support & Event Logging Troubleshooting
- [[people/kostas-koukoravas]] investigated a customer bug report claiming capture events and diary entries were failing and the virtual keyboard failed to open on iPad.
- Found the user account exists but contains zero capture events; suspecting user may be logged into an alternative account or running an outdated iOS/iPadOS version with Flutter framework mismatches.
- Discussed potentially bumping the minimum supported iOS version to prevent legacy device rendering bugs.

### 2. Ad Creative Performance & Organic Social Sales
- Reviewed recent Meta ad attribution and sales:
  - Total organic sales from social bio: 1 order over the last 14 days.
  - A legacy diabetic AI creative converted 1 sale yesterday.
  - The Older UGC Creator ad generated 3 sales yesterday after an initial slow ramp.
  - The Oatmeal creative is currently the #1 top-performing ad account-wide.

### 3. Absolutely Headline A/B Test Analysis & Subscription Test Transition
- Evaluated performance data from the Absolutely multivariate headline test:
  - **Variant A ("World's First AI Scale for tracking calories and macros"):** 16 orders, ~470 visitors (~3.4% conversion). Stable performance over time.
  - **Variant B ("World's Most Accurate AI Calorie Counter"):** 16 orders, ~470 visitors (~3.4% conversion). Had an isolated volume spike/drop due to timezone fluctuation, but mathematically equivalent revenue per visitor (~$7.42 vs ~$7.43 RPV).
- **Decision:**
  - Neither headline shows statistically significant superiority over the other.
  - Both co-founders favored keeping **"World's First AI Scale"** as the primary hero message because explicitly naming "Scale" anchors hardware expectations and reduces consumer confusion, whereas "Calorie Counter" risks sounding purely software-based.
  - Agreed to drop the redundant word *"Get"* from the subheadline ("Calories, macros and vitamins for any food in seconds").
  - Conclude this headline test and deploy the **Subscription A/B Test** immediately to optimize recurring software attach rates.

### 4. US Corporate Structuring & 3PL Customs Complications
- Analyzed proposal to establish a US LLC via Doola to support Truemed HSA/FSA requirements:
  - High operational complexity: Inventory is manufactured and owned by the UK entity (`Qalzy Ltd`). If a US subsidiary or entity acts as importer of record without owning inventory, complex intercompany debt structures and loan agreements would be required to fund imports.
  - Risk of customs scrutiny, transfer pricing overhead, and double-entry bookkeeping outweigh the isolated benefits of HSA/FSA processing.
  - Agreed not to rush into a US entity until clear scale thresholds demand it.

### 5. Print Flyers & Black Friday Creative Prep
- Awaiting formal quotes from Greek commercial printing houses (`dprint.gr`, `ximosprint`, `typography.pallis@gmail.com`) for CES 2027 horizontal bi-fold brochures.
- [[people/michael-michelis]] preparing the Black Friday landing page in Shopify.
- Reviewing an advertorial draft submitted by Hussein, hosted in the GitHub organization under a nutrition/health publication theme.

---

## Action Items & Next Steps
- **[[people/michael-michelis]]:** Finalize and deploy the Shopify templates for the Subscription A/B test.
- **[[people/michael-michelis]]:** Monitor incoming print shop quotes for 500 copies of the CES bi-fold brochure.
- **[[people/kostas-koukoravas]]:** Conclude the current headline test in Absolutely, locking in "World's First AI Scale" without "Get".
- **[[people/kostas-koukoravas]]:** Monitor crash logs and Flutter version compatibility for legacy iPad/iOS devices.
