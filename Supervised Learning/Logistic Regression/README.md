# Logistic Regression
## Introduction
Logistic Regression is a type of statistical model used in machine learning for predicting the probability of a given outcome or class based on one or more input features. It is a popular method for binary classification problems and can be extended to multi-class classification using techniques like "one-vs-all" or "one-vs-one".
## Algorithm Application
Logistic Regression uses the cross-entropy loss as the cost function, which measures the difference between the predicted probabilities and the true labels. The cross-entropy loss for binary classification is given by:
$$
L(y, \hat{y}) = -[y \log(\hat{y}) + (1 - y) \log(1 - \hat{y})]
$$
where $y$ is the true label and $\hat{y}$ is the predicted probability.\\
To minimize the cross-entropy loss, Logistic Regression uses the gradient descent optimization algorithm. 
## Data
The Fastfood dataset contains restaurant,	item,	calories,	cal_fat,	total_fat,	sat_fat,	trans_fat,	cholesterol	sodium,	total_carb,	fiber,	sugar,	protein,	vit_a,	vit_c,	calcium, and it was classified based on their calories and sugar content.
