---
type: person
title: Kai Schmidt
---

# Kai Schmidt

**Role:** Qalzy User / Community Contributor  
**Email:** `kaiziltendorf@gmail.com`  
**Context:** Power user of the [[companies/qalzy]] smart food scale and nutrition app who reported a critical OCR unit conversion bug.

## Facts & Notes
- On 2026-11-13, reported a significant bug in automatic nutrition label scanning via email:
  - The OCR image recognition computes sodium values in grams (e.g., 0.4 g for 1 g salt), but passes the raw numerical value into the Advanced Nutrition Facts screen where milligrams are expected.
  - This results in displayed sodium values being 1,000 times too low (e.g., 0.4 mg instead of 400 mg, and 0.0004 g daily summary instead of 0.4 g).
  - Verified that manual database entries (green checkmark) are unaffected; bug is isolated to camera-scanned nutrition labels.
- Noted and praised a recent firmware improvement: the scale now turns on with a significantly shorter button hold time.
- [[people/kostas-koukoravas]] confirmed the engineering team is preparing a fix and validated that the shorter power button latency was an intentional UX improvement rolled out based on customer feedback.
