# data.egov.bg (data-egov-bg)

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
