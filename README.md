# eda_and_prediction

This project conducts an exploratory data analysis of the Global Financial Inclusion (Global Findex) Database of 2014. The analysis aims to reveal data patterns, trends, correlations, and insights that can assist businesses, organizations, or researchers in making informed financial decisions. The dataset used was collected from the world bank.

The statistical and graphyical exploratory data analysis was done using PySpark.

In order to predict the outcome, the project explored six Machine Learning algorithms: Logistic Regression, Decision Tree, Support Vector Classifier, Naive Bayes, Random Forest, and Gradient Boosting. Each algorithm was chosen based on its suitability for the dataset characteristics and the problem at hand—for example, Decision Trees for their interpretability and Random Forests for handling non-linear data without overfitting. Models were trained using binary classification to ensure generalizability, and performance was evaluated using accuracy, F1- score metrics, mean square error (MSE) and root mean square error (RMSE).

The Gradient Boosting model performed the best among all the models.

F1- score: 0.72

Accuracy: 73%

Mean Square Error (MSE): 0.27

Root Mean Square Error (RMSE): 0.52

