---
name: mintlify-update-documentation
description: Trigger a documentation update for a project and then poll for its status.
api: openapi/mintlify-update-api-openapi.yml
operations:
- triggerUpdate
- getUpdateStatus
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/mintlify-update-api-openapi.yml ; every operationId checked against the contract
---

# mintlify-update-documentation

Trigger a documentation update for a project and then poll for its status.

## Steps

1. 1. Call `triggerUpdate` with the path parameter `projectId`.
2. 2. Call `getUpdateStatus` with the path parameter `statusId` returned from the previous step.

## Rules

- Include an authentication header using either the `adminKey` or `assistantKey` scheme.
- No rate limit is documented; on exhaustion the API returns no specific HTTP status.
