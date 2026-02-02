Project Title: A/B Testing Analysis Framework

Repository Summary
This project provides a robust end-to-end pipeline for evaluating experimental data. By comparing a Control group (baseline) against a Test group (variant), the analysis determines whether observed differences in user behavior are statistically significant or merely the result of random chance.

# A/B Testing Analysis: Statistical Inference for Product Decisions

## Project Overview
This project performs a comprehensive A/B test analysis to evaluate the impact of [Insert Change, e.g., a New UI/Pricing Model] on key performance metrics. We utilize statistical hypothesis testing to ensure data-driven decision-making.

## Tech Stack
* **Environment:** Google Colab / Jupyter Notebooks
* **Version Control:** GitHub
* **Data Handling:** Pandas, NumPy (CSV/Excel)
* **Statistical Analysis:** SciPy, Statsmodels
* **Visualization:** Matplotlib, Seaborn

##  Workflow
1.  **Data Ingestion:** Loading datasets from CSV/Excel.
2.  **Hypothesis Definition:** Setting $H_0$ (Null) and $H_1$ (Alternative) with $\alpha = 0.05$.
3.  **Statistical Testing:** * **Chi-Square:** For categorical conversion rates.
    * **T-Test:** For continuous metrics (e.g., average spend).
4.  **Inference:** P-value extraction and Confidence Interval calculation.
5.  **Visualization:** Plotting distributions and error bars for visual evidence.

##  Key Findings
Control Group Metric: 0.1124
Test Group Metric: 0.1349
P-Value: 0.0312
Result: Statistically Significant
