# Citibank Canada (citibank-canada)

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

Citibank Canada (Citi Canada) is the Canadian arm of Citigroup, chartered under Canada's Bank Act as a Schedule II (foreign bank subsidiary) deposit-taking institution. Established in 1919 in Toronto and headquartered at Citigroup Place, 123 Front Street West, it is a member of the Canadian Bankers Association and the Canada Deposit Insurance Corporation (CDIC). Citi Canada is an institutional and corporate bank only — securities trading, cash management, treasury, trade finance, custody, clearing, securities financing and private banking — having exited Canadian consumer retail banking (its MasterCard portfolio was sold to CIBC in 2010, and CitiFinancial Canada / Fairstone was divested in 2017).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/citibank-canada/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/citibank-canada/refs/heads/main/apis.yml)

## Open-Finance & API Posture

Citi Canada runs **no Canada-specific developer portal** — both `developer.citibank.ca` and `www.citibank.ca` fail to resolve. Its corporate and institutional clients integrate through Citigroup's **group-level** platforms: the Citi Developer Experience ([developer.citi.com](https://developer.citi.com/), HTTP 200) and the CitiConnect API Portal from Treasury and Trade Solutions, which document institutional APIs for payments, statements/reporting, balance inquiry, beneficiary data and FX. Those docs and the sandbox / API Explorer sit behind client onboarding, and no OpenAPI/Swagger definition is publicly downloadable.

Canada has **no operational open-banking mandate**: the federal Consumer-Driven Banking framework (Budget 2024 / Fall Economic Statement 2024, overseen by the Financial Consumer Agency of Canada) is legislated but not yet live. Citi Canada publishes no stated CDB position and, holding no retail consumer accounts, has no applicable consumer data-aggregation (Flinks / Plaid / MX / Salt Edge) or FDX/1033 posture.

## Tags

- Financial Services
- Banking
- Canada
- Schedule II Bank
- Institutional Banking
- Treasury and Trade
- Corporate Banking
- Payments

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Citi Institutional (CitiConnect) API Platform

Citigroup's group-level institutional API platform (Citi Developer Experience / CitiConnect, from Treasury and Trade Solutions) that Citi Canada's corporate and institutional clients integrate with for payments, statements and reporting, balance inquiry, beneficiary/payee data and FX. Documentation and the sandbox / API Explorer sit behind client onboarding; there is no Canada-specific developer portal and no publicly downloadable OpenAPI. This is the honest API surface serving this Schedule II entity's clients, not a Citi Canada first-party public API.

- **Human URL:** [https://developer.citi.com/apis/](https://developer.citi.com/apis/)

#### Properties

- [Developer Portal](https://developer.citi.com/)
- [Documentation](https://developer.citi.com/apis/)
- [CitiConnect API Portal](https://www.citigroup.com/global/insights/citiconnect-api-portal)

## Common Properties

- [Website](https://www.citigroup.com/citi/about/countries-and-jurisdictions/canada.html)
- [Developer Portal](https://developer.citi.com/)
- [Documentation](https://developer.citi.com/apis/)
- [GitHub Organization](https://github.com/Citi)
- [LinkedIn](https://www.linkedin.com/company/citi)
- [Privacy Policy](https://www.citigroup.com/global/privacy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
