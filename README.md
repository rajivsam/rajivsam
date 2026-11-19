# Rajiv Sambasivan
### Statistical learning for data-rich companies that want ML they can understand, own, and afford

Most ML problems I'm called in on aren't model problems. They're data problems
(hidden heterogeneity, shifting regimes, the wrong window) or ownership problems
(a system nobody on the team can explain or maintain). I fix both, with PhD-level
statistical training and 25+ years of production software engineering behind the work,
and without the big-vendor premium.

**Best fit if you:**
- have an existing ML system that is hard to interpret, expensive to run, or fragile to maintain, or
- are starting a new ML initiative and want it built to be explainable and owned by your team from day one.

---

## How I work

1. **Diagnose before modeling.** Structured audits of your data: trends, seasonality,
   structural breaks, and whether one model is even the right answer.
2. **Prefer interpretable methods.** Classification, regression, survival analysis, panel data,
   and optimization, with the simplest approach that meets the need.
3. **Hand over what you own.** Clean Python packages, documented and reproducible,
   no vendor lock-in, no black boxes your team can't maintain.

## What this looks like in practice

| Your situation | What I do | Typical outcome |
|---|---|---|
| Model performance has drifted and nobody knows why | Regime/structural-break diagnostics | see [tseda](https://github.com/rajivsam/tseda) and [structural decomposition tool](https://github.com/rajivsam/structure_identification_for_CS_data) for examples |
| Operational counts (orders, claims, tickets) swing unpredictably | Count Time Series Analysis| see [count window selector](https://github.com/rajivsam/count_ts_window_selector) for examples |
| One model underperforms across customer segments | Heterogeneity testing and structure identification | [e.g., segment-aware design], see   [structural decomposition tool](https://github.com/rajivsam/structure_identification_for_CS_data)|
| Cloud/vendor ML costs are climbing | Right-size to simpler, in-house-maintainable methods | see [the kmds examples for how a solution would look](https://github.com/rajivsam/kmds_migration)|



## Open-source toolkit (what I use on engagements)

| Tool | Solves |
|---|---|
| [`tseda`](https://github.com/rajivsam/tseda) | Decompose a time series into trend, seasonality, and noise before you model it |
| [`count_ts_window_selector`](https://github.com/rajivsam/count_ts_window_selector) | Detect real rate changes in count data |
| [`structure_id`](https://github.com/rajivsam/structure_identification_for_CS_data/) | Diagnose heterogeneity in cross-sectional data |
| [`KMDS`](https://github.com/rajivsam/kmds) | Keep data science work documented and reusable across a team ([case studies](https://github.com/rajivsam/kmds_migration)) |

For an example of typcial project development summary, see [the sba model development summary](https://github.com/rajivsam/kmds_migration/blob/main/sba_migration/documents/sba_modelling_overview.md)

## Writing
- [Heterogeneity Testing: Why One Model Is Sometimes the Wrong Answer](https://r2dssanity.substack.com/p/heterogeneity-testing-why-one-model): *How to test whether your data reflects one stable process or hidden sub-populations that require separate models.*
- [Foundation Models for Tabular Data: A Second Opinion or the Oracle?](https://r2dssanity.substack.com/p/foundation-models-for-tabular-data): Where pre-trained tabular models help with cold starts, and why domain judgment and interpretability still matter more than model size.*

## Background
PhD in Machine Learning ([Google Scholar](https://scholar.google.com/citations?user=96db8S4AAAAJ&hl=en)) ·
25+ years across financial services, retail, telecom, transportation, and government.

## Let's talk
**Start with a short conversation about your current ML setup or planned project: [r2-ds.com](https://r2-ds.com)**
[LinkedIn](https://www.linkedin.com/in/rajiv-sambasivan/) · [Substack](https://substack.com/@r2dssanity)
