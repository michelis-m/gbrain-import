---
type: meeting
title: >-
  Qalzy Founders Sync: Patent Center Transfer, YouTube Strategy, Food Database
  AI Verification & PDP Image Test Pause
date: '2026-11-27'
---

# Qalzy Founders Sync: Patent Center Transfer, YouTube Strategy, Food Database AI Verification & PDP Image Test Pause

**Date:** 2026-11-27  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]], [[people/john-karunungan]]  

---

## Summary
Morning founders sync beginning with a brief Intelistyle standup with [[people/john-karunungan]], followed by a strategic review between [[people/michael-michelis]] and [[people/kostas-koukoravas]]. The founders addressed the utility patent representation transfer with US patent practitioner [[people/rory-flanagan]], evaluated Meta ad performance and winning creative hooks, agreed on a YouTube upload and defensive search ranking strategy, discussed nutritional database architecture (Open Food Facts cleanup vs. in-app "Verify with AI"), reviewed mobile app staging updates (streak UI and Chinese location fix), and analyzed a failing landing page image test (-37% conversion rate drop) resulting in a decision to pause the experiment over Black Friday.

---

## Key Discussion Points

### 1. Intelistyle Standup
- [[people/john-karunungan]] reported yesterday's progress on image quality for GEST, Cuba catalog, and GEST Shop the Loop.
- Today's priorities: completing GEST Shop the Loop, continuing runs on Cuba, and subsequent follow-up on GEST.

### 2. Patent Application Jurisdiction & Upwork Representation
- Reviewed legal guidance from patent attorney [[people/rory-flanagan]]:
  - To file through the USPTO directly, an applicant must be a US citizen/resident; foreign entities can still apply, but correspondence and international patent filings (PCT) must transition through a local receiving office (e.g., UK patent office).
  - Rory requested $325 USD to transfer utility patent application `19/297,002` into his Patent Center customer number, file necessary documents, and audit previous filings.
  - Michael and Kostas agreed that $325 is reasonable and approved proceeding.

### 3. Meta Ad Creative Performance & Winning Hooks
- Evaluated performance of Meta and Instagram ads over the last 48 hours (November 25–26):
  - **"Moussaka" Ad:** Generated sales with the high-converting hook: *"Calorie counting is hard"*.
  - **Creator Creatives:** Videos from Jen and René generated repeat sales (René with 2 sales, Jen 2 days in a row).
  - **School Video:** Filmed at the Montessori school, surprisingly drove multiple high-value orders ($1k+ AOV/baskets), demonstrating the effectiveness of authentic, non-traditional creator profiles.
  - **Fiverr UGC Creator:** The older creator hired via Fiverr ($250 fee) continues to be a consistent long-term winner.
  - **Nutritionist Video:** Slow-burning steady converter (200 views but reliable incremental conversions).
  - **Action:** Decided to turn off the underperforming "born" ad creative and potentially duplicate/tweak winners.

### 4. Organic YouTube Strategy & Defensive Search Presence
- Noted a sponsored video from a creator included a visible YouTube "includes paid promotion" badge.
- Discussed YouTube search behavior: as the world's second-largest search engine, customers actively search Qalzy on YouTube before buying. Having only 1-2 videos leaves search results vulnerable.
- **Defensive Strategy:** Build out a robust library of YouTube videos, shorts, and recipe guides featuring different faces and use-cases to dominate search results.
- Michael committed to setting up an automated job/pipeline to post UGC and recipe shorts to the Qalzy YouTube channel.
- Influencer guideline: instruct creators to feature the product in the very first frame before introducing their faces.

### 5. Food Database Architecture & "Verify with AI" Feature
- Discussed long-term database sustainability and upcoming FatSecret API commercial volume pricing (threshold at 1M calls/year).
- Kostas proposed batch-cleaning the Open Food Facts database using Gemini credits.
- Michael raised concerns about bulk overwriting and hallucination risks, proposing instead a user-facing **"Verify with AI"** button in the mobile app:
  - When a user views an unverified food item or suspects nutritional inaccuracies, tapping the button calls Gemini/AI to verify the macros and provide an instant second opinion.
  - This crowdsources verification while building a proprietary, verified database over time.

### 6. Mobile App Updates & Staging Testing
- Kostas updated the streak display UI on staging to replace the previous design, currently testing to ensure clarity.
- Implemented a fix for the Chinese chatbot bug (hiding China region and reading device location directly).
- Michael to review and test staging build.

### 7. Landing Page A/B Testing & Black Friday Traffic
- Analyzed results from the current Absolutely image test:
  - Variant featuring ~20–25 lifestyle and food images without text overlay caused a massive **37% drop in conversion rate** (91% statistical confidence for the control group winning).
  - Diagnosed that removing informative text overlays and introducing too many uncurated images caused user choice overload and diminished product comprehension.
  - **Black Friday Decision:** Pausing the failing test immediately to protect revenue during peak Black Friday sales, aligning with advisor Hussain's recommendation to freeze unproven experiments during peak promotional windows.
  - Future iteration: curate 10–12 high-impact images pairing clean product visuals with concise benefit copy (e.g., *"26x faster than manual tracking"*, *"Zero daily willpower required"*).

---

## Commitments & Action Items
- [[people/michael-michelis]]: Set up an automated publishing workflow to post UGC, customer clips, and recipe shorts to YouTube.
- [[people/michael-michelis]]: Review and test the staging app build (updated streak UI and Chinese location fix).
- [[people/kostas-koukoravas]]: Pause the -37% failing image A/B test on Absolutely to protect Black Friday conversion rates.
- [[people/kostas-koukoravas]]: Turn off the underperforming "born" ad on Meta Ads Manager.
- [[people/michael-michelis]] & [[people/kostas-koukoravas]]: Proceed with [[people/rory-flanagan]]'s $325 patent representation transfer on Upwork.

---

## Key Decisions
- **Pause PDP Image A/B Test:** Immediately freeze the -37% image test on Absolutely for the duration of Black Friday to maximize revenue.
- **App Food Verification:** Prioritize developing a user-facing "Verify with AI" button over risky automated bulk overwrites of Open Food Facts data.
- **YouTube Defensive Footprint:** Commit to scaling organic YouTube content to establish brand authority and control search intent.
