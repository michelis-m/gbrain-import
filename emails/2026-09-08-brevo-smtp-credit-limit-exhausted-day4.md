# Brevo SMTP Transactional Credit Limit Alert (Day 4)

**Date:** 2026-09-08  
**From:** Brevo <contact@t.brevo.com>  
**To:** [[people/michael-michelis]] <michael@nutrioscale.com>  
**Subject:** You have reached your credit limit for transactional emails  

## Summary
Fourth consecutive daily alert notifying that Qalzy Ltd's transactional SMTP email credit limit has been exhausted on Brevo.

## Operational Impact
- Outbound transactional emails (order confirmations, account notifications, magic links/passwords) are blocked from immediate sending and placed into backlog.
- **36-Hour Expiry Window:** Emails in backlog are held for a maximum of 36 hours before permanent expiration. Because credits have been exhausted since September 5, accumulated transactional backlog is dropping permanently.
- **Immediate Action Required:** Purchase additional email credits via the [Brevo Billing Portal](https://app.brevo.com/billing/account/customize/pag) to clear backlogged sends.
