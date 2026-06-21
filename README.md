# Evisort (evisort)

Evisort is an AI-powered contract lifecycle management (CLM) and contract intelligence platform that lets teams upload, search, and extract data from contracts, and automate contract generation and review workflows. Evisort was acquired by Workday in 2024 and is now offered as Workday Contract Lifecycle Management, powered by Evisort. Its REST API supports document upload and retrieval, field and metadata extraction, search, workflow automation, and webhooks, authenticated with an Evisort API key exchanged for a JWT bearer token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/evisort/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/evisort/refs/heads/main/apis.yml)

## Tags

- Contract Lifecycle Management
- CLM
- Contract Intelligence
- Document AI
- Legal Tech

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Evisort Documents API

Upload contracts and supporting files into Evisort, retrieve and download document content (PDF, DOCX, with optional OCR), and manage documents stored in a workspace.

- **Human URL:** [https://documents.developers.evisort.com/](https://documents.developers.evisort.com/)
- **Base URL:** `https://api.evisort.com/v1`

#### Tags

- Documents
- Contracts
- Upload

#### Properties

- [Documentation](https://documents.developers.evisort.com/)
- [OpenAPI](openapi/evisort-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evisort.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evisort.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evisort Field and Metadata Extraction API

Read and write the AI-extracted fields, clauses, and metadata associated with a document, supporting import and export of structured contract data.

- **Human URL:** [https://documents.developers.evisort.com/metadata](https://documents.developers.evisort.com/metadata)
- **Base URL:** `https://api.evisort.com/v1`

#### Tags

- Fields
- Metadata
- Extraction

#### Properties

- [Documentation](https://documents.developers.evisort.com/metadata)
- [OpenAPI](openapi/evisort-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evisort.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evisort.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evisort Workflow API

Streamline and scale contract processes by initiating contract generation and review, and managing workflow tickets and their associated documents.

- **Human URL:** [https://workflow.developers.evisort.com/](https://workflow.developers.evisort.com/)
- **Base URL:** `https://api.evisort.com/v1`

#### Tags

- Workflows
- Tickets
- Automation

#### Properties

- [Documentation](https://workflow.developers.evisort.com/)
- [OpenAPI](openapi/evisort-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evisort.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evisort.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evisort Search API

Query contracts across a workspace by type, category, field values, clauses, and full-text terms, with pagination and optional unique field-value aggregation.

- **Human URL:** [https://documents.developers.evisort.com/](https://documents.developers.evisort.com/)
- **Base URL:** `https://api.evisort.com/v1`

#### Tags

- Search
- Query
- Clauses

#### Properties

- [Documentation](https://documents.developers.evisort.com/)
- [OpenAPI](openapi/evisort-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evisort.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evisort.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evisort Webhooks

Subscribe to events occurring in an Evisort workspace so external systems can react to document, field, and workflow changes in near real time.

- **Human URL:** [https://developers.evisort.com/](https://developers.evisort.com/)
- **Base URL:** `https://api.evisort.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.evisort.com/)
- [OpenAPI](openapi/evisort-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evisort.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evisort.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/evisort)
- [Website](https://www.evisort.com)
- [Documentation](https://developers.evisort.com/)
- [Plans](plans/evisort-plans-pricing.yml)
- [Rate Limits](rate-limits/evisort-rate-limits.yml)
- [Fin Ops](finops/evisort-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
