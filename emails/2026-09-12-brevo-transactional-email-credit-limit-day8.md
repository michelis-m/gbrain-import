# Brevo Transactional Email Credit Limit Depleted (Day 8)

**Date:** 2026-09-12 16:28 UTC  
**From:** Brevo <contact@t.brevo.com>  
**To:** [[people/michael-michelis]] <michael@nutrioscale.com>  
**Subject:** You have reached your credit limit for transactional emails  
**Tags:** [[companies/qalzy]], [[tags/infrastructure]], [[tags/urgent]]

## Summary
Brevo sent an automated alert notifying that the monthly transactional SMTP credit limit for the **Qalzy Ltd** account has been reached. 

## Key Details
- **Impact:** New transactional emails (order confirmations, customer support notifications, account alerts) are not delivering immediately and are diverted to the queue backlog.
- **Expiration Risk:** Messages stored in the backlog remain on the transactional platform for up to **36 hours** before they expire and are permanently dropped.
- **Action Required:** Immediate top-up of transactional email credits via the Brevo billing dashboard (`https://app.brevo.com/billing/account/customize/pag`).
