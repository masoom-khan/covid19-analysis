# COVID-19 Global Trend Analysis

This was a project I worked on to get a clearer picture of how the pandemic unfolded globally and whether vaccination campaigns actually showed up in the mortality data. Spoiler: they did, pretty strongly.

---

## What this analysis covers

- Global daily cases and deaths from January 2020 through December 2022
- Variant wave identification (Alpha, Delta, Omicron)
- Country-level comparisons — top 20 by total cases and case fatality rate
- Vaccination rate vs. case fatality rate correlation analysis

## Dataset

| Source | What it contains |
|--------|-----------------|
| [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19) | Daily confirmed cases and deaths by country |
| [Our World in Data](https://github.com/owid/covid-19-data) | Vaccination rates by country |

Both datasets are publicly available. Download instructions are in `data/README_data.md`.

## Tools used

Python 3.8+, Pandas, NumPy, Matplotlib, Seaborn

## Running this yourself

```bash
git clone https://github.com/masoom-khan/covid19-analysis.git
cd covid19-analysis
pip install -r requirements.txt
# Follow data/README_data.md to download the datasets
jupyter notebook covid19_analysis.ipynb
```

## Key findings

- Global case fatality rate dropped from ~4% in early 2020 to under 1% by end of 2022
- Countries with 70%+ vaccination coverage showed ~45% lower CFR on average
- Correlation between vaccination rate and CFR: r = -0.68 (statistically significant)
- Pakistan's peak wave was the Delta variant in July 2021

## Charts

All output charts are in the `outputs/` folder.

---

**Muhammad Masoom Khan** — Data Analyst | MSF Holland  
[Portfolio](https://masoom-khan.github.io) · [LinkedIn](https://www.linkedin.com/in/muhammadmasoomkhan/)