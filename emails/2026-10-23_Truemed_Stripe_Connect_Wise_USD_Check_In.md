# Truemed: Stripe Connect Flow & Wise USD Verification Check-In

**Date:** 2026-10-23  
**From:** Leo Schottenstein (`leo@truemed.com`)  
**To:** [[people/kostas-koukoravas]] (`kostas@qalzy.com`), [[people/michael-michelis]] (`michael@qalzy.com`)  
**Company:** [[companies/truemed]], [[companies/qalzy]]  

---

## Overview
[[people/leo-schottenstein]] from Truemed followed up with Kostas Koukoravas and Michael Michelis to check if they were able to test the custom Stripe Connect verification link using Qalzy's Wise USD account and US EIN.

---

## Key Details
- **Context:** Truemed enables pre-tax HSA/FSA checkout via Letters of Medical Necessity (LMNs). Qalzy negotiated a reduced transaction fee ($2 + 6.5%, discounted from 8%) and is working through Stripe merchant underwriting prior to remitting the $800 one-time onboarding fee.
- **Verification Link:** Leo previously supplied a test link (`connect.stripe.com/d/setup/e/...`) on Oct 19 to confirm that Qalzy's US EIN, Wise USD ACH routing, and company representative credentials pass Stripe's underwriting without locking Qalzy into financial commitments.
- **Urgency & Timing:** Truemed emphasized finalizing verification ahead of the BFCM rush and year-end FSA spend deadlines, during which Truemed marketplace traffic surges from 1M+ to 2–3M+ monthly visitors.
- **Next Steps:** Kostas and Michael need to complete the Stripe Connect test and report any blockers to Leo so Truemed's Solutions team can resolve them.
