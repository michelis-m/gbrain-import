# Brevo Transactional Email Credit Limit Exceeded

**Date:** 2026-09-18  
**Sender:** Brevo (contact@t.brevo.com)  
**Recipient:** michael@nutrioscale.com / Qalzy Ltd  
**Subject:** You have reached your credit limit for transactional emails  
**Related Entity:** [[companies/qalzy]], Brevo  

---

## Summary
Brevo issued an operational service alert notifying Qalzy Ltd that the credit limit for the Brevo SMTP transactional account has been reached.

### Impact & Urgent Action
- **Service Degradation:** All outbound transactional emails (customer order confirmations, tracking notices, password reset links) are now suspended and queued in a temporary backlog.
- **Data Loss Risk:** Emails held in the Brevo backlog expire and are permanently deleted after **36 hours** if account credits are not topped up.
- **Action Required:** Immediate purchase of additional SMTP transactional email credits via the Brevo billing dashboard.
