# 35Pharma

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

35Pharma is a Canada-based, private, clinical-stage biopharmaceutical company headquartered in Montreal, Quebec, with a research hub in Boston, Massachusetts. It designs and develops next-generation protein-based therapeutics — multi-specific Activin x GDF ligand traps engineered against the TGF-beta superfamily — for pulmonary hypertension, heart failure, cardiometabolic disease and obesity. Its lead program, HS235, is a precision-engineered activin signalling inhibitor that has completed Phase I healthy-volunteer studies and is entering proof-of-principle trials in PAH and PH-HFpEF; a second program, HS370, targets heart failure and obesity. 35Pharma publishes no developer program, API, or machine-readable API artifacts of any kind — it is a therapeutics developer, not a software or data provider. On 25 February 2026 the company announced an agreement to be acquired by GSK plc.

## Company

- **Website** — https://www.35pharma.com/
- **News & Publications** — https://www.35pharma.com/news
- **Careers** — https://www.35pharma.com/careers
- **Privacy Policy** — https://cdn.prod.website-files.com/679106f289641fbcc75092be/690117401d052d425a9a6c62_35Pharma_PrivacyPolicy_EN_FR.pdf
- **Parent company** — GSK plc (acquisition announced 25 February 2026) — https://www.gsk.com

## API surface

**None found.** 35Pharma publishes no developer program, no API, and no machine-readable
API artifact. The full contract-discovery pass (2026-09-05) probed `35pharma.com` and
`www.35pharma.com` for OpenAPI/Swagger at the host root, `llms.txt`, `apis.json`/`apis.yml`,
every named `/.well-known/` discovery document (security.txt, OIDC, OAuth AS/PR, api-catalog,
ai-plugin, aauth-resource) and both A2A agent-card paths — all returned a hard 404, including
a negative-control path that cannot exist, so the origin is not a catch-all. No `api.`,
`developer.`, `developers.`, `docs.`, `portal.`, `data.` or `trust.` subdomain resolves, and
there is no GitHub organization. The recorded absence lives in
[`well-known/35pharma-well-known.yml`](well-known/35pharma-well-known.yml).

Note on terminology: in this sector "API" means *active pharmaceutical ingredient*. 35Pharma
appears in pharma API/CDMO prospect databases for that reason; it is unrelated to a software
interface.

## Artifacts

- [`well-known/35pharma-well-known.yml`](well-known/35pharma-well-known.yml) — probed discovery surface (0 hits)
- [`security/35pharma-domain-security.yml`](security/35pharma-domain-security.yml) — probed TLS/DNS posture (TLSv1.3, SPF + DMARC `p=reject`, no DNSSEC, no CAA, no HSTS)
