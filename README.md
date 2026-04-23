A/B Test Analysis — Conversion Rate Optimization
📊 Project Context
In a professional data analytics environment, running an A/B test is only valuable when the statistical methodology is sound and the results are actionable. This project implements a complete end-to-end A/B testing pipeline to analyse conversion rate performance across control and variant groups, covering everything from raw data cleaning to executive-ready business recommendations.
The goal was to determine whether a product change produced a statistically and practically significant improvement — using industry-standard hypothesis testing methods: Python → PostgreSQL → Statistical Analysis → Business Recommendations.

🛠 Tech Stack

Language: Python (Pandas, SciPy, NumPy, Matplotlib, Seaborn)
Environment: Jupyter Notebook
Statistical Methods: Two-proportion Z-test, Confidence Intervals, Cohen's h, Power Analysis


🚀 Key Technical Achievements

Data Cleaning Pipeline: Resolved missing values, outliers, and group imbalance issues to ensure test validity before any statistical analysis.
Hypothesis Testing Framework: Applied a two-proportion Z-test at α = 0.05 with pre-calculated sample sizes to maintain 80% statistical power throughout.
Effect Size Validation: Computed Cohen's h alongside p-values to distinguish statistically significant results from practically meaningful ones — a critical distinction in high-traffic A/B environments.
Segmentation Analysis: Broke results down by user subgroups to identify where the variant performed strongest, enabling targeted rollout recommendations.


🛡️ Key Analytical Deliverables
1. Hypothesis Test & Result

Null Hypothesis (H₀): The variant produces no difference in conversion rate vs. control.
Test Used: Two-proportion Z-test (two-tailed), α = 0.05
Outcome: [Insert your p-value and decision — e.g. "Rejected H₀ at p = 0.02"]
95% Confidence Interval: [Insert your CI — e.g. "+1.1% to +4.9% conversion lift"]

2. Effect Size & Practical Significance

Cohen's h: [Insert value] — interpreted as a small/medium/large effect
Key principle applied: statistical significance ≠ practical significance. Every result was cross-validated against effect size before any recommendation was made.

3. Segmentation Analysis

Identified which user segments drove the strongest lift, informing a targeted rather than blanket rollout strategy.

4. Business Recommendations

Translated statistical output into a clear ship/no-ship decision with supporting rationale for both technical and non-technical stakeholders.


📁 Repository Structure

ab_test_analysis.ipynb — Main Jupyter Notebook containing all 6 analysis phases
data/ — Raw and cleaned datasets
README.md — Project documentation


⚙️ How to Run

Clone the repo and place the dataset in the data/ folder
Install dependencies: pip install -r requirements.txt
Launch: jupyter notebook ab_test_analysis.ipynb


📊 Concepts Demonstrated
Null & alternative hypothesis formulation · Z-score and p-value interpretation · Confidence interval construction · Cohen's h effect size · Statistical power analysis · Segment-level A/B testing · Communicating findings to non-technical stakeholders

Developed as a portfolio project to demonstrate end-to-end A/B testing methodology and applied statistical reasoning in a business context.
