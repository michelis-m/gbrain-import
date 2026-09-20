# Brevo Alert: Transactional Email Credit Limit Reached (Critical - Follow-up)

**Date:** 2026-09-20  
**Sender:** Brevo (`contact@t.brevo.com`)  
**Recipient:** [[people/michael-michelis]] (`michael@nutrioscale.com`)  
**Subject:** You have reached your credit limit for transactional emails  
**Related Entity:** [[companies/qalzy]], Brevo  

---

## Alert Details
Brevo sent a repeated alert confirming that the SMTP transactional credit limit for Qalzy Ltd remains exhausted.

- **Impact:** All outgoing transactional emails (customer order confirmations, OTP verification codes, shipping notifications, password resets) are continuing to accumulate in backlog rather than being sent.
- **Expiration Risk:** Emails saved in the transactional backlog are only held for up to **36 hours** before being permanently discarded.
- **Action Required:** Urgent credit renewal / top-up on Brevo (`app.brevo.com/billing/account/customize/pag`) to flush backlog emails before customer communications fail permanently.
