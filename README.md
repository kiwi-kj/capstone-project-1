# Home Credit Default Risk
Group Project for IS 6812\
Summer 2023
- - - - 
Table of Contents
Introduction
Business Problem Statement
Analysis and Implementation
Data Analysis
Feature Engineering
Imbalanced Classification Handling
Building Model and Validation
Business Impact
Continual Improvement
Introduction <a name="introduction"></a>
In a world where millions of individuals are unbanked and lack access to financial services, Home Credit aims to bridge this gap by providing credit to the underserved population. However, establishing creditworthiness among this demographic, which lacks traditional financial history and verifiable assets, presents unique challenges. To address this, we embarked on a data science project to develop a machine learning model that predicts the likelihood of loan repayment for Home Credit customers.

Business Problem Statement <a name="business-problem-statement"></a>
Our project focuses on using machine learning algorithms to build a classification model that accurately predicts whether a Home Credit customer is likely to repay their loan. By leveraging available data, we can help Home Credit identify trustworthy borrowers and improve their lending decisions. A successful model will enable Home Credit to extend credit to deserving individuals with confidence, leading to increased financial inclusion for the unbanked and tapping into an untapped market for the company.

Analysis and Implementation <a name="analysis-and-implementation"></a>
1. Data Analysis <a name="data-analysis"></a>
Conducted in-depth analysis of the train dataset with 300,000+ records and 122 features.
Focused on exploring the TARGET variable, identifying payment difficulties, and observing data imbalance.
Provided valuable insights for data pre-processing and modeling decisions.
2. Feature Engineering <a name="feature-engineering"></a>
Prepared data for Logistic Regression by removing columns with >60% missing values.
Imputed missing data for numeric variables using mean or median, and for categorical variables using majority class.
Implemented Logistic Regression model to identify significant features based on p-values.
3. Imbalanced Classification Handling <a name="imbalanced-classification-handling"></a>
Addressed class imbalance using upsampling to ensure model accuracy and fairness.
Enabled accurate loan repayment predictions for all customers, regardless of their payment history.
4. Building Model and Validation <a name="building-model-and-validation"></a>
Implemented Logistic Regression model on upsampled data.
Evaluated model performance using metrics such as accuracy, sensitivity, specificity, and AUC score.
Compared Logistic Regression with other models to assess relative performance.
5. Business Impact <a name="business-impact"></a>
Emphasized potential business impact, especially in terms of financial inclusion and empowering underserved individuals.
Highlighted the model's role in fostering economic growth through responsible lending.
6. Continual Improvement <a name="continual-improvement"></a>
Designed the model with scalability and adaptability to accommodate future data updates and evolving business needs.
Recognized the importance of ongoing model enhancement and optimization.
In conclusion, my individual contributions to the Home Credit Default Risk Prediction project involved extensive data analysis, feature engineering, addressing imbalanced classification, model building and validation, emphasizing the business impact, and promoting continuous improvement. As a team, we aimed to revolutionize lending practices, deliver tangible business value to Home Credit, and contribute to a more financially inclusive world.

**Deliverable:** [Combined Notebook.html](https://github.com/WestlakeData/Home-Credit-Default-Risk/blob/main/Combined-Notebook.html)
