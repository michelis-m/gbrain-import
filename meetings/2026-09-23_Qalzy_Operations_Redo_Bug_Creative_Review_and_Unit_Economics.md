# Qalzy Operations, Redo Bug, Creative Review & Unit Economics

**Date:** 2026-09-23  
**Attendees:** [[people/kostas-koukoravas]], [[people/michael-michelis]]  
**Companies:** [[companies/qalzy]], [[companies/redo]], [[companies/portless]], [[companies/social-paradigm-group]], [[companies/blazer-agency]], [[companies/intelistyle]], Google, Meta  

---

## Summary
Comprehensive operational and strategic session between Qalzy co-founders [[people/kostas-koukoravas]] and [[people/michael-michelis]]. Major topics included diagnosing a severe live checkout bug with Redo Checkout+ that failed to apply return protection fees, managing toxic early-adopter customer interactions, reviewing ad creatives from Rolandas (Blazer) and SPG, analyzing Meta ad efficiency gains (CPM dropping to $85–$86), examining 5-day attribution window dynamics, conducting a mid-month financial review (operating profit at -$60k, price elasticity vs. subscription attach rate), resolving ongoing Portless RTS friction, configuring Google Merchant Center for SPG, and confirming Intelistyle annual account filings.

---

## Key Discussion Points

### 1. Difficult Customer Interaction & Checkout+ Dilemma
- **Incident:** A customer contacted the team repeatedly across Messenger and left comments on 5+ Meta ads, complaining about checkout issues while demanding a black scale at an expired discount rate.
- **Support Strategy:** Michael drafted a preemptive expectation-setting message: *"Qalzy is an early-stage product requiring technical familiarity. If you are having difficulties navigating checkout, Qalzy will likely frustrate you, and we'd rather be upfront than see you have a poor experience."*
- **Resolution:** Kostas advised letting the discount code expire naturally at end-of-day Wednesday and ceasing manual replies to prevent escalation or abusive review extortion.

### 2. Critical Outage: Redo Checkout+ Broken on Shopify Store
- **Discovery:** While investigating customer complaints, the founders discovered that clicking the **Checkout+** button on the store failed to add the €4.50 / €6 return protection fee to the cart or checkout total.
- **Admin Verification:** Checking the Redo merchant portal revealed **zero covered orders** registered.
- **Business Impact:** The founders realized this technical failure has directly depressed store conversion and wiped out high-margin shipping protection revenue.
- **Immediate Action:** Kostas immediately logged an urgent ticket with Redo support (`support@getredo.com`, copying [[people/frank-marino]]). Redo Support (Jake Smedley) confirmed engineering escalated a dedicated fix.

### 3. Kickstarter Backer Dispute & Full Refund Policy
- **Backer Issue:** A Kickstarter backer demanded a refund and accused Qalzy of running a "scam" regarding lifetime subscription terms versus promotional website pricing.
- **Resolution:** Rather than entering an extended dispute or paying return shipping (£68 / $100) on a hostile customer, the founders agreed to issue an immediate full refund to neutralize toxic sentiment and prevent negative public reviews.

### 4. Ad Creative Review & Feedback for Blazer / SPG
- **Bottom-of-Funnel (BOFU) Ads:** Noted creatives from Rolandas still prominently feature outdated pricing ($239) rather than updated testing tiers.
- **Format Improvements:**
  - **Remove Intrusive Logos:** Agreed top/bottom brand logos clutter mobile screens and should be excised.
  - **Prioritize Food Close-Ups with Calories:** The primary selling hook is instant calorie/macro visualization. All video close-ups must prominently display food items alongside real-time calorie overlays rather than generic scale pans or empty UI screens.
- **Messaging Angles & Hooks:**
  - *Calorie vs. Protein:* Shift from generic protein tracking to clear calorie deficit messaging: *"Stop Guessing Portions"*, *"Track Accurately In One Tap"*, *"Abs are made in the kitchen, not in the gym"*.
  - *Maternal & Family Health:* Explored mother/child nutrition messaging (*"Know they're getting what they need"*, *"Help them grow with better nutrition"*) to tap into maternal wellness demographics, while noting dedicated landing pages will be needed to maximize conversion.

