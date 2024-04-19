# Project title: Heart Failure Prediction

# Abstract:
Cardiovascular diseases are serious problems and to early detection and management,
it is curial to identify the risk factors that causes the disease. 
Herein, machine learning was used to predict the different factor cause heart failure and eventually the death.

# Motivation
- Cardiovascular diseases kill approximately 17 million people globally every year (Chicco & Jurman, 2020)
- People with cardiovascular disease or who are at high cardiovascular risk need early
  detection and management wherein a machine learning model can be of great help
  
# Dataset source:
- Heart failure clinical records DataSet was used 
- Data download from Kaggle
- Data involves the possible risk factor of Heart failure.
- 12 factors and 299 records

# Data Preprocessing:
- Cleaning data form missing values
- Scaling data

# Research Question
What are the  different factors are responsible for heart failure?

# Methods
- Recursive Feature Elimination Technique(RFE)  used for feature selection 
- Logistic regression used for classification
- Many packages were used: numby, pandas, sklearn, seaborn, matplotlib

# Findings 
In the Jupyter notebook.

# Conclusions
The factors that is considers as danger for heart failure appear to be are age,
ejection_fraction, platelets, serum_creatinine, serum_sodium. 
However, Chicco & Jurman(2020) reported that  ejection fraction and serum creatinine are the two most relevant features confirmed

# Limitations
- For future works, it is better to try several classification method, for, SVM
- More analysis steps need to find the one or two most factors involving in heart failure
# References 
- Chicco, D., & Jurman, G. (2020). Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone.
  BMC Medical Informatics and Decision Making, 20(1), 16. https://doi.org/10.1186/s12911-020-1023-5
- IBM Docs. (2021, March 8). https://prod.ibmdocs-production-dal-6099123ce774e592a519d7c33db8265e-0000.us-south.containers.appdomain.
  cloud/docs/en/spss-statistics/24.0.0?topic=option-logistic-regression
- Saw, M., Saxena, T., Kaithwas, S., Yadav, R., & Lal, N. (2020). Estimation of Prediction for Getting Heart Disease Using Logistic Regression Model of Machine Learning.
2020 International Conference on Computer Communication and Informatics (ICCCI), 1–6. https://doi.org/10.1109/ICCCI48352.2020.9104210













