# SaaS Metrics Cheatsheet [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Every metric an AI startup founder should know — formulas, what's "good" at each stage, and the metric that actually matters.

[← Back to main list](../README.md) · See also: [Growth & sales tools](../growth-and-sales.md) · [Fundraising](../fundraising.md)

---

## The metrics that matter most

If you only watch four numbers as a SaaS founder, watch these:

1. **Net Revenue Retention (NRR)** — Are existing customers expanding or churning?
2. **Cash Burn / Runway** — How many months can you survive without raising?
3. **Pipeline Coverage / Activation Rate** — Are new users actually finding value?
4. **CAC Payback Period** — How fast do you recover acquisition cost?

Most other metrics are downstream of these.

---

## Revenue metrics

### MRR (Monthly Recurring Revenue)

```
MRR = sum of all recurring monthly subscription revenue
```

Strip out one-time fees, setup costs, and usage overages. Pure recurring.

### ARR (Annual Recurring Revenue)

```
ARR = MRR × 12
```

Used in fundraising and reporting. Note: only applies to subscription products, not pure-usage pricing.

### ARPU (Average Revenue Per User)

```
ARPU = MRR / number of paying customers
```

### ARPA (Average Revenue Per Account) — for B2B

Same idea, but accounts include teams. Watch this for B2B.

### Bookings vs. Revenue vs. Cash

- **Bookings**: total contract value signed (includes future periods).
- **Revenue (recognized)**: amount actually delivered to date.
- **Cash**: amount actually collected.

Don't conflate these. Annual contract paid upfront = $12k bookings, $12k cash, but only $1k revenue in month 1.

### Net New MRR

```
Net New MRR = New MRR + Expansion MRR – Contraction MRR – Churn MRR
```

The single most important leading-indicator metric.

---

## Retention & churn

### Logo Churn (count-based)

```
Logo Churn % = (customers churned this period / customers at start of period) × 100
```

### Revenue Churn

```
Revenue Churn % = (MRR lost to churn this period / MRR at start of period) × 100
```

Always look at *both*. You can have low logo churn and high revenue churn (a few big accounts left) — and vice versa.

### Gross Revenue Retention (GRR)

```
GRR % = (start MRR – churned MRR – contracted MRR) / start MRR × 100
```

Ceiling at 100%. Doesn't include expansion. The cleanest measure of "how sticky is the product."

### Net Revenue Retention (NRR)

```
NRR % = (start MRR – churn – contraction + expansion) / start MRR × 100
```

Can exceed 100%. The single most important SaaS health metric.

| NRR     | Interpretation                                     |
| ------- | -------------------------------------------------- |
| <90%    | Leaky bucket. Will need constant net-new sales.    |
| 90–100% | Average. Will scale, but slowly.                   |
| 100–110%| Good. Existing book pays for some growth.          |
| 110–130%| Great. Top-quartile public SaaS.                   |
| >130%   | Exceptional. Best-in-class (Snowflake-tier).        |

---

## Acquisition

### CAC (Customer Acquisition Cost)

```
CAC = (sales + marketing spend in period) / new customers acquired in period
```

Include fully loaded sales/marketing salaries, ad spend, agency fees.

### Blended CAC vs. Paid CAC

- **Blended CAC**: includes organic acquisitions in the denominator. Useful for board reporting.
- **Paid CAC**: only includes paid-channel customers and paid-channel spend. Useful for ad-budget decisions.

### CAC Payback Period

```
CAC Payback = CAC / (ARPA × Gross Margin)
```

| CAC payback   | Verdict                                          |
| ------------- | ------------------------------------------------ |
| <12 months    | Excellent (especially for early-stage SMB SaaS)  |
| 12–18 months  | Good for mid-market                              |
| 18–24 months  | Acceptable for enterprise                        |
| >24 months    | Hard to scale without a lot of cash              |

### LTV (Customer Lifetime Value)

Two common definitions, both flawed:

```
Simple LTV = ARPA × Gross Margin / Logo Churn
```

```
Cohort LTV = sum of revenue per cohort over their actual lifetime
```

Cohort LTV is much more honest if you have the data.

### LTV:CAC Ratio

```
LTV:CAC = LTV / CAC
```

| Ratio | Verdict                                   |
| ----- | ----------------------------------------- |
| <1:1  | You lose money on every customer          |
| 1–3:1 | Marginal — usually means you should fix CAC |
| 3:1   | The "good" benchmark                      |
| >5:1  | Exceptional, or you're under-investing in growth |

---

## Activation & engagement

### Activation Rate

```
Activation = users who hit "aha moment" / users who signed up
```

The "aha moment" is product-specific. Examples:

- Slack: send 2,000 messages within a workspace
- Facebook (early): add 7 friends in 10 days
- Dropbox: install on 1 device + sync 1 file

If you don't know yours, you don't have one — find it.

### DAU / WAU / MAU

- **DAU** = Daily Active Users
- **WAU** = Weekly Active Users
- **MAU** = Monthly Active Users

