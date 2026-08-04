# Informatica (informatica)

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

Collection of APIs for Informatica Intelligent Cloud Services (IICS) and Intelligent Data Management Cloud (IDMC), providing programmatic access to data integration, data governance, data quality, master data management, B2B gateway, and platform administration capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Address Verification
- B2B Gateway
- Cloud Services
- Data Governance
- Data Integration
- Data Profiling
- Data Quality
- Enterprise Software
- ETL
- IDMC
- IICS
- Master Data Management
- Reference Data Management

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Informatica Platform REST API

The Informatica Intelligent Cloud Services Platform REST API provides access to platform-level resources including login and authentication, roles and privileges, user and user group management, organizations, connections, schedules, runtime environments, Secure Agent services, object permissions, export and import, source control, projects and folders, licenses, metering data, and security logs. Supports version 2 (JSON and XML) and version 3 (JSON) resource formats.

- **Human URL:** [https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html](https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html)

#### Tags

- Authentication
- Platform
- Roles
- Users

#### Properties

- [Documentation](https://docs.informatica.com/integration-cloud/cloud-platform/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html)
- [Documentation](https://docs.informatica.com/integration-cloud/b2b-gateway/current-version/rest-api-reference/platform-rest-api-version-3-resources.html)
- [Documentation](https://docs.informatica.com/integration-cloud/b2b-gateway/current-version/rest-api-reference/platform-rest-api-version-3-resources/roles.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/informatica/refs/heads/main/openapi/informatica-platform-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/informatica-platform-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/informatica-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/informatica-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/informatica-connection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-login-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-login-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-connection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-connection-create-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-connection-update-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-mapping-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-mapping-parameter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-mapping-in-out-parameter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-mapping-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-mapping-task-create-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-mapping-task-update-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-job-start-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-job-start-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-job-stop-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-activity-log-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-schedule-create-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/informatica-platform-rest-error-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/informatica-platform-rest-login-request-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-login-response-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-connection-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-connection-create-request-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-connection-update-request-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-mapping-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-mapping-parameter-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-mapping-in-out-parameter-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-mapping-task-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-mapping-task-create-request-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-mapping-task-update-request-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-job-start-request-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-job-start-response-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-job-stop-request-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-activity-log-entry-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-schedule-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-schedule-create-request-structure.json)
- [JSON Structure](json-structure/informatica-platform-rest-error-response-structure.json)
- [Example](examples/informatica-platform-rest-login-request-example.json)
- [Example](examples/informatica-platform-rest-login-response-example.json)
- [Example](examples/informatica-platform-rest-connection-example.json)
- [Example](examples/informatica-platform-rest-connection-create-request-example.json)
- [Example](examples/informatica-platform-rest-connection-update-request-example.json)
- [Example](examples/informatica-platform-rest-mapping-example.json)
- [Example](examples/informatica-platform-rest-mapping-parameter-example.json)
- [Example](examples/informatica-platform-rest-mapping-in-out-parameter-example.json)
- [Example](examples/informatica-platform-rest-mapping-task-example.json)
- [Example](examples/informatica-platform-rest-mapping-task-create-request-example.json)
- [Example](examples/informatica-platform-rest-mapping-task-update-request-example.json)
- [Example](examples/informatica-platform-rest-job-start-request-example.json)
- [Example](examples/informatica-platform-rest-job-start-response-example.json)
- [Example](examples/informatica-platform-rest-job-stop-request-example.json)
- [Example](examples/informatica-platform-rest-activity-log-entry-example.json)
- [Example](examples/informatica-platform-rest-schedule-example.json)
- [Example](examples/informatica-platform-rest-schedule-create-request-example.json)
- [Example](examples/informatica-platform-rest-error-response-example.json)
- [JSON-LD](json-ld/informatica-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/informatica-platform-rest-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Informatica Data Integration REST API

The Data Integration REST API provides programmatic access to manage data integration assets and operations, including connections, mappings, mapping tasks, dynamic mapping tasks, taskflows, code tasks, connectors, data preview, fields, file listeners, file transfer, and hierarchical mappers. Uses version 2 resources with JSON or XML format.

- **Human URL:** [https://docs.informatica.com/integration-cloud/data-integration/current-version/rest-api-reference/data-integration-rest-api.html](https://docs.informatica.com/integration-cloud/data-integration/current-version/rest-api-reference/data-integration-rest-api.html)

#### Tags

- Connections
- Data Integration
- ETL
- Mappings

#### Properties

- [Documentation](https://docs.informatica.com/integration-cloud/data-integration/current-version/rest-api-reference/data-integration-rest-api.html)
- [API Reference](https://docs.informatica.com/integration-cloud/data-integration/current-version/rest-api-reference/rest-api-resource-quick-references/data-integration-resource-quick-reference.html)
- [Postman Collection](collections/informatica-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/informatica-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Informatica Cloud Data Governance and Catalog API

The Cloud Data Governance and Catalog API enables programmatic creation and management of assets, searching for assets, and viewing asset details within Informatica Data Governance and Catalog. Calls can be made using a REST client, the cURL tool, or a suitable programming interface.

- **Human URL:** [https://docs.informatica.com/data-quality-cloud/cloud-data-governance-and-catalog/current-version.html](https://docs.informatica.com/data-quality-cloud/cloud-data-governance-and-catalog/current-version.html)

#### Tags

- Data Catalog
- Data Governance

#### Properties

- [Documentation](https://docs.informatica.com/data-quality-cloud/cloud-data-governance-and-catalog/current-version.html)
- [Postman Collection](collections/informatica-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/informatica-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Informatica Cloud Data Profiling REST API

The Cloud Data Profiling REST API allows interaction with the Data Profiling Service through API calls to create, delete, update, and run queries and profiles within your organization. Supports platform REST API version 2 and version 3 resources and service-specific resources.

- **Human URL:** [https://docs.informatica.com/data-governance-and-quality-cloud/cloud-data-profiling/current-version/data-profiling/data-profiling/data-profiling-rest-api.html](https://docs.informatica.com/data-governance-and-quality-cloud/cloud-data-profiling/current-version/data-profiling/data-profiling/data-profiling-rest-api.html)

#### Tags

- Data Profiling
- Data Quality

#### Properties

- [Documentation](https://docs.informatica.com/data-governance-and-quality-cloud/cloud-data-profiling/current-version/data-profiling/data-profiling/data-profiling-rest-api.html)
- [Getting Started](https://docs.informatica.com/data-governance-and-quality-cloud/cloud-data-profiling/h2l/1547-getting-started-with-cloud-data-profiling-rest-api/getting-started-with-cloud-data-profiling-rest-api/overview.html)
- [Postman Collection](collections/informatica-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/informatica-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Informatica Cloud Address Verification API

The Cloud Address Verification API is a REST API-based solution for verifying and validating postal addresses in real time. You can integrate the Address Verification service API endpoints into your application using a REST client, the cURL tool, or any suitable programming interface.

- **Human URL:** [https://docs.informatica.com/data-governance-and-quality-cloud/data-quality/current-version/cloud-address-verification-api/introduction.html](https://docs.informatica.com/data-governance-and-quality-cloud/data-quality/current-version/cloud-address-verification-api/introduction.html)

#### Tags

- Address Verification
- Data Quality

#### Properties

- [Documentation](https://docs.informatica.com/data-governance-and-quality-cloud/data-quality/current-version/cloud-address-verification-api/introduction.html)
- [Postman Collection](collections/informatica-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/informatica-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Informatica B2B Gateway REST API

The B2B Gateway REST APIs enable running inbound and outbound partner flows, querying the status of events, and getting control numbers for outbound EDI X12 and EDIFACT messages through programmatic API calls.

- **Human URL:** [https://docs.informatica.com/ipaas/b2b-gateway/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html](https://docs.informatica.com/ipaas/b2b-gateway/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html)

#### Tags

- B2B
- EDI
- Gateway

#### Properties

- [Documentation](https://docs.informatica.com/ipaas/b2b-gateway/current-version/rest-api-reference/informatica-intelligent-cloud-services-rest-api.html)
- [Postman Collection](collections/informatica-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/informatica-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Informatica Reference 360 REST API

The Reference 360 REST API enables programmatic management of reference data, including exporting and importing reference data sets, managing code values and value mappings, retrieving asset details, managing code lists, crosswalks, hierarchies, and audit trails. Supports multiple API versions for model import and export operations.

- **Human URL:** [https://docs.informatica.com/master-data-management-cloud/reference-360/current-version/reference-360/reference-360-rest-api.html](https://docs.informatica.com/master-data-management-cloud/reference-360/current-version/reference-360/reference-360-rest-api.html)

#### Tags

- Master Data Management
- Reference Data

#### Properties

- [Documentation](https://docs.informatica.com/master-data-management-cloud/reference-360/current-version/reference-360/reference-360-rest-api.html)
- [Postman Collection](collections/informatica-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/informatica-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/informatica)
- [LinkedIn](https://www.linkedin.com/company/informatica)
- [Portal](https://developer.informatica.com/)
- [Documentation](https://docs.informatica.com/)
- [Knowledge Center](https://knowledge.informatica.com/)
- [Support](https://www.informatica.com/support.html)
- [Support](https://network.informatica.com/)
- [Login](https://dm-us.informaticacloud.com/identity-service/home)
- [Spectral Rules](rules/informatica-spectral-rules.yml)
- [Vocabulary](vocabulary/informatica-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