### 5. Video Editing Automation: CapCut & OpenMontage MCP
- **Workflow Automation:** Michael successfully integrated CapCut with the open-source **OpenMontage MCP** server to automate video assembly and subtitle generation.
- **Subtitle Cleansing:** Kostas confirmed CapCut successfully removed hardcoded burned-in subtitles from legacy video assets, allowing clean re-captioning.

### 6. Meta Ads Efficiency & Attribution Dynamics
- **CPM & Cost-Per-Result Drop:**
  - CPM has dropped from ~$120 (under Rolandas's legacy structure) down to **$85–$86** over recent days.
  - Cost per result has improved significantly across consolidated adsets. Blended ROAS sits at ~1.43–1.61.
- **Attribution Window Reality:**
  - Data audit confirmed a **5-day purchase consideration window** for Qalzy buyers (91% to 97% of conversions occur within 5 days of initial touch).
  - Validated that aggressive daily manual pausing based on 1-day ROAS is counterproductive; broad algorithmic delivery with high-performing creatives is yielding superior stability.

### 7. Mid-Month Unit Economics & Pricing Elasticity
- **Monthly P&L:** Mid-month operating profit currently stands at **-$60k**.
- **Price A/B Test ($199 vs $219 vs $239 vs $249):**
  - The $199 price point significantly improved store front-end conversion rate, but AOV decreased proportionally.
  - **Software Attach Rate Decline:** Software subscription attach rate dropped to **19%** (down from previous ~30%+). The founders hypothesized that the lower price point attracts more price-sensitive/impulse buyers who churn faster or decline subscription commitments.
  - Evaluated moving standard price to **$219** to maintain conversion while recovering margin to offset return costs.
- **Reporting Cadence:** Agreed to shift full monthly financial reviews to month-end (Sep 30/Oct 1) rather than mid-month provisional snapshots to eliminate mid-cycle distortion.

### 8. Logistics, RTS Challenges & US Inventory Planning
- **Portless Friction:** Return-to-sender (RTS) issues continue to incur losses. Portless confirmed US fulfillment centers will not be operational before Q1.
- **US Freight Consideration:** Discussed shipping an insured inventory batch directly to a domestic US fulfillment hub to eliminate international RTS overhead.
- **Batch 9 Fulfillment:** Prepared and dispatched **Kickstarter Batch 9** order list to Portless for manual ingestion into their WMS.

### 9. Google Ads & Merchant Center Setup for SPG
- **Merchant Center:** Successfully created and verified Google Merchant Center account (ID: `5790342972`) and granted Admin/Standard access to [[companies/social-paradigm-group]] (`info@socialparadigmgroup.com`).
- **Campaign Split:** SPG restructured Google Ads into distinct branded and non-branded search campaigns to isolate core brand intent from discovery testing.

### 10. Intelistyle Operations & Client Retention
- **Financial Accounts:** Kostas is finalizing Intelistyle annual statutory accounts and going-concern documentation.
- **Guess Extension:** Guess styling and Shop-the-Look catalog workflows are performing well and anticipated to renew for another full year.

---

## Action Items & Next Steps
- [ ] **[[people/kostas-koukoravas]]:** Monitor Redo engineering team's deployment of the Checkout+ Shopify fix and verify covered orders reappear in the Redo admin.
- [ ] **[[people/michael-michelis]]:** Issue full refund for the complaining Kickstarter backer to close out dispute ticket.
- [ ] **[[people/kostas-koukoravas]]:** Provide consolidated ad creative feedback to Rolandas ([[companies/blazer-agency]]) and [[companies/social-paradigm-group]] (remove brand logos, ensure calorie overlays on food close-ups, test "Stop Guessing Portions" / maternal health hooks).
- [ ] **[[people/michael-michelis]]:** Further develop CapCut + OpenMontage MCP pipeline for automated video ad variation generation.
- [ ] **[[people/kostas-koukoravas]]:** Follow up with [[companies/portless]] on manual WMS order creation for Kickstarter Import Batch 9 and track pending refund claims.
- [ ] **[[companies/social-paradigm-group]]:** Complete Google Merchant Center feed integration and launch restructured branded/non-branded search campaigns.
