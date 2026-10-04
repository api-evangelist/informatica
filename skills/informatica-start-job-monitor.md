---
name: informatica-start-job-monitor
description: Start a job, monitor its activity log, and stop it when needed.
api: openapi/informatica-jobs-api-openapi.yml
operations:
- startJob
- getActivityLog
- stopJob
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/informatica-jobs-api-openapi.yml ; every operationId checked against the contract
---

# informatica-start-job-monitor

Start a job, monitor its activity log, and stop it when needed.

## Steps

1. 1. Call `startJob` with required request body and include the `icSessionId` header for authentication.
2. 2. Call `getActivityLog` with query parameters `page` and `limit` to retrieve log entries, also sending the `icSessionId` header.
3. 3. Call `stopJob` with the job identifier in the request body and include the `icSessionId` header.

## Rules

- Authentication: Provide the `icSessionId` API key in the request header `icSessionId`.
- Pagination: Use `page` and `limit` query parameters when calling `getActivityLog`.
- Idempotency: Not applicable; no idempotency keys are defined for these operations.
- Errors: On rate‑limit exhaustion the API returns no specific HTTP status code.
