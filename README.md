# U.S. Macro Dashboard — Stagflation Watch (June 2026)

An interactive, single-file dashboard tracking the U.S. business cycle through the 2026 energy-price shock: inflation, the Fed's policy path, GDP, manufacturing activity, oil prices and consumer sentiment — all sourced from primary government and survey data.

**[View the live dashboard →](https://anastassiyatrosina.github.io/us-macro-dashboard-2026/)**

## Why this project

Built to demonstrate the core toolkit of applied macro analysis:
- **Sourcing and reconciling primary data** from BLS, BEA, the Federal Reserve, ISM and the University of Michigan
- **Framing data through an economic lens** — a growth/inflation quadrant grounded in a simple macro framework, rather than just charting numbers
- **Being explicit about data limits** — e.g. using ISM's own PMI-to-GDP read-through as a growth proxy where official GDP hasn't been released yet, and flagging where a series (like the Fed funds path before Dec 2025) is reconstructed rather than official
- **Communicating findings** for a non-specialist audience, with the chart doing the explaining rather than dense text

## What's in it

| Section | What it shows |
|---|---|
| Growth/inflation quadrant | Where the economy sits today vs. trend growth and the Fed's 2% target |
| Prices & policy | Headline vs. core CPI; Fed funds rate path and the Fed's own year-end projection |
| Growth & the energy shock | Quarterly real GDP; WTI oil price through the conflict |
| Activity vs. sentiment | ISM Manufacturing PMI vs. University of Michigan consumer sentiment |
| Timeline | The five events that connect the data points |

## Data sources

- U.S. Bureau of Labor Statistics — [CPI](https://www.bls.gov/cpi/) and [Employment Situation](https://www.bls.gov/news.release/empsit.htm)
- U.S. Bureau of Economic Analysis — [GDP releases](https://www.bea.gov/data/gdp/gross-domestic-product)
- Federal Reserve — [FOMC statements & Summary of Economic Projections](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm)
- Institute for Supply Management — [Manufacturing PMI](https://www.ismworld.org/)
- University of Michigan — [Surveys of Consumers](http://www.sca.isr.umich.edu/)

Data current as of June 27, 2026.

## Tech

Plain HTML/CSS/JS, [Chart.js](https://www.chartjs.org/) for charts, no build step.

---

**Anastassiya Troshina** · Economist
[LinkedIn](https://www.linkedin.com/in/anastassiya-troshina-216206388)
