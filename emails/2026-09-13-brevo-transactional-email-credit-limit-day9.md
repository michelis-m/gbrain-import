# Brevo Transactional Email Credit Limit Reached (Day 9 Alert)

**Date:** 2026-09-13 16:32 UTC  
**From:** Brevo <contact@t.brevo.com>  
**To:** [[people/michael-michelis]] <michael@nutrioscale.com>  
**Subject:** You have reached your credit limit for transactional emails  
**Tags:** [[companies/qalzy]], [[tags/operations]], [[tags/infrastructure]], [[tags/urgent]]

## Summary
Brevo notified Qalzy that the credit limit for its Brevo SMTP account (`Qalzy Ltd`) has been exhausted.

## Impact & Urgent Action Required
- Any new transactional emails (customer order confirmations, password resets, shipping updates) are diverted to the backlog queue.
- Backlog messages are retained for a maximum of 36 hours before expiring permanently.
- **Action Required:** Immediate credit renewal / plan upgrade via the Brevo billing portal (`https://app.brevo.com/billing/account/customize/pag`) to flush backlog emails before they drop.
