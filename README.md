## Business Question
Which customer acquisition channels and cohorts deliver the highest long-term value? How should we allocate marketing budget across channels?

## What This Model Does
- Projects Customer Lifetime Value (LTV) based on empirical retention curves
- Calculates CAC payback period for different acquisition channels
- Models funnel conversion rates and identifies bottlenecks
- Tests scenarios: "What if we increase retention by 5%?" or "What if CAC rises 10%?"

## Key Outputs
- LTV:CAC ratio by cohort
- Payback period visualization
- Sensitivity analysis (tornado chart)

## Technical Stack
Excel (Power Query, XLOOKUP, dynamic arrays) → SQL (cohort retention) → Power BI (dashboard)

## Decision Log
[Link to your decision log explaining: Why these assumptions? When does this model fail?]

## 3-Minute Pitch
"I built a dynamic financial model that tells marketing leaders where to allocate budget. Instead of guessing which channels work, it projects the actual 3-year value of customers from each channel, accounting for retention decay. The model shows that Channel A has 2x the LTV of Channel B, even though Channel B has lower upfront CAC — meaning we should shift budget toward Channel A."
