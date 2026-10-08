# Daily Email Summary: 2026-10-08

## 1. Supply Chain, Logistics & Inventory Transition
- **US Fulfillment Transition & Portless Modeling:**
  - [[people/kostas-koukoravas]] formally reached out to [[people/chloe-hu]], [[people/ryan-torreta]], and Portless Support to evaluate logistics for shifting primary inventory from Portless to a US warehouse.
  - Provided indicative inventory relocation split:
    - Scales: White ~1,730 to US (~570 retained at Portless); Black ~1,770 to US (~190 retained).
    - Accessories: Carrying Cases ~375 to US (~190 retained); Portion Plates ~560 to US (~120 retained); US Chargers ~945 to US (~100 retained); EU Chargers 133 retained.
    - Requested quotations for palletizing, wrapping, carton configurations (assuming 240 scales/pallet), export documentation/clearance from bonded warehouse, and operational lead times.
- **EU Regulatory Surcharge (Openborder & Portless):**
  - [[companies/openborder]] and [[companies/portless]] issued notices that a new €2 Union Handling Fee will apply to non-EU B2C shipments imported into the EU, clearing customs on or after 2026-11-01.
  - Applies in addition to the existing €3 fee from July 1, 2026. Levied per unique customs item (HS code + Country of Origin). Openborder's tax engine will start collecting the fee at checkout on Monday, October 26, 2026.
- **Redo Returns & Influencer SKU Workflow:**
  - Following advice from [[people/frank-marino]] (offering either a new store or transforming returned items into a distinct SKU), Kostas confirmed Qalzy will use the existing Shopify store with an unlisted SKU for manual creator dispatches, requesting instructions on how Redo performs the SKU transformation upon intake.
- **Portless Operations & Reshipments:**
  - Order `PBID007753130-1`: Portless Assistant confirmed new tracking number `00340434624230233207`.
  - Order `PBID007752595`: Kostas instructed Portless to reship to Med Maps Srl (att. Amato) in Cassano d'Adda, Italy.
  - Portless invoice `#1085261006` confirmed paid in full ($0.00 remaining).
  - [[people/michael-michelis]] urgently followed up with Ruby at Portless Billings for declared values of Norway orders needed by EOD for VOEC tax filing.
  - Export of 187 orders completed and downloaded from Portless portal.

---

## 2. Marketing, Advertising & Creators
- **Reddit Advertising (Dedicated Rep & Reddit Max):**
  - [[people/denis-augustine]] (SMB Sales Development Representative at Reddit in London) reached out as Qalzy's dedicated account manager.
  - Highlighted targeted subreddit opportunities and invited Qalzy to test **Reddit Max**, an automated campaign type delivering average 17% CPA reductions and 27% conversion volume lifts.
- **Affiliate Infrastructure (Awin & Shopify Collabs):**
  - [[companies/awin]] sent onboarding confirmation for the Awin Access program ($49/month after free first month, 20% platform commission fee) following Michael's application.
  - Shopify Collabs email verification sent to `michael@qalzy.com` to finalize creator discovery platform setup.
- **Meta Advertising:**
  - Meta billed $900.00 USD on ad account `1351291616909846`.
  - Multiple ad creative submissions approved and live in ad auctions.
- **CES 2027 Inquiries:**
  - Sarah Dcruz from AARS Exhibits followed up with `info@qalzy.com` regarding Las Vegas booth construction and fabrication services; automated reply sent directing inquiries to partnership channels.

---

## 3. Technology, Infrastructure & Engineering
- **Google AI Studio Deprecation Warning:**
  - Google AI Studio announced deprecation of `gemini-omni-flash-preview` and `veo-3.1-*-preview` models effective October 22, 2026.
  - Requires updating active project API endpoints and SDK configurations to `gemini-omni-1.1-flash` before October 22 to prevent service disruptions.
- **MongoDB Atlas Database Performance:**
  - Weekly query performance report for `QalzyDB` (Project 0) delivered; cluster metrics and query shapes operating normally.
