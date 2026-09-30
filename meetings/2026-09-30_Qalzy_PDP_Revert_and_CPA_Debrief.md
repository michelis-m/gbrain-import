# Qalzy Post-SPG Debrief: PDP Reversion & CPA Troubleshooting

**Date:** 2026-09-30  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  
**Companies:** [[companies/qalzy]]  

---

## Summary
Immediate internal debrief between Michael and Kostas following their weekly performance call with Syed Hussain (SPG). The co-founders engaged in an in-depth debate regarding the methodology for resolving Qalzy's elevated CPA and conversion slump. Kostas argued for immediately reverting all recent product page changes (re-adding add-on accessories, rolling back the UGC video section and subscription FAQ edits) back to the proven pre-slump version to de-risk revenue while ad fatigue sets in. Michael advocated maintaining the new layout for 48 hours to cleanly test the hypothesis that the newly activated $4.50 "Checkout Plus" fee was the sole friction point causing the cart-to-order drop. Ultimately, the founders agreed to hold the layout through Friday, keep Checkout Plus removed, launch incoming ad creative batches, and reassess on Friday.

---

## Key Discussion Points

### 1. Scientific Testing vs. Immediate De-risking
- **Kostas's Argument:** Bundling multiple optimizations introduces unmeasured variables. If the site is suffering from ad fatigue compounded by PDP modifications, leaving unproven layout changes live burns budget and suppresses revenue. Reverting everything to the last known working state provides an immediate safe baseline.
- **Michael's Argument:** Funnel tracking clearly demonstrated that "Add to Cart" conversion held firm while the drop occurred exclusively between cart and final checkout. The Checkout Plus button was the only modification touching the checkout stage. Reverting the entire page prematurely discards legitimate CRO enhancements (e.g. elevating social proof above the fold and removing low-converting add-ons that occupied 25% of vertical mobile space).

### 2. Ad Fatigue vs. Site Friction
- **Ad Performance Trajectory:** Kostas emphasized that CTR softening and budget reallocations by Meta strongly indicate that historical hero ads are fatiguing, requiring fresh creative injections rather than relying solely on website tweaks.
- **Friction Hypothesis:** Michael noted that even fatigued ads would primarily depress CTR and traffic volume; a sudden cliff in checkout completion strongly points to on-site transaction friction introduced by the return fee prompt.

### 3. Testing Plan & Friday Milestone
- **Agreed Approach:** Allow 48 hours (Wednesday through Friday) to observe conversion trends with Checkout Plus removed while Syed pushes new ad creatives live.
- **Trigger for Full Revert:** If conversion rates fail to recover by Friday, execute a full rollback of the PDP layout to the baseline configuration.

---

## Action Items & Decisions
- [ ] **[[people/michael-michelis]] & [[people/kostas-koukoravas]]:** Monitor Shopify cart-to-order conversion metrics hourly through Friday, October 2.
- [ ] **[[people/kostas-koukoravas]]:** Prepare the rollback code/theme in Shopify so that reverting the PDP can be executed instantly if Friday targets are missed.
