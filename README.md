# DIKWP InvestAdvisor SuitabilityLab 2026 V1

Offline, open-source reference prototype for investment education, suitability pre-review, portfolio discussion drafts, product due diligence, stress testing and advisor review.

## Quick start

Open `index.html` in a browser. No server, API key, account, brokerage, trading or fund-sales interface is required.

Optional CLI:

```bash
python tools/run_invest_suitability.py examples/sample_investor_profile.json --out outputs
```

## Boundary

This project is not a licensed investment adviser, securities investment consulting service, fund sales platform, brokerage, portfolio manager or automated trading system. It does not recommend specific securities, funds, timing, accounts or transactions, and does not promise returns.

Outputs are discussion drafts, education materials and human review packets. Formal investment advice or product sales must be provided by appropriately licensed institutions/personnel under applicable law and suitability rules.

## DIKWP workflow

Investor profile → Purpose Contract → Financial Evidence Ledger → 3-No input diagnosis → suitability/risk grade pre-check → asset-category discussion draft → stress scenarios → product due diligence → AI use log → advisor review ticket → Investment Passport.
