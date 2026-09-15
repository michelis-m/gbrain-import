# Brevo SMTP Alert: Credit Limit Reached (Day 11)

**Date:** 2026-09-15  
**From:** Brevo (`contact@t.brevo.com`)  
**To:** [[people/michael-michelis]]  
**Subject:** You have reached your credit limit for transactional emails  
**Entities:** [[companies/brevo]], [[companies/qalzy]]

## Overview
Brevo sent its daily critical warning that Qalzy Ltd has exhausted its transactional SMTP email quota for the 11th consecutive day.

## Impact & Risk
- All new outbound transactional emails (e.g. order receipts, shipping notifications, password resets) are held in an outbound backlog.
- Backlog emails are retried upon credit renewal, but unfulfilled messages are permanently dropped after 36 hours.

## Action Required
- Top up SMTP transactional email credits via `https://app.brevo.com/billing/account/customize/pag`.
