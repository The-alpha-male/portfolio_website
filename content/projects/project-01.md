---
title: "Solubility_Predictor using Machine Learning"
slug: Machine Learning
category: projects
summary:
description:
cover:
  image: "images/solubility.png" 
  alt: "Solubility_Predictor using Machine Learning"
  caption:
  relative: true
showtoc: true
draft: false
---

# Project Description

This project delves into the realm of cheminformatics to predict the aqueous solubility of chemical compounds using machine learning techniques. By leveraging a comprehensive dataset containing molecular descriptors from [Delaney's solubility dataset]('https://raw.githubusercontent.com/dataprofessor/data/master/delaney_solubility_with_descriptors.csv'), I explored key molecular properties like molecular weight, LogP, and the number of rotatable bonds, transforming raw chemical data into actionable predictive models.

- Data Analysis: I meticulously prepared the dataset by separating the target variable (logS, which represents solubility) from the features (molecular descriptors). I then split the data into training and testing sets to ensure unbiased model evaluation.

- Model Development: I built and compared two predictive models—Linear Regression and Random Forest Regressor—to determine which algorithm more accurately predicts solubility based on molecular descriptors.

- Performance Evaluation: Using performance metrics such as Mean Squared Error (MSE) and R² Score, I evaluated each model's effectiveness. The Linear Regression model slightly outperformed the Random Forest model, achieving an R² score of 0.77 on the test set.

- Visualization: To illustrate the models' predictive power, I created scatter plots comparing the actual versus predicted solubility values, including a fitted regression line to highlight the correlation.

This project showcases my ability to apply machine learning techniques to complex chemical data, transforming it into valuable insights that can assist in fields like drug discovery and materials science. It demonstrates my skills in data preprocessing, model building, evaluation, and visualization—all critical for driving data-driven decisions in a scientific context.



[Github Link](https://github.com/The-alpha-male/Solubility_Predictor_using_Machine-learning.git)
