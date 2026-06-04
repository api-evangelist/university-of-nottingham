# University of Nottingham (university-of-nottingham)

The University of Nottingham is a public research university in Nottingham, United Kingdom, ranked #71 in the QS World University Rankings 2025. This repository catalogs the institution's public developer and API footprint as an APIs.json provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-nottingham/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-nottingham-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, OAI-PMH, United Kingdom

## APIs

- **Repository@Nottingham OAI-PMH** — Publicly accessible OAI-PMH metadata-harvesting interface for the university's Worktribe-powered institutional research repository. Confirmed live returning valid OAI-PMH XML.
  - Base: https://nottingham-repository.worktribe.com/oaiprovider
  - Docs: https://www.openarchives.org/OAI/openarchivesprotocol.html
- **Nottingham ePrints / eTheses OAI-PMH (gated)** — Legacy EPrints OAI-PMH endpoints at `/perl/oai2`, now behind an AWS WAF human-verification challenge and not openly harvestable.
  - Docs: http://eprints.nottingham.ac.uk/information.html

## Plans

- plans/university-of-nottingham-plans-pricing.yml

## Rate Limits

- rate-limits/university-of-nottingham-rate-limits.yml

## FinOps

- finops/university-of-nottingham-finops.yml

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.nottingham.ac.uk/
- Developer Portal (Digital and Technology Services): https://www.nottingham.ac.uk/dts/
- GitHub: https://github.com/UniversityOfNottingham
- Source Code (Health Informatics): https://github.com/Health-Informatics-UoN
- LinkedIn: https://www.linkedin.com/school/university-of-nottingham/
- Twitter/X: https://twitter.com/UniofNottingham

## Notes

All endpoints were probed live during cataloging. Only the Repository@Nottingham OAI-PMH interface returned valid machine-readable output; the legacy EPrints/eTheses OAI-PMH endpoints are gated behind AWS WAF. No general-purpose developer portal or open-data API portal was found — most institutional systems (student records, timetabling, library discovery, identity) are behind SSO and not publicly documented. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
