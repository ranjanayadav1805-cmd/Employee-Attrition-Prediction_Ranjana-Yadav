# Employee Attrition Prediction Using Machine Learning
## Introduction

Employee attrition refers to an employee’s voluntary
or involuntary resignation from a workforce. Organizations spend many resources in hiring talented employees
and training them. Every employee is critical to a company’s success. Our goal was to predict employee attrition
and identify the factors contributing to an employee leaving a workforce. We trained various classification models on our dataset and assessed their performance using different metrics such as accuracy, precision, recall and F1 Score. We
also analyzed the dataset to identify key factors contributing
to an employee leaving a workforce. 
The goal is to help HR teams identify employees at risk of leaving and understand the main factors that drive attrition, such as job role, salary, overtime, work-life balance, and years at the company.
## Methodology
![Methodology Flowchart](https://github.com/ranjanayadav1805-cmd/EmployeeAttrition_Ranjana-Yadav/blob/dd61d5b254d55527640e713c7f62d70c1bf9ee7b/Flowchart.png)

#### Machine Learning Models

We trained and evaluated 9 supervised machine learning classification models.

1. Logistic Regression
2. Naive Bayes
3. Decision Tree
4. Random Forest
5. AdaBoost
6. Support Vector Machine
7. Linear Discriminant Analysis
8. Multilayer Perceptron
9. K-Nearest Neighbors


## Dataset
We used the [IBM Employee Attrition dataset from Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset). It contains 35 columns and 1470 rows and has a mix of
numerical and categorical features.
The dataset includes employee-related features such as:

. Age

. Department

. Job Role

. Monthle Income

. Overtime

. Work life balance

. Years at company

. Business Travel

. Job Satisfaction

. Attrition(Target variables)



Target Variables: Attrition

. Yes= Employee left the company

. No= Employee Stayed in the company



#### Best Performing Model
The best performance was obtained in Random Forest Model
with PCA and Oversampling with an accuracy of 99.2%,
the precision of 98.6%, recall of 99.8% and F1 Score of
99.2%.

## Instructions to run
Jupyter Notebook can be run using Google Colab or locally using Anaconda Navigator.

**Steps to run using Google Colab**
1. Upload the dataset
2. Click on Runtime -> Run all / Restart and Run all

## Libraries Used
1. [Numpy](https://numpy.org/)
2. [Pandas](https://pandas.pydata.org/)
3. [Matplotlib](https://matplotlib.org/)
4. [Seaborn](https://seaborn.pydata.org/)
5. [Scikit-learn](https://scikit-learn.org/stable/index.html)
