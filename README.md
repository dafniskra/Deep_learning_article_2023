# Neural Network and Ensemble Learning
This repository contains code related to the article titled "Neural Network and Ensemble Learning with Application to Accident Frequencies." The code includes implementations in both R and Python.

In collaboration with Fabien Navarro (Website: fnavarro.perso.math.cnrs.fr), this work aims to understand the contributions of ensemble methods with deep learning in predicting accident frequencies.

## Models from the Literature:
NNemb
CANN
For the tree and boosting models, the code is sourced from the article titled "Nesting Classical Actuarial Models into Neural Networks" by Schelldorfer, Jürg, and Mario V. Wuthrich (2019). The article is available here (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3320525).

# Code
In this section, we provide details on the code and data used for the experiments.

## Data Source
We utilized the FreMTPL2freq dataset for this project.

## Data Preparation
To ensure robust results, we employed a Monte Carlo cross-validation approach by creating 10 different datasets. Each dataset was divided into 85% for training and 15% for testing. This method enhances the reliability of our results.

## R Code
Regression CANN
Regression NNEmb

## Python Code
Bagging
NN with Dropout
NN with Tanh and Sigmoid activation functions


Feel free to explore and use the provided code for your own analysis and experiments!
