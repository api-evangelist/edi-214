# edi-214 (edi-214)

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

Chartered by the American National Standards Institute for more than 40 years, X12 develops and maintains EDI standards and XML schemas which drive business processes globally.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/edi-214/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/edi-214/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### EDI 214 Transportation Carrier Shipment Status Message

The EDI 214 (Transportation Carrier Shipment Status Message) is an ANSI X12 electronic data interchange standard transaction set used by transportation carriers to provide shippers, consignees, and agents with shipment status in terms of dates, times, locations, route, and conveyance. Key segments include B10 (tracking number), MS1 (current location), and AT7 (current status).

- **Human URL:** [https://x12.org/node/4214](https://x12.org/node/4214)
- **Base URL:** `https://edi-gateway.logistics-platform.example.com/api`

#### Tags

- EDI
- Freight
- Logistics
- Shipment Tracking
- Transportation
- X12

#### Properties

- [Documentation](https://x12.org/node/4214)
- [Reference](https://www.stedi.com/edi/x12/transaction-set/214)
- [Documentation](https://support.edifabric.com/hc/en-us/articles/360010385272-X12-214-Shipment-Status)
- [Getting Started](https://www.spscommerce.com/edi-document/edi-214-shipment-status/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/edi-214/refs/heads/main/openapi/stedi-edi214-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Stedi EDI API (X12 214 Support)

Stedi provides a cloud EDI platform with comprehensive X12 214 documentation and tooling. The EDI Inspector and JSONata Playground allow developers to parse, validate, and transform EDI 214 shipment status messages. Stedi supports the full X12 transaction set with REST API integration for modern supply chain applications.

- **Human URL:** [https://www.stedi.com/](https://www.stedi.com/)
- **Base URL:** `https://api.stedi.com`

#### Tags

- EDI
- JSON
- Logistics
- REST
- Shipment Tracking
- X12

#### Properties

- [Documentation](https://www.stedi.com/edi/x12/transaction-set/214)
- [Reference](https://www.stedi.com/edi)
- [Developer Tools](https://www.stedi.com/edi/inspector)

### Flexport EDI API (214 Air Shipment Status)

Flexport's EDI developer portal provides documentation for EDI 214 Air Shipment Status using X12 4010 format. Enables air freight status tracking integration with Flexport's logistics platform.

- **Human URL:** [https://developers.flexport.com/edi/](https://developers.flexport.com/edi/)
- **Base URL:** `https://api.flexport.com`

#### Tags

- Air Freight
- EDI
- Logistics
- Shipment Tracking
- X12

#### Properties

- [Documentation](https://developers.flexport.com/edi/)
- [Portal](https://developers.flexport.com/edi/)

## Common Properties

- [Website](https://x12.org/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/edi-214/refs/heads/main/openapi/stedi-edi214-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/edi-214/refs/heads/main/json-schema/edi-214-shipment-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/edi-214/refs/heads/main/json-ld/edi-214-context.jsonld)
- [Portal](https://www.stedi.com/edi)
- [Documentation](https://x12.org/node/4214)
- [Reference](https://www.stedi.com/edi/x12/transaction-set/214)
- [Getting Started](https://www.spscommerce.com/edi-document/edi-214-shipment-status/)
- [Developer Tools](https://www.stedi.com/edi/inspector)

## Maintainers

**Email:** kin@apievangelist.com
