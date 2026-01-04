# **Loan Approval Prediction using Machine Learning**
## **Project Overview**

Loan approval is a critical decision for banks and financial institutions. Making this decision manually can be slow, inconsistent, and influenced by human bias.

In this project, I built a data-driven loan approval prediction system using machine learning. The goal was to understand whether applicant information such as income, credit score, loan amount, and employment history can be used to predict loan approval outcomes accurately and consistently.

This project demonstrates my ability to take a real dataset, apply machine learning models, and translate the results into business-relevant insights.

## The Problem I Solved

Banks need to answer two important questions:

1. Should this loan be approved or rejected?

2. How risky is this applicant?

Using historical loan application data, I created predictive models that help answer both questions. This approach can support faster decisions, reduce risk, and improve overall efficiency in the loan approval process.

## What I Did

I approached this project the way a data analyst would in a real business setting:

- Explored and cleaned a real loan application dataset

- Selected the most relevant applicant features

- Built machine learning models to predict loan outcomes

- Compared different modeling approaches to understand their strengths

- Evaluated performance using appropriate metrics

- Interpreted results from a business perspective

The full analysis and results are documented in the report:
LoanApprovalPredictionsReport.pdf

## Models Used 

To solve the problem, I used two different machine learning approaches:

### Neural Networks

- Used to capture complex relationships in applicant data

- Well suited for learning patterns that are not obvious at first glance

- Applied to both loan approval prediction and risk scoring

### Decision Trees (CART)

- Used as a comparison model

- Easy to interpret and explain

- Helps identify which applicant factors influence decisions the most

By comparing these two approaches, I was able to balance predictive accuracy with model interpretability, which is important in financial decision-making.

## Results & Insights

The performance of both models was evaluated using separate training and validation datasets to ensure reliable and unbiased results.

### Overall Findings

- Decision Tree (CART) models performed better overall on this dataset for both loan approval prediction and risk score estimation.

- Neural Networks showed stable performance across training and validation data but did not outperform CART in this case.

- The results highlight the importance of model comparison, as more complex models do not always produce better outcomes.

### Classification Results (Loan Approval)

- CART achieved higher accuracy and stronger precision–recall balance than the Neural Network.

- Decision paths from CART made it easier to understand why a loan was approved or rejected.

- Neural Networks captured non-linear patterns but were less interpretable.

### Regression Results (Risk Scoring)

- CART regression produced higher R² values and lower prediction error.

- Neural Network regression showed signs of weaker generalization for this dataset.

- Simpler models proved more effective given the dataset size and feature set.

## Key Takeaways

- Machine learning can effectively support loan approval decisions

- Applicant features such as credit score and income strongly influence outcomes

- Decision trees performed well while remaining easy to interpret

- Neural networks demonstrated how complex patterns can be learned from data

- Model comparison is essential before deploying solutions in real businesses
