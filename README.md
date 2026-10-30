# Kyoto Encyclopedia of Genes and Genomes (KEGG)

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

The Kyoto Encyclopedia of Genes and Genomes (KEGG) is an integrated database resource for understanding high-level functions and utilities of biological systems from molecular-level information derived from genome sequencing and other high-throughput experiments. The KEGG REST API at rest.kegg.jp provides programmatic access to KEGG databases covering biological pathways, metabolic networks, molecular interactions, drug targets, disease associations, chemical compounds, genomic sequences, and functional orthologs across thousands of organisms. The API exposes seven core operations — info, list, find, get, conv, link, and ddi — enabling identifier conversion, cross-database linking, keyword and structure searches, and full entry retrieval in text, KGML, and JSON formats. Academic use is free via the REST API; FTP and commercial access require subscriptions managed through NPO Bioinformatics Japan and Pathway Solutions.

**Areas:** Bioinformatics · Genomics · Life Sciences · Pathways · Metabolomics · Drug Targets · Disease · Chemical Compounds · Enzymes · Orthology

## Kyoto Encyclopedia of Genes and Genomes (KEGG) on APIs.io

Everything profiled for Kyoto Encyclopedia of Genes and Genomes (KEGG) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kegg/](https://apis.io/providers/kegg/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [KEGG REST API](https://apis.io/apis/kegg/kegg-rest-api/) — The KEGG REST API provides unified programmatic access to all KEGG databases through seven operations: INFO (database statistics and release notes), LIST…
- [Kyoto Encyclopedia of Genes and Genomes (KEGG) conv API](https://apis.io/apis/kegg/kegg-conv-api/) — Convert identifiers between KEGG and external databases
- [Kyoto Encyclopedia of Genes and Genomes (KEGG) ddi API](https://apis.io/apis/kegg/kegg-ddi-api/) — Find adverse drug-drug interactions
- [Kyoto Encyclopedia of Genes and Genomes (KEGG) Find API](https://apis.io/apis/kegg/kegg-find-api/) — Search entries by keyword or molecular property
- [Kyoto Encyclopedia of Genes and Genomes (KEGG) Get API](https://apis.io/apis/kegg/kegg-get-api/) — Retrieve specific database entries
- [Kyoto Encyclopedia of Genes and Genomes (KEGG) Info API](https://apis.io/apis/kegg/kegg-info-api/) — Display database release information and statistics
- [Kyoto Encyclopedia of Genes and Genomes (KEGG) Link API](https://apis.io/apis/kegg/kegg-link-api/) — Find related entries using database cross-references
- [Kyoto Encyclopedia of Genes and Genomes (KEGG) List API](https://apis.io/apis/kegg/kegg-list-api/) — Obtain a list of entry identifiers and associated names

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Kegg Agentic Access](https://apis.io/agentic-access/kegg/kegg-agentic-access/)

#### Collections (7)

Postman and Open Collection request collections.

- [KEGG REST conv API](https://apis.io/collections/kegg/open-kegg-conv-api/)
- [KEGG REST conv ddi API](https://apis.io/collections/kegg/open-kegg-ddi-api/)
- [KEGG REST conv find API](https://apis.io/collections/kegg/open-kegg-find-api/)
- [KEGG REST conv get API](https://apis.io/collections/kegg/open-kegg-get-api/)
- [KEGG REST conv info API](https://apis.io/collections/kegg/open-kegg-info-api/)
- [KEGG REST conv link API](https://apis.io/collections/kegg/open-kegg-link-api/)
- [KEGG REST conv list API](https://apis.io/collections/kegg/open-kegg-list-api/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Kegg Domain Security](https://apis.io/security/kegg/kegg-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kegg Rest Api](https://apis.io/plans/kegg/kegg-rest-api/)

#### Rate limits (1)

Published request limits.

- [Kegg Rest Api](https://apis.io/rate-limits/kegg/kegg-rest-api/)

#### FinOps (1)

What the API costs to run, by operation.

- [Overview](https://apis.io/finops/kegg/overview/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://kegg.jp)

## API Evangelist rating

**Kin Score 25.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 48.4 |
| Contract governance | 0.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 9.5 |
| Access clarity | 18.4 |

**Agent readiness 25.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 7.8** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kegg/](https://apis.io/providers/kegg/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kyoto Encyclopedia of Genes and Genomes (KEGG): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kegg/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
