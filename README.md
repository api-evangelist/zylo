# Zylo (zylo)

Zylo is a SaaS management platform that helps organizations optimize their software usage and spending. By providing insights into software utilization, licensing agreements, and renewal dates, Zylo enables companies to make informed decisions about their software investments. With Zylo, businesses can track their software expenses, manage subscriptions, and ensure compliance with licensing agreements.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zylo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zylo/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Budgets
- SaaS Management
- Spend

## Timestamps

- **Created:** 2025-07-15
- **Modified:** 2026-05-19

## APIs

### Zylo Applications API

Applications represent SaaS software products tracked within the Zylo platform, including metadata such as owner, category, and custom fields.

- **Human URL:** [https://developer.zylo.com/](https://developer.zylo.com/)
- **Base URL:** `https://api.zylo.com/v1`

#### Tags

- Application

#### Properties

- [OpenAPI](openapi/zylo-applications-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zylo-applications-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zylo-applications-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developer.zylo.com/reference/introduction)
- [Postman Collection](https://www.postman.com/zyloteam/zylo-inc/collection/kuv1fac/zylo-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [JSON Schema](json-schema/subscription.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/application.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/export-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/import-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/zylo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Zylo Export Jobs API

Export Jobs allow you to export subscription data asynchronously. You first create an export job, then retrieve the results when the job is complete.

- **Human URL:** [https://developer.zylo.com/](https://developer.zylo.com/)
- **Base URL:** `https://api.zylo.com/v1`

#### Tags

- Export Jobs

#### Properties

- [OpenAPI](openapi/zylo-export-jobs-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zylo-export-jobs-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zylo-export-jobs-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developer.zylo.com/reference/introduction)
- [Postman Collection](https://www.postman.com/zyloteam/zylo-inc/collection/kuv1fac/zylo-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [JSON Schema](json-schema/subscription.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/application.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/export-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/import-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/zylo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Zylo Import Jobs API

Import Jobs allow you to import user, license, and activity data from non-integrated applications via CSV upload to optimize license usage across SaaS applications.

- **Human URL:** [https://developer.zylo.com/](https://developer.zylo.com/)
- **Base URL:** `https://api.zylo.com/v1`

#### Tags

- Import Jobs

#### Properties

- [OpenAPI](openapi/zylo-import-jobs-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zylo-import-jobs-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zylo-import-jobs-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developer.zylo.com/reference/introduction)
- [Postman Collection](https://www.postman.com/zyloteam/zylo-inc/collection/kuv1fac/zylo-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [JSON Schema](json-schema/subscription.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/application.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/export-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/import-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/zylo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Zylo Subscriptions API

Subscriptions are configured instances created in the Zylo user interface. They typically have a 1:1 relationship to a given application, though you may also have multiple subscriptions to the same application within your organization.

- **Human URL:** [https://developer.zylo.com/](https://developer.zylo.com/)
- **Base URL:** `https://api.zylo.com/v1`

#### Tags

- Subscription

#### Properties

- [OpenAPI](openapi/zylo-subscriptions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zylo-subscriptions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zylo-subscriptions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developer.zylo.com/reference/introduction)
- [Postman Collection](https://www.postman.com/zyloteam/zylo-inc/collection/kuv1fac/zylo-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [JSON Schema](json-schema/subscription.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/application.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/export-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/import-job.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/zylo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Postman Workspace](https://www.postman.com/kinlaneapi/zylo/overview)
- [Agentic Access](agentic-access/zylo-agentic-access.yml)
- [Trust Center](security/zylo-trust-center.yml)
- [Domain Security](security/zylo-domain-security.yml)
- [Authentication](authentication/zylo-authentication.yml)
- [Website](https://zylo.com/)
- [Customers](https://zylo.com/customers/)
- [Partners](https://zylo.com/partners/)
- [Contact](https://zylo.com/contact/)
- [Blog](https://zylo.com/blog/)
- [Case Studies](https://zylo.com/customers/)
- [Events](https://zylo.com/events/)
- [Podcast](https://podcast.zylo.com/public/112/SaaSMe-Unfiltered%3A-The-SaaS-Management-Podcast-c316deea)
- [Videos](https://zylo.com/videos/)
- [LinkedIn](https://www.linkedin.com/company/zyloapp/)
- [GitHub Organization](https://github.com/zylo)
- [Webinars](https://zylo.com/webinars/)
- [Login](https://app.zylo.com/login)
- [Privacy Policy](https://zylo.com/privacy-policy/)
- [Terms of Service](https://zylo.com/msa/)
- [Pricing](https://zylo.com/pricing/)
- [Features](undefined)
- [Llms Text](https://developer.zylo.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
