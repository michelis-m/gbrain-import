---
type: meeting
title: >-
  Qalzy Morning Sync: API Integration for Longevex, Delivery Exceptions,
  Influencer UGC & CRO Strategy
date: '2026-11-03'
---

# Qalzy Morning Sync: API Integration for Longevex, Delivery Exceptions, Influencer UGC & CRO Strategy

**Date:** 2026-11-03  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  

---

## Summary
Morning standup between Michael Michelis and Kostas Koukoravas covering Intelistyle client delivery updates and inbound enterprise inquiries, API token architecture and security boundaries for the Longevex integration, redelivery workflows for Kickstarter international orders (Germany and Hungary), detailed critique of creator UGC videos (Sol and unapproved Halloween reel), on-site A/B testing performance in Absolutely, competitor landing page teardowns (Whoop, Oura, NeuroSim), and planned CRO changes to Qalzy product pages emphasizing free app functionality and transparent feature comparisons.

---

## Key Discussion Points

### 1. Intelistyle Standup Updates & Inbound Pipeline
- **Production Tasks:** Completed image quality QA on Epicure and Twist, approved Guessery / Guess items, and finalized the clip button workflow for Dick Cuba. New arrivals incoming for Guess.
- **Inbound Lead (Ames Watson):** Evaluated an inbound enterprise lead from Ames Watson, a New York retail umbrella brand overseeing ~10 brands with ~$4M aggregate revenue. The client reached out regarding Intelistyle's "Shop the Look" solution after attempting to build it internally. Quoted standard pricing between $500–$900/month.

### 2. B2B REST API Integration for Longevex ([[people/andrei-zimiles]])
- Discussed technical architecture following yesterday's partnership session with Andrei Zimiles.
- **Access Scope & Security:**
  - Agreed to create a dedicated super-user account specifically provisioned for Longevex.
  - **Permissions Boundary:** Restrict API access strictly to the `create account` endpoint. To protect user privacy and avoid unauthorized access, do not grant rights to modify arbitrary accounts or read diary entries programmatically.
  - **Diary Data Access Flow:** Clinicians will only access patient diary logs after the user accepts an explicit authorization/consent prompt inside the Qalzy mobile app.
- **Action:** Michael to generate credentials and send API documentation.

### 3. Kickstarter International Delivery Exceptions
- Reviewed two delayed/returned international orders from the July Kickstarter backer survey cohort:
  - **Germany (`PBID007759812`):** Customer Celeste Madrid Beltran. Carrier deadline ends today (**2026-11-03**). Michael sent a second reminder email to secure correct delivery details.
  - **Hungary (`PBID007833421`):** Customer Tamas (`ekebmot@gmail.com`). Backer completed survey in July; order failed delivery. Longer window available, but requires immediate address re-confirmation.

### 4. Creator Operations & Influencer Video Critiques
- **Sol's UGC Script & Video Cut:**
  - Reviewed Sol's draft video ("Guess the Protein" concept with chicken breast, fish, and uncooked steak).
  - **Critique & Defects:** Video lacks crucial screen close-ups held for 2 seconds showing real nutritional numbers; awkward pronunciation of Qalzy ("Quasi"); unboxing clip was spliced awkwardly in the middle; lighting in Florida showed a storm outside with backlighting blowing out the scale screen.
  - **Resolution:** Request raw footage to re-cut internally, and forward draft to Sol for expert opinion.
- **Unapproved Halloween Video & Thanksgiving Pivot:**
  - Discussed an influencer who posted a Halloween-themed video without obtaining prior brand review or tagging Qalzy as a paid collaborator.
  - The contract includes rights to 2 rounds of revisions.
  - **Commercial Decision:** Avoid severing the partnership over a $100 fee. Instead of fighting over the past Halloween post, propose a Thanksgiving-themed high-protein recipe video this week.
  - **Thanksgiving Script Requirements:** Must follow the script exactly, show how the scale's recipe functionality handles complex meals, feature top-down close-ups on the screen, and deliver by Monday to leverage the 23-day window ahead of Thanksgiving (November 26).

### 5. On-Site CRO, A/B Testing & PDP Subscription Architecture
- **Absolutely A/B Test Technical Evaluation:**
  - Evaluated the live theme/template test vs visual editor test vs URL redirect test.
  - **Technical Findings:** Template tests execute on the backend but incur a ~200ms delay and artificially inflate baseline bounce rate by 25% (because half the traffic triggers two pageview events during the template shift). Visual editor tests remain fastest for client-side element toggles.
  - **Metrics Review:** Overall conversion rate (CVR) remains solid above 2.2% (worst performing group at 2.25%). Paid ads recorded 1.6x ROAS on Google Ads and 1.8x ROAS on Meta Ads. Decided to leave the test running to reach full statistical validity.
- **Competitor Landing Page Benchmarks:**
  - Teardown of Whoop's 3-step "How It Works" module and NeuroSim's interactive feature dots. Agreed consumers want to see the scale working seamlessly on complex, multi-ingredient recipes rather than generic steps.
- **PDP Value Proposition & FAQ Restructure:**
  - **App Pricing Clarification:** Replace ambiguous subscription language with clear, positive messaging: *"Is the app free? Yes, the Qalzy scale works on its own with no subscription required, including unlimited AI scans."*
  - **Feature Comparison Table:** Transition away from labelling tiers as "Base" vs "Premium". Restructure into a clear two-column SaaS comparison: *"Included for free with every Qalzy scale"* vs *"Unlock more with Qalzy Premium"*.
  - Reference Linear ticket tracking the feature comparison table and layout mocks.

### 6. Personal & Operations Update
- Kostas shared an update on an ongoing personal legal matter where opposing counsel requested a hearing postponement, incurring additional legal fees.

---

## Action Items & Tracked Commitments
- [x] **[[people/michael-michelis]]**: Generate and dispatch scoped REST API credentials (`app@longevix.com`) to [[people/andrei-zimiles]] for Longevex user onboarding.
- [x] **[[people/michael-michelis]]**: Follow up with German customer Celeste Madrid Beltran and submit redelivery address to Portless.
- [x] **[[people/michael-michelis]]**: Contact Hungarian customer Tamas regarding delivery confirmation.
- [ ] **[[people/michael-michelis]]**: Reach out to the Halloween creator with structured terms for a replacement Thanksgiving recipe video due by Monday.
- [ ] **[[people/kostas-koukoravas]]** & **[[people/michael-michelis]]**: Finalize copy and visual layout for the PDP feature comparison table ("Included for free with every Qalzy scale") in Linear.
