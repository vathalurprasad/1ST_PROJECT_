# 1ST_PROJECT_
# HR Analytics – Predicting Employee Attrition

# Project Overview

This project focuses on analyzing HR data to understand the reasons behind employee attrition and build a predictive model to identify potential attrition cases. It combines data exploration, machine learning, and dashboard visualization to provide actionable insights for HR decision-making.

---

# Objectives

- Analyze patterns of attrition based on features like department, salary, promotions, etc.
- Build a classification model to predict employee attrition.
- Visualize key factors influencing attrition using Power BI.
- Suggest data-driven strategies to reduce employee turnover.

---

#  Tools & Technologies Used

- Python (Pandas, Seaborn, Scikit-learn, SHAP)
- Jupyter Notebook
- Power BI
- Dataset: `WA_Fn-UseC_-HR-Employee-Attrition.csv`

---

# Steps Involved

1. **Data Preprocessing**
   - Cleaning and transforming raw HR data
   - Handling null values, encoding categorical data

2. **Exploratory Data Analysis (EDA)**
   - Department-wise attrition
   - Promotion and salary band analysis
   - Visualization using seaborn

3. **Machine Learning Model**
   - Logistic Regression / Decision Tree Classification
   - Model evaluation using accuracy score & confusion matrix
   - SHAP value analysis for model interpretability

4. **Power BI Dashboard**
   - Visual storytelling of attrition trends
   - Filters: Age group, Department, Job Role
   - Insight cards for key factors like overtime, satisfaction, and years at company

---

# Model Performance

- **Accuracy**: 0.8673469387755102
- **Confusion Matrix**: Displayed in the Jupyter notebook
- **Interpretation**: Key drivers of attrition identified using SHAP

---

## Suggestions to Prevent Attrition

- Review workloads for employees doing overtime
- Increase recognition & promotion opportunities in departments with high attrition
- Improve job satisfaction through feedback loops

---

## Project Structure



# Telecom Customer Churn Prediction

## Project Overview
This project aims to predict customer churn for a telecom company using machine learning techniques. Customer churn is a critical business metric that indicates the percentage of customers who stop using a service during a given period. Predicting churn helps companies proactively retain customers, reduce revenue loss, and improve customer satisfaction.

## Dataset
The dataset contains customer information such as demographics, account details, contract type, payment method, and usage metrics. Key columns include:

- Customer Status (target variable): Indicates if a customer is Active, Churned, Exited, or Inactive.
- Total Charges
- Tenure in Months
- Contract type
- Payment Method
- Other customer attributes

## Data Preprocessing
- Mapped the target column (`Customer Status`) to binary values: Active (0) and Churned/Exited/Inactive (1).
- Handled missing values in `Total Charges` by filling them with the median.
- Converted categorical variables using label encoding for binary categories and one-hot encoding for others.
- Dropped unnecessary columns like `Customer ID`.
- Split data into training and test sets with stratification to maintain class distribution.

## Model
- Used a Random Forest Classifier to predict churn.
- Trained on 80% of data and tested on 20%.
- Evaluated using accuracy, classification report (precision, recall, f1-score), and confusion matrix.

## Results
- Achieved an accuracy of **1.** (replace with your actual accuracy).
- Visualized confusion matrix to understand classification performance.
- Segmented customers into 'At Risk', 'Loyal', and 'Dormant' based on predicted churn and tenure.

## Improvements & Future Work
- Address class imbalance with techniques like SMOTE or class weights.
- Experiment with advanced models such as XGBoost or LightGBM.
- Implement hyperparameter tuning for better performance.
- Add model explainability using SHAP or ELI5.
- Develop a real-time prediction API for business deployment.
- Integrate SQL queries for feature engineering and data extraction automation.

## How to Run
1. Install required Python libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.
2. Load the dataset (`telecom_customer_churn.csv`) in the same directory.
3. Run the Python script or Jupyter notebook to train and evaluate the model.
4. Visualizations and customer segments will be displayed as output.

## Contact
For questions or collaboration, contact: **[v.prasad]** | Email: **vathaluruprasad@gmail.com**



