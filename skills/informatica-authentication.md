---
name: authentication
description: Authenticate with Informatica IICS Platform REST API
api: https://dm-us.informaticacloud.com
operations:
  - login
  - logout
---

## Steps
1. **Login** – POST to `/ma/api/v2/user/login` with JSON body containing `username` and `password`. Use operationId `login` from the OpenAPI spec.
2. **Logout** – POST to `/saas/api/v2/user/logout` using the `icSessionId` header obtained from login. Uses operationId `logout`.

## Idempotency & Concurrency
- `login` creates a session; repeatable but each call yields a new session ID.
- `logout` is idempotent; calling it multiple times after a session is ended returns `401`.
