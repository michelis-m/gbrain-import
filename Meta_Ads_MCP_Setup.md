# Meta Ads MCP Setup for AI Agents

**Date:** 2026-09-03
**Topic:** Meta Ads, MCP, Troubleshooting, Automation

## Issue
When connecting an AI agent to the official Meta Ads MCP server (`https://mcp.facebook.com/ads`), the connection fails with an `invalid_client_metadata` error. Meta restricts their hosted OAuth flow to a closed whitelist of enterprise vendors, rejecting Dynamic Client Registration from open-source tools.

## Resolution
Use the community open-source Meta Ads MCP server instead, which supports System User Access Tokens.

**Implementation:**
1. Generate a System User Access Token in Meta Business Settings with `ads_management`, `ads_read`, and `read_insights` permissions.
2. Store the token in the environment (`META_ADS_ACCESS_TOKEN` and `META_ACCESS_TOKEN`).
3. Configure the MCP client to use the local stdio server: `npx -y @getmcpads/meta-ads-mcp-server`.
4. Restart the agent gateway.

This provides 34 tools for reporting, ad management, and insight extraction without relying on Meta's locked-down OAuth endpoint.