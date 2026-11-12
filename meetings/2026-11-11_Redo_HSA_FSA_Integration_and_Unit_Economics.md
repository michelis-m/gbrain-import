---
type: meeting
title: Redo HSA/FSA Integration & Unit Economics Review
date: '2026-11-11'
---

# Redo HSA/FSA Integration & Unit Economics Review

**Date:** 2026-11-11  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]], [[people/quenson-johns]]  

---

## Summary
Commercial and technical onboarding session with [[people/quenson-johns]] ("Q") and Matthew from Redo to evaluate integrating HSA/FSA payment options for Qalzy. Discussed U.S. entity and merchant processing prerequisites, Redo's 5.9% processing fee and $6 Letter of Medical Necessity (LMN) pass-through cost, customer conversion dynamics (~70% net new buyer incrementality), product eligibility scan results across Qalzy's 7 catalog items, custom SEO/AEO landing page deployment, and technical Stripe integration timelines.

---

## Key Discussion Points

### 1. HSA/FSA Qualification & Product Eligibility Scan
- Redo ran an initial automated AI catalog scan against Qalzy's 7 active SKUs/products (white scale, black scale, portion control plate, app premium subscription, protective case, EU charger, US charger).
- Scored ~85% accuracy evaluated with their medical advisory board:
  - **Eligible items:** Qalzy smart food scales (dual-purpose / weight management & health), the app premium subscription, and the portion control plate.
  - **Pending review:** Protective travel case and accessories may also qualify under medical equipment protection guidelines.

### 2. Fee Structure & Letter of Medical Necessity (LMN) Economics
- **Processing fee:** 5.9% standard flat fee per HSA/FSA transaction (covers Shopify processing fee; not additive).
- **Letter of Medical Necessity (LMN):**
  - Requires a doctor's recommendation on dual-eligible wellness hardware ($6 pass-through provider cost).
  - Currently charged to the merchant, though Redo is developing a workflow for customer-paid LMN.
  - Quenson noted willingness to negotiate with Redo finance to discount the LMN fee by $0.50–$1.00 given Qalzy's price point ($199–$239).
- **Comparison to TrueMed:** Redo's transaction percentage is slightly higher, but Redo provides direct on-site checkout integration, eliminating off-site redirection friction.

### 3. Incrementality & Cannibalization Analysis
- Redo performance benchmarks indicate that **~70% of shoppers checking out with HSA/FSA are net new customers** who would not have converted via standard credit cards.
- Order cannibalization remains minimal (<1% of total store volume; ~30% within HSA/FSA transactions).
- Timing advantage: Q4 end-of-year HSA/FSA "use-it-or-lose-it" budget spend pairs directly with January New Year fitness resolution demand.

### 4. Custom Landing Page & Native AEO/SEO Traffic
- Redo builds a turnkey dedicated `/pages/hsa-fsa` landing page directly within the merchant's Shopify store.
- Designed to capture high-intent organic search (SEO) and AI Answer Engine Optimization (AEO) queries (e.g., *"HSA approved food scale"*, *"FSA eligible nutrition tracker"*).

### 5. Technical Next Steps & Stripe Compatibility
- Matthew from Redo verified that necessary Shopify app permissions are already active on Qalzy's store.
- Redo engineering is verifying Stripe account integration workflows (typically completing within 1–2 days if formal manual review is required).

---

## Action Items & Next Steps
- **[[people/quenson-johns]] & Matthew (Redo):** Complete technical review with engineering regarding Stripe integration; finalize catalog approval status within 3–4 hours; confirm potential discount on the $6 LMN pass-through fee.
- **[[people/michael-michelis]] & [[people/kostas-koukoravas]]:** Review formal fee schedule; coordinate deployment of the `/pages/hsa-fsa` landing page once Stripe payment gateway approval clears.
