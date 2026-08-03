# Betterment

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

Betterment is a robo-advisor and financial planning platform offering automated investment management, tax-loss harvesting, retirement planning, and goal-based portfolio rebalancing. Founded in 2010, Betterment manages billions in assets for individual investors through its Digital and Premium Advisory plans, and for employers through Betterment at Work — a 401(k) plan administration product.

## API Access

Betterment does not offer a public developer API. Third-party developers access Betterment account data through open banking aggregators:

- **[Plaid](https://plaid.com/docs/investments/)** — Primary aggregator; provides access to Betterment account balances, holdings, transactions, and account metadata.
- **[BankSync](https://www.banksyncinc.com)** — Secondary aggregator supporting Betterment connectivity.

The **Betterment at Work Payroll Integration API** is a private partner API used by payroll providers (ADP, Gusto, Rippling, Paychex, and 350+ others) to automate 401(k) contribution management and employee eligibility tracking. Access requires a formal onboarding agreement.

## Plans & Pricing

| Plan | Fee |
|------|-----|
| Digital (under $24K, no recurring deposit) | $5/month flat |
| Digital ($24K–$1M or $200+/month deposit) | 0.25% AUM/year |
| Premium Advisory (min. $100K) | 0.65% AUM/year |
| Betterment at Work (401k) | Negotiated per employer |

Progressive discounts apply above $1M AUM (0.15% on $1M–$2M; 0.10% above $2M).

See [`plans/plans.yml`](plans/plans.yml) for full plan details.

## Open Source

Betterment Engineering maintains an active open-source presence at [github.com/Betterment](https://github.com/Betterment), including:

- **[alchemist](https://github.com/Betterment/alchemist)** — Flutter golden testing tool
- **[delayed](https://github.com/Betterment/delayed)** — SQL-backed ActiveJob backend processing millions of jobs/day
- **[test_track](https://github.com/Betterment/test_track)** — Multi-platform split-testing and feature-gating system
- **[webvalve](https://github.com/Betterment/webvalve)** — Service-oriented app development with fake HTTP services

## Resources

- [Website](https://www.betterment.com)
- [Pricing](https://www.betterment.com/pricing)
- [Engineering Blog](https://www.betterment.com/engineering)
- [Betterment at Work](https://www.betterment.com/work/employers)
- [Payroll Integrations](https://www.betterment.com/work/payroll-integrations)
- [Data Aggregation Disclosure](https://www.betterment.com/legal/data-aggregation-disclosure)
- [GitHub Organization](https://github.com/Betterment)
