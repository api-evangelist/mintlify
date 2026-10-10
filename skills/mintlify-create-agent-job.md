---
name: mintlify-create-agent-job
description: Create an agent job and retrieve its status.
api: openapi/mintlify-agent-api-openapi.yml
operations:
- createAgentJob
- getAgentJob
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mintlify-agent-api-openapi.yml ; every operationId checked against the contract
---

# mintlify-create-agent-job

Create an agent job and retrieve its status.

## Steps

1. 1. Call `createAgentJob` with the required request body fields (as defined in the API contract).
2. 2. Call `getAgentJob` with the `projectId` path parameter and the `id` returned from the create step.

## Rules

- Auth: Include either the `adminKey` or `assistantKey` HTTP header as required by the API.
- No idempotency key is defined for these endpoints.
- Pagination is not applicable.
- Error responses follow standard HTTP status codes; specific error codes are not documented.
