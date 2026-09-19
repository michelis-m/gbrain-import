# Brevo Alert: Transactional Email Credit Limit Reached (Critical)

**Date:** 2026-09-19  
**Sender:** Brevo (`contact@t.brevo.com`)  
**Recipient:** [[people/michael-michelis]] (`michael@nutrioscale.com`)  
**Subject:** You have reached your credit limit for transactional emails  
**Related Entity:** [[companies/qalzy]], Brevo  

---

## Alert Details
Brevo issued an alert notifying that the SMTP credit limit for Qalzy Ltd has been reached.

- **Impact:** All newly generated transactional emails (order confirmations, customer one-time passwords/OTPs, shipping updates, password resets) are currently blocked from immediate delivery and queued into backlog.
- **Expiration Risk:** Emails in the backlog are retained on Brevo's transactional platform for up to **36 hours** before expiring permanently.
- **Action Required:** Renew/top up SMTP transactional credits in Brevo billing (`app.brevo.com/billing/account/customize/pag`) to trigger backlog retry and resume standard delivery.
