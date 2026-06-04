# University of Gothenburg (university-of-gothenburg)

The University of Gothenburg (Göteborgs universitet) is a public research university in Sweden, founded in 1891, with roughly 37,000 students and 6,000 employees, and ranked #194 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an APIs.json provider profile for the api-evangelist network. The university's machine-accessible surface is research- and library-centric: a standards-based OAI-PMH interface over the GUPEA institutional repository and open-access governance datasets from the QoG Institute. No central, documented developer portal with public API keys was found.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-gothenburg/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-gothenburg-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Sweden, Research, Open Data, Library, OAI-PMH

## APIs

- **GUPEA Repository OAI-PMH Interface** — DSpace-based institutional repository (Gothenburg University Publications Electronic Archive) exposing an OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://gupea.ub.gu.se/ — Base URL: https://gupea.ub.gu.se/server/oai/request
- **Quality of Government (QoG) Open Data** — Open-access governance datasets via file downloads (CSV/SPSS/Stata) and the Data Finder tool. Docs: https://www.gu.se/en/quality-government/qog-data and https://datafinder.qog.gu.se/

## Plans

- [plans/university-of-gothenburg-plans-pricing.yml](plans/university-of-gothenburg-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-gothenburg-rate-limits.yml](rate-limits/university-of-gothenburg-rate-limits.yml)

## FinOps

- [finops/university-of-gothenburg-finops.yml](finops/university-of-gothenburg-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.gu.se/en
- GitHub (affiliated department): https://github.com/bcfgothenburg
- LinkedIn: https://www.linkedin.com/school/university-of-gothenburg/
- Plans: plans/university-of-gothenburg-plans-pricing.yml
- Rate Limits: rate-limits/university-of-gothenburg-rate-limits.yml
- FinOps: finops/university-of-gothenburg-finops.yml
- Review: review.yml

## Notes

- No central, documented developer portal or public keyed REST API was found for the University of Gothenburg as of the review date.
- The GUPEA OAI-PMH endpoint was verified live (repository name "GUPEA", protocol 2.0).
- QoG data is distributed as downloadable files plus a Data Finder browser; it is not a keyed REST API.
- GitHub presence is distributed across departmental organizations (e.g. bcfgothenburg); there is no single official university-wide GitHub org.
- No endpoints, sign-up flows, or documentation URLs were fabricated; only verified public URLs are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
