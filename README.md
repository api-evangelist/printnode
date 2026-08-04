# PrintNode (printnode)

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
