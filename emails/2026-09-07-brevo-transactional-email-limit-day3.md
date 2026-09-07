# Brevo SMTP Transactional Credit Limit Alert (Day 3)

- **Date:** 2026-09-07 16:14 UTC
- **From:** Brevo <contact@t.brevo.com>
- **To:** <michael@nutrioscale.com>
- **Subject:** You have reached your credit limit for transactional emails
- **Entities:** [[companies/qalzy]], Brevo

## Critical Operational Alert
- **Third Consecutive Day:** Brevo issued another warning that the transactional SMTP credit limit for Qalzy Ltd remains completely exhausted.
- **Data Loss / Delivery Failure Risk:** New outgoing transactional emails (order confirmations, shipping notifications, password resets, onboarding emails) are diverted to a temporary backlog.
- **Backlog Expiration:** Backlog retention is strictly capped at **36 hours**. Emails queued on September 5 and early September 6 have begun permanently expiring and dropping without delivery.
- **Action Required:** Urgently top up or upgrade plan via [Brevo Account Billing](https://app.brevo.com/billing/account/customize/pag) to prevent continued silent email loss for customers.
