
# Machine Learning Model Development for Biodiesel Production

This project focuses on developing machine learning models to optimize biodiesel production. The outcomes of this project have been published in Elsevier's Bioresource Technology Reports.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Results](#results)
- [Acknowledgments](#acknowledgments)
  


## Introduction

This project involves the development of machine learning models to enhance the biodiesel production process. The experiments were designed using a Box-Behnken design (BBD) with four input variables: reaction temperature, catalyst concentration, reaction time, and methanol-to-oil ratio.




## Methodology

### Experimental Design

The biodiesel production experiments were planned using a Box-Behnken design (BBD) with four factors: reaction temperature, catalyst concentration, reaction time, and methanol-to-oil ratio. The design matrix was generated using the Python library, PyDoE2.

### Data Analysis

The data generated from the BBD was used to build machine learning models for the biodiesel production process. All analyses were carried out in Python (version 3.7.5) with Jupyter as the integrated development environment (IDE). The following libraries were used:

- *Numpy (version 1.17.0)*: For numerical analysis
- *Matplotlib (version 3.5)*: For data visualization
- *TensorFlow (version 2.4.0)*: For ANN modeling
- *Scikit-learn (version 0.23.2)*: For SVM, KRR, and RF modeling
- *Python-ELM*: For ELM modeling
- *XGBoost (version 1.2.3)*: For XGB modeling

### Model Development

Six machine learning models were implemented:

1. Artificial Neural Network (ANN)
2. Extreme Learning Machine (ELM)
3. Support Vector Machine (SVM)
4. Random Forest (RF)
5. Kernel Ridge Regression (KRR)
6. eXtreme Gradient Boosting (XGB)

### Cross-Validation

A 3-fold cross-validation was performed using a dataset of 29 biodiesel yield measurements. The dataset was split into an 80:20 train-test ratio. Cross-validation was conducted on the training set, while the test set was used to evaluate model performance.

## Results

The results of the machine learning models, including performance metrics and visualizations, can be found in the published paper in Bioresource Technology Reports.

## Acknowledgments

This project was a collaborative effort by a dedicated team. Special thanks to all team members for their contributions:

- *Team Member 1: Stanley Eshiemogie*
- *Team Member 2: Shedrach Igemhokai*
- *Benita*: Initiated the analysis and contributed to the overall project development
- *Team Member 4: Joshua Ayere*

