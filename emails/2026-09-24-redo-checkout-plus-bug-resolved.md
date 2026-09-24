# Redo: Checkout+ Free Returns Bug Resolved

**Date:** 2026-09-24  
**From:** Jake Smedley (`support@getredo.com`)  
**To:** Konstantinos Koukoravas (`kostas@qalzy.com`)  
**Related Entities:** [[companies/redo]], [[companies/qalzy]], [[people/kostas-koukoravas]], [[people/frank-marino]]  

---

## Overview
Jake Smedley from Redo Support confirmed that the critical **Checkout+** outage reported on September 23 has been completely resolved by Redo's engineering team.

## Resolution Details
- **Root Cause:** An account configuration setting prevented the Checkout+ toggle button from adding the $4.50 free returns line item to the cart, causing shoppers to complete orders without return coverage.
- **Engineering Fix:** Redo engineers deployed a fix on the morning of September 24.
- **Verification:** Jake verified the live checkout flow on `qalzy.com` across both the cart drawer and cart page. Clicking Checkout+ now properly includes the free returns coverage fee, matching the displayed cart total.
- **Historical Orders:** Orders completed prior to the fix were processed without the coverage fee and will remain uncovered in the Redo merchant admin. All new orders starting September 24 will be covered normally.