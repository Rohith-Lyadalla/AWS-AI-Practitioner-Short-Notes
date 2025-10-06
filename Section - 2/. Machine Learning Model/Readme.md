# 4. Machine Learning Model
# 4.1 What Is a Machine Learning Model?
- In traditional programming, **we provide input and logic (equation/code) to produce an output.**
- **Example: Provide x and use  y=x2→ get y**
- **In machine learning, we provide input and output data, and the system learns the logic/equation on its own.**
- **The learned logic (or pattern) is stored as a model, which can then make predictions on new data.**
- **Training phase:** Input + Output → Model learns logic.
- **Inference phase:** New Input → Model applies learned logic → Predicted Output.
# 4.2 Inferencing
- **Inferencing is when a trained model applies what it learned to new, unseen data.**
- It’s the stage where **the model produces real-world results — such as predicting trends, recognizing images, or detecting fraud.**
# 4.2.1 Training vs Inference:
- **Training:** Model learns by adjusting itself on known data.
- **Inference:** Model uses learned patterns to make predictions on new data.
- Inference powers applications such as recommendation systems, medical diagnostics, and spam filters.
# 4.3 Types of Inferencing
# 4.3.1 Real-Time Inferencing
- The model predicts instantly as new data arrives.
- Needed in applications requiring fast or immediate responses.

**Examples:**
- Fraud detection during live transactions
- Chatbots
- Self-driving cars
- Real-time product recommendations

**Characteristics:**
- Low latency, needs high compute resources
- Usually served through live APIs
- Uses the latest, freshest data
- AWS Example: Amazon SageMaker Endpoints for low-latency predictions.
# 4.3.2 Batch Inferencing
- The model processes **a large volume of data together in one go.**
- Ideal **when immediate output isn’t required; focuses on efficiency.**
- **Examples:**
- Daily product recommendations
- Monthly churn analysis
- Large-scale image/video analysis

**Characteristics:**
- Higher latency (minutes or hours)
- High throughput, cost-efficient for bulk processing
- Scheduled or periodic jobs
- **AWS Example:** Amazon SageMaker Batch Transform for large datasets; SageMaker Serverless Inference for auto-scaling workloads.

# Points to be remembered:
- Traditional Programming: Input + Logic → Output
- Machine Learning: Input + Output → Model (learned Logic)
- Inference: Using trained models to predict new data.
- Real-Time Inference: Immediate responses (chatbots, fraud detection).
- Batch Inference: Bulk data processing at scheduled intervals.
- AWS Tools: SageMaker Endpoints (real-time) and Batch Transform (batch).

