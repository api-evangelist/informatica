---
name: informatica-create-and-test-connection
description: Create a new connection and verify it works by testing the connection.
api: openapi/informatica-connections-api-openapi.yml
operations:
- createConnection
- testConnection
- getConnection
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/informatica-connections-api-openapi.yml ; every operationId checked against the contract
---

# informatica-create-and-test-connection

Create a new connection and verify it works by testing the connection.

## Steps

1. 1. Use `createConnection` with the request body fields required to define the connection.
2. 2. Use `testConnection` with path parameter `connectionId` returned from step 1; no additional fields required.
3. 3. Use `getConnection` with path parameter `connectionId` to retrieve the created connection details.

## Rules

- Auth: include header `icSessionId` with the API key value.
- Pagination: supported on `listConnections` with query parameters `page` and `limit` (not used in this task).
- Idempotency: not applicable for these operations.
