# Blissfully (blissfully)

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

Blissfully was a SaaS management platform providing SaaS discovery, spend optimization, and workflow automation for IT and finance teams. Blissfully was acquired by Vendr in 2022 and integrated into the Vendr platform. Vendr is now a leading SaaS buying and management platform that helps companies control software spend through vendor negotiations, pricing intelligence, and procurement automation. The Vendr API provides access to software catalog data, pricing intelligence, and scope management capabilities.

**URL:** [https://www.vendr.com](https://www.vendr.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Procurement, SaaS Discovery, SaaS Management, Software Procurement, Spend Optimization, Vendor Management

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-19

## APIs

### Vendr Catalog API
Provides structured product catalog attributes derived from thousands of unstructured software quotes. Enables buyers to understand product breadth, available add-ons, pricing tiers, and feature comparisons across the Vendr software catalog.

**Human URL:** [https://developers.vendr.com](https://developers.vendr.com)

#### Tags:

 - Procurement, SaaS Management, Software Catalog

#### Properties

- [Documentation](https://developers.vendr.com)
- [OpenAPI](openapi/blissfully-vendr-catalog-api-openapi.yaml)

### Vendr Pricing API
Delivers actionable pricing insights including fair price predictions and negotiation guidance tailored to the buyer's specific requirements, contract size, and company profile.

**Human URL:** [https://developers.vendr.com](https://developers.vendr.com)

#### Tags:

 - Pricing, Procurement, SaaS Management

#### Properties

- [Documentation](https://developers.vendr.com)

### Vendr Scope API
Enables communication of detailed purchasing needs in text or file format, whether for complex enterprise software requirements or uploaded quotes from vendors.

**Human URL:** [https://developers.vendr.com](https://developers.vendr.com)

#### Tags:

 - Procurement, SaaS Management, Scope

#### Properties

- [Documentation](https://developers.vendr.com)

### Vendr Webhooks API
Facilitates creation and management of webhooks for monitoring Vendr's data processing events, enabling integration with procurement workflows and notification systems.

**Human URL:** [https://developers.vendr.com](https://developers.vendr.com)

#### Tags:

 - Procurement, SaaS Management, Webhooks

#### Properties

- [Documentation](https://developers.vendr.com)

## Common Properties

- [Website](https://www.vendr.com)
- [Documentation](https://developers.vendr.com)
- [Sign Up](https://www.vendr.com/demo)
- [Terms of Service](https://www.vendr.com/legal/terms-of-service)
- [Privacy Policy](https://www.vendr.com/legal/privacy-policy)
- [Blog](https://www.vendr.com/blog)
- [Authentication](https://developers.vendr.com)
- [SpectralRules](rules/blissfully-spectral-rules.yml)
- [NaftikoCapability](capabilities/blissfully-saas-procurement.yaml)
- [Vocabulary](vocabulary/blissfully-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Catalog API | Structured product catalog attributes derived from thousands of unstructured software quotes, covering product breadth, add-ons, and feature comparisons. |
| Pricing API | Actionable pricing insights including fair price predictions and negotiation guidance tailored to specific buyer requirements and contract sizes. |
| Scope API | Communication of detailed purchasing needs in text or file format for complex enterprise software procurement requirements. |
| Webhooks API | Creation and management of webhooks for monitoring Vendr data processing events and integrating with procurement workflows. |
| MCP Integration | Model Context Protocol (MCP) integration options including Claude Desktop extension, GitHub-based local setup, and custom AI app configuration. |
| SaaS Benchmarking | Pricing benchmarks powered by Vendr's database of real software purchases across thousands of companies and vendors. |

## Use Cases

| Name | Description |
|------|-------------|
| Software Pricing Intelligence | Procurement teams access fair price benchmarks and negotiation guidance before and during software vendor negotiations. |
| SaaS Spend Optimization | Finance and IT teams gain visibility into software spend and identify optimization opportunities across the SaaS portfolio. |
| AI-Powered Procurement | AI applications integrate Vendr catalog and pricing data via MCP or API to provide intelligent software procurement recommendations. |
| Vendor Management Integration | Enterprise procurement platforms integrate Vendr data to enrich vendor records with pricing benchmarks and product catalog attributes. |
| Contract Renewal Automation | Webhook integrations notify procurement workflows of contract renewal events and pricing change signals from the Vendr platform. |

## Integrations

| Name | Description |
|------|-------------|
| Claude Desktop | Native MCP extension for Claude Desktop enabling AI-assisted software procurement research directly in the Claude interface. |
| Slack | Vendr integrates with Slack for procurement workflow notifications and team collaboration on software purchases. |
| Salesforce | CRM integration enabling sales teams to access vendor and software catalog data within Salesforce. |
| NetSuite | ERP integration for automated purchase order creation and financial tracking of SaaS spend through Vendr. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Vendr Catalog API](openapi/blissfully-vendr-catalog-api-openapi.yaml)

### JSON Schema

- [Product](json-schema/blissfully-product-schema.json)
- [Vendor](json-schema/blissfully-vendor-schema.json)
- [Pricing Response](json-schema/blissfully-pricing-response-schema.json)
- [Webhook](json-schema/blissfully-webhook-schema.json)

### JSON Structure

- [Product](json-structure/blissfully-product-structure.json)
- [Vendor](json-structure/blissfully-vendor-structure.json)
- [Pricing Response](json-structure/blissfully-pricing-response-structure.json)
- [Webhook](json-structure/blissfully-webhook-structure.json)

### JSON-LD

- [Blissfully Context](json-ld/blissfully-context.jsonld)

### Examples

- [Product Example](examples/blissfully-product-example.json)
- [Vendor Example](examples/blissfully-vendor-example.json)
- [Pricing Response Example](examples/blissfully-pricing-response-example.json)
- [Webhook Example](examples/blissfully-webhook-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Vendr Catalog API](capabilities/shared/vendr-catalog-api.yaml) — 5 operations for product catalog, vendor data, pricing intelligence, and webhook management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Blissfully SaaS Procurement](capabilities/blissfully-saas-procurement.yaml) | Vendr Catalog API, Vendr Pricing API | 5 | Procurement Managers, IT Managers, Finance Analysts, AI Assistants |

## Vocabulary

- [Blissfully Vocabulary](vocabulary/blissfully-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 4 actions, 1 workflow, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Blissfully Spectral Rules](rules/blissfully-spectral-rules.yml) — 28 rules across 11 categories enforcing Vendr API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
