# data.egov.bg (data-egov-bg)

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

data.egov.bg is Bulgaria's national government open-data portal, operated by the Ministry of e-Government. It is a **custom Laravel REST API** (action-style endpoints, mostly POST) — **not** CKAN.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/data-egov-bg/refs/heads/main/apis.yml)

## Type
- **kind:** government  ·  **software:** custom (Laravel)

## API
- **data.egov.bg REST API** — base `https://data.egov.bg/api`. [Docs](https://data.egov.bg/document) · [Portal](https://data.egov.bg/)
- Public read methods (no key): `listDatasets`, `getDatasetDetails`, `listResources`, `getResourceData`, `listOrganisations`, `listMainCategories`, `listTags`. Write/admin methods need an `api_key` (free account).
- Source code: [governmentbg/data-gov-bg](https://github.com/governmentbg/data-gov-bg)
- **Note:** the live site blocks datacenter IPs via a WAF (HTTP 403). The endpoint surface above is verified from the official source repo, not a live probe; dataset count unverified.

## Timestamps
- **Created:** 2026-06-23
- **Modified:** 2026-06-23

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
