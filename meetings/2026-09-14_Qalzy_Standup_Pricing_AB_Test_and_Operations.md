# Qalzy Daily Standup: Pricing A/B Test, Operations & Growth Alignment

**Date:** 2026-09-14  
**Attendees:** [[people/kostas-koukoravas]], [[people/michael-michelis]], [[people/john-karunungan]]  
**Companies:** [[companies/qalzy]], [[companies/intelistyle]]

## Summary
Daily operations and growth sync between [[people/michael-michelis]] and [[people/kostas-koukoravas]] (with [[people/john-karunungan]] covering Intelistyle tasks at the start). Major topics covered: concluding the 5-day pricing A/B test by terminating the $169 and $239 variants and standardizing on $199; restructuring Shopify COGS ($28.24) and moving fulfillment/shipping by weight into separate shipping profiles across Sellerboard and Triple Whale; scaling Meta ad spend back up to $1,200/day following weekend blended ROAS recovery (2.2 on Saturday and 2.6 on Sunday); coordinating [[companies/social-paradigm-group]] onboarding and partnership ad ownership; resolving a customer return issue tied to scale "System Busy" error messages; rejecting a $120 retail proposal from Kuwait distributor [[people/mahdi-aldashti]]; and troubleshooting Fin AI scale guide instructions.

---

## Key Discussion Points

### 1. Intelistyle Task Sync ([[people/john-karunungan]])
- John completed "Shop the Look" and category mapping for Guess on Friday.
- For Monday, John is executing Kiba imports/updates (standard recurring 30 updates), followed by Epiculent Twist, with Guess new arrivals queued next per Kostas' prioritization.

### 2. Shopify COGS & Shipping Profile Restructuring
- **COGS Adjustment:** Kostas updated the baseline unit COGS in Shopify to **$28.24** by removing shipping and fulfillment costs that were previously bundled into the COGS figure.
- **Shipping Profile by Weight:** Added a dedicated US-only shipping profile calculated by weight across Shopify, Sellerboard, and Triple Whale. This enables accurate order-level margin tracking: $\text{Profit} = \text{AOV} - \text{Shipping} - \text{COGS}$.
- **App Stack Optimization:** Considering deprecating Sellerboard once Triple Whale is fully operational to eliminate redundant subscription costs.

### 3. Pricing A/B Test Resolution ($199 Locked In)
- After 5 days of live testing across $169, $199, and $239 price points, the team analyzed results with Fable/Opus and manual order deduplication:
  - **$169 Price Point Terminated:** Delivers only ~$112 profit/contribution per order before ad spend. With Qalzy's historical CPA hovering at $150–$155, selling at $169 generates immediate unit losses. Furthermore, discount codes (10–20%) stack on top of $169, allowing customers to acquire the scale near zero margin. The $169 price also represents a 43% drop from the $299 MSRP anchor, which risks degrading perceived brand credibility.
  - **$239 Price Point Terminated:** While per-order economics are strong, website conversion dropped to ~1.8% during the test (compared to 2.3% historically).
  - **$199 Price Point Approved:** Settled on **$199** as the official retail price ($163 contribution margin per unit, leaving $13/unit operating profit at a $150 CPA). Provides an optimal balance of conversion rate and perceived value (33% off $299 MSRP anchor).
- **Decision:** End the A/B test today and lock the storefront price to $199.

### 4. Ad Spend Scaling & Performance
- Blended performance over the weekend improved significantly (blended ROAS of 2.2 on Saturday and 2.6 on Sunday).
- With the pricing test resolved and the new ad structure stabilizing, the team agreed to scale daily ad spend back up toward **$1,200/day** gradually.

