# Brevo: Depleted Transactional Email Credit Limit (Day 7)

**Date:** 2026-09-11  
**From:** Brevo <contact@t.brevo.com>  
**To:** <michael@nutrioscale.com>  
**Companies:** [[companies/qalzy]]

## Summary
Automated alert from Brevo notifying that Qalzy Ltd's transactional SMTP credit balance remains exhausted, causing new outgoing transactional emails to be saved into a temporary backlog.

## Details
- **Impact:** New customer transactional emails (order confirmations, shipping notifications) cannot be dispatched in real time.
- **Retention Window:** Backlog messages are temporarily queued and will be retried once credits are replenished, but risk permanent expiration if unaddressed.
- **Action Required:** Account administrator must log into Brevo billing and replenish SMTP credits.
