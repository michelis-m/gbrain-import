---
type: company
title: "Portless"
aliases:
  - portless.com
  - Portless Portal
  - support@portless.com
  - implementations@portless.com
  - info@portless.com
  - inbounding@portless.com
---

# Portless

Qalzy's cross-border fulfilment provider, shipping direct-to-consumer from warehouses in China. Qalzy's inventory is inbounded to a non-bonded warehouse in Shenzhen for inspection before moving to a bonded facility, and orders flow from Shopify into Portless' WMS through Pipe17 (`Portless & Qalzy Onboarding Recap and Next Steps`).

## Current state

- Onboarding kickoff call was 3 June 2026; go-live was gated on inventory arriving and being inbounded, and slipped repeatedly through July (`Portless & Qalzy Onboarding Recap and Next Steps`, `Expecting to send Qalzy White tomorrow`).
- Named contacts in the corpus: Shane Buckley (shane@, runs the relationship and escalates internally), Wesley (bonded inbounding and supplier coordination), Jake and Jeff (implementations@), Chloe (chloe@, ran the Greek delivery investigation), Craig (craig@), Aeri (bonded inbound registration), Pamela (implementation), and support agents Ryan, Jessa, Tina ("Portless Leadership"), Janeth, Kristine, Edlyn, Carlo and Tamz.
- Customer-facing systems: the Portless Portal at portal.portless.com (Kostas and Michael both have logins) and a support ticket queue. Pipe17 is managed entirely by Portless; Qalzy does not need access.
- Compliance surface Qalzy had to satisfy: Brand Authorization Form, Chinese Supplier Disclosure (one Airtable form per supplier, including accessory suppliers), Factory MID per manufacturer, transport safety certificates, and a packing and labelling SOP.
- Operational constraints stated by Portless: recipient names must not exceed 21 characters and cannot contain numbers; no shipping to APO/military addresses; some routes are DHL-only and require declared value of at least $175 / €105; inbound to bonded takes roughly 48 hours after receipt.
- A pattern of self-inflicted integration failures has run through the relationship: manually CSV-imported orders were silently auto-held by a new automation Portless' own team did not know about; the Pipe17 routing rule that sends orders to the WMS was never enabled; and on manual imports the recipient phone number was mis-mapped into the customer name field, stripping contact details from orders (`[URGENT] Qalzy orders on hold`, `Problems with multiple orders in Greece`).
- That missing-phone-number defect is the root cause of failed deliveries across Greece and Finland, and Chloe acknowledged it as "a miss on our side" on 12 August, committing to cross-check all manually created orders, ship and deliver promptly, and give regular updates on exceptions.
- Additional live defects Qalzy has reported: last-mile tracking showing "delivered" when first-mile shows otherwise and the customer has nothing (Greece and Hong Kong), a parcel delivered to the wrong recipient, missing items in an order, and last-mile tracking numbers that do not resolve on the carrier's own site.
- On 14 August, Tina from Portless leadership produced a shared "Qalzy - Order Issue Tracker" covering the 13 orders raised so far, with status, issue, actions taken and next steps, and invited Qalzy to add more.
- Carriers seen in the Qalzy flow: DPD and ACS in Greece, Matkahuolto in Finland, DHL for restricted routes.

## Open threads

- `Problems with multiple orders in Greece` — PBID007766338 was logged as refused by the recipient, but Michael phoned him on 14 August and he denies refusing; Portless has been asked to update the phone number and redeliver. PBID007753148 is still pending self-pickup.
- `Order PBID007833592` — reported 13 August as showing delivered with the customer having received nothing. No reply in the thread.
- `URGENT: Return to sender - Multiple issues with orders without contact info` — PBID007759786 appears to have been delivered to the recipient of a different order; retrieval requested 13 August, unanswered.
- `Customs Issues | Qalzy` — PBID007753408 under routine customs inspection since 8 August with no release date.
- Kostas' 12 August request for working carrier tracking numbers and contact details for every carrier used, not just DPD, is not answered in the corpus.
- Michael's standing request that Portless proactively surface any other orders failing for missing phone numbers so Qalzy can warn those customers is acknowledged but not yet delivered.

## Pricing & Duties

- **US Duties & Tariffs:** Portless collects and bills US duties directly.
  - Scale standalone: $3.42 per Qalzy AI scale.
  - Blended: $6.16 per order ($3.42 × 1.8 units/order average attach rate).
  - Note: This supersedes earlier preliminary assumptions that US shipments were under de minimis threshold and tax/duty-free.

## Gaps

