---
name: informatica-schedule-lifecycle
description: Manage the full lifecycle of schedules in Informatica.
api: openapi/informatica-schedules-api-openapi.yml
operations:
- listSchedules
- createSchedule
- getSchedule
- updateSchedule
- deleteSchedule
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/informatica-schedules-api-openapi.yml ; every operationId checked against the contract
---

# informatica-schedule-lifecycle

Manage the full lifecycle of schedules in Informatica.

## Steps

1. `listSchedules` - include query parameters `page`, `limit` and header `icSessionId`.
2. `createSchedule` - provide the required request body fields and header `icSessionId`.
3. `getSchedule` - supply path parameter `scheduleId` and header `icSessionId`.
4. `updateSchedule` - supply path parameter `scheduleId`, the request body fields to modify, and header `icSessionId`.
5. `deleteSchedule` - supply path parameter `scheduleId` and header `icSessionId`.

## Rules

- All requests must include the `icSessionId` API key in the request header.
- List operations support pagination via the `page` and `limit` query parameters.
