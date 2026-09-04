# Qalzy Ad Platform Connectors

This document outlines the active ad platform integrations and their respective configurations used by the agent to pull metrics and audit data.

## Meta Ads
- **Integration**: Native Meta Graph API
- **Ad Account ID**: `1351291616909846`
- **Credentials**: Stored locally in `~/.hermes/meta_ads.json` (System User Access Token & Page Token).

## Google Ads
- **Integration**: Windsor.ai REST API
- **API Key**: `11468dbe0739201334f55175e0cf7320f8b0`
- **Connector Name**: `google_ads`
- **Notes**: Windsor.ai strictly enforces field compatibility. Requesting incompatible dimensions/metrics returns a 400 Error. Known working fields: `campaign,clicks,spend,conversions` and `search_term,clicks,spend,conversions`.

## Reddit Ads
- **Integration**: Native Reddit Ads API (v3)
- **Account ID**: `a2_jkg46exnryaq`
- **Credentials**: Stored locally in `~/.hermes/reddit_ads.json` (OAuth2: client_id, client_secret, access_token, refresh_token).
- **Quirks & Pitfalls**:
  - Requires the specific `a2_...` Account ID in the URL path.
  - The v3 reporting endpoint (`/api/v3/ad_accounts/{account_id}/reports`) strictly requires timestamp granularity down to the exact hour for the `starts_at` and `ends_at` parameters (e.g., `YYYY-MM-DDTHH:00:00Z`). Passing times like `23:59:59Z` will result in an HTTP 400 Bad Request.
