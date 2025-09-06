# Bank-Marketing-Data-Analysis
This project analyzes the Bank Marketing dataset, which contains demographic, social and contact information from previous marketing campaigns. The goal is to understand customer behavior and predict whether a client will subscribe to a term deposit.

# Objective
To explore and analyze customer data from bank marketing campaigns.
To build predictive models that classify whether a client will subscribe to a term deposit.
To identify the most influential features affecting customer decisions.
To assist banks in optimizing their marketing strategies and resources.

# Methodology
- **1. Data Loading:** Importing the dataset using pandas.
- **2. Exploratory Data Analysis (EDA):** Checking structure, summary statistics, missing values and visualizing distributions.
- **3.Preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features.
- **4.Train-Test Split:** Dividing the dataset into training and testing sets.
- **5.Model Building:** Logistic Regression, Decision Tree, Random Forest.
- **6.Evaluation:** Confusion Matrix, Classification Report, ROC-AUC curves.
- **7.Feature Importance:** Identifying key features influencing subscription.
- **8.Model Saving:** Exporting trained pipelines for future predictions.

# Models
- **1.Logistic Regression:** Provided interpretability but limited predictive power.
- **2.Decision Tree:** Captured non-linear relationships but prone to overfitting.
- **3. Random Forest:** Best-performing model with robust handling of categorical and numerical features.
- **4. (Optional extensions:** XGBoost, Gradient Boosting (GB), and Neural Networks for deeper analysis.)


# Conclusion
This analysis of the bank marketing dataset highlights important insights into customer behavior and the effectiveness of marketing campaigns. 
## Data insights:
Customer demographics, contact history, and campaign-related attributes provide meaningful signals for predicting ter m deposit subscriptions. 
## Class imbalance: 
A large proportion of customers do not subscribe, which requires special handling (e.g., class weighting, oversampling) to avoid biased models. 
## Modeling results:
Logistic regression offered interpretability, while decision trees captured non-linear patterns. The Random Forest model achieved the best balance of accuracy, recall,
and robustness, making it suitable for deployment. 
## Key drivers: 
Features such as duration of contact, previous campaign outcome, and customer age were most influential in predicting subscriptions.

**Recommendations:**
Banks should focus their marketing efforts on high-probability customers, leverage predictive models for targeted outreach, and continuously retrain models with fresh data to adapt to changing behavior.
