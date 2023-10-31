# Sure-Tomorrow-Insurance-Machine-Learning-Evaluation
Sure Tomorrow Insurance Machine Learning Evaluation
# Sure Tomorrow Insurance Machine Learning Evaluation

## Introduction
The Sure Tomorrow insurance company aims to leverage Machine Learning to solve several tasks. In this GitHub repository, we present our analysis, experiments, and results for the following tasks:

### Task 1: Finding Similar Customers
The goal is to identify customers who are similar to a given customer, which can aid the company's marketing efforts. We explore different distance metrics, including Euclidean and Manhattan, and assess the impact of data scaling on the results.

### Task 2: Predicting Insurance Benefit Eligibility
This task involves binary classification to predict whether a new customer is likely to receive insurance benefits. We compare the performance of a k-Nearest Neighbors (kNN) classifier to a dummy model and assess the effect of data scaling on the results.

### Task 3: Predicting the Number of Insurance Benefits
Using a Linear Regression model, we predict the number of insurance benefits a new customer is likely to receive. We evaluate the model's performance with and without data scaling.

### Task 4: Data Obfuscation
To protect clients' personal data without compromising model quality, we implement data obfuscation. We explore the impact of data obfuscation on the features and analytically prove its compatibility with Linear Regression.

## Repository Contents

This repository contains the following components:

### Task 1: Finding Similar Customers
- Implementation of k-Nearest Neighbors algorithm
- Experiments with scaling and distance metrics
- Results and insights

### Task 2: Predicting Insurance Benefit Eligibility
- Implementation of a kNN-based classifier
- Evaluation of kNN classifier and dummy models
- Comparison of results with and without data scaling

### Task 3: Predicting the Number of Insurance Benefits
- Custom implementation of Linear Regression
- RMSE evaluation for Linear Regression on original and scaled data

### Task 4: Data Obfuscation
- Data obfuscation process using an invertible matrix
- Analytical proof of data obfuscation's impact on Linear Regression
- Computation of Linear Regression with obfuscated data

## Key Insights

Here are some key insights from our analysis:

- Data scaling significantly impacts the performance of k-Nearest Neighbors and Linear Regression models. Scaling can lead to better results by mitigating the effect of varying feature scales.

- The kNN classifier outperforms the dummy model for predicting insurance benefit eligibility. The choice of k can impact the model's performance.

- Linear Regression models yield consistent results with and without data scaling, as Linear Regression inherently adjusts for feature units.

- Data obfuscation can effectively protect personal data while maintaining model performance. Analytically and computationally, we demonstrated that obfuscation does not affect Linear Regression results.

## Conclusion

This GitHub repository provides a comprehensive analysis of Sure Tomorrow Insurance's Machine Learning tasks. We have explored data preprocessing, model implementation, and analytical explanations to address the company's objectives. The results and insights gathered here can guide future decisions and improvements in insurance benefit prediction and customer similarity identification.

Thank you for visiting the Sure Tomorrow Insurance Machine Learning Evaluation repository. We hope the information provided here is valuable to your endeavors.
