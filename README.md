# PrintNode (printnode)

PrintNode is a cloud and remote printing service that lets web and server applications print to any physical printer through a lightweight client installed on a remote computer. Its REST API at https://api.printnode.com covers accounts, computers, printers, print jobs, scales, child-account/API-key management, and webhooks, using HTTP Basic authentication with an API key.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/printnode/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/printnode/refs/heads/main/apis.yml)

## Tags

- Printing
- Cloud Printing
- Remote Printing
- Print Jobs
- Hardware

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### PrintNode Computers API

List and manage the computers connected to a PrintNode account, each running the PrintNode Client that bridges the cloud API to locally attached printers and devices.

- **Human URL:** [https://www.printnode.com/en/docs/api/curl](https://www.printnode.com/en/docs/api/curl)
- **Base URL:** `https://api.printnode.com`

#### Tags

- Computers
- Clients
- Devices

#### Properties

- [Documentation](https://www.printnode.com/en/docs/api/curl)
- [API Reference](https://www.printnode.com/en/docs/api/curl)
- [OpenAPI](openapi/printnode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printnode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printnode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PrintNode Printers API

Discover the printers attached to an account's computers, including printer capabilities, state, and defaults, either across the whole account or scoped to specific computers.

- **Human URL:** [https://www.printnode.com/en/docs/api/curl](https://www.printnode.com/en/docs/api/curl)
- **Base URL:** `https://api.printnode.com`

#### Tags

- Printers
- Capabilities
- Devices

#### Properties

- [Documentation](https://www.printnode.com/en/docs/api/curl)
- [API Reference](https://www.printnode.com/en/docs/api/curl)
- [OpenAPI](openapi/printnode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printnode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printnode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PrintNode PrintJobs API

Submit print jobs to a printer from PDF or raw content (URI or base64), list historical print jobs, inspect their states, and retrieve job state changes across the account or per printer.

- **Human URL:** [https://www.printnode.com/en/docs/api/curl](https://www.printnode.com/en/docs/api/curl)
- **Base URL:** `https://api.printnode.com`

#### Tags

- Print Jobs
- Printing
- PDF

#### Properties

- [Documentation](https://www.printnode.com/en/docs/api/curl)
- [API Reference](https://www.printnode.com/en/docs/api/curl)
- [OpenAPI](openapi/printnode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printnode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printnode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PrintNode Scales API

Read weight measurements from USB scales connected to a computer running the PrintNode Client, supporting point-of-sale and shipping use cases alongside printing.

- **Human URL:** [https://www.printnode.com/en/docs/api/curl](https://www.printnode.com/en/docs/api/curl)
- **Base URL:** `https://api.printnode.com`

#### Tags

- Scales
- Weighing
- Hardware

#### Properties

- [Documentation](https://www.printnode.com/en/docs/api/curl)
- [API Reference](https://www.printnode.com/en/docs/api/curl)
- [OpenAPI](openapi/printnode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printnode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printnode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PrintNode Account and API Keys API

Inspect the authenticated account via whoami, and for Integrator accounts create, modify, and delete child accounts along with their API keys and tags for managed multi-tenant printing.

- **Human URL:** [https://www.printnode.com/en/docs/api/curl](https://www.printnode.com/en/docs/api/curl)
- **Base URL:** `https://api.printnode.com`

#### Tags

- Account
- Child Accounts
- API Keys

#### Properties

- [Documentation](https://www.printnode.com/en/docs/api/curl)
- [API Reference](https://www.printnode.com/en/docs/api/curl)
- [OpenAPI](openapi/printnode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printnode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printnode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PrintNode Webhooks API

Register, view, modify, and delete webhooks that deliver event notifications about account activity such as print job and printer state changes to a configured HTTP endpoint.

- **Human URL:** [https://www.printnode.com/en/docs/api/curl](https://www.printnode.com/en/docs/api/curl)
- **Base URL:** `https://api.printnode.com`

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://www.printnode.com/en/docs/api/curl)
- [API Reference](https://www.printnode.com/en/docs/api/curl)
- [OpenAPI](openapi/printnode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printnode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printnode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/PrintNode)
- [LinkedIn](https://www.linkedin.com/company/printnode)
- [Website](https://www.printnode.com/)
- [Documentation](https://www.printnode.com/en/docs/api/curl)
- [Plans](plans/printnode-plans-pricing.yml)
- [Rate Limits](rate-limits/printnode-rate-limits.yml)
- [Fin Ops](finops/printnode-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
