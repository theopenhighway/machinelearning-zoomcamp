# Churn Predictor (Logistic Regression)

## Feature Importance
### Difference
Compare the difference between the average global churn rate  with the average churn rate per group.
- If > 0: less likely to churn
- If < 0: more likely to churn

### Risk Ratio
Risk = group / global
- If > 1: more likely to churn
- If < 1: less likely to churn

### Mutual Information
- Concept from information theory
- Tells about one variable if the value of another is known

### Correlation
- r > 1: x increases, y increases
- r < 1: x increases, y decreases

- 0 < r < 0.2 or -0.2 < r < 0: low (rarely)
- 0.2 < r < 0.5 or -0.5 < r < -0.2: moderate (sometimes)
- 0.6 < r < 1 or -1 < r < -0.6: strong (often/always)

e.g. tenure vs churn
+ve: more tenure, higher churn
-ve: more tenure, less churn
zero: no effect on churn