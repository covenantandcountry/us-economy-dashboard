# U.S. Economy 1950–2024: Interactive Dashboard

### Companion to the Substack series *"The Uncomfortable Truth Nobody Is Talking About"*

---

## Overview

This dashboard provides a data-driven comparison of U.S. economic performance under Democratic and Republican administrations from 1950 to 2024. It covers **75 years of data**, **13 presidents**, **38 Congresses**, and **20 tracked metrics** across a three-tier scoring system. All data is drawn from primary government sources: the Bureau of Labor Statistics, Bureau of Economic Analysis, Federal Reserve, U.S. Census Bureau, and Office of Management and Budget.

The dashboard is designed for a general audience. Every score can be read without statistical training. For readers who want the underlying numbers, Z-scores are available on hover throughout.

---

## How to Use the Dashboard

### Navigation

The dashboard has five tabs:

| Tab | What It Shows |
|---|---|
| **Overview** | Summary scorecard, era selector, how-to-read guide, navigation cards |
| **Tier 1 — Core** | The five primary scored metrics with full chart controls |
| **Tier 2 — Supporting** | Five supporting scored metrics plus the productivity-wage gap |
| **Tier 3 — Context** | Nine unscored reference metrics |
| **Scorecard** | Full D vs R breakdown, president rankings, inherited conditions, gap panel |

### Era Filter

A sticky bar below the navigation tabs lets you filter the entire dashboard — charts, scores, rankings, and all panels — to any of seven historical eras:

| Era | Years | Economic Narrative |
|---|---|---|
| All | 1950–2024 | Full 75-year baseline |
| Postwar Boom | 1950–1969 | High growth, low inequality, bipartisan consensus |
| Stagflation Era | 1970–1979 | Oil shocks, inflation, dollar crisis |
| Reagan Revolution | 1980–2000 | Deregulation, deficits, tech boom, Clinton surplus |
| Modern Era | 2001–2024 | Financial crisis, pandemic, polarization |
| Pre-Reagan | 1950–1979 | Pre-supply-side policy consensus |
| Post-Reagan | 1980–2024 | Supply-side policy regime |

All scores, rankings, and charts update automatically when you switch eras.

### Chart Controls

Each tier tab has four layers of controls:

**Metric Toggle** — switch between metrics using the buttons above the chart. Hold `Shift` and click to overlay multiple metrics of the same unit type simultaneously (e.g. GDP Growth + Unemployment + Inflation, all measured in %).

**View** — `President` shows presidential party bands; `Congress` shows congressional majority bands; `Both` splits the chart horizontally showing both simultaneously.

**Party Filter** — `All` shows all administrations; `Democrat`, `Republican`, or `Split Gov` dims all other periods so you can isolate a single party's record.

**Annotation Overlays** — toggle Economic Shocks (amber triangles), Legislation (green diamonds), and Fed Policy (purple circles) on and off. Click the chevron below the chart to expand the individual event picker — a checklist of every event in the database, grouped by category. Events outside the active era are automatically greyed out.

**Zoom** — `+` and `−` buttons above the chart scale the chart width from 50% to 400%. At zoom levels above 100% a horizontal scrollbar appears for navigation. `Reset` returns to 100%.

---

## Scoring Methodology

### Percentile Ranking

Scores are **percentile ranks**, not raw numbers. A score of 78 means that administration performed better than 78% of all other administrations in the dataset on that metric. This is a relative measure — it captures how each era's performance compares against history rather than against some abstract ideal.

**For metrics where lower is better** (unemployment, inflation, deficit, poverty rate, Gini coefficient), the percentile is inverted: a score of 100 always means best performance, regardless of the metric's direction.

### Z-Score (hover for depth)

Every percentile score in the dashboard has a Z-score available on hover. The Z-score measures how far above or below the historical average a result was, in standard deviations:

| Z-Score | Interpretation |
|---|---|
| +2.0 or higher | Exceptional — among the best on record |
| +0.3 to +2.0 | Above average |
| −0.3 to +0.3 | Near average — essentially typical |
| −0.3 to −2.0 | Below average |
| −2.0 or lower | Among the worst on record |

A high Z-score does not automatically mean good policy. Use the event markers to read it in context — a president who inherited a severe recession and presided over a recovery may have a mediocre Z-score because the crisis years drag down the term average, even if the policy response was effective.

### Lag Adjustment

Policies take time to affect the economy. The dashboard attributes outcomes to administrations with the following lags:

- **Presidential scoring** — outcomes lagged 6–12 months from inauguration (approximately one year)
- **Congressional scoring** — outcomes lagged 12–18 months from the start of each Congress
- **Legislation** — three measurement windows: pre-passage (−12 to 0 months), immediate (0–6 months), long-term (6–18 months)

This means the economy a president "inherits" on inauguration day is largely attributed to their predecessor. The 2008 financial crisis, for example, is attributed to the Bush administration even though its worst effects registered in 2009.

### Tier Weights

