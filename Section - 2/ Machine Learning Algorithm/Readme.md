# 3. Machine Learning Algorithm
# 3.1 What is a Machine Learning Algorithm?
- **Step-by-step instructions for a computer to learn from data.**

- **Finds patterns and makes predictions without explicit rules.**
  
- **Example:** Teach cat recognition by feeding labeled "cat" and "not cat" images.

- **Key idea:** Algorithms use math/statistics to spot patterns and generalize.
# 3.1.2 Machine Learning Process Types

- **Supervised Learning:** Learn from labeled data; output known.

- **Unsupervised Learning:** Learn from unlabeled data; find hidden patterns.
  
- **Reinforcement Learning:** Learn via trial & error with rewards/penalties.
  
- **Semi-supervised Learning:** Small labeled set + large unlabeled set.
  
- **Self-supervised Learning:** Model generates labels from data itself.
# 3.2 Supervised Learning
- Trains on **input-output pairs.**
- Checks predictions **against labels and improves.**

**Two problem types:**

- **Classification:** Predict categories (spam/not spam).
  
- **Regression:** Predict continuous values (house prices).

# 3.2.1 Classification Types

- **Binary:** Two classes.
  
- **Multiclass:** Three or more classes, one label per input.

- **Multi-label:** Multiple labels per input.

# 3.2.2 Classification Use Cases
- Spam detection
- Fraud detection
- Image classification
- Customer segmentation
- Disease diagnosis
- Quality control
# 3.2.3 Regression Use Cases
- House price prediction
- Weather forecasting
- Sales prediction
- Sports performance analysis
- Medical cost estimation
- Fuel efficiency prediction
# 3.3 Unsupervised Learning
- Analyzes unlabeled data to find patterns.
# 3.3.1 Subtypes

- **Clustering:** Group data by similarity.
  
- **Use cases:** Customer segmentation, targeted marketing.
  
- **Dimensionality Reduction:** Reduce features while keeping key info.
  
- **Use cases:** Data visualization, compression.
  
- **Association Rule Learning:** Discover item relationships (e.g., bread → butter → jam).
  
- **Anomaly Detection:** Find unusual data points (e.g., fraudulent transactions).
# 3.4 Reinforcement Learning (RL)

- **The agent interacts with the environment, takes actions, gets rewards.**
  
- Learn optimal policy via exploration and exploitation.
  
- **Use cases:** Robotics, autonomous vehicles, gaming, resource optimization.
  
- **RLHF:** Human feedback shapes reward function for better alignment.
  
- **Steps: Data collection → supervised fine-tuning → reward model → optimization.**
# 3.5 Semi-supervised Learning
- Mixes **small labeled data with large unlabeled data.**
- Uses **pseudo-labeling:** Model guesses labels, retrains with new set.
- Useful **when labeling is costly.**
# 3.6 Self-supervised Learning
- The **model creates its own training labels from data.**
  
- **Example: Predict missing words from context.**
  
- Effective for scarce labeled data.
# Points to be remembered:
- Supervised learning: Needs labeled data, predicts categories or values.
- Unsupervised learning: Finds hidden patterns without labels.
- Reinforcement learning: Learns by trial & error with feedback.
- Semi-supervised: Combines small labeled set + large unlabeled set.
- Self-supervised: Generates labels from data structure.
- Applications span fraud detection, autonomous driving, forecasting, and recommendation systems.

