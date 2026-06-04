# University of Warsaw (university-of-warsaw)

The University of Warsaw (Uniwersytet Warszawski) is Poland's largest and highest-ranked university, placed #258 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an APIs.json provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-warsaw/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-warsaw-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Poland, Academic Data, Research Data, Open Data

## APIs

- **USOS API (University of Warsaw)** — OAuth-secured REST-like protocol for the university's academic database (courses, grades, exams, users, payments, housing, events). Docs: https://usosapps.uw.edu.pl/developers/api/ — Auth: https://usosapps.uw.edu.pl/developers/api/authorization/ — Sign up: https://usosapps.uw.edu.pl/developers/
- **Dane Badawcze UW Research Data Repository REST API** — Native Dataverse REST API for the institutional research data repository. Docs: https://info.danebadawcze.uw.edu.pl/en/about-the-service/ — Base: https://danebadawcze.uw.edu.pl/api/
- **Dane Badawcze UW OAI-PMH Endpoint** — OAI-PMH 2.0 metadata harvesting endpoint ("Dane Badawcze UW Dataverse OAI Archive"). Base: https://danebadawcze.uw.edu.pl/oai

## Plans

- [plans/university-of-warsaw-plans-pricing.yml](plans/university-of-warsaw-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-warsaw-rate-limits.yml](rate-limits/university-of-warsaw-rate-limits.yml)

## FinOps

- [finops/university-of-warsaw-finops.yml](finops/university-of-warsaw-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://en.uw.edu.pl/
- GitHub: https://github.com/icm-uw
- LinkedIn: https://www.linkedin.com/school/uniwersytet-warszawski
- Developer Portal: https://usosapps.uw.edu.pl/developers/
- Authentication: https://usosapps.uw.edu.pl/developers/api/authorization/

## Notes

- The USOS API documentation (https://usosapps.uw.edu.pl/developers/api/) returned HTTP 200; the developers portal (https://usosapps.uw.edu.pl/developers/) returned HTTP 403 to automated probing (likely bot protection) but is the documented sign-up location.
- The research data repository runs Dataverse (footer: "Powered by RepOD, based on Dataverse"); its REST API version endpoint and OAI-PMH Identify verb both returned live responses (HTTP 200).
- USOS is a shared platform used by many Polish universities; the URLs cataloged here are the University of Warsaw-specific installation.
- The GitHub entry (icm-uw) is the Interdisciplinary Centre for Mathematical and Computational Modelling at the University of Warsaw; there is no single monolithic official UW GitHub org. ICM operates the research data repository.
- Only confirmed, publicly reachable resources are cataloged. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
