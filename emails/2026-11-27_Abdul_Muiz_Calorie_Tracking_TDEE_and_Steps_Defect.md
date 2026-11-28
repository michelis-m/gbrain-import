---
type: email
title: 'Abdul Muiz: In-App Calorie Tracking & TDEE Step Goal Calculation Defect'
date: '2026-11-27'
from: Abdul Muiz <abdulmuiza50@gmail.com>
to: michael@qalzy.com
subject: Weird calorie tracking issue
---

# Abdul Muiz: In-App Calorie Tracking & TDEE Step Goal Calculation Defect

**Date:** 2026-11-27  
**From:** [[people/abdul-muiz]] (`abdulmuiza50@gmail.com`)  
**To:** [[people/michael-michelis]] (`michael@qalzy.com`)  
**Subject:** Weird calorie tracking issue  

---

## 1. Summary of Bug Report
- User [[people/abdul-muiz]] reported an ongoing calculation bug in the Qalzy iOS mobile app affecting daily calorie budgeting when syncing activity data from Apple Health.
- User profile parameters: Height: 5'10", Weight: 88.4 kg, recommended base TDEE: 1,874 kcal. Weight updates automatically via Apple Health linked to *Happy Scale*.

## 2. Defect Breakdown
- **Intended Behavior:**
  - With "including steps in daily calorie goal" enabled, tracked food calories fill the green portion of the calorie ring toward the 1,874 kcal goal.
  - Active step calories increase the yellow exercise allowance on the ring, enabling earned calories for snacks while maintaining the baseline deficit.
- **Observed Glitch:**
  - When the "including steps in daily calorie goal" toggle is enabled, step burn calories are added directly onto the base TDEE itself (e.g., displaying 2,429 kcal instead of 1,874 kcal).
  - Concurrently, the app continues to subtract step calories from the daily food goal, causing a conflicting 100–200 kcal deficit discrepancy on the diary dashboard.
- **Troubleshooting Steps Already Attempted:**
  - Uninstalled and reinstalled the application.
  - Restricted Apple Health permissions to step data only.
  - Manually input weight values instead of syncing via third-party apps. None resolved the bug.
- User expressed enthusiasm for Qalzy but noted this bug has temporarily halted his tracking.
