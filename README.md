# Shadeform (shadeform)

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

Shadeform is a GPU cloud marketplace that exposes a single REST API for deploying and managing GPU compute across many underlying clouds. One interface lets you compare real-time availability and per-GPU-hour pricing, then launch, inspect, restart, and delete instances, attach volumes and SSH keys, and reuse saved launch templates across providers such as Lambda, Nebius, Crusoe, and Hyperstack.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/shadeform/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shadeform/refs/heads/main/apis.yml)

## Tags

- GPU
- Cloud
- Marketplace
- Compute
- Infrastructure
- AI

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Shadeform Instances API

Create, list, inspect, restart, update, and delete GPU instances across every supported cloud through one standardized interface, with Docker or script launch configurations, auto-delete and spend-alert triggers, tags, and environment variables.

- **Human URL:** [https://docs.shadeform.ai/api-reference/instances/instances](https://docs.shadeform.ai/api-reference/instances/instances)
- **Base URL:** `https://api.shadeform.ai/v1`

#### Tags

- Instances
- GPU
- Compute
- Provisioning

#### Properties

- [Documentation](https://docs.shadeform.ai/getting-started/quickstart)
- [API Reference](https://docs.shadeform.ai/api-reference/instances/instances)
- [OpenAPI](openapi/shadeform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shadeform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shadeform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shadeform Instance Types & Availability API

Query standardized GPU instance types, their configurations, hourly price in cents, deployment type, boot-time estimates, and per-region availability across providers, with filtering by cloud, region, GPU type, GPU count, and availability, and sorting by price.

- **Human URL:** [https://docs.shadeform.ai/api-reference/instances/instances-types](https://docs.shadeform.ai/api-reference/instances/instances-types)
- **Base URL:** `https://api.shadeform.ai/v1`

#### Tags

- Instance Types
- Availability
- Pricing
- GPU

#### Properties

- [Documentation](https://docs.shadeform.ai/api-reference/instances/instances-types)
- [API Reference](https://docs.shadeform.ai/api-reference/instances/instances-types)
- [OpenAPI](openapi/shadeform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shadeform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shadeform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shadeform Templates API

Save, list, inspect, update, and delete reusable launch templates that bundle launch configuration, auto-delete and alert thresholds, volume mounts, networking, tags, and environment variables; includes a featured/public templates listing.

- **Human URL:** [https://docs.shadeform.ai/api-reference/templates/templates](https://docs.shadeform.ai/api-reference/templates/templates)
- **Base URL:** `https://api.shadeform.ai/v1`

#### Tags

- Templates
- Launch Configuration
- Reuse

#### Properties

- [Documentation](https://docs.shadeform.ai/api-reference/templates/templates)
- [API Reference](https://docs.shadeform.ai/api-reference/templates/templates)
- [OpenAPI](openapi/shadeform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shadeform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shadeform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shadeform Volumes API

Create, list, inspect, and delete persistent storage volumes scoped to a cloud and region, and query the supported volume types, to attach durable storage to GPU instances.

- **Human URL:** [https://docs.shadeform.ai/api-reference/volumes/volumes](https://docs.shadeform.ai/api-reference/volumes/volumes)
- **Base URL:** `https://api.shadeform.ai/v1`

#### Tags

- Volumes
- Storage
- Block Storage

#### Properties

- [Documentation](https://docs.shadeform.ai/api-reference/volumes/volumes)
- [API Reference](https://docs.shadeform.ai/api-reference/volumes/volumes)
- [OpenAPI](openapi/shadeform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shadeform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shadeform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shadeform SSH Keys API

Add, list, inspect, delete, and set a default SSH public key used to grant secure shell access to launched GPU instances.

- **Human URL:** [https://docs.shadeform.ai/api-reference/sshkeys/sshkeys](https://docs.shadeform.ai/api-reference/sshkeys/sshkeys)
- **Base URL:** `https://api.shadeform.ai/v1`

#### Tags

- SSH Keys
- Access
- Security

#### Properties

- [Documentation](https://docs.shadeform.ai/api-reference/sshkeys/sshkeys)
- [API Reference](https://docs.shadeform.ai/api-reference/sshkeys/sshkeys)
- [OpenAPI](openapi/shadeform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shadeform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shadeform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/shadeform)
- [LinkedIn](https://www.linkedin.com/company/shadeformai)
- [Website](https://www.shadeform.ai)
- [Documentation](https://docs.shadeform.ai)
- [Plans](plans/shadeform-plans-pricing.yml)
- [Rate Limits](rate-limits/shadeform-rate-limits.yml)
- [Fin Ops](finops/shadeform-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