- Specific freight contract terms, SLA, or volume commitments beyond verified per-unit US duties ($3.42 scale, $6.16 blended).
- Daily shipping capacity. Kostas asked twice ("how many orders can you ship per day?") and was never given a number.
- Where Portless is headquartered and how its US, Chinese and support operations are organised.
- Whether a formal account manager is assigned. Shane behaves like the commercial owner but is never described as one.
- Whether the manual-import phone-mapping defect has actually been fixed, versus mitigated by manual cross-checking.
- Whether any credits, refunds or remediation were offered for the delivery failures.

## See also

- [[companies/qalzy]]
- [[people/kostas-koukoravas]]
- [[people/michael]]

## Referenced by

- Referenced in [Portless & Qalzy Onboarding Recap and Next Steps](../emails/2026-07-20-portless-qalzy-onboarding-recap-and-next-steps)
- Referenced in [[URGENT] Qalzy orders on hold](../emails/2026-07-27-urgent-qalzy-orders-on-hold)
- Referenced in [Portless RTS Order: Customer Tax ID Required (PBID007771348-1)](../emails/2026-09-15-portless-rts-customs-tax-id-pbid007771348-1)
- Referenced in [Portless Invoices 1085260901 & 1085260825 Marked Paid](../emails/2026-09-12-portless-invoices-paid-1085260901-1085260825)
- Referenced in [Action Needed | QALZY | Shipment Issue | #PBID007771351](../emails/2026-08-08-action-needed-qalzy-shipment-issue-pbid007771351)
- Referenced in [Invitation: Portless sync @ Wed 27 May 2026 1pm - 1:25pm (GMT+3) (michael@qalzy.com)](../emails/2026-05-27-invitation-portless-sync-wed-27-may-2026-1pm-1-25pm-gmt-3-mi)
- Referenced in [OpenBorder: Kickstarter Order Tax Remittance & VAT Reconciliation](../emails/2026-09-10-openborder-kickstarter-vat-tax-update)
- Referenced in [ACTION NEEDED | QALZY | Shipment & Delivery Issues](../emails/2026-08-10-action-needed-qalzy-shipment-delivery-issues)
- Referenced in [Expecting to send Qalzy White tomorrow](../emails/2026-07-20-expecting-to-send-qalzy-white-tomorrow)
- Referenced in [Re: Can I ask about orders PBID007833471, PBID007771348, PBID007753301,...](../emails/2026-08-12-can-i-ask-about-orders-pbid007833471-pbid007771348-pbid00775)
- Referenced in [Portless Customs Issue: Order PBID007752929 Returning to Overseas Warehouse](../emails/2026-09-13-portless-customs-order-return-pbid007752929)
- Referenced in [ACTION NEEDED | QALZY | Shipment Issues](../emails/2026-08-14-action-needed-qalzy-shipment-issues)
- Referenced in [Portless Overdue Invoice #1085260908](../emails/2026-09-15-portless-overdue-invoice-1085260908)
- Referenced in [Portless Orders Status and Account Transition](../emails/2026-09-16-portless-orders-status-and-account-transition)
- Referenced in [Portless Support Updates: Order Reshipment & Wrong Address Escalation](../emails/2026-09-07-portless-order-reshipment-and-address-issues)
- Referenced in [Portless Notice: China Golden Week Deadlines & Inventory Planning](../emails/2026-09-05-portless-golden-week-inventory-replenishment)
- Referenced in [Problems with multiple orders in Greece](../emails/2026-08-14-problems-with-multiple-orders-in-greece)
- Referenced in [Order PBID007833592](../emails/2026-08-13-order-pbid007833592)
- Referenced in [URGENT: Return to sender - Multiple issues with orders without contact info](../emails/2026-08-13-urgent-return-to-sender-multiple-issues-with-orders-without)
- Referenced in [Portless: RTS Reshipment Confirmation & Kickstarter Batch 8](../emails/2026-09-10-portless-order-reshipment-and-kickstarter-batch8)
- Referenced in [Customs Issues | Qalzy](../emails/2026-08-13-customs-issues-qalzy)
- Referenced in [ACTION NEEDED | QALZY | Delivery Issues](../emails/2026-08-14-action-needed-qalzy-delivery-issues)
- Referenced in [Chloe Hu](../people/chloe-hu)
- Referenced in [Harteg Singh](../people/harteg-singh)
- Referenced in [Ryan Torreta](../people/ryan-torreta)
- Referenced in [Qalzy X Portless Bi-Weekly Operations Check-In](../meetings/2026-09-11_Qalzy_X_Portless_Check_In)
- Referenced in [OpenBorder](../companies/openborder)
