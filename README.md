# Stellate

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
