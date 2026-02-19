# Revenue-Weughted-Churn-Prediction–End-to-End ML-Analysis
Built a revenue-weighted churn prediction model for telecom customers that prioritizes retention based on financial risk rather than churn probability alone. Leveraged behavioral usage data, feature engineering, and ML classification to estimate expected revenue loss and produce actionable, high-ROI retention targeting.

 1. BUSINESS PROBLEM

Customer attrition directly impacts recurring revenue.
This project builds a machine learning model to predict which customers are likely to churn, enabling proactive retention strategies.

 2. OBJECTIVE

Develop a classification model that identifies high-risk customers using behavioral and billing data.

 3. DATASET

* Source: Telecom customer dataset
* Records: ~7,000 customers
* Features include:

  * Tenure
  * Monthly Charges
  * Contract Type
  * Usage Patterns

(Note: Dataset not uploaded due to size. Download link provided below.)

 4. ML PIPELINE

The project follows a production-style workflow:

1. Data Cleaning & Validation
2. Exploratory Data Analysis (EDA)
3. Feature Engineering, Pipeline
4. Model Training (Logistic Regression)
5. Model Evaluation (ROC-AUC, Precision-Recall, Accuracy)

 5. TECK STACK

* Python
* Pandas / NumPy
* Scikit-learn
* FastAPI (Model Serving)
* Power BI (Visualization)
* Docker (Containerization)

 6. MODEL PERFORMANCE

| Metric   | Score |
| -------- | ----- |
| ROC-AUC  | 0.83  |
| Accuracy | 0.71  |
| Recall   | 0.95  |

The model prioritizes recall to minimize false negatives (missed churners).

