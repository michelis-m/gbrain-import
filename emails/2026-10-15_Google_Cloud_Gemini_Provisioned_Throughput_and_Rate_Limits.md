---
type: note
title: 'Google Cloud: Gemini API 429 Rate Limits and Provisioned Throughput Proposal'
date: '2026-10-15'
---

# Google Cloud: Gemini API 429 Rate Limits and Provisioned Throughput Proposal

**Date:** 2026-10-15  
**From:** [[people/caelum-rosenkranz]] (Google Cloud)  
**To:** [[people/michael-michelis]]  
**Subject:** Google / Qalzy: fix the Gemini 429s with your credits  
**Entities:** Google Cloud, [[companies/qalzy]]  

---

## Summary
Caelum Rosenkranz, Qalzy's Google Cloud Account Manager, reached out regarding observed rate-limit (HTTP 429) errors on Gemini API calls. He recommended reserving Gemini Provisioned Throughput to ensure dedicated capacity, noting it can be funded using Qalzy's remaining ~2,000 in Google for Startups cloud credits. Michael Michelis responded requesting technical log clarification.

## Key Points & Correspondence
- **Google Cloud Alert:** Caelum reported that Qalzy's Gemini API requests had encountered 429 rate-limit errors hundreds of times over the past 30 days.
- **Proposed Solution (Provisioned Throughput):**
  - Dedicated capacity reservation at a fixed weekly or monthly price, preventing shared-capacity throttling.
  - Consistent latency during traffic spikes, with automatic overflow to pay-as-you-go pricing for volume exceeding the reservation.
  - Fully payable via Qalzy's remaining Google for Startups credit balance (~2,000).
- **Qalzy Response:** [[people/michael-michelis]] noted that internal monitoring and logs do not show rate limit errors or degradation, asking Caelum to specify the exact model name, region, and project ID where these errors were registered.
