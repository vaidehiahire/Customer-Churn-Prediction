# Customer Churn Prediction using Machine Learning
Customer churn is a major challenge for telecom companies, as losing customers directly impacts revenue.
This project focuses on building a **machine learning model** to predict whether a customer is likely to churn based on their service usage, account details, and billing information.

## Problem Statement
The goal is to identify customers who are at risk of leaving the service so that businesses can take **early retention actions**.

## Dataset
* **Telco Customer Churn Dataset**
* Contains **7,000+ customer records**
* Includes demographic details, service subscriptions, tenure, and billing information
* **Target Variable:** `Churn` (Yes / No)

## Approach
1. Loaded and explored the dataset to understand patterns and class imbalance
2. Cleaned data by handling missing values and correcting data types
3. Encoded categorical features for machine learning compatibility
4. Split data into training and testing sets
5. Trained a **Logistic Regression** model for binary classification
6. Used **probability-based threshold tuning (0.35)** to improve churn recall
7. Evaluated performance using:

   * Confusion Matrix
   * ROC Curve and AUC score
   * Feature importance from model coefficients

## Key Visualizations
* Customer churn distribution (with percentage labels)
* Confusion matrix at optimized threshold
* ROC curve to assess overall classification performance
* Feature importance plot to interpret churn drivers

## Key Insights
* The dataset is **imbalanced**, with fewer churned customers
* Lowering the threshold improved detection of churn-prone customers
* Contract type, tenure, and monthly charges significantly influence churn

## Tools & Technologies
* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Conclusion
This project demonstrates how machine learning can be applied to **predict customer churn** and support **data-driven retention strategies**.
By focusing on recall and business impact rather than default accuracy, the model aligns better with real-world decision-making.

### ⭐ If you found this project useful, feel free to explore the notebook or suggest improvements!
