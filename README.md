# Bank Customer Churn Analysis

Behavioral analysis of 10,000 bank customers to identify signals that predict churn — with a focus on finding patterns before they become obvious.

## Questions I was asking

- What's the actual churn rate, and how does it break down by geography?
- Which customer attributes correlate most strongly with churn — age, balance, activity level?
- Are there customer profiles that look fine on the surface but are at high risk?

## Key findings

- Overall churn rate: ~20% — higher than typical industry benchmarks
- Age is a stronger predictor than balance: customers 40–55 churn at significantly higher rates
- Germany shows 2x the churn rate of France and Spain despite similar product distribution
- Inactive members (IsActiveMember=0) churn at nearly double the rate of active members

## Stack

Python — pandas, numpy, matplotlib, seaborn

## Files

```
analysis.ipynb                     # Full churn analysis
Bank_Churn.csv                     # 10,000 customer records
Bank_Churn_Data_Dictionary.csv     # Column definitions
```