### 5. SPG Agency Onboarding & Partnership Ads
- Qalzy must complete the SPG onboarding document/questionnaire today.
- Need to reschedule the SPG onboarding call to Tuesday because Kostas is traveling on Wednesday (SPG's initial calendar invite was set for Thursday Sep 17).
- Partnership ad featuring the diabetic doctor/creator will be assigned to [[companies/social-paradigm-group]] rather than [[people/ronaldas-blazer]], ensuring it aligns with SPG's dedicated middle-of-funnel/creator testing strategy.

### 6. Creative Production & Content Strategy
- **Kostas & Father Video:** Outperformed standard UGC (1,000 views vs 400 for Halelio video). Kostas will add a dedicated voiceover hook: *"Getting Enough Protein for 60 Year Olds"*.
- **US Localization:** Michael emphasized that US-targeted ad creatives and B-roll must feature measurements in pounds (lbs) and cups rather than grams.
- **Blazer Creative Delivery:** Ronaldas has delivered 1 founder video (out of 3 planned hooks) and Stella's video. Remaining credits/units will be allocated toward remaining founder hooks, gestational diabetes angles, and Q&A cutdowns.
- **Social Media Queue:** Current posting queue is exhausted. Plan to repurpose high-performing formats, test humor hooks (similar to Cali AI), or cut down founder content.

### 7. Kuwait Wholesale & Distribution Terms ([[people/mahdi-aldashti]])
- Mahdi proposed an EXW wholesale price of $85/unit for an initial 250-unit order, with an intended Kuwait retail price of ~$120 (high-volume, low-margin model).
- Kostas strongly objected to a $120 retail price, pointing out that selling at $120 overseas while charging $199–$250 globally severely erodes brand integrity, positioning, and price parity.
- Team consensus: Wholesale at $85 is only viable if the minimum retail price is maintained at **$169–$170**, or via an exclusive local retail distribution structure that prevents cross-border price cannibalization. Michael sent an email to schedule a video call with Mahdi for Thursday/Friday to review distribution strategy and unit economics.

### 8. Customer Support & Fin AI Guidance
- Kostas flagged that Fin AI is providing inadequate responses to customer onboarding questions regarding macro tracking (e.g. directing users to QuickScan or phone AI camera for drinks/macros instead of linking the official guide).
- **Action:** Intercom/Fin AI workflows must be updated so that whenever a customer asks about basic scale usage or macros, Fin automatically surfaces the link to the Quick Scale Guide with embedded video walkthroughs. Michael updated scale dimensions in Fin knowledge base.

### 9. Hardware/Software "System Busy" Scale Bug
- Two recent customer returns were caused by scales hanging on a "System Busy" error state.
- Kostas noted that his father's scale experienced this repeatedly in the same household/Wi-Fi where Kostas' personal scale functioned without issues, suggesting a possible internal wiring contact or electronics flaw.
- Michael noted the error previously triggered when tapping live scan / quick scan in rapid succession (firmware/software loop).
- Kostas will log an engineering ticket to track root cause and arrange inspection of returned units.

### 10. Kickstarter Backer Warranty Outreach
- Plan to export Kickstarter backer emails into a dedicated [[companies/klaviyo]] segment and re-send the warranty and referral offer, ensuring backers receive and review the promotion directly.

---

## Commitments & Action Items
- **[[people/kostas-koukoravas]]:**
  - Kill the Shopify pricing A/B test and lock storefront price to $199.
  - Scale daily Meta ad spend gradually toward $1,200/day.
  - File an engineering ticket for the scale "System Busy" freeze bug.
  - Finalize voiceover for the "Getting Enough Protein for 60 Year Olds" video ad.
  - Confirm Ronaldas' remaining creative unit balance and brief gestational diabetes + founder hook edits.
- **[[people/michael-michelis]]:**
  - Complete the SPG client onboarding questionnaire.
  - Request SPG reschedule the kickoff call to Tuesday due to Kostas' Wednesday travel.
  - Update Fin AI resolution flows to link the Quick Scale Guide on scale usage inquiries.
  - Conduct call with [[people/mahdi-aldashti]] on Thursday/Friday regarding Kuwait retail pricing and distribution terms.
  - Set up Klaviyo warranty email campaign for Kickstarter backer list.
- **[[people/john-karunungan]]:**
  - Process Kiba 30 updates, followed by Epiculent Twist and Guess new arrivals.

---

## Claim Verification Gate
- *Claim:* Unit COGS updated to $28.24 in Shopify.  
  *Verification:* Confirmed in transcript (`00:02:35` - "Yeah, it's 28.24, because before we were including the shipping and fulfillment...").
- *Claim:* $169 price point generates $112 profit per order, leading to losses at $150 CPA.  
  *Verification:* Confirmed in transcript (`00:06:05`–`00:07:07` - "You're making $112 per order. There is no scenario where your CPA is below $112... CPA is at 150 to 155").
- *Claim:* Weekend blended ROAS was 2.2 and 2.6.  
  *Verification:* Confirmed in transcript (`00:50:54` - "blended now, is 2.2 we had, 2.6 yesterday").
- *Claim:* Wholesaler offered $85 EXW to retail at $120.  
  *Verification:* Confirmed in transcript (`00:26:45`–`00:29:35` - "85 dollars... to retail at 120... when we sell at 200").
