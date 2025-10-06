# 2. Training Data
# 2.1 What Is Training Data?
- Training data **is the information that teaches a machine learning model how to make predictions or recognize patterns.**
- It includes **inputs and their correct outputs (labels) so the model can learn by example.**
- **Example:** To detect cats, training data includes images labeled as “cat” or “not cat.”
 - The phrase **"garbage in, garbage out"** highlights that **poor-quality data leads to poor model performance.**

**The process of building a model starts with:**

- Data collection and preparation
- Selecting an algorithm
- Training and testing the model
# 2.2 Why Do We Need Training Data?
- A model must **“learn” before it can make decisions or predictions.**
- Training data is the learning material — **it shows the model many labeled examples (e.g., spam vs. not spam, cat vs. dog).**
- The model studies these examples **to find patterns or distinguishing features.**

- **After learning, it’s tested with new, unseen data to check understanding.**
- Without quality training data, model predictions are unreliable.
# 2.3 Data Types in Machine Learning
# 2.3.1 Labeled Data
- Includes **input features + target outputs.**
- Used in **supervised learning.**
- **Example:** Image data labeled with “cat,” “dog,” or “car.”
- Labels are provided by humans or through reliable annotation processes.
# 2.3.2  Unlabeled Data
- Contains only input features, no target outputs.
- Used in unsupervised learning to find hidden patterns or groupings.
**Example:** A large dataset of untagged images.

- Common when labeling is too costly or time-intensive.
# 2.4 Structured vs. Unstructured Data
# 2.4.1 Structured Data
- Organized in **rows and columns (e.g., spreadsheets, databases).**
- Suitable for **traditional ML algorithms that rely on clear features.**
**Types:**

**1. Tabular data:** Rows = examples, Columns = features.

**2. Time-series data:** Sequential values measured over time (e.g., stock prices, sensor readings).
# 2.4.2  Unstructured Data
- **No predefined structure** — includes text, images, audio, and video.
- Requires special preprocessing **to convert into usable features.**

**Types:**

**1. Text data:** Articles, documents, social media posts.

**2. Image data:** Photos, video frames.

- Used in more advanced ML systems like computer vision and NLP.
# Points to be remembered:
- Training data is what helps ML models learn by example.
- Good quality data = better model performance.
- Labeled data → Supervised learning; Unlabeled data → Unsupervised learning.
- Structured data is organized and numeric; Unstructured data is complex and varied.
- Every effective ML model depends on well-prepared, reliable training data.

