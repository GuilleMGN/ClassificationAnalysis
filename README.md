# ClassificationAnalysis

## Description

Mortgages, student and auto loans, and debt consolidation are just a few examples of credit and loans that people seek online. Peer-to-peer lending services such as Loans Canada and Mogo let investors loan people money without using a bank. However, because investors always want to mitigate risk, a client has asked that you help them predict credit risk with machine learning techniques.
In this assignment we will build and evaluate several machine learning models to predict credit risk using data we'd typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so we will need to employ different techniques for training and evaluating models with imbalanced classes. We will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

* Resampling
* Ensemble Learning

## Technologies
* pandas
* numpy
* pathlib
* collections
* sklearn

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) </br>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) </br>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) </br>

## Conclusions

### Credit Risk Ensemble

#### Which model had the best balanced accuracy score?

* Easy Ensemble Classifier had the best balanced accuracy score of 0.9263912558266958

#### Which model had the best recall score?

* Easy Ensemble Classifier had the best recall score of avg/total 0.94

#### Which model had the best geometric mean score?

* Easy Ensemble Classifier had the best geometric mean score of avg/total 0.93

#### What are the top three features?

* The top 3 features are total_rec_prncp, total_rec_int, and total_pymnt_inv

---

### Credit Risk Resampling

#### Which model had the best balanced accuracy score?

* Both the SMOTE Oversampling and the Combination Sampling had the best balanced accuracy score of 0.9946680739911509

#### Which model had the best recall score?

* Naive Random Oversampling, SMOTE Oversampling, and Combination Sampling all had the best recall score of high_risk 1.00, low_risk 0.99 and avg/total 0.99

#### Which model had the best geometric mean score?

* All the models have the same geometric mean score of 0.99

---

Copyright 2022 © Matthew Guillen
