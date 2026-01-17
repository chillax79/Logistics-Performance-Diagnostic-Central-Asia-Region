# Logistics Performance Diagnostic: Central Asia Region

## 1. Project Overview

This project provides a data-driven diagnostic of the logistics performance in the Central Asia region. With a recorded late delivery rate of 67%, the analysis aims to identify systemic bottlenecks and distinguish between operational inefficiencies and capacity constraints.

## 2. Key Insights & Findings

### Segment 1: Shipping Mode & SLA Compliance

* **First Class Failure:** Data reveals a 100% failure rate for First Class shipments, which consistently miss the premium 0-1 day delivery window, flat-lining at a 2-day median.
* **Resource Misallocation:** "Standard Class" orders frequently arrive in 0-1 days (over-servicing), suggesting that resources are being diverted from priority express shipments to low-tier orders.
* **Category Inconsistency:** High-value items like Electronics are prioritized (2-5 days), while other top categories regularly hit a 6-day delay cap.

### Segment 2: Regional Hotspots & Causality (Pareto & Correlation)

* **The Vital Few (Key Accounts):** Using the **Pareto (80/20) Principle**, we identified that 85% of regional volume is driven by a small group of "Key Account" states (hubs with ≥ 23 orders).
* **Process vs. Capacity:** A Correlation Analysis between order volume and late rates yielded $r \approx -0.15$. This near-zero correlation proves that higher volume does NOT cause more delays, confirming the issue is a process-driven failure rather than a lack of physical capacity.

### Segment 3: Temporal Trends & Data Integrity

* **Seasonal Bottleneck:** Late rates surge during Q4 (Holiday Season), peaking at 75% in December due to scalability issues.
* **Statistical Outlier (August 2016):** A 100% late rate was recorded for this month; however, it was identified as a noise point with only **one order ($n=1$)**. This was excluded from the trend narrative to ensure statistical integrity.

## 3. Data Source & Credit
* **Dataset:** DataCo Smart Supply Chain Systems
* **Source:** [Kaggle Repository](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)
* **Credits:** Original research data by Fabian Constante, Fernando Relvas, and Ianir Iakovlev. Curated for Kaggle by Shashwat Tiwari.
* **License:** CC0: Public Domain

**Note:** The raw data file is too large for GitHub storage. To reproduce this analysis, please download the CSV from Kaggle and place it in the project root directory.

## 4. Tech Stack & Methodology
* **Environment:** Analyzed using Python 3 on Google Colab.

* **Libraries Used:**
  * Pandas: Data manipulation and column pruning (53 down to 10 columns).
  * Seaborn & Matplotlib: Statistical visualizations (Boxplots, Scatter plots, Trendlines).

* **Methodology:**
  * Data Cleaning: Standardized datetime objects and binary target variables (Late Delivery).
  * Segmentation: Categorized states into "Key Accounts" vs. "Long-tail" for targeted diagnostic.

## 5. How to Reproduce

* Clone this repository.
* Download the dataset from the Kaggle link in Section 3.
* Open Analytics_Notebook.ipynb and run all cells sequentially.
