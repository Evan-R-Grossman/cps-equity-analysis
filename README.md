# cps-equity-analysis# Chicago Public Schools Equity Analysis

## The Question

Schools serving low-income students are often assumed to underperform across the board. But is that uniformly true, or are some high-poverty schools succeeding despite serving the most challenging populations? This project looks at every Chicago Public School to find: **which high-need schools are beating expectations, and what does that tell us about where targeted interventions are actually working?**

## The Data

- **652 Chicago Public Schools**
- Sourced from the City of Chicago's open data portal
- Joined the **School Profile** and **School Progress Reports** files on school ID
- Required cleaning and reconciliation across the two files before analysis

## Methodology

- Joined two source files using VLOOKUP on school ID
- Segmented schools into need tiers by low-income population (Low Need, Mid Need, High Need)
- Compared graduation rates and other outcome metrics across tiers
- Identified high-need schools outperforming their tier (the schools worth studying)

## Key Findings

- **The relationship between school poverty and outcomes is not what most people assume.** High Need schools (85%+ low income) actually graduated students at *higher* rates than Mid Need schools (60–85%).
- That pattern suggests **targeted interventions are working at the high end** — the schools serving the most challenging populations have received concentrated support, and it shows in outcomes.
- The Mid Need tier appears to be the actual gap: high enough poverty to face real challenges, but not high enough to attract the same targeted support.

## Why This Matters

The conventional framing — more poverty equals worse outcomes — is too simple to drive policy. This analysis identifies which schools deserve study (high-need outperformers) and where the funding/attention gap actually lives (the middle tier). That's the kind of finding that changes how a district allocates resources.

## Skills Demonstrated

- Joining multiple public datasets on a shared key
- Segmentation analysis (need tiers)
- Identifying outliers worth studying rather than just summarizing averages
- Translating data findings into a policy-relevant frame

## Files

- `CPS_equity_analysis.xlsx` — joined dataset, segmentation, and pivot analyses
- `README.md` — this file
