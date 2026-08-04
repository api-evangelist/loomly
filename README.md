# Loomly

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

Loomly is a brand success platform that empowers marketing teams to grow successful brands online through collaboration, publishing, and analytics features. It provides a REST API for managing social media content calendars, post ideas, approval workflows, publishing, and audience engagement analytics across 10+ social channels.

## API

The Loomly API is a REST API authenticated via OAuth 2.0 Bearer tokens. It provides endpoints for managing calendars, creating and scheduling posts, handling approval workflows, and retrieving analytics data. The base URL is `https://api.loomly.com/v1`.

## Plans

- **Starter** - $49/month (annual) — 12 social accounts, 3 users, unlimited calendars
- **Beyond** - $249/month (annual) — 60 social accounts, unlimited users, custom workflows
- **Enterprise** - Custom pricing — 61+ social accounts, priority support

See [plans/loomly-plans-pricing.yml](plans/loomly-plans-pricing.yml) for full pricing details.

## Rate Limits

The public Status API enforces a 10 requests-per-second fair-use limit. Core API rate limits are not publicly disclosed. See [rate-limits/loomly-rate-limits.yml](rate-limits/loomly-rate-limits.yml) for details.

## FinOps

Key cost optimization: stay under 12 social accounts and 3 users on Starter to avoid a 408% cost jump to Beyond. Annual billing saves 25%. Nonprofits qualify for a 50% lifetime discount. See [finops/loomly-finops.yml](finops/loomly-finops.yml).

## Links

- Website: https://www.loomly.com
- Pricing: https://www.loomly.com/pricing
- Status: https://status.loomly.com
- Blog: https://www.loomly.com/blog
- LinkedIn: https://www.linkedin.com/company/loomly
- X: https://x.com/LoomlySocial
