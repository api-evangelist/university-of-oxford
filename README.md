# University of Oxford (university-of-oxford)

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
