# Intelistyle Standup & Qalzy Operations Review

**Date:** 2026-09-30  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]], [[people/john-karunungan]]  
**Companies:** [[companies/intelistyle]], [[companies/qalzy]]  

---

## Summary
Morning daily sync covering Intelistyle client execution and an urgent operational review of Qalzy's severe performance drop over the previous 48 hours. For Intelistyle, John completed category mapping and image quality checks for Epicure and Twist, while the team aligned on feed indexation timelines and outfit approval prerequisites for Guess. For Qalzy, daily performance deteriorated to only 3 orders, with cost per checkout spiking to $207 and cost per landing to $566. Analysis revealed that add-to-cart rates remained consistent while the cart-to-order completion rate collapsed. The founders diagnosed that the recently activated $4.50 charge on the "Checkout Plus" button (for unlimited free returns) was conflicting with Qalzy's prominent 30-day money-back guarantee messaging, sparking customer distrust right at checkout. The team agreed to remove the Checkout Plus button immediately to de-risk the checkout flow.

---

## Key Discussion Points

### 1. Intelistyle Client Operations
- **Epicure & Twist Progress:** [[people/john-karunungan]] completed category mapping and image quality audits for Epicure and Twist, alongside configuring "Shop the Look" assets.
- **Guess Integration & Approvals:** Discussed feed indexation turnaround and confirmed that all outfits must undergo formal client approval before being pushed live. [[people/michael-michelis]] agreed to review the email thread history regarding the indexation rules.

### 2. Qalzy E-Commerce Performance Drop
- **Severe Conversion Collapse:** Kostas reported that morning orders dropped to just 3 units, with cost per checkout climbing to $207 and cost per landing reaching $566.
- **Funnel Bottleneck Location:** Funnel metrics showed that the top of funnel and add-to-cart rates remained relatively stable; the entire conversion collapse occurred between "Add to Cart" and final order completion.

### 3. Diagnosis: "Checkout Plus" Return Add-On
- **Fee Activation Friction:** Previously, the "Checkout Plus" option was clicked without the $4.50 fee being appended to the cart. A recent code fix ensured the $4.50 was added to checkout.
- **Messaging Conflict:** Displaying a prompt to pay $4.50 for returns directly contradicted the sitewide "30-day money-back guarantee / free returns" promise, likely triggering trust concerns for first-time buyers.
- **Immediate Resolution:** Michael and Kostas agreed to completely remove the Checkout Plus button from the cart/checkout flow.

### 4. Review of Other PDP Modifications
- Discussed other recent adjustments to the product page: removing add-on upsells, introducing a user-generated video section above the fold, adding the "discover our free app" feature section, and reducing subscription FAQs to a single straightforward answer.
- Both agreed that while add-on removal could affect AOV, it would not explain a total collapse in checkout completion rate.

---

## Action Items & Decisions
- [x] **[[people/michael-michelis]]:** Remove the "Checkout Plus" ($4.50 fee) button from the Qalzy Shopify cart/checkout flow immediately.
- [ ] **[[people/michael-michelis]]:** Reply to Guess regarding feed indexation timelines and outfit approval workflow.
- [ ] **[[people/john-karunungan]]:** Continue image quality and catalog audits for Twist and monitor Guess live status.
