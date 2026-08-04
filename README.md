# Redwood Bank (redwood-bank)

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

Redwood Bank is a specialist UK challenger bank for small and medium-sized businesses, headquartered in Letchworth Garden City, Hertfordshire. Launched in 2017 after receiving its banking licence from the Prudential Regulation Authority (PRA) and Financial Conduct Authority (FCA), it is wholly owned by Redwood Financial Partners Ltd (controlled by Jonathan and David Rowland, with Warrington Borough Council holding roughly a one-third stake). Redwood focuses on business and charity savings accounts and individually underwritten commercial and buy-to-let mortgages.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/redwood-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/redwood-bank/refs/heads/main/apis.yml)

## Regulatory

- **Financial Services Register (FCA/PRA) firm reference:** 755924
- **Company number:** 09872265 (England and Wales)
- **Registered office:** Suite 101, The Nexus Building, Broadway, Letchworth Garden City, Hertfordshire, SG6 3TA
- **Authorisation:** Authorised by the Prudential Regulation Authority; regulated by the Financial Conduct Authority and the Prudential Regulation Authority.

## Tags

- Financial Services
- Banking
- Business Banking
- SME
- Savings
- Commercial Mortgages
- Open Banking
- PSD2
- OBIE
- United Kingdom

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public API surface was found for Redwood Bank at bootstrap time.

Redwood Bank is **not** one of the CMA9 mandated banks and its product range is deposit- and lending-only (business/charity savings accounts and commercial mortgages). It does not offer a payment / business current account, so it sits outside the PSD2 scope that compels UK Open Banking. As of this review:

- No developer or Open Banking portal was found (`developer.`, `api.`, and `openbanking.` subdomains of `redwoodbank.co.uk` do not resolve).
- No OBIE Read/Write APIs — Account & Transaction Information (AIS), Payment Initiation (PIS), or Confirmation of Funds (CBPII) — are documented.
- No Open Banking Open Data endpoint was confirmed; the standard `/open-banking/v2.3/atms` and `/open-banking/v3.1/atms` paths and `/.well-known/open-banking` return HTTP 404.

For reference, the shared UK Open Banking standards that any obligated ASPSP would conform to are published by the Open Banking Implementation Entity (OBIE):

- Open Data API specs: [github.com/OpenBankingUK/opendata-api-specs](https://github.com/OpenBankingUK/opendata-api-specs)
- Read/Write API specs: [github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

## Common Properties

- [Website](https://www.redwoodbank.co.uk/)
- [Blog / News](https://redwoodbank.co.uk/news)
- [Support](https://redwoodbank.co.uk/contact-us/support)
- [Terms of Service](https://redwoodbank.co.uk/legal/website-terms)
- [Privacy Policy](https://redwoodbank.co.uk/legal/privacy)
- [Legal](https://redwoodbank.co.uk/legal)
- [LinkedIn](https://www.linkedin.com/company/redwoodbank/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
