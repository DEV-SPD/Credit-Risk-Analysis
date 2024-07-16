# Table of Contents
- [About Credit Risk Analysis](#about-credit-risk-analysis)
- [Why credit risk is so relevant in finance?](#why-credit-risk-is-so-relevant-in-finance?)
- [Primary Objective](#primary-objective)
- [Project Steps](#project-steps)


  
# About Credit Risk Analysis
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

Credit risk analysis is the process of evaluating the potential risk that a borrower may default on a loan or credit agreement. This involves assessing the borrower's creditworthiness through various quantitative and qualitative factors, such as credit history, financial statements, market conditions, and economic indicators. The goal is to predict the likelihood of default and mitigate potential losses by making informed lending decisions, setting appropriate interest rates, and implementing effective risk management strategies.

# Why credit risk is so relevant in finance?
Financial institutions used credit risk analysis models to determine the probability of default of a potential borrower. 
The model provides information on the level of a borrower’s credit risk at any particular time. If the lender fails to detect the credit risk in advance, it exposes them to the risk of default and loss of funds. 
Lenders rely on the validation provided by credit risk analysis models to make key lending decisions on whether or not to extend credit to the borrower and the credit to be charged.
With the continuous evolution of technology, banks are continually researching and developing effective ways of modeling credit risk. 

# Primary Objective
The primary aim is to understand which are the factors that are effecting more the probability of having an high credit risk of a given company/organization, and build models capable to predict (given some features) the credit risk level.

# Project Steps
1. **Environment Setup**: Installing necessary libraries and loading the dataset.
2. **Data Exploration**: Exploring dataset to discover data distribution, detect missing values in columns, detect outliers, detect class imbalance, statistical analysis was done & insights were also derived from plots like violin plot, count plot etc.
3. **Data Preprocessing**: Removing null values, replacing outliers with extreme value either upper or lower limit with conditional check using np.where(), Textual features were converted into numerical features, fixing class imbalance issue using SMOTE, dropping irrelevant columns.
4. **Feature Selection**: Selected top 45 features based on mutual info score using selectkbest available in sklearn library.
5. **Feature Scaling**: Dataset was splitted into train and test data & z-score normalization was done on both train and test data separately to prevent data leaks.
6. **Data Modelling**: Best model was selected & Validated on test data.
7. **Documentation**: Writing the README file and code documentation.

