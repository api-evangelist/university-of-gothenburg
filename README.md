# University of Gothenburg (university-of-gothenburg)

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

The University of Gothenburg (Göteborgs universitet) is a public research university in Sweden, founded in 1891, with roughly 37,000 students and 6,000 employees. This repository catalogs the institution's public developer/API footprint as an APIs.json provider profile for the api-evangelist network.

**Re-profiled 2026-09-01 under the university pipeline, correcting the 2026-06-03 profile upward.** The June profile recorded two surfaces and concluded there was no developer programme. The correction: **Språkbanken Text** — the Swedish Language Bank's text division at the Department of Swedish, Multilingualism, Language Technology — publishes **six OpenAPI documents** from a single documentation index at `ws.spraakbanken.gu.se/docs`, all on University of Gothenburg hosts, all answering anonymous requests with HTTP 200.

Every surface in this profile carries an `x-operator`. Nine are `institution`, two are `federation`, two are `registry`, one is `tenant`. **No vendor contract is stored under this slug.**

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-gothenburg/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-gothenburg-api-evangelist&utm_content=repo

## Type

- Index
- Provider
- Public

## Tags

University, Higher Education, Education, Sweden, Research, Research Data, Research Repository, Open Data, Library, OAI-PMH, Identity Federation, Language Technology, Natural Language Processing, Corpus Linguistics

## APIs

### Institution-operated

- **Korp API v8** — corpus concordance search over 1,133 corpora (CQP query language on IMS Open Corpus Workbench). Fourteen operations. `https://ws.spraakbanken.gu.se/ws/korp/v8`
- **Språkbanken Text Metadata API v3** — the 1,499-resource catalogue, with BibTeX export and a published JSON schema endpoint. `https://ws.spraakbanken.gu.se/ws/metadata/v3`
- **Mink API v3** — upload, annotate and publish your own corpus. 63 paths; the only surface with a real authorisation model. `https://ws.spraakbanken.gu.se/ws/mink/v3`
- **Sparv API v3** — the annotation pipeline as a job service. `https://ws.spraakbanken.gu.se/ws/sparv/v3`
- **Karp API v7** — lexical-resource editing, entry history and inflection tables. `https://spraakbanken4.it.gu.se/karp/v7`
- **Karp Search API v1** — read-only search across 31 lexical resources. `https://spraakbanken4.it.gu.se/karps/v1`
- **GUPEA OAI-PMH 2.0** — the library's institutional repository, fourteen metadata formats including the Swedish national `uppsok` thesis profile. `https://gupea.ub.gu.se/server/oai/request`
- **GUPEA DSpace 8 REST API** — HAL+JSON on the library's own host. Deployment recorded; the DSpace contract is the DSpace project's and is not stored here.
- **Quality of Government (QoG) Open Data** — governance datasets as CSV/SPSS/Stata downloads plus a Data Finder browser. Institution-operated but **not an API**.

### Federation

- **Shibboleth Identity Provider** — entityID `https://idp3.it.gu.se/idp/shibboleth`, scope `gu.se`, published through SWAMID and eduGAIN.
- **Microsoft AD FS entity** — `http://idp.auth.gu.se/adfs/services/trust`, a second University entity in the SWAMID aggregate.

### Registry memberships

- **DataCite** — client `SND.SPRKB` ("Språkbanken Text"), prefix `10.23695`, via the Swedish National Data Service. Invisible to a DataCite name search for "gothenburg"; found by resolving a DOI the University minted.
- **Crossref** — two members named University of Gothenburg: `36737` (520 DOIs) and `51378` (351 DOIs).

### Tenant

- **Microsoft 365 / Entra ID** on `medarbetarportalen.gu.se` (tenant `0798ed31-…`, resource `gunet.sharepoint.com`). Relationship recorded; no Microsoft contract stored.

## Artifacts

- [openapi/](openapi/) — seven specifications, six of them published by the institution; pristine pre-refine copies in [openapi/_original/](openapi/_original/)
- [examples/](examples/) — nine live response bodies captured 2026-09-01
- [json-schema/](json-schema/) · [authentication/](authentication/) · [scopes/](scopes/) · [errors/](errors/) · [conformance/](conformance/) · [vocabulary/](vocabulary/) · [rules/](rules/) · [lifecycle/](lifecycle/) · [json-ld/](json-ld/)
- [plans/](plans/) · [rate-limits/](rate-limits/) · [finops/](finops/) · [security/](security/) · [review.yml](review.yml)
- [provenance.yml](provenance.yml) — who wrote each artifact in this repository

## Education-regime conformance (Kin Score)

Confirmed by live probe: **oai-pmh**, **shibboleth**, **saml**, **crossref**, **datacite**, plus **ror**. Not observed and recorded as `null`, never false: scim, lti, oneroster, ed-fi, caliper, qti, orcid. See [conformance/](conformance/university-of-gothenburg-conformance.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Notes

- **What is thin here is product, not surface.** No central developer portal (`api.gu.se` and `data.gu.se` do not resolve), no changelog, no status page, no rate-limit signal, no support channel for any API, and no documented way to obtain a credential for any of the five declared security schemes.
- Karp v7 and Karp Search v1 publish a **relative** `servers[]` and no `info.contact` — nothing in either document names its operator. They were attributed by the gu.se host serving them and re-based in `openapi/`; the relative originals are unchanged in `openapi/_original/`.
- The Korp contract declares version 8.1.0 while the running service reports 8.2.5. Mink publishes `3.1.0.dev` on a production path. GUPEA runs a `DSpace 8.3-SNAPSHOT` build.
- Strix (`ws.spraakbanken.gu.se/ws/strix/`) returned HTTP 503 — registered at the edge, not serving.
- `www.gu.se` returns nginx HTTP 403 for unknown paths including `/.well-known/security.txt` and `/llms.txt`. That is a blanket edge deny, not evidence those files were considered and withheld.
- No AI policy or AI-tooling pointer was found on any gu.se URL probed, so none is claimed.
- No endpoints, sign-up flows, or documentation URLs were fabricated; only URLs probed live are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
