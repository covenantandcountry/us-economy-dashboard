# U.S. Economy 1950–2024: Party Performance Dashboard

An interactive data dashboard comparing U.S. economic performance under Democratic and Republican presidents and Congresses from 1950 to 2024.

## What This Is

This dashboard scores economic performance across **21 metrics**, **13 presidents**, and **38 Congresses** using a transparent, three-tier methodology. It is not a partisan argument — it is a structured framework for comparison, built on public data from BLS, BEA, FRED, the U.S. Census Bureau, and OMB.

## How It Works

**Three-Tier Scoring System**
- **Tier 1 (60% weight):** Core metrics — GDP growth, unemployment, inflation, federal deficit % GDP
- **Tier 2 (40% weight):** Supporting metrics — wages, jobs, poverty rate, income inequality (Gini), labor force participation
- **Tier 3 (unscored):** Context metrics — Fed funds rate, oil prices, S&P 500, 10-yr Treasury yield. Shown for interpretive context only.

**Lag Adjustment:** Presidential outcomes are attributed 6–12 months after inauguration. Congressional outcomes are lagged 12–18 months. No president or Congress is penalized for the economy they inherited on day one.

**Scores are percentile rankings** (0–100) relative to all administrations in the 1950–2024 baseline — not raw values. Higher always means better performance, regardless of whether the metric is one where lower numbers are desirable (e.g., unemployment).

## Features

- Toggle between **7 historical eras** — scores, charts, and rankings update automatically
- **Annotated event overlays** — economic shocks, major legislation, and Fed policy decisions on every chart
- **Unified government flag** — isolates periods when one party controlled the White House and both chambers simultaneously
- **Per-president and per-Congress rankings** with composite scores and Z-scores on hover
- Zero external dependencies — pure vanilla JS, works offline

## Data Sources

| Source | Data Provided |
|--------|--------------|
| Bureau of Economic Analysis (BEA) | Real GDP growth, real disposable income |
| Bureau of Labor Statistics (BLS) | Unemployment, CPI inflation, payrolls, LFPR |
| Federal Reserve (FRED) | Fed funds rate, 10-yr Treasury, housing starts |
| U.S. Census Bureau (CPS) | Poverty rate, Gini coefficient |
| Office of Management & Budget (OMB) | Federal deficit/surplus |

## Caveats

Economic outcomes are multi-causal. No model can fully isolate presidential or congressional impact from inherited conditions, global forces, or independent Federal Reserve decisions. These scores are a structured framework for comparison — not a definitive causal claim. Use the Tier 3 context tab to understand the external environment each administration faced.
