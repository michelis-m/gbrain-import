---
type: meeting
title: >-
  Qalzy Morning Sync: A/B Test Wins, Subscription Page Architecture, CES 2027
  Planning & Customer Support Exceptions
date: '2026-11-04'
---

# Qalzy Morning Sync: A/B Test Wins, Subscription Page Architecture, CES 2027 Planning & Customer Support Exceptions

**Date:** 2026-11-04  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]], [[people/john-karunungan]] (Intelistyle standup)  

---

## Summary
Daily standup between Michael Michelis and Kostas Koukoravas covering Intelistyle client delivery updates, breakthrough results in the live Absolutely headline A/B test, PDP subscription tier design and copy refinement ($49/yr tier), CES 2027 booth and print collateral logistics, creator collaboration guidelines with certified nutritionists, customer support resolutions for USPS delivery discrepancies, TrueMed HSA/FSA prerequisites, developer infrastructure key security, and market investing observations.

---

## Key Discussion Points

### 1. Intelistyle Standup
- [[people/john-karunungan]] reported on client QA and catalog mapping:
  - Completed image quality QA and category mapping for Cuba and Guest ("Shop the Look").
  - Today's focus: Guest "Shop the Look" and continuing catalog re-approvals.

### 2. Qalzy Absolutely A/B Test Breakthrough
- **Headline Test Winner:** The latest headline test variant in Absolutely showed a significant conversion surge compared to the flat control group.
  - Best performing headline: *"World's first AI food scale that automatically counts calories"* (tested against *"World's most accurate calorie counter"*).
  - Removing long, essay-like subtitle text and keeping a clean visual hierarchy with icons drove the conversion lift.

### 3. PDP Subscription Architecture & Tier Features
- Reviewed Kostas's Figma mocks for the upcoming subscription comparison section on the PDP.
- **Copy & Feature Simplification:**
  - Removed confusing or perceived negative distinctions:
    - Omitted "Nutrition Insights" as a paid-only distinction from "Nutrition Score" to prevent customer confusion over whether baseline metrics include actionable feedback.
    - Removed "Recipe Importer" from premium highlights so users do not assume core recipe creation is paywalled.
    - Eliminated generic low-value bullet points (e.g., unlimited scans, phone meal logging) from cluttering the table.
  - **Core Reassuring Message:** Emphasize that the Qalzy scale works out of the box with unlimited scans and full core features forever without any subscription required.
  - Position the premium upgrade ($49/year) cleanly as optional advanced coaching / nutrition advisor tools.

### 4. Operations, Phone Numbers & IRS Follow-up
- Kostas spent 2 hours on hold with the IRS via Viber Out, only to discover the number was an internal administrative line that could not resolve taxpayer entity queries.
- Discussed setting up a dedicated US phone number (Michael uses Call.com) to support US entity verification, TrueMed onboarding, and inbound vendor calls at CES.

### 5. Mobile App Bug: OneSignal Push Notifications
- Push notifications for meal reminders are currently broken across iOS/Android test builds.
- Clarified that the bug affects user utility and habit retention (meal logging reminders), distinct from marketing notifications. Identified as an immediate engineering priority.

### 6. CES 2027 Exhibition Logistics & Marketing Collateral
- **Print Collateral:**
  - Standardized on an A5 bi-fold brochure design (compact enough for attendees to slip into pockets).
  - Quantity target: 500–600 copies (~120–150 per day across the 4-day event, January 6–9).
  - Content structure: Page 1 (Product overview & value proposition), Pages 2–3 (How it works & technical specs), Page 4 (Exclusive CES discount QR code, 15%–20% off).
- **Booth Signage (Booth #61855):**
  - Finalized banner printing requirements (~$260 for front banner; sides and header required so attendees approaching from aisles do not see bare white partitions).
- **Badge Logistics:**
  - Confirmed replacement exhibitor badges incur a steep $350 on-site penalty fee if lost.
  - AI advisory recommended picking up physical badges directly at Las Vegas airport upon arrival to bypass severe convention center registration queues.
- **Media Outreach:** Michael following up on unanswered CES Media Pitch submissions via CTA exhibit sales contacts.

### 7. Creator Operations & Nutritionist Endorsement ([[people/laurel-macdougall]])
- Reviewed creator collaboration terms with certified nutritionist Laurel Macdougall (@thecleaneatingmom).
- **Hook & Script Guidance:** Mandated that she explicitly introduce her recommendation with the phrase *"as a certified nutritionist"* to reinforce medical and professional authority.
- Recommended seasonal recipe formats (e.g., pumpkin dip with chocolate) or high-protein yogurt bowls that clearly demonstrate automatic multi-ingredient scanning on the scale.

### 8. Customer Support & Lost Package Resolution (Marina / Order #2415)
- Customer reported non-receipt of order #2415; USPS tracking indicated successful delivery to a community parcel locker.
- Portless stated they do not receive parcel locker access codes or GPS coordinate logs from USPS and declined an automatic carrier reimbursement.
- **Resolution Strategy:** Rather than escalating a dispute or risking a damaging public review, Michael decided to grant a one-time goodwill exception offering a replacement unit or full refund, while clarifying that USPS records indicate delivery.
- Discussed implementing optional shipping insurance / package protection (Checkout+ / Redo) on checkout to formalize lost-in-transit claims.

### 9. Infrastructure Security & Developer Access Keys
- Discussed the high-profile Binance cyber incident ($6B drain via malicious code execution in a developer interview task).
- **Immediate Security Action:** Prioritized revoking and disabling developer Giorgos's active infrastructure credentials and AWS access keys from his personal workstation.

### 10. Financial & Market Observations
- Brief discussion on US midterm elections market reactions and substantial single-day tech pullbacks (Google and Amazon -12%). Michael reported dollar-cost averaging into long-term positions via Revolut.

---

## Action Items & Tracked Commitments
- [ ] **[[people/kostas-koukoravas]]**: Disable and revoke developer Giorgos's infrastructure and AWS access keys from his personal workstation.
- [ ] **[[people/michael-michelis]]**: Reply to customer Marina regarding Order #2415 offering a replacement unit or refund as a one-time goodwill exception.
- [ ] **[[people/michael-michelis]]**: Finalize A5 bi-fold brochure print files (500–600 copies) and order booth #61855 banner graphics for CES 2027.
- [ ] **[[people/michael-michelis]]**: Confirm with [[people/laurel-macdougall]] that she will include *"as a certified nutritionist"* in her dedicated video hook.
- [ ] **[[people/kostas-koukoravas]]**: Finalize PDP subscription section design in Figma and deploy the $49/year comparison test in Absolutely.
- [ ] **[[people/kostas-koukoravas]]**: Investigate and resolve the OneSignal meal reminder push notification delivery issue.
