# Brevo Alert: Transactional Email Credit Limit Reached (Day 10)

**Date:** 2026-09-14 16:33 UTC  
**From:** Brevo <contact@t.brevo.com>  
**To:** michael@nutrioscale.com  
**Subject:** You have reached your credit limit for transactional emails  

## Summary
Brevo issued an alert notifying that the SMTP transactional email credit limit for account **Qalzy Ltd** has been exhausted. 

## Key Details & Risks
- Outbound transactional emails (order confirmations, password resets, customer notifications) cannot be dispatched immediately.
- Undelivered emails are temporarily queued in Brevo's backlog.
- **Critical Expiration Window:** Backlog emails are stored on the transactional platform for a maximum of **36 hours** before being permanently dropped.
- **Required Action:** Replenish SMTP credits immediately via the Brevo billing portal (`https://app.brevo.com/billing/account/customize/pag`) to trigger backlog delivery.
