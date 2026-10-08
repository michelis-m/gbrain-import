# Qalzy Influencer Review, Ad Creative Strategy & Hardware Stability

**Date:** 2026-10-08  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  
**Companies:** [[companies/qalzy]], [[companies/blazer-agency]]  

---

## Summary
Operational sync between Michael Michelis and Kostas Koukoravas reviewing creator outreach responses from the newly deployed Meta Creator Marketplace automation. The discussion evaluated candidate creator profiles against target audience demographics, established mandatory criteria for influencer video formats, reviewed new AI ad creative drafts from Blazer Agency / Rolandas, investigated an intermittent scale camera/sync hardware bug, and planned safeguards against customer return abuse.

---

## Key Discussion Points

### 1. Influencer Candidate Review & Video Selection Criteria
- **Mandatory Creative Filter (Talking Directly to Camera):**
  - Agreed that creator videos where the influencer does NOT talk directly to the camera (e.g. voiceover over gym montages or silent b-roll) consistently underperform and should be rejected outright.
  - Authentic, direct-to-camera storytelling is essential for high-converting social proof.
- **Audience & Demographic Alignment:**
  - Evaluated candidate creators who responded to outreach:
    - *Climbing & Extreme Fitness Creators:* Deemed too niche and disjointed from Qalzy's core weight-loss demographic.
    - *Bodybuilding Personas:* Excessively muscular framing alienates everyday consumers seeking sustainable weight management; agreed to decline heavy bodybuilding angles.
    - *Mature Women (Ages 45–51):* Highly aligned with Qalzy's primary target buyer persona.
      - Profile 1: Disqualified after audience analysis revealed 55% international/bot followers (originating from giveaway loops).
      - Profile 2: Strong authentic resonance, but quoted an initial rate of $800. Agreed this does not yield positive ROI; Michael to submit a counteroffer of $300 plus product.
    - *AI Synthetic Creators:* Identified several applicants utilizing AI synthetic avatars and voiceovers; agreed synthetic content should be produced in-house rather than paid for externally.

### 2. Outbound Creator Outreach Automation
- **Pacing & Conversion Rate:**
  - Michael configured an automated DM outreach script operating with randomized delay timers sending 30 DMs per day across a 6-hour window to protect account reputation.
  - Achieved an impressive response rate of ~33% (yielding 6–7 responses per batch), creating a steady pipeline of candidate creators for review.

### 3. Blazer Agency / Rolandas Ad Creative Drafts
- **Creative Variations & Visual Hook:**
  - Reviewed concept drafts focusing on "eyeballing calories every meal" and dynamic visuals of calories/food on fire with the AI Kitchen Scale.
  - Iterations 1, 2, and 3 reviewed: Overall pacing is engaging, but drafts rely too heavily on young male gym personas.
  - Feedback for Rolandas: Pivot future iterations toward everyday female and older demographics that match actual customer conversion cohorts.

### 4. Hardware Stability & Intermittent Scale Camera Bug
- **Bug Symptoms & Root Cause:**
  - Investigated an intermittent issue where the scale camera freezes or fails to sync logs to the mobile app.
  - Suspected causes: Camera sensor sync timeout or local microcontroller out-of-memory (OOM) condition.
  - Customer friction: Impatient users encountering the bug immediately interpret it as a hardware defect and request a return after only 1–2 failed attempts.
- **Mitigation & In-App UX Improvements:**
  - Current in-app status message ("No new foods identified") is displayed in low-contrast gray text and easily overlooked.
  - Planned UI changes: Increase font weight and contrast, provide distinct status prompts ("Food already identified"), and introduce clear in-app troubleshooting steps to prevent unnecessary returns.

### 5. Return Logistics & Policy Enforcement
- **Customer Return Behavior & Pairing Mode:**
  - Noted that numerous returned units arrive already paired to customer phones without being reset to pairing mode, requiring manual reconfiguration before re-seeding to creators.
  - Proposed establishing a structured return intake flow: Requiring customers to confirm the unit is in pairing mode and submit a verification photo before generating an automated prepaid return label.

---

## Action Items & Commitments

| Owner | Task | Status |
|---|---|---|
| [[people/michael-michelis]] | Send $300 counteroffer to mature female creator candidate (quoted $800) | In Progress |
| [[people/michael-michelis]] | Continue automated Creator Marketplace DM pipeline (30/day rate limit) | Active |
| [[people/michael-michelis]] | Provide feedback to [[people/ronaldas-blazer]] to replace gym male personas with women/mature demographics | In Progress |
| [[people/michael-michelis]] | Update mobile app status UI ("No new foods identified") with bold styling and troubleshooting guide | Pending |
| [[people/kostas-koukoravas]] | Continue investigating intermittent camera freeze / OOM sync issue on scale firmware | In Progress |
| [[people/kostas-koukoravas]] | Design verification step in return flow requiring photo proof of pairing mode prior to label generation | Pending |
