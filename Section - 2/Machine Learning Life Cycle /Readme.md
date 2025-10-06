# 8. Machine Learning Life Cycle 
# 8.1 What is the Machine Learning Life Cycle?
- The ML life cycle covers **every step from business goal setting to model deployment and continuous refinement.**
- It is **iterative—models and processes are continually updated as business needs and data change.**
- **Success depends on teamwork:** product managers, data scientists, engineers, and other stakeholders all contribute.
# 8.2 Main Phases:
1. Business goal identification
2. ML problem framing
3. Data processing (collection, preprocessing, feature engineering)
4. Model development (training, tuning, evaluation)
5. Deployment
6. Monitoring
7. Retraining
# 8.2.1 Define Business Goals
- Start with **clear objectives** (e.g., reduce customer churn).
- Stakeholders set KPIs—know **what success means before building a model.**
- Clear goals **ensure ML efforts are aligned with actual business value.**
# 8.2.2 ML Problem Framing
- Translate business goals **into machine learning problems** (e.g., "churn reduction" becomes a classification task).
- Select the **best ML technique: classification, regression, clustering, etc.**
- Define **measurable metrics tied to business outcomes.**
- Check **if ML is appropriate—assess if enough data is available and the problem matches ML strengths.**
# 8.2.3 Data Processing
- **Prepares raw data for modeling through three core steps:**

- **Data collection:** Gather all relevant sources; check for completeness and quality; use robust data pipelines.
- **Data preprocessing:** Clean data (remove duplicates, handle missing values), standardize formats, encode categories, and normalize.
- **Feature engineering:** Create or select useful variables/features. Domain knowledge is key here.
# 8.2.3.1 Feature Engineering Techniques
- **Feature Extraction:** Use techniques like PCA to create new features that capture key information in a compact way.
- **Feature Selection:** Choose only the most relevant variables; methods include filters, wrappers, and embedded strategies.
- **Feature Transformation:** Adjust feature scales (normalize, standardize), encode categories, or apply math transformations for better model learning.
# 8.2.4 Exploratory Data Analysis (EDA)
- EDA means examining and visualizing data to understand its structure, spot trends, find outliers, and detect problems before modeling.
# Why EDA?
- Understand key patterns and relationships.
- Find errors, missing values, or outliers.
- Guide what features to use and how to clean data.
- **Typical steps include:**

- Data summarization (statistics, plots)
- Cleaning and error checking
- Exploring relationships (correlations, distributions)
- Hypothesis testing
# 8.2.5  Model Development

- **Train, tune, and evaluate models iteratively.**
- Experiment with different features and algorithm settings (hyperparameters).
- The process is cyclical—results inform more feature engineering and data cleaning.
# 8.2.6 Retraining
- If the model underperforms, revisit feature engineering, retrain, and fine-tune.
- Retraining may be required as data patterns change over time.
# 8.2.7 Deployment
- Deploy the model for real-world predictions: choose the right setup (real-time, batch, serverless, etc.).
- Model readiness is checked by its alignment with business KPIs.
# 8.2.8 Monitoring and Iterations

- **Monitor model performance after deployment to catch drops or failures early.**

- **ML projects are never static—models must be regularly updated as data and business needs evolve.**

- **Continuous improvement is essential for long-term value and accuracy.**

- **Collaboration between all roles remains vital through the life cycle.**

# Points to be remembered:
- The ML life cycle is an end-to-end, repeatable process—from business goals to maintenance.
- Main steps: goal setting, problem framing, data processing, EDA, model development, deployment, monitoring, and retraining.
- Each phase is connected and often revisited as data or business needs change.
- Effective ML projects rely on teamwork and continuous improvement to remain valuable and accurate.

