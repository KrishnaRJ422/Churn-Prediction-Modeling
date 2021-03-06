# Churn-Prediction-Modeling
In this, an artificial neural network is modeled to predict the customer churn. HTML view of the optimum model:
https://krishnarj422.github.io/Churn-Prediction-Modeling/Churn_prediction_using_deep_learning.html

Source of dataset: https://www.kaggle.com/shubh0799/churn-modelling

Problem statement: Creating a model to predict the customer churn using customer demographic and financial details. Since the target variable 'Exited' is binary in nature, this is a binary classification case (whether the customer will churn(1) or not(0)).

Approach: For this problem, deep learning techniques (keras over tensorflow framework) are used to model the problem.

Performance metric: F1-score is considered as metric to evaluate the model performance.

Loss function: Binary cross entropy

A base line model is considered which has around 71% f1-score over which different techniques like feature-scaling, re-sampling, hyper-parameter tuning were using to improve the metric of interest. Final model is save as .h5 and loaded for reproduceability of results.

Conclusion: After applying multiple techniques, the final f1-score is arrived at 89% from baseline value of 71%.

Test data results in predicted_churn.csv

References:
1. https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/
2. https://machinelearningmastery.com/improve-deep-learning-performance/
3. https://keras.io/api/layers/initializers/#randomnormal
4. https://keras.io/api/losses/
5. https://keras.io/api/optimizers/
6. https://www.finex.co/how-to-display-html-in-github/
