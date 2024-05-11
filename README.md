Data loading and preprocessing: I loaded the dataset from a CSV file, handled bad lines, dropped unnecessary columns, encoded categorical variables using LabelEncoder, and removed duplicate rows.

Linear Regression: I trained a linear regression model to predict the outcome variable ('game_result') based on the remaining features. I evaluated the model's performance using metrics such as mean squared error, mean absolute error, and R-squared.

Polynomial Regression: I applied polynomial features to the dataset and trained another linear regression model with polynomial features. I evaluated the performance of this model using the same metrics.

Decision Tree Classifier: I trained a decision tree classifier to predict the outcome variable and evaluated its accuracy, as well as generated a confusion matrix and classification report.

K-Nearest Neighbors Classifier: I trained a KNN classifier with 3 neighbors, evaluated its accuracy, generated a confusion matrix, and a classification report.

Bias Analysis: I calculated the bias of the linear regression model predictions compared to the mean of the training target variable.
