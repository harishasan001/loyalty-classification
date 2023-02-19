TLDR: A self-challenged speedrun to best solve a customer loyalty binary classification problem with and without ML libraries

View in a new tab [here](https://htmlpreview.github.io/?https://github.com/harishasan001/loyalty-classification/blob/main/loyalty-classification.html)!

------

# Binary Classification Model Comparison
This repository contains a Jupyter Notebook that compares the performance of three binary classification models on a dataset. The models compared are logistic regression, k-nearest neighbors, and support vector machine. The dataset used for training and validation consists of two features and a binary label.

The objective of the analysis is to identify the best model based on evaluation metrics such as accuracy, precision, recall, and F1 score. The dataset is also visualized using scatter plots to gain an understanding of the data distribution.

The notebook contains the following sections:

- Data Exploration
- Model Training
- Model Comparison
- Model Selection
- Generating Predictions

In the "Model Training" section, the logistic regression, k-nearest neighbors, and support vector machine models are trained and their evaluation metrics are computed on a validation dataset. In the "Model Comparison" section, the best hyperparameters for each model are selected using cross-validation and grid search. In the "Model Selection" section, the best model is chosen based on its evaluation metrics. Finally, in the "Generating Predictions" section, the chosen model is used to generate predictions on the validation datasets and the predictions are saved to CSV files.

There is also an additional section that generates predictions without the use of traditional libraries via linear regression and the normality equation.

![Alt Text](loyalty classification scroll.gif)
