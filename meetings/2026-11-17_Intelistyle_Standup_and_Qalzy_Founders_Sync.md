---
type: meeting
title: >-
  Intelistyle Standup & Qalzy Founders Sync: Tare UI, CES Booth Design, Ad Hooks
  & AI Model Evals
date: '2026-11-17'
---

# Intelistyle Standup & Qalzy Founders Sync: Tare UI, CES Booth Design, Ad Hooks & AI Model Evals

**Date:** 2026-11-17  
**Attendees:** [[people/john-karunungan]], [[people/kostas-koukoravas]], [[people/michael-michelis]]  

---

## Summary
Morning sync covering Intelistyle engineering updates, followed by an in-depth operational and strategy session between Qalzy co-founders. Topics included Intelistyle image quality workflows, ongoing litigation disclosure demands, Qalzy scale software and session clearing UI design, CES 2027 turnkey booth aesthetics, Black Friday ad creative hooks, US entity/inventory strategy, Redo returns question logic, and Gemini model benchmark evaluations.

---

## Key Discussion Points

### 1. Intelistyle Engineering Standup
- [[people/john-karunungan]] reported completing image quality checks for Guess and Guess "Shop the Look."
- John is currently working on image quality for De Cuba and flagged a missing item photo issue to [[people/michael-michelis]] in the De Cuba channel.
- [[people/kostas-koukoravas]] noted an upcoming meeting with CAS representatives to pitch their proposal, though CAS requires approval from their board and grower representatives.

### 2. Litigation Update & Financial Disclosure Demands
- Kostas shared severe frustration with opposing counsel in his long-running legal proceedings, who requested business bank account disclosures (£400k balance across both companies) just three days prior to court without a formal court order.
- Kostas observed that opposing counsel’s questions mirror raw ChatGPT outputs.
- Strategy agreed: Refuse voluntary disclosure of unmandated business accounts on short notice, citing privacy, third-party shareholder interests, and lack of court direction.

### 3. Qalzy Scale Firmware & Session Clearing UX
- Michael reported testing the updated scale firmware and live scan functionality daily on food, confirming stable performance without issues.
- Discussed UX improvements for scale tare and session clearing:
  - Introducing dynamic status feedback ("New foods", "No new foods identified", "Previous foods", "Session cleared") to give users clarity on scale state.
  - Keeps hardware costs lean by delivering intuitive software-driven UX instead of adding expensive hardware screens.

### 4. CRO & "With Recipes" A/B Test Interpretation
- Michael clarified the analytics for the "With Recipes" PDP A/B test: the control group included recipes, meaning negative variance indicators reflect positive test performance.

### 5. CES 2027 Booth Design & Print Collateral
- Finalized turnkey booth styling: Silver frame with white panels and a high-contrast black back.
- Approved core graphic callout: "Try it live - put any food on the scale" with a prominent arrow and camera recognition graphic.
- Action needed to finalize and order printed flyers/brochures for the show.

### 6. Ad Creative Hooks & Black Friday Repurposing
- Discussed repurposing existing video footage with fresh hooks to scale ad variations ahead of Black Friday.
- Ideas agreed:
  - Test the hook: "No way this is accurate" to directly tackle recipe tracking skepticism in comments.
  - Adapt Michael’s school video concept with promotional text overlays.
  - Test "Calorie counting is hard" angle.

### 7. US Entity Formation & Inventory Strategy
- Discussed stalled progress and high quotes ($8k without transfer pricing/IP agreements) from US corporate advisors.
- Agreed that the pragmatic way forward is using the existing corporate structure to clear and position inventory in the US market to prevent stockout losses.

### 8. Redo Returns Logic & Customer Support Friction
- Michael flagged an issue in the Redo returns questionnaire where question ordering (first question requires "No", second requires "Yes") causes customer confusion and support tickets that automated agents cannot easily reset.

### 9. AI Model Evaluation (Gemini Benchmarks)
- Michael benchmarked Gemini models for food recognition: large models are too slow for real-time application.
- Tested Flash-Lite 3.1 vs Flash-Lite 3.5.
- Discrepancy noted: Michael observed 15–16 test failures in his current test setup compared to 4–5 failures in Kostas’s recent run (Kostas noted Giorgos’s Slack integration test failure and potential model variance).

---

## Action Items & Commitments
- [ ] [[people/john-karunungan]]: Share screenshot of missing De Cuba item photo in Slack channel for review.
- [ ] [[people/kostas-koukoravas]]: Formulate legal response rejecting unmandated business bank disclosure.
- [ ] [[people/michael-michelis]]: Finalize CES flyer print orders and booth graphic specs.
- [ ] [[people/michael-michelis]]: Cut new ad variations testing "No way this is accurate" and school video hooks.
- [ ] [[people/kostas-koukoravas]] & [[people/michael-michelis]]: Investigate Gemini test failure discrepancy (15 vs 4 failures) and inspect test setup.
- [ ] [[people/michael-michelis]]: Adjust Redo returns question flow logic to eliminate customer submission errors.
