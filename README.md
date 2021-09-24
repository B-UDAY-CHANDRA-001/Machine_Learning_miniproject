# Machine_Learning_miniproject

# Supervised Learning
Supervised machine learning algorithms derive insights, patterns, and relationships from a labeled training dataset. It means the dataset already contains a known value for the target variable for each record. It is called supervised learning because the process of an algorithm learning from the training dataset is like an instructor supervising the learning process. You know the correct answers, the algorithm iteratively makes predictions on the training data and the instructor corrects it. Learning ends when the algorithm achieves the desired level of performance and accuracy.

Supervised learning problems can be further classified into regression and classification problems.

1) Classification: In a classification problem, the output variable is a category, such as “red” or “blue,” “disease” or “no disease,” “true” or “false,” etc.
2) Regression: In a regression problem, the output variable is a real continuous value, such as “dollars” or “weight.
Logistic regression
Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable. Some of the examples of classification problems are Email spam or not spam, Online transactions Fraud or not Fraud, Tumor Malignant or Benign. Logistic regression transforms its output using the logistic sigmoid function to return a probability value. What are the types of logistic regression

Binary (eg. Tumor Malignant or Benign)
Multi-linear functions failsClass (eg. Cats, dogs or Sheep's)
We can call a Logistic Regression a Linear Regression model but the Logistic Regression uses a more complex cost function, this cost function can be defined as the ‘Sigmoid function’ or also known as the ‘logistic function’ instead of a linear function.

Logistic regression is a generalized linear model. And it uses the same basic formula of linear regression

In linear regression, we predict the output variable Y base on the weighted sum of input variables.
In logistic regression, we perform the exact same thing but with one small addition. We pass the result through a special function known as the Sigmoid Function to predict the output Y.

## Advantages of the Logistic Regression Algorithm

1) Logistic regression performs better when the data is linearly separable
2) It does not require too many computational resources as it’s highly interpretable
3) There is no problem scaling the input features—It does not require tuning
4) It is easy to implement and train a model using logistic regression
5) It gives a measure of how relevant a predictor (coefficient size) is, and its direction of association (positive or negative)

## Logistic Regression Assumptions


1) In case of binary logistic regression, the target variables must be binary always and the desired outcome is represented by the factor level 1.

2) There should not be any multi-collinearity in the model, which means the independent variables must be independent of each other.

3) We must include meaningful variables in our model.

4) We should choose a large sample size for logistic regression.

## Applications of Logistic Regression

applications of logistic regression:

1) Predicting a probability of a person having a heart attack

2) Predicting a customer’s propensity to purchase a product or halt a subscription.

3) Predicting the probability of failure of a given process or product.

## Libraries used for Logistic regression(for this project):

One of the most amazing things about Python’s **scikit-learn** library is that is has a 4-step modeling pattern that makes it easy to code a machine learning classifier.

1. Import the model you want to use
2. Make an instance of the Model
3. Training the model on the data, storing the information learned from the data
4. Predict labels for new data
