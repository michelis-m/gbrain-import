---
type: note
title: >-
  Redo Returns: Urgent Escalation on Used Returns Shipped to DTC Customers &
  Grading SOP Update
date: '2026-11-18'
---

# Redo Returns: Urgent Escalation on Used Returns Shipped to DTC Customers & Grading SOP Update

**Date:** 2026-11-18  
**Participants:** [[people/michael-michelis]], [[people/frank-marino]]  
**Thread Subject:** Re: URGENT: Used returns being graded "Factory Sealed" & shipped to new Qalzy customers (#2742, #2744, #2790)  

---

## Context
Following a serious customer complaint (Order #2742) reporting a returned scale arrived with food residue and a missing USB cable, Michael investigated warehouse fulfillments and discovered three DTC orders (#2742, #2744, and #2790) were fulfilled with used returns from Redo's SLC warehouse. Michael escalated urgently to Frank Marino to halt all "Factory Sealed" restocking into sellable DTC SKUs.

## Key Updates & Details
- **Root Cause Identified:**
  - Redo's SLC warehouse graded returns `rtrn_1YDVC8W6JT3JM`, `rtrn_5ABNS9GA9D755`, and `rtrn_5MSHF4PS7MZS6` as "Factory Sealed" with outcome "Restock", despite customer return reasons stating "AI Food Recognition / Scanning Inaccuracy" (meaning scales were opened and used).
  - Units automatically restocked under sellable SKU `QZ-01-WHT` instead of routing to `QZ-01-WHT-REDO`.
- **Frank Marino's Response & Warehouse Adjustments:**
  - Apologized for the breakdown and confirmed immediate protocol changes:
    - **Grading Freeze:** Going forward, every returned scale will be graded as opened until next steps are formally finalized, ensuring zero returns restock into `QZ-01-WHT` or `QZ-01-BLK`.
    - **American Bass Units:** Clarified that the three `QZ-01-WHT` units in the American Bass holding location were graded *Cosmetic Damage* (two units) and *Open Packaging - Like New* (one unit from orders #2175, #2365, #2567). Acknowledged they failed to automatically transfer to `QZ-01-WHT-REDO` as intended; following up with warehouse operations to move them immediately.
    - **Return rtrn_7WJBAEZY5BZVM:** Stated no unit was received tied to that return; noted order #2118 arrived under a separate return ID, was graded *Open Packaging - Like New*, and was moved to `QZ-01-WHT-REDO` on Nov 11.
  - **Proposed SOP Resolution:**
    - Redo warehouse instructions previously lacked explicit Grade A rules (full intact factory seal, no resealed packaging, downgrade to Grade B on any doubt).
    - Frank proposed either permanently disabling "Factory Sealed" restocking, or embedding strict visual SOP instructions (including photo examples of sealed boxes) directly into the warehouse operator workflow to safely allow true unopened restocks.
