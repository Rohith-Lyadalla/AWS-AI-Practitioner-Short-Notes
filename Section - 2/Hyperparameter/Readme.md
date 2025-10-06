# 7. Hyperparameter
# 7.1 Hyperparameters in Machine Learning
- **Definition:** Configuration settings fixed before training that control the learning process.
- **Difference from parameters:** Parameters are learned from data; hyperparameters are set by the practitioner.
- **Impact:** Affect model complexity, performance, and convergence rate.
# 7.2 Key Characteristics
- Not learned from data.
- Require tuning to optimize model accuracy.
- **Examples:** learning rate, batch size, epochs, regularization strength, model architecture.
# 7.3 Important Hyperparameters
- **Learning rate:** Speed of weight updates.
- **Batch size:** Number of samples per weight update.
- **Number of epochs:** Times dataset passes through the model.
- **Regularization strength:** Penalizes complexity to prevent overfitting.
- **Model architecture:** Layer counts, neurons, etc.
# 7.4 Hyperparameter Tuning
- **Purpose:** Find the best hyperparameter values to maximize performance.
- **Approach:** Experiment, evaluate on validation data, select best combo.
- **Benefits:** Increase accuracy, reduce overfitting, enhance generalization.
# 7.4.1 Common Strategies
- **Grid search:** Try all combos in a fixed grid.
- **Random search:** Randomly sample combos.
- **Bayesian optimization:** Use probabilistic models to explore space.
# 7.5 Types of Hyperparameter Tuning
- **Learning rate:** High = fast but risk overshooting; Low = precise but slower.
- **Batch size: Small = stable, slow; Large = faster, may be less stable.**
- **Number of epochs: Few = underfit; Many = overfit.**
- **Regularization: High = simpler model, less overfit.**
# 7.6 Preventing Overfitting
- Increase training data size.
- Early stopping training.
- Data augmentation.
- Adjust hyperparameters when needed.
# 7.7 Hyperparameter Tuning Techniques

**1. Grid Search**

- Brute force; tries all combinations.
- **Pros:** exhaustive, simple.
- **Cons:** slow, costly.

**2. Random Search**

- Randomly selects combinations.
- **Pros:** faster, effective in high dimensions.
- **Cons:** may miss optimal solution.

**3. SageMaker Automatic Model Tuning (AMT)** 

- Automates search using Bayesian optimization.
- **Pros:** scalable, AWS-integrated, parallel jobs.
- **Cons:** AWS-specific.

# Points to be remembered:
- Hyperparameters set before training control learning.
- Tuning finds optimal values to boost performance.
- Key hyperparameters: learning rate, batch size, epochs, regularization.
- Overfitting prevention: more data, early stopping, augmentation.
- Main tuning methods: grid search, random search, SageMaker AMT.

