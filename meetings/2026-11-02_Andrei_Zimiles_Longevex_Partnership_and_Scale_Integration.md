---
type: meeting
title: >-
  Andrei Zimiles (Longevex): Partnership, Qalzy Scale Bundling, API Integration
  & Clinic Distribution
date: '2026-11-02'
---

# Andrei Zimiles (Longevex): Partnership, Qalzy Scale Bundling, API Integration & Clinic Distribution

**Date:** 2026-11-02  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]], [[people/andrei-zimiles]]  
**Companies:** [[companies/qalzy]], [[companies/longevex]]  

---

## Summary
Strategic partnership discussion between Qalzy founders (Michael Michelis, Kostas Koukoravas) and serial entrepreneur and investor Andrei Zimiles (Founder & CEO of Longevex / Performance Lab; formerly co-founder & CEO of Doctor.com). Andrei tested the Qalzy scale prior to the call and was impressed by its real-world accuracy and onboarding UX. Discussion centered on bundling Qalzy smart scales into Longevex membership welcome kits, integrating nutrition and macro data via REST API into Longevex's platform, broader B2B distribution across weight loss / GLP-1 and aesthetic clinics, and future fundraising synergies.

---

## Key Discussion Points

### 1. Hands-On Product Validation (The Pret Sandwich Test)
- Andrei Zimiles shared his real-world test results: he purchased a sandwich from Pret A Manger, deconstructed each component layer by layer, and weighed them on the Qalzy scale.
- **Accuracy:** The computed caloric and macronutrient breakdown came remarkably close to Pret's published nutritional facts.
- **Onboarding UX:** Praised the onboarding flow and detailed questionnaire, noting that the depth creates an effective "sunk cost" commitment that boosts user conversion and retention.

### 2. Longevex / Performance Lab Overview
- **Background:** Andrei previously built and sold Doctor.com (2012–2020; raised ~$20M, grew to hundreds of employees). He is also an investor in hardware health tech companies (including ShapeScale / Shapeshift).
- **Current Business:** Andrei founded **Longevex**, the parent company of **Performance Lab**—a high-end longevity clinic and human performance testing lab in New York City, currently expanding to the Bay Area.
- **Services:** Combines medical care, precision medicine physicians, physical therapists, exercise physiologists, DEXA body scans, VO2 max testing, gait analysis, and blood panel tracking.
- **Current Scale Setup:** Members pay premium annual subscriptions and receive a welcome kit containing a smart weight scale and a standard "dumb" food scale. They currently onboard 15–20 high-end members per month.
- **Expansion:** Launching a lower-cost membership tier projected to onboard 30–40 additional members per month.

### 3. Scale Bundling & Membership Integration
- Andrei expressed strong interest in replacing dumb kitchen scales with Qalzy smart scales across all new membership welcome kits.
- **Value Proposition:** Automated computer-vision food logging eliminates the primary friction point where dietary compliance fails.
- Rather than leaving clients to manually type food weights into apps, providing a dedicated smart scale increases compliance and actionable clinical data.

### 4. Technical Architecture & REST API Integration
- Andrei inquired about bidirectional data exchange (mentioning Google Health Connect on Android and Apple HealthKit on iOS).
- [[people/kostas-koukoravas]] explained that while HealthKit/Health Connect sync exists, platform APIs (especially Apple HealthKit) lack unique entry identifiers and create severe limitations when editing or syncing historical logs back and forth.
- **REST API Solution:** Kostas confirmed Qalzy provides a standard, robust REST web API. Andrei's engineering team can connect directly to Qalzy's API to pull client food logs, meal photos, and macronutrient breakdowns directly into the Longevex clinician dashboard.

### 5. B2B Channel Expansion: Weight Loss, GLP-1 & Aesthetic Clinics
- Andrei outlined significant enterprise and B2B expansion opportunities for Qalzy:
  - **GLP-1 & Endocrinology Practices:** Patients on Ozempic/Wegovy require rigorous lean mass preservation and protein tracking to prevent muscle loss while losing weight.
  - **Aesthetic Medicine & Plastic Surgery:** Post-procedure maintenance (liposuction, body contouring) requires strict nutritional tracking to preserve clinical outcomes.
  - **ShapeScale Collaboration:** Suggested exploring synergies with ShapeScale (3D body scanning hardware), as they target the identical medical, aesthetic, and longevity clinic customer base.

### 6. Pitch Deck Review, Investor Intros & NYC Lab Invitation
- Andrei offered to review Qalzy's investor deck, provide strategic feedback, and introduce relevant health-tech/hardware investors when Qalzy prepares for its next funding round.
- Invited Michael and Kostas to visit the Longevex lab in New York City for a complimentary full clinical testing day (DEXA scan, VO2 max, gait analysis).

---

## Action Items & Next Steps
- [ ] [[people/kostas-koukoravas]]: Follow up with Andrei Zimiles via email with Qalzy REST API technical documentation and integration guides.
- [ ] [[people/michael-michelis]] & [[people/kostas-koukoravas]]: Prepare commercial bundling proposal for Longevex membership welcome kits (15–20 current tier + 30–40 new tier/month).
- [ ] [[people/michael-michelis]]: Keep Andrei Zimiles updated on fundraising timelines and share pitch deck when ready for review.
