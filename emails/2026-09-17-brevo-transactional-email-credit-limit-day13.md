# Brevo Transactional Email Credit Limit Exhausted (Day 13 Alert)

**Date:** 2026-09-17  
**From:** Brevo (`contact@t.brevo.com`)  
**To:** `michael@nutrioscale.com`  
**Subject:** You have reached your credit limit for transactional emails  
**Related Entity:** [[companies/qalzy]], Brevo SMTP  

---

## Summary & Impact
Brevo notified Qalzy that the credit limit for its Brevo SMTP account (`Qalzy Ltd`) remains exhausted. 

### Critical Consequences
- All new outbound transactional emails (customer order confirmations, password reset emails, shipping notices, and account notifications) are trapped in the backlog queue.
- Backlogged emails are retained on the transactional platform for a maximum of **36 hours** before expiring and being permanently dropped.
- This alert has now persisted for 13 consecutive days, creating an acute operational and customer support failure risk.

### Required Action
- Top up transactional email credits immediately via the Brevo billing dashboard (`https://app.brevo.com/billing/account/customize/pag`).
