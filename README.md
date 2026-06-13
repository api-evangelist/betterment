# Betterment

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
