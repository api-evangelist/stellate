# Stellate Rate Limits

Source: https://stellate.co/docs/graphql-security/rate-limiting/about-rate-limiting

## Public GraphQL API Limits

- **Complexity limit:** 1,000 nodes per query (enforced during early access)
- **Complexity calculation:** Based on maximum nodes a query might return; list fields default to an expected size of 20 when not specified.
- **Authentication:** Bearer token required via `Authorization` header.

## Rate Limiting Feature (Customer-Facing)

Stellate provides a configurable rate limiting feature for customers to apply to their own GraphQL APIs proxied through Stellate.

### Configuration Options

- **Request-based limits:** Cap number of requests per consumer within a time window.
- **Complexity-based limits:** Rate limit by query complexity score rather than raw request count.
- **Operation-specific limits:** Apply different limits to specific queries or mutations.
- **Tiered limits:** Set different thresholds for authenticated vs. unauthenticated users, or by subscription tier.
- **Consumer identification:** Identify consumers by IP address, header, cookie, JWT claim, or custom request property.
- **Allow-listing:** Exempt trusted consumers or internal services from limits.
- **Global limits:** Apply universal thresholds across all API consumers.

### Latency Impact

- Enabling rate limiting adds approximately **20ms** of additional latency per request.

### Testing

- **Dry Run Mode:** Test rate limiting rules without actually blocking requests.
- **Debugging functions:** Built-in testing utilities available in the Stellate dashboard.

### Plan Availability

- Rate Limiting is available on the **Business plan** as an add-on (+$5/month).
- Not available on the Free plan.

## Free Plan Limits

- **Requests:** 100,000 requests/month
- Exceeding this limit causes requests to pass through without caching or rate limiting (features disabled, requests not blocked).
