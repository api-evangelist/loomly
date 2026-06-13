# Loomly

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
