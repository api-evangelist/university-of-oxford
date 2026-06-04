# University of Oxford (university-of-oxford)

The University of Oxford (QS World 2025 #3) is a collegiate research university. Its former Open Data Service (data.ox.ac.uk) and Mobile Oxford platform — OxPoints, places, courses, vacancies via REST/SPARQL — are now deprecated and no longer resolve. The clearly live public API today is the Bodleian Libraries' ORA (Oxford University Research Archive) OAI-PMH interface.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/university-of-oxford/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-oxford-api-evangelist&utm_content=repo)

## Type
- **x-type:** Index (Consumer / 3rd-Party)

## Tags
- Education, Higher Education, University, Research, United Kingdom, Open Access, OAI-PMH, Repository

## APIs
- **ORA — Oxford University Research Archive API** — OAI-PMH 2.0 metadata harvesting for Oxford's open-access repository (theses, datasets, articles). Base `https://ora.ox.ac.uk/oai2`. [Docs](https://ora.ox.ac.uk/api)

## Plans, Rate Limits, FinOps
- [Plans](plans/university-of-oxford-plans-pricing.yml) — Free/open for ORA harvesting.
- [RateLimits](rate-limits/university-of-oxford-rate-limits.yml) — Large downloads require contacting ORA first.
- [FinOps](finops/university-of-oxford-finops.yml) — Non-commercial; no usage-based API billing.

## Timestamps
- **Created:** 2026-06-03
- **Modified:** 2026-06-03

## Common Properties
- [Website](https://www.ox.ac.uk/)
- [GitHub (IT Services)](https://github.com/ox-it)
- [GitHub (Research SW Eng)](https://github.com/OxfordRSE)
- [Status](https://status.it.ox.ac.uk/)

## Notes
- The legacy Open Data Service (data.ox.ac.uk), OxPoints, and Mobile Oxford APIs (api.m.ox.ac.uk) no longer resolve — treated as decommissioned. See [review.yml](review.yml).
- Confirmed live: ora.ox.ac.uk/api (200), ora.ox.ac.uk/oai2 Identify (200), github.com/ox-it (200), status.it.ox.ac.uk (200).

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
