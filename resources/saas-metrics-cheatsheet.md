# SaaS Metrics Reference [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Definitions, formulas, and benchmark tables for common SaaS metrics.

[← Back to main list](../README.md) · See also: [Growth & sales tools](../growth-and-sales.md) · [Fundraising](../fundraising.md)

## Contents

- [Revenue metrics](#revenue-metrics)
- [Retention and churn](#retention-and-churn)
- [Acquisition](#acquisition)
- [Activation and engagement](#activation-and-engagement)
- [Cash and runway](#cash-and-runway)
- [Sales metrics](#sales-metrics)
- [Public-SaaS benchmarks](#public-saas-benchmarks)
- [Tools to track these](#tools-to-track-these)

## Revenue metrics

### MRR (Monthly Recurring Revenue)

```
MRR = sum of all recurring monthly subscription revenue
```

Excludes one-time fees, setup costs, and usage overages.

### ARR (Annual Recurring Revenue)

```
ARR = MRR × 12
```

Applies to subscription products.

### ARPU (Average Revenue Per User)

```
ARPU = MRR / number of paying customers
```

### ARPA (Average Revenue Per Account)

Same calculation as ARPU but the unit is an account (typically a team) rather than an individual user. Used in B2B reporting.

### Bookings vs. Revenue vs. Cash

- **Bookings**: total contract value signed, including future periods.
- **Revenue (recognized)**: amount delivered to date.
- **Cash**: amount actually collected.

A 12-month contract paid upfront generates $12k bookings, $12k cash, and $1k revenue in month 1.

### Net New MRR

```
Net New MRR = New MRR + Expansion MRR – Contraction MRR – Churn MRR
```

## Retention and churn

### Logo Churn (count-based)

```
Logo Churn % = (customers churned this period / customers at start of period) × 100
```

### Revenue Churn

```
Revenue Churn % = (MRR lost to churn this period / MRR at start of period) × 100
```

### Gross Revenue Retention (GRR)

```
GRR % = (start MRR – churned MRR – contracted MRR) / start MRR × 100
```

Excludes expansion. Caps at 100%.

### Net Revenue Retention (NRR)

```
NRR % = (start MRR – churn – contraction + expansion) / start MRR × 100
```

Includes expansion. Can exceed 100%.

| NRR     | Public-SaaS benchmark interpretation               |
| ------- | -------------------------------------------------- |
| <90%    | Below median.                                      |
| 90–100% | Median range.                                      |
| 100–110%| Above median.                                      |
| 110–130%| Top quartile (public SaaS).                        |
| >130%   | Top decile (public SaaS).                          |

## Acquisition

### CAC (Customer Acquisition Cost)

```
CAC = (sales + marketing spend in period) / new customers acquired in period
```

Includes fully loaded sales/marketing salaries, ad spend, agency fees.

### Blended vs. Paid CAC

- **Blended CAC**: includes organic acquisitions in the denominator.
- **Paid CAC**: only includes paid-channel customers and paid-channel spend.

### CAC Payback Period

```
CAC Payback = CAC / (ARPA × Gross Margin)
```

| CAC payback   | Stage benchmark                                  |
| ------------- | ------------------------------------------------ |
| <12 months    | Common for early-stage SMB SaaS.                 |
| 12–18 months  | Common for mid-market.                           |
| 18–24 months  | Common for enterprise.                           |
| >24 months    | Requires significant capital to scale.           |

### LTV (Customer Lifetime Value)

Two common definitions:

```
Simple LTV = ARPA × Gross Margin / Logo Churn
```

```
Cohort LTV = sum of revenue per cohort over their actual lifetime
```

### LTV:CAC Ratio

```
LTV:CAC = LTV / CAC
```

| Ratio | Interpretation                          |
| ----- | --------------------------------------- |
| <1:1  | Negative unit economics.                |
| 1–3:1 | Marginal.                               |
| 3:1   | Common SaaS benchmark.                  |
| >5:1  | Strong unit economics.                  |

## Activation and engagement

### Activation Rate

```
Activation = users who hit "aha moment" / users who signed up
```

The "aha moment" is product-specific. Examples include:

- Slack: 2,000 messages sent within a workspace.
- Facebook (early): 7 friends added in 10 days.
- Dropbox: install on 1 device + sync 1 file.

### DAU / WAU / MAU

- **DAU** = Daily Active Users.
- **WAU** = Weekly Active Users.
- **MAU** = Monthly Active Users.

DAU/MAU ratio is sometimes called "stickiness."

### North Star Metric

A single metric that captures the core value of the product. Examples:

- Airbnb: nights booked.
- Stripe: TPV (total payment volume).
- Notion: weekly active editors.
- Spotify: time listened.

## Cash and runway

### Burn Rate

```
Net Burn = (cash at start of month) – (cash at end of month)
```

Or:

```
Net Burn = expenses – revenue (per month)
```

### Runway

```
Runway = current cash / monthly net burn
```

### Default Alive vs. Default Dead

A framework introduced by Paul Graham. At your current burn and revenue growth rate:

- **Default Alive**: you'll reach profitability before cash runs out.
- **Default Dead**: you won't, and you'd need to raise to survive.

## Sales metrics

### Pipeline coverage

```
Pipeline Coverage = total open pipeline value / quota for period
```

### Win Rate

```
Win Rate = closed-won deals / total closed deals (in period)
```

### Sales Cycle Length

Days from "qualified opportunity" to "closed-won."

### Magic Number

```
Magic Number = (Net New ARR in quarter × 4) / S&M spend in prior quarter
```

| Magic Number | Interpretation                       |
| ------------ | ------------------------------------ |
| <0.5         | Below median.                        |
| 0.5–0.75     | Median range.                        |
| 0.75–1.0     | Above median.                        |
| >1.0         | Top quartile.                        |

### Quick Ratio

```
Quick Ratio = (New MRR + Expansion MRR) / (Churned MRR + Contraction MRR)
```

| Quick Ratio | Interpretation                   |
| ----------- | -------------------------------- |
| <1          | Net contraction.                 |
| 1–2         | Flat.                            |
| 2–4         | Growth.                          |
| >4          | High growth.                     |

## Public-SaaS benchmarks

These figures shift over time and should be cross-referenced with current public-SaaS reporting (e.g., Tomasz Tunguz, SaaStr, Bessemer, Dimension).

| Stage                   | Growth (YoY) | NRR    | Gross Margin | CAC Payback |
| ----------------------- | ------------ | ------ | ------------ | ----------- |
| Pre-product-market-fit  | n/a          | n/a    | n/a          | n/a         |
| $1M ARR                 | >200%        | 100%+  | 70%+         | <12 mo      |
| $10M ARR                | >100%        | 110%+  | 75%+         | <18 mo      |
| $50M ARR                | >50%         | 115%+  | 78%+         | <24 mo      |
| $100M+ ARR              | >40%         | 120%+  | 80%+         | <24 mo      |

## Tools to track these

See [growth-and-sales.md](../growth-and-sales.md) and [building.md](../building.md) for tool listings. Common categories:

- **Subscription analytics**: ChartMogul, Stripe Sigma, Baremetrics, ProfitWell.
- **Cash and runway modeling**: Pry, Causal, Finmark, Runway.
- **Product analytics**: PostHog, Mixpanel, Amplitude, June, Heap.
- **Pipeline tracking**: Attio, HubSpot, Salesforce, Pipedrive.
