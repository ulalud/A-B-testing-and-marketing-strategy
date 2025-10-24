# A-B-testing-and-marketing-strategy

## Overview

This analysis evaluates whether a modification in a marketing campaign (test group) led to a higher number of clients and improved engagement metrics compared to the original campaign (control group).

The dataset contains daily observations of marketing performance metrics for each group over a 30-day period.

## **Statistical Methodology**

### **Assumptions**
- Population variances are unknown.  
- Sample sizes are relatively small (*n* ≈ 29 per group).  
- Therefore, a **two-sample t-test** was used.  
- Confidence level: **95%**, corresponding to a **significance level (α = 0.05)**.  
- A **one-sided test** was conducted, since the goal is to test whether the test group performs better.

### **Hypotheses**


H_0: mu_control >= mu_test


H_1: mu_control < mu_test


This specifies a **one-sided alternative hypothesis**, testing whether the mean number of purchases (or another performance metric) is greater in the **test group**.


## Interpretation

Both Click-Through Rate and Conversion Rate declined in the test condition compared to control.

The effect was large for CTR (d = −1.05), suggesting a major reduction in engagement.

For Conversion Rate, the effect was moderate (d = −0.41), indicating a smaller but noticeable drop.

Purchases per unit spend showed no significant improvement, suggesting that the campaign modification did not generate additional value per dollar spent.

Overall, the results provide no statistical evidence that the new campaign version increased user engagement or conversions — and in fact, suggest a potential decrease in performance.
