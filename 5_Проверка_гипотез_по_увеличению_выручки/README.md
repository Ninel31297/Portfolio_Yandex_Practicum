# Project: Hypothesis Testing for Revenue Growth in an Online Store — A/B Test Evaluation

## Description:
Source: e-commerce dataset with user purchases across different experiment groups

Objective: prioritize hypotheses and evaluate the results of A/B testing

Prioritized hypotheses using ICE and RICE frameworks. Then analyzed A/B test results by building cumulative revenue, average order value, and conversion rate graphs for each group. Calculated the statistical significance of differences in conversion rates and average order values using both raw and cleaned data. Based on the analysis, concluded that continuing the test is not reasonable.

## Tech Stack:
A/B testing, Matplotlib, Pandas, Python, SciPy, statistical hypothesis testing

## Conclusions:
Hypothesis prioritization:
according to ICE, hypotheses 8, 0, and 7 should be tested first; according to RICE — hypotheses 7, 2, 0, and 6.

A/B test results:
- both raw and cleaned data show a statistically significant difference in the average number of orders between groups; group B has approximately 14% more orders on average;
- in both raw and cleaned data, the p-value for average order value is 0.8, which does not allow rejection of the null hypothesis of no difference between groups; after data cleaning, the observed difference decreased from 25% to 2%;
- the relative change in average order value for group B shows growth but includes a significant drop mid-test, making conclusions unreliable based on this metric alone;
- the relative change in the number of orders per user is stable, without major fluctuations, and shows a consistent minimum increase of 10% in group B compared to group A.

Based on the analysis, it is reasonable to stop the test and declare group B as the winner.

## Status:
Project completed
