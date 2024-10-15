# Bank Churn Analysis

This project analyzes the **Bank Churners** dataset to understand patterns related to customer churn, aiming to identify factors influencing whether a customer leaves the bank. By leveraging data analysis and machine learning techniques, we seek to provide actionable insights for reducing customer attrition.

## Table of Contents
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Analysis](#analysis)
- [How to Run the Notebook](#how-to-run-the-notebook)
- [Requirements](#requirements)
- [Results and Insights](#results-and-insights)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used for this analysis is the **Bank Churners dataset**. It includes a wide range of customer data, providing a comprehensive view of customer behavior and characteristics. The dataset contains the following columns:

1. CLIENTNUM: Unique identifier for the customer
2. Attrition_Flag: Customer attrition status (target variable)
3. Customer_Age: Age of the customer
4. Gender: Gender of the customer
5. Dependent_count: Number of dependents
6. Education_Level: Education level of the customer
7. Marital_Status: Marital status of the customer
8. Income_Category: Income category of the customer
9. Card_Category: Type of card held by the customer
10. Months_on_book: Period of relationship with bank
11. Total_Relationship_Count: Total number of products held by the customer
12. Months_Inactive_12_mon: Number of months inactive in the last 12 months
13. Contacts_Count_12_mon: Number of contacts in the last 12 months
14. Credit_Limit: Credit limit on the credit card
15. Total_Revolving_Bal: Total revolving balance on the credit card
16. Avg_Open_To_Buy: Average open to buy credit line (last 12 months)
17. Total_Amt_Chng_Q4_Q1: Change in transaction amount (Q4 over Q1)
18. Total_Trans_Amt: Total transaction amount (last 12 months)
19. Total_Trans_Ct: Total transaction count (last 12 months)
20. Total_Ct_Chng_Q4_Q1: Change in transaction count (Q4 over Q1)
21. Avg_Utilization_Ratio: Average card utilization ratio
22. Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1: Naive Bayes classifier score 1
23. Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_2: Naive Bayes classifier score 2

This rich dataset allows for in-depth analysis of various factors that may contribute to customer churn, including demographic information, card usage patterns, transaction history, and customer engagement metrics.

# Analysis
The notebook bank_churners_analysis.ipynb performs the following analysis steps:

# Data Cleaning and Preprocessing

Handling missing values
Encoding categorical variables
Feature scaling and normalization


# Exploratory Data Analysis (EDA)

Univariate analysis of key features
Bivariate analysis to identify relationships between variables
Correlation analysis
Visualization of key insights


# Churn Prediction Modeling

Feature selection
Model selection (e.g., Logistic Regression, Random Forest, XGBoost)
Model training and evaluation
Hyperparameter tuning


# Insights and Visualizations

Key factors influencing churn
Customer segmentation analysis
Actionable recommendations for reducing churn



How to Run the Notebook

Clone the repository:
bashCopygit clone https://github.com/Fathima1123/bank_churn.git

Navigate to the project directory:
bashCopycd bank_churn

Install the required dependencies:
bashCopypip install -r requirements.txt

Launch Jupyter Notebook:
bashCopyjupyter notebook

Open the notebooks/bank_churners_analysis.ipynb file and run the cells sequentially.

Requirements
The main libraries used in this project are:

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost

A complete list of dependencies can be found in the requirements.txt file.
Results and Insights
(This section can be populated after completing the analysis. Include key findings, visualizations, and actionable insights derived from the analysis.)
Contributing
Contributions to this project are welcome! Please follow these steps:

Fork the repository
Create a new branch: git checkout -b feature/your-feature-name
Make your changes and commit them: git commit -m 'Add some feature'
Push to the branch: git push origin feature/your-feature-name
Submit a pull request

License
This project is licensed under the MIT License - see the LICENSE file for details.
