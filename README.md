# Shadeform (shadeform)

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
