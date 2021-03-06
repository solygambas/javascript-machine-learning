# Machine Learning Projects with JavaScript

6 projects to understand basic algorithms in Machine Learning, using Lodash and Tensorflow.js.

| #   | Project                                      | Description                                                                                  |
| --- | -------------------------------------------- | -------------------------------------------------------------------------------------------- |
| 01  | [**Plinko**](#plinko)                        | A quick introduction to K-Nearest Neighbors (KNN) algorithm using Lodash.                    |
| 02  | [**House Pricings**](#housepricings)         | Another implementation of K-Nearest Neighbors (KNN) algorithm with Tensorflow.js.            |
| 03  | [**Gas Mileage Calculator**](#gasmileage)    | A gradient descent algorithm in linear regression using Tensorflow.js.                       |
| 04  | [**Smog Test**](#smogtest)                   | A gradient descent algorithm in logistic regression to handle natural binary classification. |
| 05  | [**Fuel Efficiency Class**](#fuelefficiency) | A multinominal logistic regression to handle multi-value classification.                     |
| 06  | [**Handwriting Recognition**](#handwriting)  | Another multinominal logistic regression with a larger dataset.                              |

## <a name="plinko"></a> 1) Plinko

A quick introduction to K-Nearest Neighbors (KNN) algorithm using Lodash.

[See 01-plinko folder](01-plinko)

<p align="center">
    <a href="01-plinko">
        <img src="01-plinko/screenshot.png">
    </a>
</p>

### Features

- implementing K-Nearest Neighbors (KNN) algorithm with Lodash methods.
- testing the algorithm and interpreting bad results.
- creating random test and training datasets.
- generalizing KNN, gauging accuracy and printing a report.
- investigating optimal k values.
- updating KNN for multiple features.
- applying normalization with MinMax.
- handling objective feature selection with KNN.

## <a name="housepricings"></a> 2) House Pricings

Another implementation of K-Nearest Neighbors (KNN) algorithm with Tensorflow.js.

[See 02-house-pricings folder](02-house-pricings)

### Features

- loading CSV data.
- running K-Nearest Neighbors (KNN) algorithm with Tensorflow.js.
- analyzing results and reporting error percentages.
- applying standardization.
- debugging calculations with node --inspect-brk and Chrome debugger.
- adding features to get a better accuracy.

## <a name="gasmileage"></a> 3) Gas Mileage Calculator

A gradient descent algorithm in linear regression using Tensorflow.js.

[See 03-gas-mileage-calculator folder](03-gas-mileage-calculator)

<p align="center">
    <a href="03-gas-mileage-calculator">
        <img src="03-gas-mileage-calculator/screenshot.png">
    </a>
</p>

### Features

- loading CSV data and creating a LinearRegression class.
- creating a basic gradient descent implementation with arrays of data and for loops.
- calculating mean squared error (MSE) slopes, updating coefficients and interpreting results.
- understanding matrix multiplication.
- vectorizing the gradient descent algorithm with Tensorflow.js helpers.
- gauging model accuracy by implementing the coefficient of determination.
- applying standardization and massaging learning rates.
- refactoring for multivariate regression.
- tracking MSE history to update learning rate automatically.
- plotting MSE history with nodeplotlib.
- refactoring towards batch and stochastic gradient descent for better performances.
- making predictions with the model.

## <a name="smogtest"></a> 4) Smog Test

A gradient descent algorithm in logistic regression to handle natural binary classification.

[See 04-smog-test folder](04-smog-test)

<p align="center">
    <a href="04-smog-test">
        <img src="04-smog-test/screenshot.png">
    </a>
</p>

### Features

- updating linear regression for logistic regression by adding the sigmoid equation.
- implementing a test function to gauge classification accuracy.
- supporting variable decision boundaries.
- refactoring with cross entropy to update learning rate.
- plotting cost history with nodeplotlib.

## <a name="fuelefficiency"></a> 5) Fuel Efficiency Class

A multinominal logistic regression to handle multi-value classification.

[See 05-fuel-efficiency folder](05-fuel-efficiency)

### Features

- refactoring to multi-column weights.
- classifying continuous values in 3 ranges of fuel consumption: low, medium and high.
- training a multinominal model.
- handling conditional probability distribution with the softmax equation.
- implementing accuracy gauges with argMax() and calculating accurary.

## <a name="handwriting"></a> 6) Handwriting Recognition

Another multinominal logistic regression with a larger dataset.

[See 06-handwriting-recognition folder](06-handwriting-recognition)

<p align="center">
    <a href="06-handwriting-recognition">
        <img src="06-handwriting-recognition/screenshot.png">
    </a>
</p>

### Features

- flattening image data from MNIST handwritten digit database.
- encoding label values and implementing an accuracy gauge.
- debugging the calculation process with node --inspect-brk.
- dealing with zero variances.
- creating memory snapshots with Chrome debugger.
- releasing references to MNIST dataset.
- optimizing Tensorflow.js memory usage with tf.tidy().
- measuring footprint reduction.
- plotting cost history and improving model accuracy.

Based on [Machine Learning with JavaScript](https://www.udemy.com/course/machine-learning-with-javascript/) by Stephen Grider (2021).
