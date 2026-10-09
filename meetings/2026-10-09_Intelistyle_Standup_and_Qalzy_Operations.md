# Intelistyle Standup & Qalzy Operations: Ad Budget Scaling, Case Inventory Air Freight, Landing Page CRO, and Onboarding Education

**Date:** 2026-10-09  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]], [[people/john-karunungan]]  
**Companies:** [[companies/intelistyle]], [[companies/qalzy]], [[companies/portless]], [[companies/redo]], [[companies/klaviyo]]  

---

## Summary
Daily standup began with a brief Intelistyle wrap-up by John Karunungan ahead of the weekend, followed by an in-depth operational and strategic review between Michael Michelis and Kostas Koukoravas. Key discussions covered monitoring ad performance after yesterday's £100 budget bump, resolving acute carrying case shortages via expedited air freight, issuing a final one-week deadline for outstanding Kickstarter backers, revamping the PDP/landing page in Figma to visually demystify AI food recognition (USDA database matching vs magic), diagnosing underperforming Klaviyo abandoned cart emails (1.1% vs 7.6% industry benchmark), engineering interactive in-app onboarding tutorials to curb product returns, critiquing recent UGC/ad video iterations, and reviewing Michael's local multi-agent Hermes workflow over Slack.

---

## Key Discussion Points

### 1. Ad Spend & Weekend Scaling
- **Performance Evaluation:** Ad performance was solid following yesterday's £100 daily budget increase.
- **Decision:** Maintain current spend through the weekend; if CPA and efficiency hold up, consider increasing the budget further early next week.

### 2. Supply Chain, Inventory & Distribution
- **Portless Communication:** Still waiting on responses from Portless regarding ongoing delivery queries and Norway tax/declared values.
- **Kuwait Wholesale/Distribution:** [[people/mahdi-aldashti]] wants units dispatched immediately; logistics need to be coordinated.
- **Carrying Case Stockout Risk:** Severe case inventory shortage identified. Agreed to ship cases immediately via air freight to beat escalating peak-season freight rates.
- **Kickstarter Backer Hard Deadline:** Kostas noted backers have been contacted repeatedly; agreed to institute a strict 1-week final cutoff for remaining backers to submit details or forfeit priority fulfillment.

### 3. Website CRO & Landing Page Test (Figma)
- **AI Recognition Demystification ("How It Works"):** Customer comments frequently reveal skepticism that AI "hallucinates" calories out of thin air or frustration when hidden ingredients in sandwiches aren't detected.
  - Planned section: Visually explain the mechanics in simple steps: (1) Camera captures food item, (2) AI vision identifies food/portion, (3) Exact nutritional data matched against USDA ingredient database.
  - Emphasize that ingredients must be visible ("AI is not a magic crystal ball").
- **Clinical Authority & Timeline Sections:** Incorporate a "Diet Science Expert / Clinical Study" section (modeled after Neurosym) and a timeline section ("How you will feel: Month 1, Month 2...").
  - Clear messaging around lifetime AI access (avoiding confusing subscription language).
- **Gamified Popups & Urgency Badges:** Scratch card popup has gathered ~10 submissions; agreed to keep it live until statistical significance is achieved rather than switching to "match 3 cards". Reject artificial countdown timers or permanent "flash sale" banners to preserve brand credibility, reserving countdowns strictly for authentic Black Friday promotions.
- **Visual Proof & Bloopers:** Move homepage GIF / bloopers showing complex meals, crowded plates, and salads directly to the product page or create a video mashup reel.

### 4. Klaviyo Email Performance & Funnel Abandonment
- **Abandoned Cart Flow:** Klaviyo benchmark report indicated Qalzy's abandoned cart conversion is at 1.1%, trailing peer benchmarks of 7.6%, despite healthy initial Add-to-Cart numbers.
- **Action:** Analyze bottom-of-funnel sequences from competitors (Athletic Greens, Hume Health, Neurosym) to rebuild the email flow.

### 5. Onboarding Experience & Reducing Product Returns
- **Return Diagnosis:** Root cause of early returns is user expectation mismatch (expecting zero-effort automated logging without understanding barcodes or portion separation) compounded by a 10-day shipping transit window.
- **Interactive In-App Tutorial:** Move beyond passive multi-slide walkthroughs. Propose an interactive "game-like graduation" onboarding (e.g., "Find an orange, place it on the scale, scan the barcode, congratulations you graduated").
- **Educational Quiz:** Add a playful reality check: "Can you tell what this white mash is? If you can't tell, the AI can't either."
- **Email Post-Purchase Drip:** Expand post-purchase sequence to 4–5 days with dedicated visual troubleshooting guides on sessions, barcodes, and complex meals.

### 6. Creative & Social Media Strategy
- **Video Ad Critique:** Rejected latest edit from Rolandas (Blazer) due to unnatural AI voiceover and lack of on-camera talent. Confirmed that direct-to-camera creator videos with a handheld microphone deliver superior authority and conversion compared to generic voiceovers over b-roll.
- **Organic Instagram:** Recorded ~250k views over the past month (97% non-followers) yielding an estimated 2–8 tracked sales. Planned new content formats: AI recipe videos with end-screen scale branding and short educational animations on nutritional fundamentals (USDA database, TDEE calculation, caloric deficits).

### 7. AI Agent Infrastructure & Linear Task Management
- **Hermes Agent Slack Harness:** Michael demonstrated his multi-agent architecture running Hermes agents linked directly to Slack threads, GDrive transcript auto-sync from Fathom, and Gmail.
- **Claude Billing Separation:** Kostas noted difficulties migrating personal Claude setups due to Intelistyle billing entanglement; Michael offered the team harness with shared enterprise API keys.
- **Linear Ticket Ordering:** Resolved task display discrepancy between priority-sorted views and manual sorting in Linear.

---

## Action Items & Tracked Commitments

- [ ] **[[people/michael-michelis]]**: Finalize new landing page A/B test layout in Figma (incorporating the visual 3-step USDA database breakdown, Diet Science Expert section, and timeline).
- [ ] **[[people/michael-michelis]]**: Audit competitor abandoned cart email flows (Athletic Greens, Hume Health, Neurosym) and draft new Klaviyo sequence copy.
- [ ] **[[people/michael-michelis]]**: Review and dispatch test unit to [[people/fred-fishkin]] for Techstination review.
- [ ] **[[people/kostas-koukoravas]]**: Book urgent air freight shipment for carrying case inventory.
- [ ] **[[people/kostas-koukoravas]]**: Issue 1-week final deadline notice to remaining Kickstarter backers.
- [ ] **[[people/kostas-koukoravas]]**: Create Linear tickets for website "How It Works" and complex food demonstration sections.
- [ ] **[[people/kostas-koukoravas]]**: Confirm SKU mapping `[original sku name]-redo` with [[people/frank-marino]] for returned units.
