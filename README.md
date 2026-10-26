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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Oxford is a collegiate public research university in Oxford, United Kingdom, and a Russell Group member. It operates **no central developer programme, no API portal, no developer account and no authenticated API of any kind** — and the one it used to run, the Open Data Service at `data.ox.ac.uk` (OxPoints linked data, places, courses, vacancies over REST and SPARQL), was decommissioned without a successor.

What Oxford *does* operate sits entirely inside its library and research-infrastructure estate, and it is more substantial than that absence suggests.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/university-of-oxford/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-oxford-api-evangelist&utm_content=repo)

## Type
- **x-type:** `university`
- **x-category:** Public Research University
- **Position:** Consumer / 3rd-Party

## Who operates what

Every surface here carries an `x-operator`. `method:` says how API Evangelist came to hold an artifact; `x-operator:` says **who runs the thing the artifact describes** — and for a university those are rarely the same answer.

### Institution-operated (6)

| Surface | Base | Evidence it is Oxford's |
|---|---|---|
| ORA OAI-PMH | `https://ora.ox.ac.uk/oai2` | Identify reports origin `ora4-rhel9-prd-public2.bodleian.ox.ac.uk`, adminEmail `ora-dev@bodleian.ox.ac.uk` |
| ORA search / record JSON | `https://ora.ox.ac.uk` | Oxford's own Blacklight front end; source referenced at `gitlab.bodleian.ox.ac.uk/ORA4` |
| Digital Bodleian IIIF | `https://iiif.bodleian.ox.ac.uk` | CNAME `digital92-prd-public.bodleian.ox.ac.uk` → 129.67.247.151, Oxford address space |
| Oxford Text Archive OAI-PMH | `https://ota.bodleian.ox.ac.uk/repository/oai/request` | Identify carries an OLAC description naming Bodleian Libraries, University of Oxford |
| Shibboleth Identity Provider | `https://idp.shibboleth.ox.ac.uk/idp` | eduGAIN entity `https://registry.shibboleth.ox.ac.uk/idp`, reg. authority `ukfederation.org.uk` |
| Continuing Education WP REST | `https://lifelong-learning.ox.ac.uk/wp-json` | Oxford registrable domain, self-hosted WordPress |

The IIIF stack is the strongest of these and was entirely absent from this profile before 2026-08-19: Image API 2.1 at level 2, Presentation API 2.1, and **Change Discovery API 1.0** — an activity stream of 21,843 items across 219 pages, i.e. a real incremental-sync surface.

### Vendor tenancies (4) — recorded, never credited

A tenancy is a real institutional fact. The data is Oxford's; the contract is not. No vendor specification is stored in this repository.

| Surface | Vendor | Evidence |
|---|---|---|
| `portal.sds.ox.ac.uk` — research data portal | Figshare | CNAME `proxy-eu-01.figshare.com`; DataCite client `figshare.oxford`, 155,787 DOIs under `10.25446/oxford` |
| SOLO — library discovery | Ex Libris Primo VE | CNAME `oxford.primo.exlibrisgroup.com`, `vid=44OXF_INST:SOLO` |
| Canvas — VLE | Instructure | CNAME `universityofoxford-vanity.instructure.com`; `/api/v1/accounts` returns 401 |
| Recruitment | CoreHR | `recruit.ox.ac.uk` redirects off `ox.ac.uk` to `my.corehr.com/pls/uoxrecruit` |

**One false lead, rejected on evidence:** `oxford.figshare.com` appears to resolve, but `*.figshare.com` is wildcard DNS — a deliberately nonsensical subdomain returns the identical AWS WAF challenge. The real tenancy is `portal.sds.ox.ac.uk`.

## Domain standards (Kin Score `education` regime)

Four of twelve, each evidenced from what an endpoint actually returned — see [conformance/](conformance/university-of-oxford-domain-standards.yml).

- **oai-pmh** — two independent institution-operated providers (ORA, Oxford Text Archive)
- **datacite** — `datacite_dc` against kernel 4.6; DataCite client `bl.oxdb`, 40,283 DOIs
- **orcid** — `nameIdentifierScheme="ORCID"` in DataCite records, `orcid.org/` URIs in RIOXX
- **shibboleth** / **saml** — live SAML 2.0 IdP metadata; 38 `ox.ac.uk` entities in eduGAIN (3 IdPs, 35 SPs)

`lti` is explicitly **not** claimed: Canvas is LTI-certified, but that certification is Instructure's, not Oxford's.

## Artifacts

Oxford publishes **no machine-readable API contract of any kind**. Every OpenAPI and JSON Schema here was `method: derived` by API Evangelist from live responses, and the payloads they were derived from are stored verbatim in [examples/](examples/index.yml).

- [openapi/](openapi/) — 4 derived contracts, with pristine copies in [`openapi/_original/`](openapi/_original/)
- [json-schema/](json-schema/) — 3 derived schemas
- [examples/](examples/index.yml) — 11 probed payloads, each with its URL and status
- [conformance/](conformance/university-of-oxford-domain-standards.yml) · [vocabulary/](vocabulary/university-of-oxford-vocabulary.yml) · [rules/](rules/university-of-oxford-rules.yml)
- [authentication/](authentication/university-of-oxford-authentication.yml) · [scopes/](scopes/university-of-oxford-scopes.yml) · [errors/](errors/university-of-oxford-errors.yml) · [lifecycle/](lifecycle/university-of-oxford-lifecycle.yml)
- [Plans](plans/university-of-oxford-plans-pricing.yml) · [RateLimits](rate-limits/university-of-oxford-rate-limits.yml) · [FinOps](finops/university-of-oxford-finops.yml) · [review.yml](review.yml)

## What Oxford does not have

Stated plainly, because a correct thin profile is a correct profile:

- No API portal, developer account, API key or OAuth anywhere.
- No OpenAPI, AsyncAPI, JSON Schema or `llms.txt` published by Oxford.
- No versioning policy, changelog or deprecation policy for any live surface.
- No structured error format — errors are HTML, plain-English sentences, or an OAI-PMH `<error>` element inside an HTTP 200.
- No API coverage on `status.it.ox.ac.uk`.
- The former Open Data Service was retired silently; no reachable URL announces it.

## Coverage

`state: covered`. Two limits are on the record: the whole `www.ox.ac.uk` estate returns a Cloudflare managed challenge (`cf-mitigated: challenge`) to non-browser clients — **live, not dead** — and `portal.sds.ox.ac.uk` sits behind an AWS WAF challenge, so that tenancy was settled by DNS and the DataCite registry rather than by reading the portal.

## Timestamps
- **Created:** 2026-06-03
- **Modified:** 2026-08-19

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
