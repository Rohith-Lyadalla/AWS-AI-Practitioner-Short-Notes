# 6. Model Evaluation Metrics and Performance Optimisation
# 6.1 What Are Model Evaluation Metrics?
- Tools to measure **how well a ML model performs.**
- Act like **a report card for predictions.**
- Identify **weaknesses (bias, overfitting) & guide improvements.**
- Help **choose the best model for deployment.**
# 6.2 Why Are They Needed?
- Choose the **most suitable model.**
- Confirm **readiness for real-world use.**
- Guide **targeted performance improvements.**
# 6.3 Types of Metrics
# 6.3.1  Classification Metrics
 - **Confusion Matrix:** True Positives (TP), True Negatives (TN), False Positives (FP), False Negatives (FN).
 - **Accuracy:**  TP+TN/ TP+TN+FP+FN  – overall correctness.
- **Precision:** TP / TP+FP – reliability of positive predictions.
- **Recall/Sensitivity:**  TP/ TP+FN  – ability to detect positives.
- **F1 Score:** balances precision & recall.
- **AUC-ROC:** evaluates class separability at various thresholds.
# 6.3.2 Regression Metrics
- **Mean Squared Error (MSE):** Average squared difference between predicted & actual values.
- **Root Mean Squared Error (RMSE):** Square root of MSE; interpretable in target units.
- **Mean Absolute Error (MAE):** Average absolute difference; robust to outliers.
- **Symmetric Mean Absolute Error (SMAE):** Scales error relative to value sizes.
- **R² (Coefficient of Determination):** Proportion of variance explained.
- **Adjusted R²:** Accounts for number of predictors.
# 6.4 Classification Example Workflow
- Send held-out test data to the model.
- Compare predictions to actual target values.
- Use metrics (accuracy, precision, recall, F1, AUC-ROC) to summarise performance.
# 6.5 Error types:
- **TP:** Correctly classified positive.
- **TN:** Correctly classified negative.
- **FP:** Incorrectly predicted positive.
- **FN:** Missed actual positive.
# 6.6 Business Metrics in ML
- **Definition:** Quantifiable measures tracking ML impact on business outcomes.
- **Examples:** Revenue increase, click-through rate, retention, cost reduction.
- Distinct from model metrics – focus on real-world value.
  
**Purpose:**

- Align ML with core business objectives.
- Evaluate model impact via A/B tests.
- Ensure technical performance translates into business gains.
# Points to be remembered:
- Model metrics evaluate technical performance (accuracy, precision, recall, etc.).
- Classification metrics suit discrete output tasks; regression metrics suit continuous value prediction.
- Confusion matrices diagnose specific error types.
- AUC-ROC helps find optimal thresholds.
- Business metrics ensure ML work delivers real-world benefits.
- Combining model & business metrics ensures both accuracy and value.

