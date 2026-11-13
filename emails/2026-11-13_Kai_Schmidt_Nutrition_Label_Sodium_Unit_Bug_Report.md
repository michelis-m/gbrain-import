---
type: email
title: >-
  Qalzy App Bug: Nutrition Label Scanning Sodium Unit Conversion Error (Grams vs
  Milligrams)
date: '2026-11-13'
---

# Qalzy App Bug: Nutrition Label Scanning Sodium Unit Conversion Error (Grams vs Milligrams)

**Date:** 2026-11-13  
**Parties:** [[people/kai-schmidt]] <kaiziltendorf@gmail.com>, [[people/kostas-koukoravas]] <kostas@qalzy.com>, [[people/michael-michelis]] <michael@qalzy.com>  
**Subject:** Bug Report: Incorrect Sodium Units in Label Scanning & Scale Question  

## Context & Details
- **Bug Discovery:** Qalzy user Kai Schmidt identified a unit conversion bug when scanning nutrition labels with the app camera:
  - The optical character recognition (OCR) correctly reads sodium in grams (e.g., 0.4 g of sodium for 1 g of table salt).
  - However, the raw numerical value is passed directly to Advanced Nutrition Facts—which expects milligrams—without multiplying by 1,000.
  - As a result, the value appears as 0.4 mg instead of 400 mg (1,000x too low), skewing the daily intake summary to 0.0004 g instead of 0.4 g.
  - Verified database entries (green checkmark) are unaffected; the defect is isolated to camera-scanned nutrition labels.
- **Hardware Feedback:** Kai also noted and praised a noticeable responsiveness improvement on the physical scale, observing a significantly shorter button hold time required to turn on the device.
- **Response & Resolution:**
  - Kostas acknowledged the bug, confirmed the engineering team is rolling out a fix, and confirmed that the reduced button power-on latency was an intentional UX enhancement recently pushed via firmware.
  - Michael reviewed label scanning flows to trace whether the issue occurs during food item creation vs scanning.
