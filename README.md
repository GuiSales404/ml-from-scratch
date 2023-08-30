# Machine Learning Course Exercises Repository
This repository was created to store the exercises for the Machine Learning course of the Bachelor's in Computer Science course at Federal University of Ceará. The exercises include implementations of algorithms studied during the course.

## Exercise Lists

### List 1 - Linear, Polynomial and Regularized Regression
The first exercise list covers the following topics:

- Linear Regression 
- Polynomial Regression
- L2 Regularization

The exercise in the first question involves implementing and evaluating regression models (OLS, GD, and SGD) on a dataset (artificial1d.csv) with two columns (x and y). The models' parameters, MSE, and resulting lines are presented. In the second question, the exercise focuses on a dataset used for predicting median house prices in California districts during the 1990s. It includes steps such as data splitting, training 13 polynomial regression models using OLS, and reporting RMSE for training and testing. L2 Regularization, data normalization, and the creation of graphs for training and testing are also incorporated.

### List 2 - Logistic Regression and Statistical Methods
The second exercise list covers the following topics:

- Logistic Regression
- Gaussian Discriminant Analysis (GDA)
- Gaussian Naive Bayes (GNB)
- K-Fold Cross Validation

The exercise in the first question involves implementing and evaluating binary classification models (Logistic Regression, Gaussian Discriminant Analysis, and Gaussian Naive Bayes) on a breast cancer dataset. In the second question, the exercise focuses on evaluating multiclass classification models (Softmax Regression, Gaussian Discriminant Analysis, and Gaussian Naive Bayes) on a vehicle dataset for classifying vehicles into four classes. Both models in each question are assessed using 10-fold cross-validation, and the average and standard deviation of accuracy are reported.


### List 3 - KNN and Decision Trees
The third exercise list covers the following topics:

- K-Nearest Neighbors, with Euclidean and Mahalanobis distances
- Decision Trees, with impurity indices of gini or entropy
- K-Fold Cross Validation

The exercise involves implementing and evaluating binary classification models using KNN and Decision Tree approaches on a dataset of NASA source code attributes, and reporting the average value and standard deviation of Accuracy, Recall, Precision, and F1-score for each model.


### List 4 - Artificial Neural Networks for Nonlinear Regression and Classification
The forth exercise list covers the following topics:

- Nonlinear Regression using MLP
- Classification using MLP
- Minibatch Stochastic Gradient Descent with Momentum
- Model Evaluation Metrics

This exercise list explores the application of Artificial Neural Networks in nonlinear regression and classification tasks. In question 1, a dataset on concrete properties is used to train and evaluate a nonlinear regression model. The model, based on a Multilayer Perceptron (MLP) with 1 hidden layer, is trained using minibatch stochastic gradient descent with momentum. The dataset is randomly split into training, validation, and test sets, and metrics such as RMSE, MAE, and MRE are reported. In question 2, a dataset on British speech samples is employed to train and evaluate a nonlinear classification model using a similar architecture. The accuracy is reported for the training, validation, and test sets. Both questions provide insights into the model's learning process through cost function curves over epochs.

### List 5 - Binary Classification with SVM and Random Forest
The fifth exercise list covers the following topics:

SVM with RBF Kernel and Grid-Search
Random Forest and Grid-Search
The fifth exercise list focuses on binary classification using SVM and Random Forest models. It involves tuning the hyperparameters using grid-search and evaluating the models' performance on test data. The goal is to optimize the Accuracy, Recall, Precision, and F1-score metrics for predicting house prices in California districts during the 1990s. Additionally, plots were created for the ROC curve and the Precision-Recall curve. Existing implementations, such as those provided by Scikit-learn, were used for this task.

## Contributing
Contributions are always welcome! If you find an error in the exercises, have a suggestion for improvement, or wish to add new exercises, feel free to create an issue or send a pull request.

## License
This repository is licensed under the MIT License. See the LICENSE file for more information.
