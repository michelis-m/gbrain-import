# Redo Returns x Qalzy: Re-Fulfillment Setup & Warehouse Routing Resolution

**Date:** 2026-09-09  
**Attendees:** [[people/michael-michelis]], [[people/konnor-kah]] (Redo Account Manager)  
**Mentioned:** [[people/frank-marino]] (Redo Shipping Specialist), [[people/kostas-koukoravas]], Linus (former Redo contact)  
**Companies:** [[companies/qalzy]], [[companies/redo]]

## Summary
Urgent technical alignment call between [[people/michael-michelis]] and [[people/konnor-kah]] (Redo Account Manager) to resolve a critical reverse-logistics failure that has blocked customer returns and re-fulfillment since August 1, 2026.

## Key Discussion Points

### 1. Root Cause of Stalled Returns
- Qalzy customers have been unable to process returns and receive replacements because Shopify fulfillment locations and shipping profiles were never properly mapped to Redo's reverse-logistics hubs.
- Konnor apologized for the delay, explaining that Qalzy's account fell through the cracks during the recent corporate merger between Redo and Return Bear, combined with the departure of their former onboarding engineer Linus.

### 2. Required Technical Configuration in Shopify
- **Fulfillment Locations:** Added Redo inspection warehouses as active fulfillment locations:
  - **SLC:** Salt Lake City, Utah (handling US domestic return inspection and re-shipments)
  - **Ontario:** Handling Canadian/regional routing
  - **RMR:** Reverse logistics return inspection centers
- **Inventory & Barcode Mapping:** Once an item is inspected at SLC or Ontario, Redo's system adds the unit to available stock under the matching SKU/barcode.
- **Fulfillment Priority Routing:** Shopify routing rules must prioritize shipping from the local return warehouse if inventory exists near the purchasing customer.

### 3. Execution Plan
- Michael shared screens and verified Shopify admin permissions with Konnor.
- Konnor and Redo shipping specialist [[people/frank-marino]] will access Qalzy's Shopify backend directly to finalize the shipping profiles and routing rules today.
- Konnor committed to sending a confirmation email by end of day detailing the exact changes made and verifying that the single SLC test return unit is recognized in Shopify inventory.

## Commitments & Action Items
- **Konnor Kah & Frank Marino (Redo):** Configure Shopify shipping profiles and warehouse routing today; test single SLC inventory unit; send confirmation email to Michael and Kostas by end of day.
- **Michael Michelis & Kostas Koukoravas:** Verify test return unit is visible in Shopify stock and confirm customer returns portal is active.

## Claim Verification Gate
- *Claim:* Issue has persisted since August 1 due to Redo/Return Bear merger and Linus's departure.  
  *Verification:* Confirmed in raw transcript (`00:03:01` - "Linus... moved on to another company... apologize for the misstep", and `00:07:37` - "We've been trying to do this since 1st of August").
- *Claim:* Locations added include SLC, Ontario, and RMR abbreviations.  
  *Verification:* Confirmed in raw transcript (`00:03:01` - "The RMR abbreviation looks that way... Ontario looks right", and `00:06:08` - "we have one at SLC").
