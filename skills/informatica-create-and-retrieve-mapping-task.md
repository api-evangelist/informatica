---
name: informatica-create-and-retrieve-mapping-task
description: Create a new mapping task and then retrieve it by its identifier.
api: openapi/informatica-mapping-tasks-api-openapi.yml
operations:
- createMappingTask
- getMappingTask
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/informatica-mapping-tasks-api-openapi.yml ; every operationId checked against the contract
---

# informatica-create-and-retrieve-mapping-task

Create a new mapping task and then retrieve it by its identifier.

## Steps

1. 1. Use `createMappingTask` with the request body fields required to define the new task.
2. 2. Use `getMappingTask` with the path parameter `taskId` returned from the create step.

## Rules

- Auth: Include the `icSessionId` API key in the request header `icSessionId`.
- Pagination: When listing tasks, use query parameters `page` and `limit`.
- Idempotency: The `createMappingTask` operation is not idempotent; repeat calls will create duplicate tasks.
- Errors: On authentication failure, the API returns HTTP 401; on missing task, HTTP 404.
