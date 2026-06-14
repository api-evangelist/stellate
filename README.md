# Stellate

Stellate is a GraphQL edge caching and API management platform that caches GraphQL query results at 60 data centers worldwide, reducing origin traffic by up to 95% and delivering responses in milliseconds. The platform provides edge caching, real-time metrics and insights, rate limiting, and security features to help teams scale, protect, and optimize their GraphQL APIs.

## Links

- **Website:** https://stellate.co
- **Documentation:** https://stellate.co/docs
- **Pricing:** https://stellate.co/pricing
- **GraphQL API:** https://graph.stellate.co
- **Public API Docs:** https://stellate.co/docs/reference/public-api
- **GitHub Organization:** https://github.com/StellateHQ
- **LinkedIn:** https://www.linkedin.com/company/stellatehq

## About

Stellate (formerly GraphCDN) provides a GraphQL-native CDN and edge proxy that sits in front of any GraphQL API. Key capabilities include:

- **Edge Caching:** Cache GraphQL query results at 60+ global data centers.
- **Metrics & Insights:** Real-time performance monitoring and analytics.
- **Rate Limiting:** Complexity-based and request-based rate limiting with per-consumer configuration.
- **Security:** Filters, persisted operations, introspection blocking, and request signing.
- **Developer Portal:** Branded API portal with consumer API key management.

Note: The Guild acquired Stellate in September 2024 and is integrating its capabilities into the GraphQL Hive platform.

## Repository Structure

```
stellate/
├── apis.yml                        # APIs.json 0.19 catalog entry
├── plans/
│   └── stellate-plans.md           # Pricing plans detail
├── rate-limits/
│   └── stellate-rate-limits.md     # Rate limiting documentation
└── finops/
    └── stellate-finops.md          # FinOps and cost analysis
```
