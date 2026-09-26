# Stripe Sandbox Webhook Delivery Failure

**Date:** 2026-09-26  
**From:** Stripe notifications (`notifications@stripe.com`)  
**To:** [[people/michael-michelis]] (`michael@qalzy.com`)  
**Account:** Qalzy Subscriptions Sandbox (`acct_1TvwKx90tW4jDAJI`)  
**Subject:** `[Sandbox] Stripe webhook delivery issues [test mode] for https://api.qalzy.com`

---

## Summary
Stripe sent an automated alert warning that test mode webhook requests to `https://api.qalzy.com/latest/subscriptions/webhooks/stripe` are failing with HTTP 404 (Not Found).

- **Failing Endpoint:** `https://api.qalzy.com/latest/subscriptions/webhooks/stripe`
- **Error:** HTTP 404
- **First Failure:** September 23, 2026 at 11:47:53 AM UTC
- **Deadline:** Stripe will automatically stop sending notifications to this endpoint on **October 2, 2026 at 11:47:53 AM UTC** unless resolved.

## Impact & Next Steps
- Verify the webhook routing configuration on `api.qalzy.com` for subscription lifecycle events (`customer.subscription.*`, `invoice.*`, `checkout.session.completed`).
- Update the Stripe webhook URL in the dashboard if the API route was changed or remove it if sandbox testing on this endpoint is deprecated.
