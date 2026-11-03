---
type: note
title: 'Redo Connector: Reset Returns Tool Bug & AI Returns Workflow Feedback'
date: '2026-11-03'
---

# Redo Connector: Reset Returns Tool Bug & AI Returns Workflow Feedback

**Date:** 2026-11-03  
**Participants:** [[people/michael-michelis]], [[people/jack-otto]] (`jack.otto@redo.com`), [[people/kostas-koukoravas]]  
**Entity:** [[companies/redo]]  

---

## Key Takeaways
- **Operational Limitation Raised:** [[people/michael-michelis]] communicated a critical bottleneck when using AI agents via the Redo MCP connector: agents cannot invoke the `reset_returns` action when customer returns are mistakenly rejected, requiring manual intervention in the merchant admin dashboard.
- **Bug Confirmed:** Jack Otto confirmed that the `reset_returns` tool has a known defect currently being addressed by the Redo engineering team.
- **Workflow Discovery:** Redo requested detailed insight into how Qalzy structures AI-assisted returns management—specifically whether returns are evaluated one-by-one or in batch, whether AI executes autonomous decisions or requires approval gates, and how complex return edge cases are segregated.
