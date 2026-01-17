# 📦 Logistics Performance Diagnostic: Central Asia Region

### 📋 Executive Summary

This project investigates a critical operational bottleneck: a 67% late delivery rate within the Central Asia region. By applying the Pareto Principle (80/20) and correlation analysis, I identified the "Vital Few" hotspots and provided strategic recommendations to optimize SLA compliance and restore brand reliability.

* **Core Problem:** High late delivery rates threatening customer trust and increasing operational overhead.

* **Key Achievement:** Isolated the top 20% of locations responsible for 80% of delays and debunked the "Volume Overload" myth through statistical verification.

### 🎓 Project Context: Self-Study & Research

*This is a personal research project developed for self-learning purposes.*

* **Objective:** To apply data analytics methodologies (Pareto, Correlation, EDA) to a real-world logistics dataset and practice end-to-end business problem-solving.

* **Scope:** The analysis is based on a publicly available dataset from Kaggle to simulate a business diagnostic process for educational and portfolio development.
  
* **AI Collaboration:** Developed with strategic assistance from AI tools for code optimization and documentation structure, ensuring rigorous statistical standards and professional reporting.

### 🛠️ Tech Stack & Methodology

* **Language:** Python (Pandas, Matplotlib, Seaborn).

* **Analytical Techniques:**

  - **Pareto Principle (80/20 Rule):** Used to eliminate statistical noise and focus on high-impact geographic hotspots.

  - **Pearson Correlation:** Evaluated the relationship between order volume and delivery performance to distinguish between capacity vs. process issues.
   
  - **SLA Compliance Analysis:** Benchmarked performance across different shipping tiers.

### 🔍 Key Insights

1. **"First Class" Shipping Failure:** Priority shipping modes exhibit delay rates comparable to standard modes, indicating a breakdown in the "Priority Lane" operational process.

2. **Geographic Concentration:** Identified specific states as hotspots where delays are localized, regardless of total order volume.

3. **Seasonality Bottleneck:** Delay rates spike significantly in Q4, revealing a lack of system elasticity during peak demand periods.

4. **Operational vs. Capacity:** Correlation analysis ($r \approx -0.15$) proved that delays are not driven by order volume, but rather by localized operational inefficiencies.

### 💡 Strategic Business Recommendations

1. **Restructure "First Class" Workflow:** Implement a dedicated priority sorting lane at regional hubs to ensure expedited orders meet their SLA commitments.

2. **Resource Allocation for Hotspots:** Redirect infrastructure investment or re-negotiate 3PL contracts specifically for the top 5 states identified in the Pareto analysis.

3. **Peak Season Elasticity Plan:** Scale temporary labor or expand transit warehouse capacity starting in early October to mitigate the Q4 seasonal surge.

4. **Real-time Monitoring:** Develop a triggered alert system for the Central Asia region when a state's late rate exceeds a 60% threshold.

### 🤝 Contributing & Feedback

I welcome any feedback, questions, or suggestions to improve this diagnostic model!

* **Feedback:** If you have insights on the methodology or business recommendations, please feel free to open an Issue or reach out via LinkedIn.

* **Contribute:** If you'd like to improve the code or visualizations, forks and Pull Requests are more than welcome.

### 📂 Repository Structure

* **Analytics_Notebook.ipynb:** Detailed Jupyter Notebook containing data cleaning, EDA, and statistical testing.

* **data/:** Directory containing the raw Kaggle dataset.

* **images/:** Exported visualizations (Pareto charts, Heatmaps, Trend lines).

### 👤 Contact Information

* **Name:** Phan Thi Thuy Anh

* **LinkedIn:** https://www.linkedin.com/in/blessed-thuy-anh/

* **Email:** thuyanhptta@gmail.com
