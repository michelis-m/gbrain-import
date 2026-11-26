---
type: meeting
title: >-
  Qalzy Hardware Sync: New Camera Sensor Bench Testing, Barcode Scanning Failure
  Rate & Latency Optimization
date: '2026-11-25'
---

# Qalzy Hardware Sync: New Camera Sensor Bench Testing, Barcode Scanning Failure Rate & Latency Optimization

**Date:** 2026-11-25  
**Attendees:** [[people/kostas-koukoravas]], [[people/michael-michelis]]  

---

## Summary
Ad-hoc afternoon technical and hardware evaluation session between [[people/kostas-koukoravas]] and [[people/michael-michelis]]. Kostas conducted live bench testing of the new replacement camera sensor prototype module for the Qalzy AI smart scale, comparing its real-world performance against the existing production hardware. The tests revealed severe operational degradation: barcode scan failure rates increased to 60%, image capture latency slowed by ~4x (taking ~12 seconds vs 2–3 seconds), and an excessively wide field of view introduced significant background visual noise. Kostas and Michael formulated an immediate remediation plan with the manufacturing partner ahead of the December production order freeze.

---

## Key Discussion Points

### 1. Barcode Scanning Performance & OCR Accuracy
- [[people/kostas-koukoravas]] conducted live comparative barcode scanning across 5 standard packaged food products:
  - **Old Production Camera:** Successfully scanned and recognized **5 of 5** items (100% success rate).
  - **New Prototype Camera Sensor:** Failed on **3 of 5** items (40% success rate).
- In failure cases, the AI vision/OCR model either failed to detect the barcode boundaries or dropped critical digits (e.g. omitting trailing digits like "1") due to blurred focus and edge distortion.

### 2. Capture Speed & Latency Regression
- **Severe Latency:** Image capture on the new module required **~12 seconds** per shot, compared to **2–3 seconds** on the existing camera.
- **Discrepancy with Manufacturer Claims:** The manufacturing vendor previously assured that the new sensor would only introduce a negligible 1–2 second difference. An 8–10 second penalty is unacceptable for consumer real-time portion logging.
- Kostas noted the delay appears linked to frame-averaging, unoptimized capture routines, or slow sensor clocking in the vendor's demo firmware.

### 3. Field of View (FOV) & Background Clutter
- **Excessive Wide Angle:** The tested prototype features a wide field of view that captures expansive peripheral areas surrounding the weighing platform.
- **AI Recognition False Positives:** Expansive FOV causes the computer vision model to identify and log irrelevant countertop objects, background items, or utensils located near the scale rather than focusing strictly on the plate contents.
- In certain orientations, the wide angle clipped the scale's integrated OLED display boundary.

### 4. Lighting, Glare & LED Exposure
- **LED Flash Distortion:** Activating the hardware LED flash caused severe flare, specular reflection, and complete washout on glossy food packaging and barcode surfaces.
- **Ambient Light Sensitivity:** Operating without the LED resulted in high brightness levels but low micro-contrast, making small typography and barcode lines indistinct.

### 5. Evaluation of Alternative "Narrow-FOV" Camera Module
- Kostas reported that the factory has access to a second, newer camera module option that was initially deprioritized because of a narrower field of view.
- Both founders concluded that a narrower FOV is actually vastly preferable:
  - Prevents extraneous countertop clutter from entering the AI frame.
  - Ensures sharp focus and higher pixel density over the plate and weighing surface.
  - Mirrors user expectations for focused plate scanning.

---

## Action Items & Commitments
- [ ] [[people/kostas-koukoravas]]: Request urgent prototype samples from the hardware manufacturer featuring the alternative narrow-FOV camera module.
- [ ] [[people/kostas-koukoravas]]: Demand manufacturer optimize firmware capture routines and frame acquisition to eliminate the 12-second latency.
- [ ] [[people/kostas-koukoravas]]: Pull firmware repository branch to inspect capture code, adjust sensor exposure/brightness registers, and benchmark custom settings.
- [ ] [[people/michael-michelis]] & [[people/kostas-koukoravas]]: Finalize camera sensor selection prior to locking 5,000-unit BOM and placing the factory order in late December.
