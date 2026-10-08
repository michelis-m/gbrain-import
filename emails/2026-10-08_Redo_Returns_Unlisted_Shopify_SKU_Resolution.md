# Redo Returns: Unlisted Shopify SKU Resolution for Influencer Orders

**Date:** 2026-10-08  
**From:** [[people/kostas-koukoravas]]  
**To:** [[people/frank-marino]] (`frank@redo.com`)  
**Companies:** [[companies/redo]], [[companies/qalzy]]  

---

## Context
Following extensive discussions regarding Redo's inability to support custom manual creator fulfillment flows for returned/inspected units, Frank Marino proposed two paths: building a separate Shopify outlet store with Redo collaborator access, or placing returned items into a hidden collection on the existing store transformed to a distinct SKU.

## Resolution & Implementation
- **Architecture Choice:** [[people/kostas-koukoravas]] and [[people/michael-michelis]] confirmed Qalzy will use the existing primary Shopify storefront rather than incurring the subscription costs and technical maintenance of a secondary store.
- **Workflow:**
  1. Returned scales inspected and shelved at Redo will be converted to an unlisted secondary SKU in the warehouse management system.
  2. The unlisted SKU will remain hidden from the consumer-facing online storefront.
  3. Michael and Kostas will manually generate draft orders in Shopify assigned to creators using this unlisted SKU.
  4. Redo fulfills these draft orders normally via standard D2C warehouse pick/pack procedures at their agreed $2.00 handling rate.
- **Next Step:** Kostas requested confirmation from Frank Marino on how Redo's intake team executes the SKU transformation upon receiving return parcels.
