# 5. Machine Learning Models & Performance Evaluation
# 5.1 Model Evaluation Datasets
# 1. Training Set
- **60–80%** of total data.
- **Used to train the model — learn patterns from features and labels.**
- **Quality & variety influence bias and learning quality.**
# 2. Validation Set
- **10–20% of total data.**
- **Used for tuning hyperparameters** (learning rate, depth, etc.) and checking generalization.
- Helps **detect and prevent overfitting.**
# 2. Test Set
- **Final evaluation only — unseen data.**
- **Measures real-world performance — unbiased accuracy.**
- **Kept aside until the final stage.**
- **Simplified: Train → Tune → Test.**
# 5.2 Model Fit
- **Fit:** How well the model captures the data's relationships.
- **Overfitting (High Variance, Low Bias)**
- Great **on training data, poor on test data.**
- **Memorizes instead of generalizing.**
- **Underfitting (High Bias, Low Variance)**
- **Poor on training and test data.**
- Model too simple, features not expressive enough.
- **Balanced: Low bias & low variance — accurate and consistent.**
# 5.3 Bias
- **Difference between predicted value and actual value.**
- **High Bias:** Predictions far from actual values — underfitting.
- **Reduce Bias:** Use more complex models, add more expressive features.
# 5.4 Variance
- **Sensitivity of model to changes in training data.**
- **High Variance:** Predictions vary a lot — overfitting.
- **Reduce Variance:** Focus on important features, use simpler models, perform repeated data splits.
# 5.5 Bias–Variance Relationship
- Both contribute **to prediction errors on unseen data.**
- **Ideal Model: Low bias + low variance.**
- **Analogy: Bullseye — bias shifts aim from the center; variance spreads results.**
# Points to be remembered:
- Training Set: Learn patterns.
- Validation Set: Tune & validate.
- Test Set: Final unbiased performance check.
- Overfitting → High variance, low bias.
- Underfitting → High bias, low variance.
- Goal: Low bias, low variance — accurate and consistent predictions.
