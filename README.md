# Citibank Canada (citibank-canada)

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
