---
type: note
title: 'Klaviyo: Profile Usage Limit Exceeded (Sending Suspended)'
date: '2026-11-01'
---

# Klaviyo: Profile Usage Limit Exceeded (Sending Suspended)

**Date:** 2026-11-01  
**Recipient:** [[people/michael-michelis]]  
**Platform:** [[companies/klaviyo]], [[companies/qalzy]]  

---

## 1. Summary
Klaviyo system notifications issued an account usage alert for Qalzy (Account ID: `SSw9fB`). The account has severely exceeded its free-tier email profile limit, reaching **953.2% capacity**.

## 2. Operational Impact
- **Outbound Email Blocked:** No automated flow emails (e.g., Abandoned Cart, Welcome Series, Order Nurture) or manual campaigns can be dispatched.
- **Flow Activation Blocked:** New or modified automated flows cannot be published live.
- **Billing State:** No unexpected automated charges incurred (account remains on free tier).

## 3. Required Action
To restore sending capabilities, Qalzy must either:
1. Prune/suppress unengaged and unsubscribed profiles to bring active profiles below the free cap.
2. Upgrade to an appropriate paid tier via Klaviyo billing settings (`https://www.klaviyo.com/settings/billing/overview`).
