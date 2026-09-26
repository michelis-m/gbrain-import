# Daily Email Summary: 2026-09-26

## 1. Supply Chain, Billing & Carrier Operations
- **OpenBorder & Portless Billing Dispute Escalation ([[companies/openborder]], [[companies/portless]]):**
  - Following OpenBorder's request for payment on Invoice 5091 (Urvi Godha), [[people/kostas-koukoravas]] placed invoice payment on hold.
  - Kostas escalated to Portless leadership (Harteg Singh, Craig Shaver), highlighting duplicate tariff charges across both platforms (e.g. Order #1930) alongside Portless's erroneous £3 small parcel fees caused by misapplying US COGS to declared value.
  - Kostas demanded a joint 3-way reconciliation spreadsheet for all non-US orders and written procedures on tariff responsibilities before releasing invoice payments.
- **Portless RTS Policy Clarification (PBID007771348):**
  - Mandy from Portless Support clarified that parcels held under return-to-origin status are retained at destination facilities for 1 month and can be redispatched during that period, after which they are destroyed. Alternatively, units can be destroyed directly at customs. A decision from Qalzy is pending.
- **B2B Supply Outreach (Cruduus):**
  - Aksel Erga followed up regarding vetted FDA supply access and manufacturing capacity for Qalzy.

---

## 2. Infrastructure, Mobile & Technical Operations
- **Stripe Sandbox Webhook 404 Failures ([[companies/stripe]]):**
  - Stripe automated alert warned that webhook deliveries to `https://api.qalzy.com/latest/subscriptions/webhooks/stripe` (Account: `acct_1TvwKx90tW4jDAJI`) have failed with HTTP 404 since Sep 23.
  - Stripe will deactivate webhook delivery to this URL on October 2, 2026 if not rectified.
- **Android App Stability Warning (Firebase):**
  - Firebase reported a trending crash on Android (`com.qalzy.app`) for Sep 25 in `io.flutter.view.AccessibilityBridge$Api31Impl.isBoldText`.

---

## 3. Customer Retention & Product Feedback
- **Subscription Paywall Friction Drives Scale Return ([[companies/redo]]):**
  - Customer Lynnette Bauer shipped her scale back via FedEx today for a full refund despite Michael's personal explanation that the scale can be connected for free.
  - Customer stated: *"Unfortunately I feel it's not clear enough."* This reinforces the need to deploy the planned onboarding UI improvements and banner clarifying that no paid subscription is required to operate the scale.

---

## 4. Growth, Press & Montessorians Onboarding
- **Press & Media Pitching Batch:**
  - Automated/scheduled outreach emails sent pitching Qalzy (*"Building the 'OURA of nutrition tracking'"*) to 8 technology and health journalists/editors (Insight Links, CareCognitics, Bertel King, Naturepedic, Manifest, Herald & Times, The Channel Co, CIE Online).
- **Montessorians AI School Onboarding:**
  - [[people/michael-michelis]] emailed Nantia Ceni with step-by-step instructions to connect to Slack and test the school's Hermes AI assistant.
