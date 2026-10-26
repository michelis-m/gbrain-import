---
type: meeting
title: >-
  Qalzy Technical Sync: Session GUID Timestamp Fix, Gemini 3.5 Evaluation & Food
  Deduplication
date: '2026-10-26'
---

# Qalzy Technical Sync: Session GUID Timestamp Fix, Gemini 3.5 Evaluation & Food Deduplication

**Date:** 2026-10-26  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  
**Companies:** [[companies/qalzy]], [[companies/social-paradigm-group]]  

---

## Executive Summary
Michael Michelis and Kostas Koukoravas held a technical sync to resolve backend session allocation logic, evaluate Gemini vision model performance, address food parsing edge cases, and debate website subscription positioning. Kostas implemented an architectural fix extracting timestamps from event GUIDs rather than mutable request headers to prevent cross-day session corruption, which will be validated on staging before deployment. Benchmark evaluations on the Colson test suite demonstrated that Gemini 3.5 Flash degraded accuracy, increased latency, and cost 66% more than Gemini 3.1 Flash, prompting the team to keep 3.1 Flash in production. The founders also reviewed food deduplication issues surrounding descriptor words like "slice", corrected external Open Food Facts database discrepancies, dismissed an irrelevant custom B2B inquiry from France, and aligned on radical transparency for the upcoming website subscription test following input from Syed Hussain.

---

## Key Discussion Points

### 1. Backend Session Tracking & GUID Timestamp Fix
- **Root Cause Analysis:** Investigated a backend bug where meal tracking events moved across days inadvertently inherited the previous day's active session, creating corrupted session groupings.
- **Architectural Solution:** Kostas modified the grouping logic: instead of evaluating request timestamps, the backend now extracts the immutable creation timestamp embedded directly within the MongoDB ObjectId / GUID. This ensures rescheduled events correctly generate fresh sessions.
- **Safe Staging Rollout:** Recognizing the risk of pushing core data-layer modifications directly to production, Michael offered to deploy the branch (`get backend try new model` / staging branch) to the staging environment and conduct end-to-end integration testing with both the mobile app and physical scale hardware.

### 2. Gemini 3.5 Flash vs. Gemini 3.1 Flash Evaluation
- **Benchmark Performance:** Kostas executed the Colson automated capture benchmark suite (15 iterations over comparative food imagery sets).
- **Evaluation Findings:**
  - **Accuracy:** Gemini 3.5 Flash succeeded in only 15 out of 21 test scenarios, underperforming the existing production baseline.
  - **Latency:** Requests exhibited extreme latency, taking between 1.5 and 4 minutes per call or triggering timeouts.
  - **Cost:** Pricing at $2.50 per million tokens compared to $1.50 for Gemini 3.1 Flash represents an unwarranted 66% increase.
- **Conclusion:** Qalzy will remain on Gemini 3.1 Flash. Upgrading to 3.5 Flash is deferred indefinitely until Google improves latency and recognition consistency.

### 3. Google Cloud Startup Credits Extension
- **Account Outreach:** Google Cloud Account Manager Caelum Rosenkranz contacted Michael indicating Qalzy retains ~$50,800 in startup cloud credits slated to expire in April 2027.
- **Credit Preservation:** Caelum offered to pursue an extension through the Google for Startups program. Michael scheduled a video call with Caelum for Tuesday, October 27 to finalize the credit rollover.

### 4. Food Recognition Parsing & Database Inaccuracies
- **Descriptor Suppression Bug ("Slice"):** Evaluated a critical parsing flaw where food items containing descriptive nouns such as "slice" (e.g., turkey slice vs. cheese slice) cause unintended item suppression or false deduplication.
- **Exception Modeling:** Discussed expanding exception whitelists (similar to existing rules distinguishing sweet potato from standard potato, and scallion/spring onion from green onion). Decided that "slice" should either be whitelisted or filtered out as a quantity descriptor rather than a food category identifier.
- **Data Source Quality:** Investigated calorie calculation discrepancies (e.g., a stir-fry logged at 300 kcal rather than 700 kcal). Identified faulty upstream serving-size metadata on Open Food Facts (e.g., McDonald's portion fields defaulting incorrectly to 100g vs. 500g). Kostas manually corrected the corrupted records on Open Food Facts.
- **Recipe URL Importer:** Noted recurring extraction failures when attempting to parse recipes from specific food blogs (e.g., *The Woks of Life*).

### 5. Inbound Commercial Lead ("Kyriakos" / Food Trucks)
- **Inquiry Details:** An individual named Kyriakos reached out via Facebook Messenger and Fin AI inquiring about adapting Qalzy scales for commercial food trucks and canteens in France, requesting a pilot unit.
- **Strategic Verdict:** Both founders agreed to disregard the inquiry, noting it requires non-standard commercial hardware and bespoke software development, representing an unnecessary distraction from consumer DTC focus.

### 6. Website Subscription CRO & Transparency Debate
- **Syed Hussain Feedback:** Reviewed commentary from [[people/syed-hussain]] regarding the planned subscription PDP A/B test.
- **Downstream Consequences of Obfuscation:** Kostas argued strongly against deceptive CRO tactics that hide subscription pricing or falsely claim the mobile app is entirely free forever. Masking fees inevitably drives 1-star reviews, customer disputes, and return requests (*"You tricked me / scam"*).
- **Clarity-Driven Variant:** The team agreed that the test variant should lean into clarity: incorporating explicit anchor links directly to a breakdown of free core scale tracking vs. optional premium features and clear subscription pricing.

---

## Action Items & Next Steps
- [ ] **Kostas Koukoravas:** Commit the session GUID timestamp fix to the dedicated backend staging branch and link it to the Linear/Dev backlog ticket.
- [ ] **Michael Michelis:** Configure the mobile app and test scale against the staging server to validate the GUID session allocation fix across cross-day logging scenarios.
- [ ] **Michael Michelis:** Attend scheduled sync with Caelum Rosenkranz on Tuesday, October 27 to negotiate the extension of Qalzy's $50,800 Google Cloud startup credits.
- [ ] **Kostas Koukoravas:** Implement exception rules for quantity and unit descriptors (starting with "slice") to prevent cross-food deduplication errors.
- [ ] **Michael Michelis & Syed Hussain:** Finalize the subscription clarity wireframe in Figma featuring clear anchor links and explicit free vs. premium feature breakdowns.
