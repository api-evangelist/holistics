# Holistics (holistics)

Holistics is a self-service business intelligence and analytics platform built around code-based data modeling (AML - Analytics Modeling Language), Git version control, and a SQL/dataset semantic layer. Its REST API lets teams query datasets and reports, export data to CSV/JSON/XLSX, trigger data imports and transforms, and poll ETL jobs, while a JWT-signed Embed API powers embedded, multi-tenant analytics inside customer applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/holistics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/holistics/refs/heads/main/apis.yml)

## Tags

- Business Intelligence
- Analytics
- Self-Service BI
- Data Modeling
- Embedded Analytics

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Holistics Data Schedules & Jobs API

Programmatically execute data imports and data transforms, and poll ETL job status (logs and last-run jobs) for Holistics data pipelines.

- **Human URL:** [https://docs-v2.holistics.io/api/data-pipeline-api](https://docs-v2.holistics.io/api/data-pipeline-api)
- **Base URL:** `https://secure.holistics.io/api/v2`

#### Tags

- Data Pipeline
- Jobs
- ETL
- Schedules

#### Properties

- [Documentation](https://docs-v2.holistics.io/api/data-pipeline-api)
- [API Reference](https://docs-v2.holistics.io/api)
- [OpenAPI](openapi/holistics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/holistics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/holistics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Holistics Dashboards & Reports API

Submit report and dataset queries, generate SQL without executing, and retrieve paginated query results from Holistics reports and the dataset semantic layer.

- **Human URL:** [https://docs-v2.holistics.io/api/getting-report-data-api](https://docs-v2.holistics.io/api/getting-report-data-api)
- **Base URL:** `https://secure.holistics.io/api/v2`

#### Tags

- Reports
- Dashboards
- Datasets
- Query

#### Properties

- [Documentation](https://docs-v2.holistics.io/api/getting-report-data-api)
- [API Reference](https://docs.holistics.io/api/v2/query-data)
- [OpenAPI](openapi/holistics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/holistics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/holistics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Holistics Export API

Submit asynchronous export jobs for report data in CSV, JSON, or XLSX format, poll export job status, and download the resulting file.

- **Human URL:** [https://docs-v2.holistics.io/api/getting-report-data-api](https://docs-v2.holistics.io/api/getting-report-data-api)
- **Base URL:** `https://secure.holistics.io/api/v2`

#### Tags

- Export
- CSV
- JSON
- XLSX

#### Properties

- [Documentation](https://docs-v2.holistics.io/api/getting-report-data-api)
- [OpenAPI](openapi/holistics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/holistics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/holistics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Holistics Users & Permissions API

Per-user API keys generated in user settings authorize programmatic access via the X-Holistics-Key header; permissions and row-level access follow the calling user's account scope.

- **Human URL:** [https://docs-v2.holistics.io/docs/holistics-api-for-python-and-programmatic-platform-access](https://docs-v2.holistics.io/docs/holistics-api-for-python-and-programmatic-platform-access)
- **Base URL:** `https://secure.holistics.io/api/v2`

#### Tags

- Users
- Permissions
- API Keys
- Authentication

#### Properties

- [Documentation](https://docs-v2.holistics.io/docs/holistics-api-for-python-and-programmatic-platform-access)
- [OpenAPI](openapi/holistics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Holistics Embedded Analytics API

Server-side JWT (HS256) signed embed tokens carrying customer_id, exp, and dynamic filter claims render row-level-secured dashboards via the /embed/<embed_code>?_token=<jwt> URL pattern for multi-tenant embedded analytics.

- **Human URL:** [https://docs-v2.holistics.io/docs/embedded-analytics/](https://docs-v2.holistics.io/docs/embedded-analytics/)
- **Base URL:** `https://secure.holistics.io`

#### Tags

- Embedded Analytics
- JWT
- Embed Token
- Multi-Tenant

#### Properties

- [Documentation](https://docs-v2.holistics.io/docs/embedded-analytics/)
- [API Reference](https://www.holistics.io/bi-tools/concepts/jwt-embedding/)
- [OpenAPI](openapi/holistics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/holistics)
- [LinkedIn](https://www.linkedin.com/company/holistics)
- [Website](https://www.holistics.io)
- [Documentation](https://docs-v2.holistics.io/api)
- [Plans](plans/holistics-plans-pricing.yml)
- [Rate Limits](rate-limits/holistics-rate-limits.yml)
- [Fin Ops](finops/holistics-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