| Tier | Weight | Metrics |
|---|---|---|
| Tier 1 — Core | 60% of composite | GDP Growth · Unemployment · CPI Inflation · Deficit % GDP · Labor Productivity |
| Tier 2 — Supporting | 40% of composite | LFPR · Real DPI Growth · Poverty Rate · Gini Coefficient · Real Median Wages |
| Tier 3 — Context | Unscored (reference only) | Fed Funds Rate · S&P 500 · Oil Price · Housing Starts · Consumer Sentiment · 10-Yr Treasury · US Total Debt · Nonfarm Payrolls · Federal Deficit ($B) |

Tier 3 metrics are deliberately excluded from scoring. No president controls the Federal Reserve, global oil prices, or equity markets. Including them would reward or penalize administrations for conditions largely beyond their control.

**Note on the Productivity-Wage Gap:** This derived metric (labor productivity growth minus real median wage growth) appears on the Tier 2 chart and the Scorecard's gap panel, but is **not scored** and does not contribute to party percentile rankings. It is provided as analytical context for the inequality discussion.

---

## Absolute vs. Trajectory Scoring

The Scorecard tab offers two scoring frameworks, toggled at the top of the tab:

**Absolute Performance** — the standard percentile rank described above. Compares each administration's average metric levels against all other administrations 1950–2024.

**Trajectory (Inherited Adjusted)** — percentile rank of *improvement* during the term relative to the inherited baseline. Calculates the change from entry conditions to exit conditions on each Tier 1 metric, then ranks that change against all other administrations. This framework rewards presidents who turned bad situations around, and is more forgiving of administrations that inherited severe economic crises (e.g. Obama in 2009, Reagan in 1981).

**Both** — shows Absolute and Trajectory scores side by side, with a divergence indicator showing where the two frameworks disagree most. Where the gap is large, inherited conditions played a significant role in shaping the record.

Trajectory scoring covers **Tier 1 metrics only**. Tier 2 metrics move too slowly and are too influenced by long-term demographic trends to produce reliable trajectory scores within a single presidential term.

### Inherited Conditions

Each president row in the Scorecard table has an "Inherited ▼" button. Clicking it expands a panel showing the five Tier 1 metric values at the point that president took economic ownership (approximately 12 months into their term). Values are color-coded relative to the 1950–2024 historical average:

- **Green** — favorable inherited conditions (better than average)
- **Amber** — mildly unfavorable conditions
- **Red** — significantly unfavorable conditions (severe crisis)

---

## Metric Reference

### Tier 1 — Core Scored Metrics

| Metric | Source | Notes |
|---|---|---|
| Real GDP Growth (%) | BEA NIPA Table 1.1.1 | Year-over-year % change in real GDP |
| Unemployment Rate (%) | BLS Current Population Survey | Annual average of monthly rates |
| CPI Inflation (%) | BLS CPI-U | Year-over-year % change, annual average |
| Federal Deficit (% GDP) | OMB Historical Tables, Table 1.2 | Positive = deficit; negative = surplus |
| Labor Productivity Growth (%) | BLS Nonfarm Business Productivity | Output per hour worked, YoY % change |

### Tier 2 — Supporting Scored Metrics

| Metric | Source | Notes |
|---|---|---|
| Labor Force Participation (%) | BLS Current Population Survey | Annual average of monthly rates |
| Real DPI Growth (%) | FRED DSPIC96 | Real disposable personal income, YoY % change |
| Poverty Rate (%) | Census Bureau CPS | Annual; data begins 1959 |
| Gini Coefficient | Census Bureau CPS | 0 = perfect equality; 1 = perfect inequality. Annual; data begins 1963. Displayed to 3 decimal places |
| Real Median Wages (%) | Census / BLS (spliced) | Census median family income 1950–1978; BLS median usual weekly earnings 1979–2024. **Scored from 1979 only** to avoid mixing methodologies. A dashed amber marker at 1979 indicates the splice point on the chart |

### Tier 3 — Context (Unscored)

| Metric | Source | Notes |
|---|---|---|
| Federal Funds Rate (%) | FRED FEDFUNDS | Annual average; independent Fed decisions |
| S&P 500 Annual Return (%) | Standard & Poor's | Total return including dividends |
| WTI Crude Oil Price ($/bbl) | EIA | Annual average spot price |
| Housing Starts (thousands) | Census Bureau | Annual total starts |
| Consumer Sentiment (index) | University of Michigan | Annual average; data begins 1966 |
| 10-Year Treasury Yield (%) | FRED DGS10 | Annual average |
| US Total Public Debt ($B) | Treasury/FRED GFDEBTN | End-of-year nominal balance |
| Nonfarm Payrolls Change (M) | BLS CES | Annual net job change in millions |
| Federal Deficit (Nominal $B) | OMB Historical Tables | Annual unified budget deficit in nominal dollars |

