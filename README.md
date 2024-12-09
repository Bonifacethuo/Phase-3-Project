
**SyriaTel Customer Churn Prediction**

**Overview**
This project aims to predict customer churn for SyriaTel, a telecommunications company in Syria. By identifying customers likely to churn, the goal is to help SyriaTel implement targeted retention strategies, reduce churn rates, and improve profitability.

**Problem Statement**
Customer churn is a major challenge for telecommunications companies. By predicting which customers are most likely to churn, SyriaTel can take proactive steps to retain high-risk customers, ensuring better customer satisfaction and reducing customer acquisition costs.

**Data Source**
The dataset used for this project is from Kaggle's Churn in Telecom's Dataset. It includes various customer features such as account details, usage patterns, and subscription plans.
**Kaggle Dataset: Churn in Telecom's Dataset**

**Approach**
1. Data Preprocessing
Checked for missing, null, and duplicate values.
Dropped irrelevant features (e.g., "phone number").
Categorized features into numerical and categorical for easier analysis.
2. Modeling
Built several models to predict churn:
Logistic Regression (with ElasticNet regularization)
Decision Tree Classifier (achieved 90.1% accuracy)
Used cross-validation, confusion matrix, and ROC curve for model evaluation.
3. Metrics
Accuracy: 90.1% (for Decision Tree Classifier)
Precision: 80% or higher to reduce false positives.
Log-Loss: 0.335 for training data, 0.343 for validation data.

**Conclusion**
The Decision Tree Classifier showed excellent performance in predicting customer churn. Further enhancements could include using ensemble methods like Random Forests or Gradient Boosting to improve model robustness.

**Recommendations**
Implement advanced retention strategies based on the churn model's predictions.
Collect additional customer feedback and network complaints to improve model accuracy.

**Next Steps**
Deploy the churn prediction model for real-time usage.
Continuously update the dataset and model for improved accuracy.
