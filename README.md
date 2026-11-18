A/B Testing & User Behavior Analysis

Conversion Funnel and Experimental Analysis

Author: Gabriela Veriato
Project Type: Exploratory Data Analysis & A/B Testing
Tools: Python | Pandas | NumPy | Matplotlib | Seaborn | SciPy | Statsmodels | Jupyter Notebook

---

Project Overview

This project analyzes user behavior in a food products application to understand the purchasing journey and evaluate the impact of an experimental interface change.

The analysis combines event funnel exploration with A/A/B testing to investigate user engagement, conversion rates and statistically significant differences between experimental groups.

Business Objectives

- Understand how users navigate through the application.
- Identify conversion rates at each stage of the purchasing funnel.
- Detect the stages with the highest user drop-off.
- Validate the consistency of control groups through A/A testing.
- Evaluate the impact of an experimental change through A/B testing.
- Apply statistical adjustments to reduce false positive conclusions.

Tools & Technologies

- Python: Data analysis and statistical computing.
- Pandas & NumPy: Data preparation and manipulation.
- Matplotlib & Seaborn: Data visualization.
- SciPy & Statsmodels: Statistical hypothesis testing.
- Jupyter Notebook: Interactive analysis environment.

Project Workflow

1. Data Inspection: Exploration of event logs, users and timestamps.
2. Data Preparation: Column standardization, datetime conversion and filtering incomplete data.
3. Event Analysis: Investigation of user activity and application usage.
4. Conversion Funnel: Analysis of the journey from the main screen to successful payment.
5. A/A Testing: Validation of the two control groups (246 and 247).
6. A/B Testing: Comparison of the experimental group (248) against each control group and the combined controls.
7. Statistical Validation: Application of the Bonferroni correction to account for multiple hypothesis tests.

Key Findings

- The main drop-off occurs between the main screen and the offers screen, with a conversion rate of 61.9%.
- 81.3% of users move from the offers screen to the cart.
- 94.8% of users move from the cart to successful payment.
- Overall, 47.7% of users who viewed the main screen completed the purchasing journey.
- The A/A test confirmed similar behavior between the two control groups.
- Initial A/B comparisons showed a difference in one event, but no statistically significant differences remained after applying the Bonferroni correction.

Repository Structure

ab-testing-user-behavior-analysis/
│
├── README.md
└── ab_testing_user_behavior_analysis.ipynb

How to Run

1. Clone or download this repository.
2. Open the notebook using Jupyter Notebook or Google Colab.
3. Install the required libraries:

pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter

4. Make the "logs_exp_us.csv" dataset available in the notebook environment.
5. Execute the notebook cells sequentially.

Project Status

Completed and approved as an academic data analytics project.

---

This project demonstrates practical skills in user behavior analysis, conversion funnel metrics, A/B experimentation and statistical hypothesis testing.
