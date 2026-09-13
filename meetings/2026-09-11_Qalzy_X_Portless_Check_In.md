# Qalzy X Portless Bi-Weekly Operations Check-In

**Date:** 2026-09-11  
**Attendees:** [[people/harteg-singh]], [[people/chloe-hu]], [[people/kostas-koukoravas]], [[people/michael-michelis]]  
**Companies:** [[companies/portless]], [[companies/qalzy]]

## Summary
Bi-weekly logistics and fulfillment review between Qalzy founders and the [[companies/portless]] team. [[people/chloe-hu]] introduced [[people/harteg-singh]] (VP of Customer Success). The discussion addressed customs tax handling and OpenBorder dissatisfaction, the root cause of recent return-to-sender (RTS) orders (developer data mapping errors during bulk imports), activation of local RTS facilities in the US and the Netherlands, unfulfilled Kickstarter backer orders, and a screen-share audit of specific delayed and reshipped customer orders.

---

## Key Discussion Points

### 1. Executive Introduction & Tax Handling / OpenBorder Discontent
- **Harteg Singh Role:** Introduced as VP of Customer Success at Portless to help resolve high-level merchant escalations.
- **Tax Routing Architecture:** Harteg explained that Portless routes parcel tax remittance through OpenBorder when merchants utilize OpenBorder's tax ID. Alternatively, Portless can utilize its own carrier tax ID if merchants opt out of OpenBorder.
- **OpenBorder Failures:** Kostas expressed intense dissatisfaction with OpenBorder. Despite persistent requests since early July, OpenBorder has failed to reconcile taxes, and their August invoice completely omitted taxes for manually imported European Kickstarter orders.
- **Portless Escalation Offer:** Harteg acknowledged that tax friction is a common pain point and offered Portless's executive assistance. He requested Kostas forward the OpenBorder email thread so Portless can apply carrier-level pressure and assist with tax reconciliation.

### 2. Fulfillment Delivery Errors & Root Cause Analysis
- Over 50 customer orders experienced shipping failures, misdeliveries, or returns over the past month.
- **Root Cause:** Kostas identified that the issue originated from external developer error during Kickstarter bulk data imports, where address, phone, and name fields were incorrectly cross-mapped into fulfillment files without adequate QA.

### 3. Return-to-Sender (RTS) Infrastructure
- Chloe confirmed that Portless RTS hubs are now operational in the United States and the Netherlands.
- Rather than shipping failed deliveries back to China at prohibitive costs, RTS units in these regions are routed to local hubs where they can be restocked, inspected, or redirected.

### 4. Kickstarter Backer Order Resolution
- Approximately 10–20 Kickstarter backers have still not provided valid shipping details, phone numbers, or addresses.
- Kostas proposed issuing a strict deadline notice: backers must provide valid delivery details by the end of the week or their pledge shipment will be closed.

### 5. Live Order Audit & Status Review
- **Order #15:** Reviewed shipping details and confirmed address update.
- **Order #43:** Identified as having been double-shipped previously due to an incomplete address; marked for resolution.
- **Order #53:** Confirmed as successfully delivered / reshipped; marked cleared in the tracking portal.

---

## Commitments & Action Items
- **[[people/kostas-koukoravas]]:** Forward the OpenBorder email correspondence to [[people/harteg-singh]] for Portless escalation.
- **[[people/kostas-koukoravas]]:** Issue an ultimatum communication to the remaining unresponsive Kickstarter backers to finalize unfulfilled pledges.
- **[[people/chloe-hu]] & Portless Fulfillment:** Ensure automated address validation blocks incomplete addresses before carrier dispatch, and manage local RTS processing in the US and Netherlands.

---

## Claim Verification Gate
- *Claim:* Harteg Singh is VP of Customer Success at Portless.  
  *Verification:* Confirmed in raw transcript (`00:00:12` & `00:01:09` - "Harteg is our VP of Customer Success...").
- *Claim:* OpenBorder failed to reconcile taxes on European Kickstarter orders since July.  
  *Verification:* Confirmed in raw transcript (`00:07:57` & `00:08:30` - "I've been begging since the beginning of July... invoice where none of the Kickstarter orders that were manually imported have been taxed...").
- *Claim:* Developer import error caused over 50 order misdeliveries.  
  *Verification:* Confirmed in raw transcript (`00:14:07` & `00:20:38` - "some developer did the import. No one checked the work of the developer. The developer mapped the wrong fields... 50 orders of having money that were just getting delivered to the wrong people...").
- *Claim:* RTS warehouses are operational in the US and Netherlands.  
  *Verification:* Confirmed in raw transcript (`00:24:19` - "So for the US and Netherlands, yes.").
