# Home Credit Default Risk
Group Project for IS 6812 - Summer 2023
### Team
Roman, Che, Kalyani, and Chris

- - - - 

## Table of Contents

1. [Introduction](#introduction)
2. [Business Problem Statement](#business-problem-statement)
3. [Analysis and Implementation](#analysis-and-implementation)
   - [Data Analysis](#data-analysis)
   - [Feature Engineering](#feature-engineering)
   - [Imbalanced Classification Handling](#imbalanced-classification-handling)
   - [Building Model and Validation](#building-model-and-validation)
   - [Business Impact](#business-impact)
   - [Continual Improvement](#continual-improvement)
4. [Group's Solution](#groups-solution)
5. [Contribution](#contribution)
6. [Business Value](#business-value)
7. [Difficulties Encountered](#difficulties-encountered)
8. [Learning](#learning)

## Introduction <a name="introduction"></a>
In a world where millions of individuals are unbanked and lack access to financial services, Home Credit aims to bridge this gap by providing credit to the underserved population. However, establishing creditworthiness among this demographic, which lacks traditional financial history and verifiable assets, presents unique challenges. To address this, we embarked on a data science project to develop a machine learning model that predicts the likelihood of loan repayment for Home Credit customers.

## Business Problem Statement <a name="business-problem-statement"></a>
Our project focuses on using machine learning algorithms to build a classification model that accurately predicts whether a Home Credit customer is likely to repay their loan. By leveraging available data, we can help Home Credit identify trustworthy borrowers and improve their lending decisions. A successful model will enable Home Credit to extend credit to deserving individuals with confidence, leading to increased financial inclusion for the unbanked and tapping into an untapped market for the company.

## Analysis and Implementation <a name="analysis-and-implementation"></a>

### Data Analysis <a name="data-analysis"></a>
- Conducted in-depth analysis of the train dataset with 300,000+ records and 122 features.
- Focused on exploring the TARGET variable, identifying payment difficulties, and observing data imbalance.
- Provided valuable insights for data pre-processing and modeling decisions.

### Feature Engineering <a name="feature-engineering"></a>
- Prepared data for Logistic Regression by removing columns with >60% missing values.
- Imputed missing data for numeric variables using mean or median, and for categorical variables using the majority class.
- Implemented Logistic Regression model to identify significant features based on p-values.

### Imbalanced Classification Handling <a name="imbalanced-classification-handling"></a>
- Addressed class imbalance using upsampling to ensure model accuracy and fairness.
- Enabled accurate loan repayment predictions for all customers, regardless of their payment history.

### Building Model and Validation <a name="building-model-and-validation"></a>
- Implemented Logistic Regression model on upsampled data.
- Evaluated model performance using metrics such as accuracy, sensitivity, specificity, and AUC score.
- Compared Logistic Regression with other models to assess relative performance.

### Business Impact <a name="business-impact"></a>
- Emphasized potential business impact, especially in terms of financial inclusion and empowering underserved individuals.
- Highlighted the model's role in fostering economic growth through responsible lending.

### Continual Improvement <a name="continual-improvement"></a>
- Designed the model with scalability and adaptability to accommodate future data updates and evolving business needs.
- Recognized the importance of ongoing model enhancement and optimization.

## Group's Solution to the Business Problem <a name="groups-solution"></a>
Our group implemented various models, to predict loan repayment probabilities and see which model performs the best. We addressed the challenge of class imbalance using upsampling techniques to ensure accurate predictions for all customers, regardless of their payment history. The model's performance was rigorously evaluated using metrics such as accuracy, sensitivity, specificity, and AUC score. Our collaborative efforts and problem-solving skills resulted in a robust solution that Home Credit can leverage to enhance their lending practices.

## Contribution <a name="contribution"></a>
As a team member, I actively participated in various aspects of the project. Played a crucial role in conducting in-depth data analysis, exploring the TARGET variable, identifying payment difficulties, and providing valuable insights for data pre-processing and modeling decisions. Additionally, I prepared the data for Logistic Regression, and implemented the model to identify significant features based on p-values. 

## Business Value of the Solution <a name="business-value"></a>
The successful implementation of our model has immense business value for Home Credit. By accurately predicting loan repayment probabilities, Home Credit can make more informed lending decisions, reducing default risks, and increasing profitability. Moreover, the model promotes financial inclusion, allowing Home Credit to extend credit to deserving individuals from the underserved population, fostering economic growth.

## Difficulties Encountered <a name="difficulties-encountered"></a>
Throughout the project, our team encountered challenges related to handling class imbalance, selecting the most suitable model, and ensuring model interpretability. Also since the size of data was too large we saw logistic issues like system slowness and crashing. However, our collaborative efforts and problem-solving skills enabled us to overcome these difficulties and deliver a robust solution.

## Learning <a name="learning"></a>
Through this project, I have gained invaluable experience in data analysis, feature engineering, and handling imbalanced classification tasks. I learned how to interpret model results and communicate insights effectively. Additionally, working in a team setting enhanced my collaboration and communication skills, contributing to a successful outcome.

In conclusion, our Home Credit Default Risk Prediction project showcases our dedication to data science, collaboration, and delivering business value. It is a testament to our problem-solving abilities and highlights the impact of data analysis in driving informed decisions for Home Credit and fostering financial inclusion.
