# Shopify Admin API Integration

This document outlines the direct Shopify Admin API connection configured for [[companies/qalzy]].

## Store Overview
- **Store Name**: Qalzy
- **Storefront**: [qalzy.com](https://qalzy.com)
- **Primary Myshopify Domain**: `nutrioscale.myshopify.com`
- **Shopify Admin Path**: `admin.shopify.com/store/qalzy`
- **Currency**: USD

## Authentication & Credentials
- **Integration Type**: Shopify Dev Dashboard App (OAuth 2.0 Authorization Code Grant)
- **Access Token Type**: Offline persistent access token (`shpca_...`)
- **Credentials Location**:
  - `~/.hermes/shopify_token.json` (Full token payload & granted scopes)
  - `~/.hermes/.env` (`SHOPIFY_ACCESS_TOKEN`, `SHOPIFY_CLIENT_ID`, `SHOPIFY_CLIENT_SECRET`, `SHOPIFY_SHOP_DOMAIN`)
- **API Version**: `2025-01`
- **Endpoint**: `https://nutrioscale.myshopify.com/admin/api/2025-01/graphql.json`

## Permissions / Scopes
The app has full read and write access across core commerce scopes:
- `read_products`, `write_products`
- `read_orders`, `write_orders`, `write_order_edits`
- `write_draft_orders`, `customer_read_draft_orders`
- `write_inventory`, `write_inventory_shipments`, `write_inventory_transfers`
- `write_customers`, `customer_write_customers`, `write_customer_data_erasure`
- `write_discounts`, `write_price_rules`
- `write_fulfillments`, `write_returns`
- `read_analytics`, `write_analytics_annotations`

## Integration Architecture & Notes
- **Client Credentials Restriction**: Shopify's Dev Dashboard `client_credentials` grant returns `shop_not_permitted` on live merchant stores (restricted to development stores and Shopify Plus). Standalone server integrations on live merchant stores must use the Authorization Code Grant to generate the offline token.
- **Domain Addressing**: Even when accessing the store via `admin.shopify.com/store/qalzy`, API requests must strictly be directed to the primary root myshopify domain: `https://nutrioscale.myshopify.com/admin/api/...`.
