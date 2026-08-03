# Azure Container Instances (azure-container-instances)

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

Azure Container Instances (ACI) is the fastest and simplest way to run containers in Azure without having to manage virtual machines or adopt a higher-level orchestration service.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, Cloud, Container Instances, Containers, Microsoft, Serverless

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Azure Container Instances
Azure Container Instances (ACI) is the fastest and simplest way to run containers in Azure without having to manage virtual machines or adopt a higher-level orchestration service.

**Human URL:** [https://azure.microsoft.com/en-us/products/container-instances](https://azure.microsoft.com/en-us/products/container-instances)

#### Tags:

 - Container Instances, Containers, Serverless

#### Properties

- [Documentation](https://azure.microsoft.com/en-us/products/container-instances)
- [OpenAPI](openapi/azure-container-instances-openapi.yaml)

## Common Properties


## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Container Instances](openapi/azure-container-instances-openapi.yaml)

### JSON Schema

- [Container Probe](json-schema/azure-container-instances-container-probe-schema.json)
- [Empty Dir Volume](json-schema/azure-container-instances-empty-dir-volume-schema.json)
- [Container Http Get](json-schema/azure-container-instances-container-http-get-schema.json)
- [Container Group](json-schema/azure-container-instances-container-group-schema.json)
- [Capabilities List Result](json-schema/azure-container-instances-capabilities-list-result-schema.json)
- [Container Exec Request](json-schema/azure-container-instances-container-exec-request-schema.json)
- [Container Group Network Profile](json-schema/azure-container-instances-container-group-network-profile-schema.json)
- [Log Analytics](json-schema/azure-container-instances-log-analytics-schema.json)
- [Container Exec](json-schema/azure-container-instances-container-exec-schema.json)
- [Capabilities](json-schema/azure-container-instances-capabilities-schema.json)

### JSON-LD

- [Azure Container Instances Context](json-ld/azure-container-instances-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Container Instances](capabilities/shared/azure-container-instances.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|----------|
| [Azure Container Instances Management](capabilities/azure-container-instances-management.yaml) | Azure Container Instances | 5 | Cloud Engineer |

## Vocabulary

- [Azure Container Instances Vocabulary](vocabulary/azure-container-instances-vocabulary.yaml)

## Rules

- [Azure Container Instances Spectral Rules](rules/azure-container-instances-spectral-rules.yml) — 15 rules enforcing Azure Container Instances API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
