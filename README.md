# Mindbody (mindbody)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Mindbody is a business management and consumer marketplace platform for the fitness, beauty, and wellness industries, providing scheduling, point of sale, client management, marketing, and reporting tools for studios, gyms, salons, and spas. The Mindbody Public API (v6) provides REST endpoints for appointments, classes, clients, enrollments, sales, sites, staff, payroll, and cross-site identity, and is paired with a Webhooks API that pushes real-time event notifications using API key + SiteId headers, with optional OAuth 2.0 bearer tokens from the Mindbody Identity Service for staff- and client-scoped operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mindbody/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Fitness, Wellness, Beauty, Scheduling, Booking, Point of Sale, Studios, Salons, Spas, Webhooks

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-28

## APIs

### Mindbody Public API v6

REST API for Mindbody business data including appointments, classes, clients, enrollments, sales, sites, staff, payroll, pick-a-spot reservations, and cross-site identity. Authentication combines a Mindbody-issued API-Key header and SiteId header with optional OAuth 2.0 bearer tokens issued by Mindbody Identity Service for staff- and client-scoped operations. Base URL: `https://api.mindbodyonline.com`.

**Human URL:** [https://developers.mindbodyonline.com/PublicDocumentation/V6](https://developers.mindbodyonline.com/PublicDocumentation/V6)

**Base URL:** `https://api.mindbodyonline.com`

#### Tags:

 - REST, OAuth 2.0, API Key, Appointments, Classes, Clients, Sales, Staff, Payroll, Sites

#### Properties

- [Documentation](https://developers.mindbodyonline.com/PublicDocumentation/V6)
- [APIReference](https://developers.mindbodyonline.com/ui/documentation/public-api)
- [GettingStarted](https://developers.mindbodyonline.com/PublicDocumentation/GettingStarted)
- [OpenAPI](openapi/mindbody-public-api-v6-openapi-original.yml)
- [C# .NET Standard SDK](https://github.com/mindbody/Mindbody-API-SDKs/raw/main/PublicAPI/mindbody-public-api-cs_net_standard_lib.zip)
- [PHP SDK](https://github.com/mindbody/Mindbody-API-SDKs/raw/main/PublicAPI/mindbody-public-api-php_generic_lib_v2.zip)
- [Python SDK](https://github.com/mindbody/Mindbody-API-SDKs/raw/main/PublicAPI/mindbody-public-api-python_generic_lib.zip)
- [Ruby SDK](https://github.com/mindbody/Mindbody-API-SDKs/raw/main/PublicAPI/mindbody-public-api-ruby_generic_lib.zip)
- [Partner OAuth Sample App (C#)](https://github.com/mindbody/PartnerOAuthWebApp)
- [OAuth 2.0 (Mindbody Identity Service)](https://signin.mindbodyonline.com/connect/authorize)
- [JSON-LD Context](json-ld/mindbody-public-api-v6-context.jsonld)

### Mindbody Webhooks API

Subscription and delivery platform that pushes near real-time event notifications for sites, locations, appointments, classes, clients, sales, and staff. Partners manage subscriptions over a REST control plane (POST/GET/PATCH/DELETE /api/v1/subscriptions, GET /api/v1/metrics), and Mindbody pushes JSON events with HMAC-SHA256 signature verification via the X-Mindbody-Signature header. Base URL: `https://push-api.mindbodyonline.com`.

**Human URL:** [https://developers.mindbodyonline.com/WebhooksDocumentation](https://developers.mindbodyonline.com/WebhooksDocumentation)

**Base URL:** `https://push-api.mindbodyonline.com`

#### Tags:

 - Webhooks, Events, Subscriptions, Real-Time, HMAC

#### Properties

- [Documentation](https://developers.mindbodyonline.com/WebhooksDocumentation)
- [APIReference](https://developers.mindbodyonline.com/ui/documentation/webhooks-api)
- [OpenAPI](openapi/mindbody-webhooks-api-openapi-original.yml)
- [C# .NET Standard SDK](https://github.com/mindbody/Mindbody-API-SDKs/raw/main/WebhooksAPI/mindbody.pushapi.api-cs_net_standard_lib.zip)
- [PHP SDK](https://github.com/mindbody/Mindbody-API-SDKs/raw/main/WebhooksAPI/mindbody.pushapi.api-php_generic_lib_v2.zip)
- [Python SDK](https://github.com/mindbody/Mindbody-API-SDKs/raw/main/WebhooksAPI/mindbody.pushapi.api-python_generic_lib.zip)
- [Ruby SDK](https://github.com/mindbody/Mindbody-API-SDKs/raw/main/WebhooksAPI/mindbody.pushapi.api-ruby_generic_lib.zip)
- [JSON-LD Context](json-ld/mindbody-webhooks-api-context.jsonld)

## Common Properties

- [Website](https://www.mindbodyonline.com/)
- [Documentation](https://developers.mindbodyonline.com/)
- [Developer Portal](https://developers.mindbodyonline.com/)
- [GettingStarted](https://developers.mindbodyonline.com/PublicDocumentation/GettingStarted)
- [SignUp](https://developers.mindbodyonline.com/Signup)
- [Pricing](https://www.mindbodyonline.com/business/pricing)
- [Support](https://support.mindbodyonline.com/s/contactapisupport)
- [FAQ](https://developers.mindbodyonline.com/resources/faqs)
- [StatusPage](https://status.mindbodyonline.com/)
- [GitHubOrganization](https://github.com/mindbody)
- [Mindbody-API-SDKs](https://github.com/mindbody/Mindbody-API-SDKs)
- [LinkedIn](https://www.linkedin.com/company/mindbody)
- [ReleaseNotes](https://developers.mindbodyonline.com/Resources/ApiReleaseNotes)
- [Plans](plans/mindbody-plans-pricing.yml)
- [RateLimits](rate-limits/mindbody-rate-limits.yml)
- [FinOps](finops/mindbody-finops.yml)
- [SpectralRules](rules/mindbody-spectral-rules.yml)
- [Vocabulary](vocabulary/mindbody-vocabulary.yml)

## Features

| Name | Description |
|------|-------------|
| Booking and Scheduling | Online booking widgets, class schedules, appointments, enrollments, and Pick-a-Spot reservations. |
| Point of Sale | In-studio POS for products, services, contracts, gift cards, custom payment methods, refunds, and returns. |
| Client Management | Client profiles, contracts, services, contact logs, formula notes, custom fields, and red/yellow alerts. |
| Staff and Payroll | Staff schedules, permissions, availability, class pay, commissions, and time-clock reporting. |
| Webhooks | HMAC-signed, near real-time delivery of site, location, appointment, class, client, sale, and staff events. |
| Identity and OAuth | OpenID Connect via signin.mindbodyonline.com with the Mindbody.Api.Public.v6 scope for delegated calls. |
| Cross-Site Lookup | Discover which Mindbody businesses a client is associated with across the network. |
| Marketplace Listing | Mindbody consumer app marketplace exposes participating studios to nearby members. |

## Use Cases

| Name | Description |
|------|-------------|
| Studio Booking Apps | Build branded mobile or web booking experiences for yoga, pilates, barre, and fitness studios. |
| CRM and Marketing Automation | Sync clients and sales events into CRMs (HubSpot, Salesforce) and trigger marketing journeys. |
| Wellness Aggregator Integrations | Power class/appointment discovery and booking in third-party wellness apps and ClassPass-style platforms. |
| Studio Operations Analytics | Pipe payroll, sales, and class fill data into BI tooling for chain operators. |
| Customer Loyalty Programs | Drive loyalty points and rewards from visit/sale events delivered via the Webhooks API. |
| Network Identity | Use Cross-Site to recognize repeat clients across affiliated Mindbody businesses. |

## Integrations

| Name | Description |
|------|-------------|
| Mindbody Identity Service | OpenID Connect provider at signin.mindbodyonline.com powering OAuth 2.0 flows for the Public API. |
| Mindbody Marketplace | Consumer app surface exposing participating studios for nearby discovery and booking. |
| Partner Store | Mindbody-vetted directory of integrations at partnerstore.mindbodyonline.com. |
| ClassPass | Aggregator marketplace integrating with Mindbody for class supply. |
| Payment Processors | Integrated card processing and custom payment methods routed through the Sale endpoints. |

## Solutions

| Name | Description |
|------|-------------|
| Boutique Fitness | Yoga, pilates, barre, indoor cycling, HIIT, and martial-arts studios. |
| Beauty and Salon | Hair, nail, and beauty salons using appointment scheduling and POS. |
| Spa and Wellness | Day spas, medspas, and integrative wellness centers. |
| Health Clubs and Gyms | Multi-location gyms and health clubs with classes, personal training, and recurring memberships. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Mindbody Public API v6](openapi/mindbody-public-api-v6-openapi-original.yml) — 148 operations across 11 tags (Appointment, Class, Client, Cross Site, Enrollment, Payroll, Pick A Spot, Sale, Site, Staff, User Token)
- [Mindbody Webhooks API](openapi/mindbody-webhooks-api-openapi-original.yml) — 6 operations across 2 tags (Subscriptions, Metrics)

### JSON Schema

351 standalone JSON Schema files under [`json-schema/`](json-schema/) — one per OpenAPI component schema, draft 2020-12.

### JSON Structure

351 standalone JSON Structure files under [`json-structure/`](json-structure/) — converted from the JSON Schemas with strict-typed numeric and date types.

### JSON-LD

- [Mindbody Public API v6 Context](json-ld/mindbody-public-api-v6-context.jsonld)
- [Mindbody Webhooks API Context](json-ld/mindbody-webhooks-api-context.jsonld)

### Examples

351 example payloads under [`examples/`](examples/) — one per schema, populated with realistic Mindbody-shaped values.

## Capabilities

Naftiko capabilities organized as self-contained per-tag files, each declaring both a REST adapter and an MCP adapter.

| Capability | API | Tools | Persona |
|----------|--------------|-------|---------|
| [Appointment](capabilities/public-api-v6-appointment.yaml) | Public API v6 | 17 | Studio Front Desk, Booking Bot |
| [Class](capabilities/public-api-v6-class.yaml) | Public API v6 | 16 | Studio Front Desk, Class Manager, Member |
| [Client](capabilities/public-api-v6-client.yaml) | Public API v6 | 42 | CRM Operator, Front Desk, Marketing Automation |
| [Cross Site](capabilities/public-api-v6-cross-site.yaml) | Public API v6 | 1 | Network Admin |
| [Enrollment](capabilities/public-api-v6-enrollment.yaml) | Public API v6 | 4 | Course Coordinator |
| [Payroll](capabilities/public-api-v6-payroll.yaml) | Public API v6 | 4 | Studio Owner, Finance |
| [Pick A Spot](capabilities/public-api-v6-pick-a-spot.yaml) | Public API v6 | 6 | Studio Front Desk, Member |
| [Sale](capabilities/public-api-v6-sale.yaml) | Public API v6 | 25 | POS Cashier, Membership Sales, Finance |
| [Site](capabilities/public-api-v6-site.yaml) | Public API v6 | 20 | Site Admin, Integration Engineer |
| [Staff](capabilities/public-api-v6-staff.yaml) | Public API v6 | 10 | Studio Owner, HR |
| [User Token](capabilities/public-api-v6-user-token.yaml) | Public API v6 | 3 | Integration Engineer |
| [Subscriptions](capabilities/webhooks-api-subscriptions.yaml) | Webhooks API | 5 | Integration Engineer, Platform Operator |
| [Metrics](capabilities/webhooks-api-metrics.yaml) | Webhooks API | 1 | Platform Operator |

## Plans

- [Mindbody Plans and Pricing](plans/mindbody-plans-pricing.yml) — Starter ($99/month per location), Accelerate, Ultimate, and Developer Sandbox tiers; Public API access bundled with a 1,000-call-per-key-per-day free quota and ~$0.003 per-call overage in live mode.

## Rate Limits

- [Mindbody Rate Limits](rate-limits/mindbody-rate-limits.yml) — 1,000 calls per API key per day across both live and sandbox modes; live overage billed rather than throttled; sandbox hard-capped; webhook subscriber response SLA of 10s with 15-minute retries up to 3 hours.

## FinOps

- [Mindbody FinOps](finops/mindbody-finops.yml) — FOCUS 1.3 aligned, Tiered Subscription + Pay-As-You-Go billing model, monthly invoicing in USD; meters for software_subscription, api_calls_live, api_calls_sandbox, payment_transactions, payment_volume, sms_messages, webhook_deliveries, marketplace_discovery_fees, and add_on_subscriptions.

## Vocabulary

- [Mindbody Vocabulary](vocabulary/mindbody-vocabulary.yml) — Unified taxonomy mapping 13 operational resources, 8 actions, 13 workflows, and 7 personas across the operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Mindbody Spectral Ruleset](rules/mindbody-spectral-rules.yml) — 44 rules across 13 categories enforcing Mindbody API conventions (info/metadata, OpenAPI version, servers, paths, operations, tags, parameters, request bodies, responses, schemas, security, HTTP method conventions, Microcks).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
