# ML

## Assumptions
![Screenshot from 2023-11-24 23-04-37](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/b4e2d354-5b88-46a3-b17e-1161fa519db5)

![Screenshot from 2023-11-24 23-24-47](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/65d21ed3-f0a4-47f7-8273-c0a3144de2d6)

## How we choose the dummy variables?

Alwayse no matter how many of the categorical columns we have we have to omit one of the categorical dummy variables from the total we have, suppose we have 10 then only 9 we have to consider. SO suppose we are having a column of Gender with Male and Female then we will only have the dummy variable for one in the linear equations

```
y = b0+b1x1+b2x2+b3D3

D3= Dummy Variable
```

## Null Hypothesis

Null Hypothesis represents a default assumption. Researchers and data scientists typically use the null hypothesis as a starting point for statistical analysis. Suppose we are tossing a coin, and we have two case that the Coin can be fair or not, So the null hypothesis would be to take the coin as fair in the starting of analysis

 ## P-Value

It represents the probability of obtaining the observed results if the null hypothesis is true. A small p-value (typically less than a chosen significance level, often 0.05) indicates that you can reject the null hypothesis in favor of the alternative hypothesis.

```
Alpha Values = 0.05 (P value)
```

## Building a Model

![Screenshot from 2023-11-25 00-31-42](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/69837e27-77e2-4a66-ab42-8cb8f2aaf93c)
![Screenshot from 2023-11-25 00-36-33](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/32823ecc-2d54-4430-ad23-3622e1ca334c)
![Screenshot from 2023-11-25 00-38-16](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/b9bd62db-4e91-4a63-9c2a-5185ee3b1657)
![Screenshot from 2023-11-25 00-49-37](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/1d0fdfba-1090-41bc-b0db-d3304fd94a31)
![Screenshot from 2023-11-25 00-49-06](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/1ef68a6b-af62-4312-9657-f96c1ddef38a)
![Screenshot from 2023-11-25 00-48-03](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/56787e7d-e8cf-45fc-914d-72827d7156ca)

## SVR
![Screenshot from 2023-11-25 04-44-07](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/46fcb919-e7d5-4cd8-ad50-bba4065d9302)


## Decision Tree 

![Screenshot from 2023-11-25 17-03-54](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/c0baa31b-7402-4f00-b5e8-3b95d2164068)

## Random Forest

Random forests or random decision forests is an ensemble learning method which combines the output of multiple decision trees to reach a result

- Gini impurity ('gini'):

Gini impurity is a measure of how often a randomly chosen element would be incorrectly classified. It reaches its minimum (zero) when all elements of a node are pure (belong to the same class).
The Gini impurity for a node is calculated as the sum of the squared probabilities of each class being chosen times the probability of a mistake in categorizing that class.

- Entropy ('entropy'):

Entropy is a measure of impurity in information theory. In the context of decision trees, it quantifies the amount of information or disorder at a node. A node with a low entropy means it is pure (all elements belong to the same class).
The entropy for a node is calculated as the sum of the probability of each class times the log base 2 of the probability.

- Classification error ('class_weight'):

This criterion measures the classification error, which is the fraction of training samples that are misclassified.
It is not commonly used as it is less sensitive to changes in the class probabilities.

- Logarithmic loss ('log' or 'log_loss'):

Logarithmic loss measures the performance of a classification model where the prediction is a probability value between 0 and 1.
The loss increases as the predicted probability diverges from the actual label.

![Screenshot from 2023-11-25 17-51-13](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/90ecc884-a937-4807-9836-ffe13b79e869)

## R Squared
![Screenshot from 2023-11-25 21-09-15](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/b55b3f28-9587-40e8-bed6-98d8456416a5)

## Adjusted R Squared

![Screenshot from 2023-11-25 21-13-22](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/cec1f84a-b624-48cc-aeea-f66f2e6ab99f)

## K-NN

![Screenshot from 2023-11-26 01-47-06](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/34151fe4-3fa1-4f83-99f2-54847bc24a37)

## SVM 

![Screenshot from 2023-12-03 15-59-45](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/9283716e-a73b-4e9d-9f86-79be2517c0a4)
![Screenshot from 2023-12-03 16-02-02](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/0f7982fe-4a35-401a-bd99-4ed1a4349216)
![Screenshot from 2023-12-03 16-02-25](https://github.com/shuklaritvik06/machine-learning-course/assets/72812470/5305b725-b58a-4650-8007-d26c479c104f)
