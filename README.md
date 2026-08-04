# Mintlify (mintlify)

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

Mintlify is an AI-native intelligent documentation platform designed for the next generation of technical documentation, combining beautiful out-of-the-box design with advanced collaboration and AI capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Documentation

## Timestamps

- **Created:** 2026-01-05
- **Modified:** 2026-05-30

## APIs

### Mintlify

Mintlify is a developer documentation platform that helps product and engineering teams create, maintain, and host modern docs. It uses a docs‑as‑code workflow (Markdown in your repo) with a rich component library and GitHub integration. Mintlify can generate polished API references from OpenAPI/Swagger or Postman, add interactive “Try it” requests and dynamic code samples/SDKs, and includes AI tools (like its Doc Writer) to draft and update docs from your code.

- **Human URL:** [ https://www.mintlify.com/]( https://www.mintlify.com/)

#### Tags

- Documentation

#### Properties

- [Documentation]( https://www.mintlify.com/)
- [A P I Reference Documentation](https://www.mintlify.com/docs/api/introduction)
- [Postman Collection](collections/mintlify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mintlify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mintlify Update API

The Mintlify Update API allows you to programmatically trigger deployment updates for your documentation project and check update status. You can queue a deployment update from your configured deployment branch by calling the trigger endpoint, and then monitor its progress using the status endpoint. This is useful for integrating documentation updates into CI/CD pipelines after updating your OpenAPI document or documentation source. Authentication requires an admin API key with the mint_ prefix.

- **Human URL:** [https://www.mintlify.com/docs/api/update/trigger](https://www.mintlify.com/docs/api/update/trigger)

#### Tags

- Deployment
- Documentation

#### Properties

- [A P I Reference Documentation](https://www.mintlify.com/docs/api/update/trigger)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mintlify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mintlify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mintlify Agent API

The Mintlify Agent API enables you to programmatically automate documentation editing through agent jobs. You can create agent jobs that generate and edit documentation based on provided messages and branch information, retrieve the details and current progress of a specific job, or list all jobs for a domain. The agent monitors your codebase, detects changes, and proposes documentation updates automatically. Authentication requires an admin API key with the mint_ prefix.

- **Human URL:** [https://www.mintlify.com/docs/api/agent/create-agent-job](https://www.mintlify.com/docs/api/agent/create-agent-job)

#### Tags

- AI
- Automation
- Documentation

#### Properties

- [A P I Reference Documentation](https://www.mintlify.com/docs/api/agent/create-agent-job)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mintlify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mintlify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mintlify Assistant API

The Mintlify Assistant API allows you to embed the AI chat experience grounded in your documentation into any application. You can generate assistant messages trained on your docs and perform semantic and keyword searches across your documentation with configurable filtering and pagination. Responses include citations pointing users to the relevant documentation pages. Authentication requires an assistant API key with the mint_dsc_ prefix, which is safe for frontend implementation.

- **Human URL:** [https://www.mintlify.com/docs/api/assistant/create-assistant-message-v2](https://www.mintlify.com/docs/api/assistant/create-assistant-message-v2)

#### Tags

- AI
- Documentation
- Search

#### Properties

- [A P I Reference Documentation](https://www.mintlify.com/docs/api/assistant/create-assistant-message-v2)
- [A P I Reference Documentation](https://www.mintlify.com/docs/api/assistant/search)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mintlify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mintlify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mintlify Analytics API

The Mintlify Analytics API enables you to export user feedback and assistant conversation history from your documentation for external analysis. You can retrieve user feedback responses and AI assistant chat interaction logs to gain deeper insights into how users engage with your documentation. Authentication requires an admin API key with the mint_ prefix.

- **Human URL:** [https://www.mintlify.com/docs/api/introduction](https://www.mintlify.com/docs/api/introduction)

#### Tags

- Analytics
- Documentation

#### Properties

- [A P I Reference Documentation](https://www.mintlify.com/docs/api/introduction)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mintlify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mintlify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.mintlify.com/)
- [Customers](https://www.mintlify.com/customers)
- [Blog](https://www.mintlify.com/blog)
- [Pricing](https://www.mintlify.com/pricing)
- [Guide](https://www.mintlify.com/guides/introduction)
- [Documentation](https://www.mintlify.com/docs/api/introduction)
- [Changelog](https://www.mintlify.com/docs/changelog)
- [Sign Up](https://dashboard.mintlify.com/signup)
- [Login](https://dashboard.mintlify.com/login)
- [Getting Started](https://www.mintlify.com/docs/quickstart)
- [Status Page](https://status.mintlify.com/)
- [Git Hub](https://github.com/mintlify)
- [LinkedIn](https://www.linkedin.com/company/mintlify/posts)
- [Twitter](https://x.com/mintlify)
- [Privacy Policy](https://www.mintlify.com/legal/privacy)
- [Terms of Service](https://www.mintlify.com/legal/terms)
- [Security](https://security.mintlify.com)
- [Support](https://www.mintlify.com/docs/contact-support)
- [Enterprise](https://www.mintlify.com/enterprise)
- [Startups](https://www.mintlify.com/startups)
- [Open Source](https://www.mintlify.com/oss-program)
- [Sales Contact](https://www.mintlify.com/contact/sales)
- [Careers](https://www.mintlify.com/careers)
- [Testimonials](https://www.mintlify.com/wall-of-love)
- [Migration](https://www.mintlify.com/switch)
- [Responsible Disclosure](https://www.mintlify.com/security/responsible-disclosure)
- [YouTube](https://www.youtube.com/@GetMintlify/videos)
- [L L Ms Txt](https://www.mintlify.com/docs/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
