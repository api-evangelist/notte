# Notte (notte)

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
