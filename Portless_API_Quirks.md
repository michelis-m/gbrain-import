# Portless (Pipe17) API Quirks

## PBID Orders
Orders in Portless starting with the prefix `PBID` (e.g., `PBID007752757-1`) are internal/portal-generated orders (such as wholesale, B2B, replacements, or exception/inbound documents). 

These are **not accessible** via the Pipe17/Portless API. The API will only return standard integration orders (e.g., Shopify orders formatted like `#2000`).

To view details, line items, or tracking for `PBID` orders, you must use the Portless Web Portal directly or contact `support@portless.com`.