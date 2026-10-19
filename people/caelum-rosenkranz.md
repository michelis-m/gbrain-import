# Caelum Rosenkranz

**Role:** Google Cloud Account Manager  
**Company:** Google Cloud  
**Email:** `caelumr@google.com`  

## Context
Google Cloud Account Manager assigned to Qalzy, overseeing Google Cloud infrastructure, Vertex AI / Gemini API utilization, and Google for Startups credit deployment.

## Facts & Notes
- On 2026-10-15, contacted [[people/michael-michelis]] reporting that Qalzy's Gemini API requests had registered hundreds of rate limit (429) errors over the past 30 days.
- Recommended reserving Gemini Provisioned Throughput to eliminate 429 errors and secure dedicated capacity, noting it could be paid for using Qalzy's remaining ~$52,000 in Google for Startups cloud credits.
- [[people/michael-michelis]] replied requesting clarification on specific model and region logs since internal monitoring showed no rate limit spikes.
- On 2026-10-16, Caelum followed up with precise telemetry: the 429 errors occurred exclusively on `gemini-3.1-flash-lite` in `us-central1` via AI Studio (project 822330144457). Total errors amounted to only ~290 over 30 days (~0.2% of requests), with the majority isolated to 2026-09-24. Caelum acknowledged Google's internal modeling had been overly cautious and confirmed there is nothing to fix or reserve.

## Referenced by
- Referenced in [Google Cloud: Gemini API 429 Rate Limits and Provisioned Throughput Proposal](../emails/2026-10-15_Google_Cloud_Gemini_Provisioned_Throughput_and_Rate_Limits)
- Referenced in [Daily Email Summary: 2026-10-15](../emails/2026-10-15_daily_emails)
- Referenced in [Daily Email Summary: 2026-10-16](../emails/2026-10-16_daily_emails)
- Referenced in [Google Cloud: Gemini 429 Resolution and Project Telemetry](../emails/2026-10-16_Google_Cloud_Gemini_429_Resolution)
- On 2026-10-19, followed up to inform Michael that Qalzy has $11,910 in Google Cloud Enhanced Support credits valid until 30 April 2027 from the Startups program, providing 24/7 engineer access and 1-hour response times. Provided step-by-step console instructions to activate against billing account 010A69-E01095-C382CF.

## Referenced by
- Referenced in [Google Cloud: $11,910 Enhanced Support Startup Credit](../emails/2026-10-19_Google_Cloud_Enhanced_Support_Credit_Activated)
- Referenced in [Daily Email Summary: 2026-10-19](../emails/2026-10-19_daily_emails)
