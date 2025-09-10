# A/B Testing with Fairness

**Simulated experiment + fairness analysis** for a personalization algorithm in e-commerce.

## Project summary
- Simulated an A/B experiment with **N = 50,000** users.
- Primary metric: **conversion** (binary).
- Performed: sample-size planning, two-proportion z-test, subgroup analysis, logistic regression with interaction terms to test heterogeneous effects.
- Key insight: Treatment increases overall conversions (≈ +2.08 pp), but benefits concentrate among older and high-income users → fairness concerns.

## Repo structure
- `data/` — synthetic dataset (`ab_test_fairness_sim.csv`)
- `scripts/` —interactive analysis notebook
- `figures/` — plots used in the report
- `report/` — final PDF report


## How to run (quick)
1.download the dataset
2.Colab/Jupiter Run the python scripts 
