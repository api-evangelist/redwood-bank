# Redwood Bank (redwood-bank)

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
