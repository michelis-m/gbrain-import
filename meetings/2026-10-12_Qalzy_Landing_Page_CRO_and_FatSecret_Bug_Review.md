---
type: meeting
title: >-
  Qalzy Operations & Landing Page CRO: FatSecret Bug Resolution, Game-Style
  Onboarding, and Figma Wireframes
date: '2026-10-12'
---

# Qalzy Operations & Landing Page CRO: FatSecret Bug Resolution, Game-Style Onboarding, and Figma Wireframes

**Date:** 2026-10-12  
**Attendees:** [[people/michael-michelis]], [[people/kostas-koukoravas]]  
**Companies:** [[companies/qalzy]]  

---

## Summary
Operational debrief between Michael Michelis and Kostas Koukoravas following the wholesale call with Mahdi Aldashti. Discussions focused on root-causing the FatSecret database scaling bug, designing a gamified, locked onboarding tutorial inspired by modern video game UX to curb product returns, refining landing page sections in Figma (Convenience vs. Precision modes, clinical trial data, and 3-month timeline), and evaluating AI video editing and influencer scripts.

---

## Key Discussion Points

### 1. FatSecret Database Scaling Bug Root Cause
- **Issue Analysis:** Michael confirmed the root cause of the 1,000-calorie fried potatoes bug identified by Mahdi: FatSecret lacked a 1-gram baseline entry and only had a 35g serving entry, causing a bad multiplication scaling bug.
- **Resolution:** Michael deployed a backend fix to properly handle non-standard database serving increments.

### 2. Gamified In-App Onboarding & Return Reduction
- **User Expectation Mismatch:** The primary driver of early returns is users expecting "magic" rather than understanding that camera-based AI requires visible ingredients and baseline calibration.
- **Game UX Inspiration:** Discussed how complex video games (e.g. World of Warcraft) gate full gameplay behind mandatory tutorial completion to ensure players master mechanics.
- **Locked First-Scan Tutorial:** Propose locking the scale/app interface upon first unboxing until the user completes an interactive guided scan (e.g., scan a piece of fruit, scan a barcode).
- **Educational Reality Quiz:** Introduce a brief interactive quiz showing real food photos (*"Can the AI see hidden oil in this sauce? Can you tell if this is boiled or fried? If you can't tell, the AI can't either"*), setting honest expectations and establishing credibility.

### 3. Figma Landing Page Redesign
- **Built for Speed and Accuracy:** Introducing two distinct ways to log meals without framing them as mutually exclusive:
  - **Convenience Mode:** One-tap plate scan identifying multiple visible ingredients simultaneously.
  - **Precision Mode:** Ingredient-by-ingredient logging on the scale for maximum macro accuracy.
- **Clinical Data & Authority Endorsement:** Incorporating a clinical nutrition study section and professional endorsement to build scientific authority.
- **Outcome Timeline:** Adding a 3-month progressive benefits section (*"Month 1: Effortless habit formation, Month 2: Visible body composition changes, Month 3: Sustained metabolic transformation"*).
- **Autoplay Video Micro-demos:** Embedding muted autoplay video loops demonstrating real meals on scroll.
- **SEO Keyword Targeting:** Evaluating organic search volume across terms: *"AI kitchen scale"*, *"AI nutrition scale"*, *"smart food scale"*, and *"scale that counts calories"*.

### 4. Creative Production & Influencer Scripts
- **AI Video Subtitle Editing:** Critiqued automated subtitle generation on recent podcast clips that failed to edit out verbal filler words (*"um"*, *"ah"*).
- **Short-form Educational Content:** Planning fast-turnaround AI-assisted educational videos on calorie deficits to schedule across social channels via Buffer.
- **Influencer Scripts:** Reviewing influencer video briefs and scripts submitted by Rolandas (Blazer agency).

---

## Action Items
- [ ] **Michael Michelis:** Finalize Figma wireframes for the Convenience vs. Precision and 3-Month Timeline sections.
- [ ] **Michael Michelis:** Draft UX specifications for the locked first-scan onboarding tutorial flow.
- [ ] **Kostas Koukoravas:** Review and provide feedback on Rolandas's influencer video scripts.
