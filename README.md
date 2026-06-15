# Mintlify (mintlify)

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
