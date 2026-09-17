# Brevo Transactional Email Credit Limit Exhausted (Day 12 Alert)

**Date:** 2026-09-16  
**From:** Brevo (`contact@t.brevo.com`)  
**To:** `michael@nutrioscale.com`  
**Subject:** You have reached your credit limit for transactional emails  
**Related Entity:** [[companies/qalzy]], Brevo SMTP  

---

## Summary & Impact
Brevo notified Qalzy that the credit limit for its Brevo SMTP account (`Qalzy Ltd`) remains completely exhausted. 

### Critical Consequences
- All new outbound transactional emails (such as Shopify customer order confirmations, password reset emails, shipping notices, and customer notifications) are being deferred to a backlog queue.
- Backlogged emails are retained on the transactional platform for a maximum of **36 hours** before expiring and being permanently dropped.
- This alert has persisted for 12 consecutive days, creating an urgent customer support and order fulfillment risk.

### Required Action
- Refill transactional email credits via the Brevo billing dashboard (`https://app.brevo.com/billing/account/customize/pag`).
