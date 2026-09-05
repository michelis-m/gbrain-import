# Brevo Transactional Email Credit Limit Reached

- **Date:** 2026-09-05 16:00 UTC
- **From:** Brevo <contact@t.brevo.com>
- **To:** <michael@nutrioscale.com>
- **Subject:** You have reached your credit limit for transactional emails
- **Entities:** [[companies/qalzy]], Brevo

## Critical Alert & Operational Impact
- **Credit Limit Reached:** The credit limit for Qalzy Ltd's Brevo SMTP account has been completely exhausted.
- **Email Delivery Interruption:** All new transactional emails (account creation, OTPs, order updates, customer notifications) are no longer being sent and are currently diverted into a backlog.
- **Backlog Expiration Window:** Backlog emails are stored on the transactional platform for up to **36 hours** before they expire and are permanently dropped.
- **Action Required:** Immediate credit renewal/top-up on Brevo billing (https://app.brevo.com/billing/account/customize/pag) to clear the backlog and resume sending.
