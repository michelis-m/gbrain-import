# Intelistyle Standup & Qalzy Operations, Hardware Firmware & In-App Troubleshooting

**Date:** 2026-09-28  
**Attendees:** [[people/kostas-koukoravas]], [[people/michael-michelis]], [[people/john-karunungan]]  
**Companies:** [[companies/qalzy]], [[companies/intelistyle]], [[companies/redo]]  

---

## Summary
Morning standup and operational sync between [[people/kostas-koukoravas]], [[people/michael-michelis]], and [[people/john-karunungan]]. The session opened with an Intelistyle operations update from John covering Guess and Funky Buddha image quality, Shop the Look curation, and Guess re-approvals. Michael resolved a Google Vision job automation glitch that caused processing to stall, establishing an automated cost-monitoring alert. Kostas and Michael then evaluated critical Qalzy hardware and app UX issues driving elevated product returns: user confusion over physical scale button responsiveness, camera scanning errors (e.g. dark photos, mixed foods like yogurt or cocoa), and an automated support AI that prematurely suggests returns. They agreed to prioritize a firmware update for button handling, overhaul the in-app Scale Guide with prominent FAQs and troubleshooting tips, and continue shortlisting DTC creators directly to improve blended acquisition ROI while navigating persistent operational friction with returned units at Redo.

---

## Key Discussion Points

### 1. Intelistyle Operations & Google Vision Pipeline Fix
- **Operations Standup (John Karunungan):** Completed image quality and Shop the Look workflows for Funky Buddha and Guess, along with Guess re-approvals. Today focusing on remaining Guess re-approvals and new incoming IDs before daily deadlines.
- **Google Vision Indexing Automation:** Addressed an Edge/indexing failure caused when Google Vision was previously deactivated. Michael corrected the script logic to dynamically enable Google Vision during catalog batch jobs and shut it off immediately upon completion to prevent excessive API billing charges.
- **Cost Guardrails:** Michael implemented automated cloud billing monitoring to alert the team immediately if vision indexing jobs fail to terminate.
- **Catalog Runs:** Re-running all client indexing jobs across Funky Buddha, Guess, and Ipek Yol so John can process new seasonal SKUs.

### 2. Qalzy Scale Firmware & Button Responsiveness
- **Hardware Button Friction:** Customers are reporting that the scale's physical button does not trigger or register promptly, leading users to press it with extreme force under the impression that the hardware is broken or unresponsive.
- **Return Impact:** Michael emphasized that physical button hesitation is a primary driver of instant returns, as users assume hardware failure before even completing setup.
- **Firmware Release:** Prioritizing an immediate firmware update alongside mobile app improvements to optimize button sensitivity, state locking, and flag management.

### 3. In-App Troubleshooting UX & Support AI Behavior
- **Scale Guide Enhancement:** Kostas insisted on placing a prominent troubleshooting and FAQ section directly above the Scale Guide in the app rather than relying solely on post-purchase documentation.
- **Targeted FAQ Categories:**
  - *Lighting & Camera:* Handling dark environments, flash settings, and camera alignment.
  - *Button & Power:* Correct button pressure and connection states.
  - *Food Recognition:* Proper scanning of complex foods, liquids, and barcode fallbacks.
  - *App Navigation:* Explicit reminders to select the "From AI Scale" button within the app interface.
- **Support AI Defect:** Reviewed instances where the automated customer support AI prematurely advised confused users to initiate a return (*"looks like there might be an issue, would you like to return it?"*) rather than offering diagnostic guidance. Decided to constrain AI return suggestions and direct users to explicit troubleshooting flows first.

### 4. Direct DTC Influencer Strategy & Redo Friction
- **Influencer Pipeline Diversification:** In light of slow response times from existing influencer channels, Michael proposed proactively sourcing and shortlisting relevant micro-creators directly.
- **Unit Economics Target:** Discussed achieving positive blended ROI by targeting creators capable of generating 250+ unit sales or achieving target CPA efficiency on scale purchases.
- **Redo Unit Grading Inconsistencies:** Noted continued delays and lack of clarity from Redo warehouse staff regarding returned units marked with cosmetic defects (such as the unit designated for influencer seeding), which exhibited no visible exterior damage in inspection photos.

### 5. Personal / Administrative Update (London Tenancy)
- Kostas discussed progress on securing a London flat and coordinated with Michael regarding joint tenancy verification and address updating.

---

## Action Items & Next Steps
- [ ] **[[people/michael-michelis]]:** Verify all Intelistyle catalog indexing runs complete successfully and confirm Google Vision cost monitoring alerts are active.
- [ ] **[[people/kostas-koukoravas]]:** Finalize and deploy the mobile app and firmware updates addressing button responsiveness and state management.
- [ ] **[[people/kostas-koukoravas]]:** Design and publish the in-app FAQ and troubleshooting guide (covering dark photos, button handling, and "From AI Scale" prompts) above the Scale Guide.
- [ ] **[[people/michael-michelis]]:** Build an outreach shortlist of direct DTC health and nutrition creators to drive influencer seeding and blended ROI.
- [ ] **[[people/john-karunungan]]:** Complete Guess catalog re-approvals and ingest newly released IDs across client accounts.
