# Google AI Studio: Deprecation Notice & Migration to Gemini Omni 1.1 Flash

**Date:** 2026-10-08  
**From:** Google AI Studio (`googleaistudio-noreply@google.com`)  
**To:** [[people/michael-michelis]] (`michael@qalzy.com`)  

---

## Alert Summary
Mandatory technical service announcement regarding API model deprecation in Google AI Studio / Gemini API.

## Deprecated Models (Effective October 22, 2026)
- `gemini-omni-flash-preview`
- `veo-3.1-generate-preview`
- `veo-3.1-fast-generate-preview`
- `veo-3.1-lite-generate-preview`

## Required Actions
- Update active endpoints, scripts, and SDK configurations to target `gemini-omni-1.1-flash` (the Generally Available GA release for multimodal vision, food recognition, and video processing).
- Migrate any Veo 3.1 video workflows to the Gemini Enterprise Agent Platform.
- Complete updates prior to October 22, 2026 to ensure zero disruption to production vision parsing and internal creative pipelines.
