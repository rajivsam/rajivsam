# Rajiv Sambasivan | Statistical Learning & Decision Architecture

Independent advisor and builder specializing in **statistically grounded, interpretable analytical systems**. I combine PhD-level training in statistical machine learning with 25+ years of software engineering experience to help organizations understand their data's underlying structure before committing to complex predictive models.

Rather than treating modeling as a black-box exercise or selling rigid platform lock-in, I focus on **descriptive diagnostics, problem framing, and auditable open-source workflows** that stay valid as operating conditions change.

---

## 🔬 Core Approach & Specializations

* **Descriptive Diagnostics & Structure Discovery:** Time-series decomposition (SSA), Poisson window selection for arrival processes, regime and structural-break detection, heterogeneity assessment, and variance accounting before modeling.
* **Statistical Learning & Domain Modeling:** Interpretable classification, regression, survival analysis, panel data, intensity-based count modeling, graph representations, and discrete optimization tailored to real operational constraints.
* **Reproducible Engineering & Knowledge Lineage:** Translating statistical methodology into clean, client-owned Python packages and auditable analytical workflows without proprietary vendor lock-in.

---

## 🛠️ Open-Source Analytical Toolkit

I maintain an interconnected suite of open-source Python tools built for **analyst-guided, diagnostic-first data science**:

### 📈 `tseda` — Time-Series Exploratory Decomposition & Diagnostics
An SSA-first Python package and interactive UI for solving the "cold-start" problem in operational time series. It separates trend, seasonality, and residual noise, identifies regime shifts, and validates signal structure using spectral checks and Durbin-Watson diagnostics before forecasting or anomaly detection begins.
* 👉 **Repository:** [Exploratory tool for Time Series Analysis](https://github.com/rajivsam/tseda)

### ⏱️ `count_ts_window_selector` — Poisson Window Selection for Count Time Series
A statistical pre-modeling package for higher-event-rate arrival and count processes. Using density screening, zero-inflation checks, and Fano-factor confidence intervals, it identifies sampling windows where event counts behave locally as a homogeneous Poisson process—allowing downstream models (including `tseda`) to track the evolution of arrival intensity cleanly.
* 👉 **Repository:** [count time series window selection](https://github.com/rajivsam/count_ts_window_selector)

### 🔍 `structure_id` — Cross-Sectional Dataset Structure Identification
A descriptive diagnostic package for uncovering internal heterogeneity in tabular datasets prior to global modeling. It detects redundant feature blocks (via normalized mutual information), dense subpopulations, and latent structural breaks so teams know when i.i.d. assumptions fail or drift emerges.
* 👉 **Repository:** [Structural Decomposition Tool for Cross-Sectional Datasets](https://github.com/rajivsam/structure_identification_for_CS_data/)

### 🧠 `KMDS` — Knowledge Management for Data Science
An ontology-backed knowledge layer that captures the analytical reasoning, data-quality decisions, and modeling assumptions behind a project. Rather than acting as an MLOps execution tracker, KMDS preserves modeling continuity so teams can warm-start future iterations from a documented, auditable baseline.
* 👉 **Core Framework:** [Core KMDS Framework](https://github.com/rajivsam/kmds)
* 👉 **Applied Case Studies (Finance, Retail, IT Ops):** [KMDS Case Studies](https://github.com/rajivsam/kmds_migration)

---

## 📈 Background & Experience

* **25+ Years of Software & Analytical Engineering:** Built and scaled data-centric applications across **Financial Services, Retail, Telecom, Transportation, and Government**.
* **Engineering + Modeling Depth:** 10 years architecting software for scheduling and capacity management, followed by 15+ years focused on statistical learning, information retrieval, graph analytics, and discrete optimization.
* **Academic Foundation:** PhD in Machine Learning (trained under a committee of statisticians). Published research spanning fast Gaussian processes, Bayesian learning for big data, Singular Spectrum Analysis, augmented trees, and graph neural networks is available on [Google Scholar](https://google.com).

---

## 💼 Advisory & Collaboration

I partner directly with CTOs, engineering leaders, and analytical teams on focused engagements where **decision validity, interpretability, and mathematical maintenance** matter:
* **Problem Framing & Diagnostic Audits:** Assessing whether operational data supports modeling, uncovering hidden subpopulations, and diagnosing structural drift.
* **Domain-Specific Statistical Solutions:** Designing transparent, maintainable models and feature representations rooted in the actual data-generating process.
* **Open-Platform Transition:** Replacing opaque, costly vendor workflows with auditable, client-owned Python pipelines.

📫 **Connect:**
* **Advisory & Methodology:** [r2-ds.com](https://r2-ds.com)
* **LinkedIn:** [://linkedin.com](https://www.://linkedin.com/)
* **Publications:** [Google Scholar](https://google.com)
