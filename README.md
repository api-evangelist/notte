# Notte (notte)

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

Notte is web browser and agent infrastructure for AI. The REST API at api.notte.cc provisions cloud browser sessions, runs autonomous web agents from natural-language tasks, observes and acts on pages, scrapes structured data, and manages personas, vaults, profiles, and serverless functions. The core framework is open source (SSPL-1.0) on GitHub under nottelabs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/notte/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/notte/refs/heads/main/apis.yml)

## Tags

- AI
- Web Agents
- Browser Automation
- Sessions
- Scraping

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Notte Sessions API

Start, status, and stop remote cloud browser sessions with stealth, proxies, and CAPTCHA solving. Manage cookies, network logs, replay, debug info, and CDP/viewer connection URLs for Playwright, Puppeteer, Selenium, or browser-use.

- **Human URL:** [https://docs.notte.cc/api-reference/sessions/session-start](https://docs.notte.cc/api-reference/sessions/session-start)
- **Base URL:** `https://api.notte.cc`

#### Tags

- Sessions
- Cloud Browser
- CDP

#### Properties

- [Documentation](https://docs.notte.cc/features/sessions/overview)
- [API Reference](https://docs.notte.cc/api-reference/sessions/session-start)
- [OpenAPI](openapi/notte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/nottelabs/notte)

### Notte Agents API

Run autonomous web agents that take a natural-language task and act on a browser session. Start, poll status, stop, list agents, request structured (Pydantic) output, and retrieve the generated workflow script.

- **Human URL:** [https://docs.notte.cc/api-reference/agents/agent-start](https://docs.notte.cc/api-reference/agents/agent-start)
- **Base URL:** `https://api.notte.cc`

#### Tags

- Agents
- Autonomous
- Natural Language

#### Properties

- [Documentation](https://docs.notte.cc/features/agents/overview)
- [API Reference](https://docs.notte.cc/api-reference/agents/agent-start)
- [OpenAPI](openapi/notte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/nottelabs/notte)

### Notte Page Observe / Step / Scrape API

Notte's perception layer for a live session - observe the page to list available actions, execute (step) an action such as click/fill/scroll/navigate, scrape structured content from the current page, and capture screenshots.

- **Human URL:** [https://docs.notte.cc/api-reference/sessions/page-observe](https://docs.notte.cc/api-reference/sessions/page-observe)
- **Base URL:** `https://api.notte.cc`

#### Tags

- Perception
- Observe
- Step
- Scrape

#### Properties

- [Documentation](https://docs.notte.cc/features/perception/overview)
- [API Reference](https://docs.notte.cc/api-reference/sessions/page-observe)
- [OpenAPI](openapi/notte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/nottelabs/notte)

### Notte Scraping API

One-shot scraping endpoints that fetch a URL (or accept raw HTML) and return main content, links, images, or AI-extracted structured data against a response format, plus an AI web search endpoint.

- **Human URL:** [https://docs.notte.cc/api-reference/scrape/scrape-webpage](https://docs.notte.cc/api-reference/scrape/scrape-webpage)
- **Base URL:** `https://api.notte.cc`

#### Tags

- Scraping
- Extraction
- Structured Data

#### Properties

- [Documentation](https://docs.notte.cc/features/scraping/overview)
- [API Reference](https://docs.notte.cc/api-reference/scrape/scrape-webpage)
- [OpenAPI](openapi/notte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/nottelabs/notte)

### Notte Personas and Vaults API

Personas are disposable digital identities with email addresses, phone numbers, and automated 2FA for account workflows. Vaults securely store credentials and credit cards that are injected into agent and session runs.

- **Human URL:** [https://docs.notte.cc/api-reference/personas/persona-create](https://docs.notte.cc/api-reference/personas/persona-create)
- **Base URL:** `https://api.notte.cc`

#### Tags

- Personas
- Vaults
- Credentials

#### Properties

- [Documentation](https://docs.notte.cc/features/personas/overview)
- [API Reference](https://docs.notte.cc/api-reference/personas/persona-create)
- [OpenAPI](openapi/notte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/nottelabs/notte)

## Common Properties

- [GitHub Organization](https://github.com/nottelabs)
- [LinkedIn](https://www.linkedin.com/company/nottelabs)
- [Website](https://notte.cc)
- [Documentation](https://docs.notte.cc)
- [Plans](plans/notte-plans-pricing.yml)
- [Rate Limits](rate-limits/notte-rate-limits.yml)
- [Fin Ops](finops/notte-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
