---
type: meeting
title: >-
  Intelistyle Standup & Qalzy Founders Sync: Redo Used Returns Crisis, App Label
  Scan Bug, Patent Attorney & Court Prep
date: '2026-11-18'
---

# Intelistyle Standup & Qalzy Founders Sync: Redo Used Returns Crisis, App Label Scan Bug, Patent Attorney & Court Prep

**Date:** 2026-11-18  
**Attendees:** [[people/john-karunungan]], [[people/kostas-koukoravas]], [[people/michael-michelis]]  

---

## Summary
Morning standup opening with Intelistyle catalog processing, followed by an operational crisis and strategy sync between Qalzy co-founders. Key issues addressed included Redo Returns mistakenly grading opened/used customer returns as "Factory Sealed" and fulfilling them to new DTC customers, app UX fixes for nutrition label scanning vs barcode detection, final court filings and litigation preparation ahead of Kostas's Friday final hearing at the Royal Courts of Justice, selecting a USPTO patent attorney for issuance follow-up, and travel logistics for India and CES 2027.

---

## Key Discussion Points

### 1. Intelistyle Catalog Operations Standup
- [[people/john-karunungan]] reported completing image quality checks for De Cuba and De Cuba "Shop the Look."
- Started the day on Guess processing new arrivals, followed by catalog re-approvals.

### 2. Redo Returns: Used Scales Shipped to New Customers Crisis
- Michael flagged a severe operational error with Redo: 6 returned scales have shipped out from Redo's SLC warehouse to new DTC paying customers over the past 30 days, including recent customer orders (#2742, #2744, #2790) that received dirty units with food residue.
- [[people/kostas-koukoravas]] and [[people/michael-michelis]] discussed financial and customer experience impact:
  - Reshipping and processing a full return costs ~$30-$60 in two-way shipping, warehouse fees, inventory write-off, and heavy customer service overhead.
  - Agreed strategy for affected customers: Offer a $50 partial refund where acceptable, or issue an immediate brand-new replacement from primary inventory to preserve brand goodwill.
  - Michael sent an urgent escalation to [[people/frank-marino]] demanding an immediate freeze on "Factory Sealed" grading so that all returned scales route exclusively to refurbished `-REDO` creator SKUs.

### 3. Qalzy Scale & App: "Scan Label" Bug & Firmware Rollout
- Michael reported testing the app on rice pudding (ρυζόγαλο) and observed that scanning nutrition facts returned an `unknown` error.
- Kostas diagnosed the root cause: when a nutrition label is physically positioned close to a barcode, the computer vision algorithm detects the barcode first, fails to parse it, and outputs `unknown`.
- **Agreed UX Fix:** Update the app flow so that when a nutrition label is detected near a barcode, the interface explicitly prompts `Scan label` rather than failing with `unknown`.
- **Firmware Release:** Discussed releasing the v22 firmware/app update directly to production rather than keeping it restricted to a single beta tester, as Kostas has tested it daily on hardware without stability issues.

### 4. Litigation & Final Hearing Preparation (Royal Courts of Justice)
- Kostas provided an update on his legal proceedings ahead of the final hearing this Friday:
  - Opposing counsel dumped a massive batch of late documents just three days prior to the trial, including their witness statement (which was due three weeks earlier) and unilateral mortgage capacity assessments.
  - Kostas and his barrister must urgently redraft and merge their position statement before court submission deadlines tomorrow.
  - Rebutted false claims in opposing statements:
    - Opposing party claimed Kostas leads a "lavish lifestyle" and made vacation trips to Thailand (passport records confirm he has never set foot in Thailand; travel was strictly business visits to hardware manufacturing factories in Dongguan, China).
    - Opposing party placed a hypothetical £2.5M valuation on Qalzy and alleged £250k–£300k in withheld corporate funds, whereas actual bank balances stand at ~£70k in one entity and -£50k in the other.
    - Opposing party requested £4,800/month net personal maintenance while claiming to "tighten belts," along with new demands for furniture purchases and child medical/extracurricular subsidies.
  - Kostas is working late with his legal team to ensure their position statement clearly refutes these assertions before the judge.

### 5. USPTO Patent Attorney Selection
- Michael reviewed proposals on Upwork for a USPTO-registered patent attorney/agent to file Form PTO/AIA/82 and manage patent issuance follow-up.
- Found a highly rated practitioner (4.9 rating, $200 fixed fee) with prior USPTO experience to handle the filing cost-effectively.

### 6. India Trip & Personal Logistics
- Kostas outlined upcoming personal travel to India departing December 4 (traveling Delhi -> Bangalore -> Kerala), following the court-ordered tenancy agreement execution deadline on December 3. Plans to use AI tools to quickly finalize internal domestic flights and itinerary bookings.

---

## Action Items & Commitments
- [ ] [[people/john-karunungan]]: Complete Guess new arrivals and continue catalog re-approvals.
- [ ] [[people/michael-michelis]]: Monitor Redo warehouse response from [[people/frank-marino]] and handle outreach/refunds ($50 partial refund or replacement) for affected customers (#2742, #2744, #2790).
- [ ] [[people/kostas-koukoravas]]: Implement app fix changing `unknown` to `Scan label` when nutrition labels are detected near barcodes.
- [ ] [[people/kostas-koukoravas]]: Finalize and merge position statement with barrister ahead of tomorrow's court filing deadline for Friday's RCJ hearing.
- [ ] [[people/michael-michelis]]: Contract the selected $200 Upwork patent attorney for Form PTO/AIA/82 submission.
- [ ] [[people/kostas-koukoravas]]: Push v22 scale firmware/app build to general availability.