For consumer or daily-use products: track DAU/MAU ratio (also called "stickiness"). 50%+ is great.

### North Star Metric

The single metric that best captures the value your product delivers. Examples:

- Airbnb: nights booked
- Stripe: TPV (total payment volume)
- Notion: weekly active editors
- Spotify: time listened
- Yaps: words dictated per active user per week

Pick one. Put it on a wall. Argue about it weekly.

---

## Cash and runway

### Burn Rate

```
Net Burn = (cash at start of month) – (cash at end of month)
```

Or, simplified:

```
Net Burn = expenses – revenue (per month)
```

### Runway

```
Runway = current cash / monthly net burn
```

| Runway        | Action                                            |
| ------------- | ------------------------------------------------- |
| <6 months     | Raise NOW, even at unfavorable terms              |
| 6–12 months   | Start fundraising                                 |
| 12–18 months  | Healthy. Use the time to hit milestones.          |
| 18–24 months  | Comfortable. Focus on growth, not fundraising.    |
| >24 months    | Either you raised a lot, or you're profitable.    |

### Default Alive vs. Default Dead

Paul Graham's framing. At your current burn and revenue growth rate, will you run out of cash before becoming profitable?

- **Default Alive**: you'll get to profitability before cash runs out
- **Default Dead**: you won't, and you have to raise to survive

Plot it.

---

## Sales metrics (for B2B)

### Pipeline coverage

```
Pipeline Coverage = total open pipeline value / quota for period
```

3x is the rule of thumb (i.e., 3x your quarterly quota in the pipeline).

### Win Rate

```
Win Rate = closed-won deals / total closed deals (in period)
```

Look at this by ICP, channel, deal size — single average is too coarse.

### Sales Cycle Length

Days from "qualified opportunity" to "closed-won." Track median, not mean.

### Magic Number

```
Magic Number = (Net New ARR in quarter × 4) / S&M spend in prior quarter
```

| Magic Number | Verdict                              |
| ------------ | ------------------------------------ |
| <0.5         | Sales engine is broken — fix before scaling |
| 0.5–0.75     | Tweak                                |
| 0.75–1.0     | Healthy                              |
| >1.0         | Excellent. Pour fuel.                |

### Quick Ratio

```
Quick Ratio = (New MRR + Expansion MRR) / (Churned MRR + Contraction MRR)
```

| Quick Ratio | Verdict                          |
| ----------- | -------------------------------- |
| <1          | Shrinking                        |
| 1–2         | Treading water                   |
| 2–4         | Growing                          |
| >4          | Hyper-growth                     |

---

## Funnel benchmarks (rough)

For a B2B SaaS with PLG distribution:

| Stage                         | Median  | Top quartile |
| ----------------------------- | ------- | ------------ |
| Visitor → Signup              | 2–5%    | 5–10%        |
| Signup → Activated            | 20–40%  | 50%+         |
| Activated → Paid              | 5–10%   | 15%+         |
| Trial → Paid (free trial)     | 10–20%  | 30%+         |
| Free → Paid (freemium)        | 1–4%    | 5%+          |

If you're materially below median on one step, focus all your fix-it energy there.

---

## Public-SaaS benchmarks (Q1 2026 reference)

These shift constantly — check Tomasz Tunguz, SaaStr, or Dimension's reports for the latest.

| Stage               | Growth (YoY)  | NRR      | Gross Margin | CAC Payback |
| ------------------- | ------------- | -------- | ------------ | ----------- |
| Pre-product-market-fit | n/a — focus on activation | n/a | n/a | n/a |
| $1M ARR             | >200%         | 100%+    | 70%+         | <12 mo      |
| $10M ARR            | >100%         | 110%+    | 75%+         | <18 mo      |
| $50M ARR            | >50%          | 115%+    | 78%+         | <24 mo      |
| $100M+ ARR          | >40%          | 120%+    | 80%+         | <24 mo      |

---

## What investors actually look at

Most VCs build a simple model the moment they see your deck. They want:

1. **Growth rate (MoM, QoQ, YoY)** — the most predictive metric of future ARR
2. **NRR** — the proxy for product quality
3. **Gross margin** — to model long-term unit economics
4. **CAC payback / LTV:CAC** — to model marketing scale-up cost
5. **Burn multiple** ($ burned per $ of net new ARR) — capital efficiency
6. **Headcount efficiency** ($ ARR per FTE)

Have these in row 1 of your deck. Don't bury them in slide 18.

---

## Tools to actually track all this

See [growth-and-sales.md](../growth-and-sales.md) and [building.md](../building.md) for tools. Quick recommendations:

- **MRR / ARR / churn**: ChartMogul, Stripe Sigma, Baremetrics, ProfitWell (free)
- **Cash / runway**: Pry, Causal, a Google Sheet (no shame)
- **Product analytics**: PostHog, Mixpanel, Amplitude, June, Heap
- **Pipeline**: Linear (informally), Attio, HubSpot, Salesforce
