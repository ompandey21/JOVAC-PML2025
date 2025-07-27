# Part-III: General Questions - Linear and Logistic Regression

## Question 1: What are the assumptions of linear regression?

Linear regression has four key assumptions that must be satisfied for the model to produce valid results:

**Linearity**: The relationship between independent variables and the dependent variable must be linear. This means changes in predictors should result in proportional changes in the outcome variable.

**Independence**: All observations must be independent of each other. There should be no correlation between residuals, meaning one observation should not influence another.


---

## Question 2: When should you use logistic regression instead of linear regression?

Logistic regression should be used when the dependent variable is categorical rather than continuous:


**Classification problems**: When the goal is to classify observations into discrete categories rather than predict numerical values on a continuous scale.

**Non-linear relationships**: When the relationship between predictors and the outcome follows a sigmoid pattern rather than a straight line.

---

## Question 3: What is the interpretation of coefficients in logistic regression?

Coefficients in logistic regression have a different interpretation compared to linear regression:

**Log-odds interpretation**: Each coefficient represents the change in log-odds of the outcome for a one-unit increase in the predictor variable, holding other variables constant.


**Direction of effect**: Positive coefficients increase the probability of the positive class, while negative coefficients decrease it. The magnitude indicates the strength of association.

**Non-linear impact**: Unlike linear regression, the effect of changing a predictor depends on the current values of all predictors due to the sigmoid transformation.

---

## Question 4: What is the difference between sigmoid and softmax functions?

The sigmoid and softmax functions serve different purposes in classification:

**Sigmoid function**: Used for binary classification, it maps any real number to a probability between 0 and 1 using the formula σ(x) = 1/(1 + e^(-x)). It outputs a single probability value.

**Softmax function**: Used for multiclass classification, it converts a vector of real numbers into a probability distribution where all probabilities sum to 1. 

**Use cases**: Sigmoid is for binary decisions (spam/not spam), while softmax handles multiple categories (classifying images into dog/cat/bird).

---

## Question 5: Why is R-squared not suitable for evaluating logistic regression models?

R-squared is inappropriate for logistic regression evaluation for several fundamental reasons:

**Continuous vs categorical**: R-squared measures how well a model explains variance in continuous outcomes, but logistic regression predicts categorical outcomes where the concept of "variance explained" doesn't apply meaningfully.

**Probability vs values**: Logistic regression outputs probabilities bounded between 0 and 1, not unbounded continuous values like linear regression, making traditional R-squared calculations problematic.



---

