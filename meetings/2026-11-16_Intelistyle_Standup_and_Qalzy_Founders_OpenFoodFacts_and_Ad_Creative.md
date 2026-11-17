---
type: meeting
title: >-
  Intelistyle Standup & Qalzy Founders Sync: OpenFoodFacts Database Fix, App
  Bugs & Black Friday CRO
date: '2026-11-16'
---

# Intelistyle Standup & Qalzy Founders Sync: OpenFoodFacts Database Fix, App Bugs & Black Friday CRO

**Date:** 2026-11-16  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]], John  

---

## Summary
Founders morning operational sync covering Intelistyle catalog tasks, legal litigation updates in the UK, resolving an OpenFoodFacts database parsing discrepancy in Qalzy, investigating reported app bugs and international customer shipments, and refining the product landing page and Black Friday creative messaging.

---

## Key Discussion Points

### 1. Intelistyle Standup & UK Legal Proceedings
- John provided a brief morning status update: completed image quality checks for Cuba, processed guest re-approvals, and reviewed Cuba Shop the Look; no new arrivals today.
- [[people/kostas-koukoravas]] spent approximately 10 hours on UK court filings and legal preparation over the weekend. Opposing counsel missed court deadlines and submitted the cost bundle late after close of business Friday; Kostas drafted comprehensive responses and will coordinate with his barrister for the upcoming hearing.

### 2. Qalzy OpenFoodFacts Nutrient Parsing Fix
- [[people/kostas-koukoravas]] diagnosed and resolved a data corruption issue in nutritional values:
  - OpenFoodFacts supplies nutrient data in grams, whereas FatSecret provides values in milligrams.
  - The previous parser applied FatSecret's milligram parsing logic universally across OpenFoodFacts records, resulting in skewed database values.
  - Kostas updated the parser, deployed the fix to production, spun up a dedicated remote cloud instance to process the multi-gigabyte scrape without saturating local hardware, and executed smoke tests verifying accurate macronutrient and sodium values.

### 3. App Bugs & International Delivery Support
- [[people/michael-michelis]] identified two app issues to be resolved: one affecting user scoring calculations and another in video summary generation.
- Reviewed a delivery inquiry from a French CES backer whose scale shipment tracking appears stalled in customs; team to follow up on tracking details.

### 4. PDP Conversion Optimization & Social Proof
- Evaluated layout updates for the Qalzy product detail page (PDP), specifically comparing customer reviews, nutritionist endorsements, and recipe highlights.
- Michael noted that generic nutritionist badges can look artificial; agreed that featuring real recipes with visual calorie and macronutrient breakdowns connects directly with high-converting video concepts.

### 5. Black Friday Creative Framing & Discount Anchoring
- Discussed the psychology of discount messaging:
  - [[people/kostas-koukoravas]] pointed out that showing the full £119 / 99 price on top-of-funnel static ads distracts users into sticker shock, whereas highlighting "42% / 43% Off" functions as a far stronger clickbait hook.
  - Agreed to remove confusing membership terminology in favor of clean, transparent value propositions (*"Free calorie tracking forever"*, *"Pay once, track forever"*).

---

## Action Items & Commitments
- [ ] [[people/kostas-koukoravas]]: Finalize legal court bundle responses with UK barrister.
- [ ] [[people/kostas-koukoravas]]: Check carrier and customs status for French CES backer scale shipment.
- [ ] [[people/michael-michelis]]: Document and log specifications for the score calculation and video summary bugs.
- [ ] [[people/kostas-koukoravas]] & [[people/michael-michelis]]: Implement recipe breakdown module on the PDP to enhance post-click conversion.