**Note on Nonfarm Payrolls and Federal Deficit ($B):** These metrics were moved from Tier 2 to Tier 3 to address structural imbalances in the scoring framework. Payrolls overlaps significantly with the unemployment rate and LFPR. Nominal deficit overlaps with Deficit % GDP in Tier 1. Both remain visible and explorable on the Tier 3 chart.

### Derived Metric (Unscored)

| Metric | Calculation | Notes |
|---|---|---|
| Productivity-Wage Gap (% pts) | Labor Productivity Growth − Real Median Wage Growth | Positive = productivity outpacing wages (workers capturing less). Negative = wages outpacing productivity. Available on the Tier 2 chart (blue line) and Scorecard gap panel |

---

## Political Control Data

| Data Point | Source |
|---|---|
| Presidential party by year | Congressional Research Service / National Archives |
| Senate majority by year | U.S. Senate Historical Office |
| House majority by year | Office of the Historian, U.S. House of Representatives |

**Unified Government** is defined as one party controlling the White House, Senate, and House simultaneously. Periods of unified control are highlighted with a dotted border overlay on the charts.

**Split Government** occurs when no single party controls all three simultaneously (including tied Senates, e.g. 2001).

---

## Event Database

The dashboard includes three categories of overlay events, each individually selectable via the event picker below each chart:

**Economic Shocks (18 events)** — OPEC embargo, Volcker shock, dot-com bust, 9/11, Global Financial Crisis, COVID-19, and others. Rendered as amber triangles.

**Major Legislation (24 events)** — Revenue Act of 1964, Reagan tax cuts, NAFTA, Clinton deficit reduction, Bush tax cuts, TARP, ACA, Dodd-Frank, Tax Cuts and Jobs Act, CARES Act, American Rescue Plan, Infrastructure Law, IRA, CHIPS Act, and others. Rendered as green diamonds.

**Fed Policy Shifts (13 events)** — Volcker disinflation, Greenspan era, post-recession rate cuts, quantitative easing cycles, taper tantrum, liftoff, emergency COVID cuts, 2022 hike cycle, and others. Rendered as purple circles.

Events outside the active era window are automatically excluded from chart rendering and greyed out in the event picker.

---

## Key Caveats

**Economic outcomes are multi-causal.** No statistical model can fully isolate presidential or congressional impact from global forces, inherited conditions, or Federal Reserve decisions. These scores are a structured framework for comparison — not a definitive causal claim.

**The lag adjustment is an approximation.** A 6–12 month lag is methodologically defensible but imprecise. Some policies work faster; some take years. The lag is applied consistently across all administrations.

**Trajectory scoring has limits.** A president who inherited a disaster and showed modest improvement may score higher than a president who maintained excellent conditions they inherited, even if the latter's record was objectively better in absolute terms. This is why both frameworks are shown.

**Tier 2 inequality metrics require context.** A rising Gini coefficient indicates growing income dispersion but does not by itself indicate falling living standards — real DPI and poverty rate must be read alongside it. The dashboard provides all three.

**Real median wages use a spliced series.** Pre-1979 Census family income data and post-1979 BLS weekly earnings data use different methodologies and sampling frames. The splice is disclosed on the chart and wages are scored from 1979 only.

---

## Data Sources

- **Bureau of Economic Analysis (BEA)** — Real GDP. https://www.bea.gov
- **Bureau of Labor Statistics (BLS)** — Unemployment, CPI, LFPR, payrolls, labor productivity, median weekly earnings. https://www.bls.gov
- **Federal Reserve Economic Data (FRED)** — Fed funds rate, 10-yr Treasury, real DPI, monetary aggregates. https://fred.stlouisfed.org
- **U.S. Census Bureau** — Poverty rate (from 1959), Gini coefficient (from 1963), median family income (1950–1978). https://www.census.gov
- **Office of Management and Budget (OMB)** — Federal deficit/surplus, public debt. https://www.whitehouse.gov/omb/budget/historical-tables
- **Energy Information Administration (EIA)** — WTI crude oil price. https://www.eia.gov
- **University of Michigan** — Consumer Sentiment Index. https://data.sca.isr.umich.edu
- **National Bureau of Economic Research (NBER)** — Business cycle dating. https://www.nber.org/research/business-cycle-dating

---

## Article Series

This dashboard was built as the data foundation for a three-part Substack series:

- **Part 1** — The Presidential Record: 75 Years of U.S. Economic Data Tells a More Complicated Story Than Either Party Wants You to Believe
- **Part 2a** — The Legislative Effect: Congressional Control and the Economy
- **Part 2b** — The Legislative Effect: When Laws Move the Needle (five landmark laws examined)
- **Part 3** — The Verdict: What 75 Years Has Shown Us

---

## License & Attribution

Data is from U.S. government primary sources and is in the public domain. Dashboard code and visualizations are original work. If you use this dashboard or its methodology in your own analysis, attribution is appreciated.

*Built with pure HTML/CSS/JavaScript — no frameworks, no external dependencies beyond Google Fonts. Works offline, on GitHub Pages, and in any modern browser.*
