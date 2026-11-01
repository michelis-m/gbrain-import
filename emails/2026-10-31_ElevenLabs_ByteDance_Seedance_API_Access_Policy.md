---
type: note
title: 'ElevenLabs: ByteDance Seedance Video Models Restricted to Enterprise API'
date: '2026-10-31'
---

# ElevenLabs: ByteDance Seedance Video Models Restricted to Enterprise API

**Date:** 2026-10-31  
**Participants:** [[people/michael-michelis]], ElevenLabs Support (`support@elevenlabs.io`)  
**Company:** [[companies/elevenlabs]]  

---

## 1. Context & Request
- [[people/michael-michelis]] submitted a request to enable ByteDance video models (`bytedance-seedance-v2.5`, `bytedance-seedance-v2`, `bytedance-seedance-v2-fast`) on the Flows Image & Video API.
- **Intended Use Case:** Automated production of short DTC video ads for [[companies/qalzy]], utilizing AI-generated fictional characters, ElevenLabs voices for lip synchronization, and complementary Veo video generation.
- **Error Encountered:** `model_access_denied: “ByteDance models are disabled by default and require explicit approval before use.”` (Request ID: `ab81a5c55a717f7fd08bcc6e297d0f66`).

## 2. Policy & Resolution
- ElevenLabs Support clarified that API access to ByteDance Seedance models is gated strictly to **Enterprise plans**. There is no self-serve or manual exception approval path for non-Enterprise tiers.
- **Alternative Solution:** Seedance models remain accessible for manual generation directly inside the **ElevenCreative web platform** UI (Image & Video) without Enterprise plan gating.
