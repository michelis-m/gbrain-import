---
type: note
title: 'Redo Returns: Fulfillment Logic Switch & SKU Remapping Bug'
date: '2026-10-21'
---

# Redo Returns: Fulfillment Logic Switch & SKU Remapping Bug

**Date:** 2026-10-21  
**From:** Frank Marino (`frank@redo.com`), [[people/kostas-koukoravas]] (`kostas@qalzy.com`)  
**To:** [[people/kostas-koukoravas]], [[people/michael-michelis]]  
**Company:** Redo, [[companies/qalzy]]  

---

## Overview
Redo implemented the backend fulfillment logic switch for remapped SKUs, but Kostas identified an inventory mapping discrepancy during morning return processing.

## Details
- **Warehouse Flow Updated:** Frank Marino confirmed the warehouse processing logic was updated so that all "Like New" and "Cosmetic Damage" returns stock to the remapped outlet SKU going forward (15 items pending). Requested Qalzy accept updated permissions in Redo.
- **Mapping Bug Reported:** Kostas processed two returns and discovered they were still mapping to old SKUs on the `returns -> managed returns -> inventory` page. Reported the issue to Frank for engineering review.
- **Individual Return Inspections:**
  - Return #2085: Kostas queried a visible mark on the camera arm to determine if it is a scratch or lighting reflection.
  - Return #2231: Kostas processed the return after Sofie confirmed white food residue on the face of the scale from poor wiping.
