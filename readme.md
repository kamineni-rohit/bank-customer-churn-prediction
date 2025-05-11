# Bank Customer Churn Prediction

This project focuses on identifying customers likely to churn from a bank's services using supervised machine learning models. By analyzing customer behavior and demographics, the goal was to build a predictive pipeline that empowers proactive retention strategies.

## 🧠 Objective
To accurately classify whether a customer will churn based on behavioral and account-related features, enabling the bank to take preventive actions.

## 🧪 Methodology

### Data Cleaning
- Handled missing values by imputing or removing where appropriate.
- Removed validation rows and duplicates to ensure data quality.
- Identified and handled outliers that could distort model learning.

### Exploratory Data Analysis
- Found that only ~16% of the dataset represents churned customers, highlighting a significant class imbalance.
- Visualized feature relationships with churn to identify key predictive attributes.

### Model Development
Trained and evaluated multiple models to identify the best-performing churn classifier:
- **Logistic Regression**
- **Naïve Bayes**
- **Decision Tree**
- **Discriminant Analysis**
- **K-Nearest Neighbors (KNN)**
- **Neural Network**

Evaluation metrics included accuracy, recall, and confusion matrices to assess effectiveness under class imbalance.

## 📊 Results
- Neural Networks showed superior performance in detecting churn patterns.
- Class imbalance was addressed through model tuning and evaluation adjustments.
- The final model offers a decision-support system to identify high-risk churn customers early.

## 🛠️ Tech Stack
- Python (Scikit-learn, Pandas, NumPy, Matplotlib)
- Jupyter Notebook
- Machine Learning (Classification)

## 👥 Team
- Rohit Kamineni  
- Supraja Bala  
- Ryan Nelson  

## 📌 Notes
- Business insights derived from model interpretation can guide targeted marketing and retention strategies.
- Future work may include feature importance ranking, SMOTE for class imbalance, and cost-sensitive modeling.

