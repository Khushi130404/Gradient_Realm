# Gradient_Realm

Gradient_Realm is a Python-based project that implements various regression techniques and optimization methods using both scikit-learn and custom implementations. The goal is to explore and compare methods such as Regularization techniques, Batch Gradient Descent, Stochastic Gradient Descent, and Mini-batch Gradient Descent, offering a hands-on understanding of their working principles.

## Gradient Descent Methods :-
- Batch Gradient Descent : Processes the entire dataset for each gradient update.
- Stochastic Gradient Descent (SGD) : Updates gradients using one sample at a time.
- Mini-batch Gradient Descent : Combines the efficiency of Batch and Stochastic methods by processing small random batches of data.

Implemented both via scikit-learn and manually.
Implementation with visualization & animations.

## Used Libraries :-
1. Batch Gradient Descent:
- Custom class: BatchGradientDescent
- Scikit-learn: Implemented via LinearRegression.

2. Stochastic Gradient Descent (SGD):
- Custom class: StochasticGradientDescent
- Scikit-learn: Implemented via SGDRegressor.

3. Mini-batch Gradient Descent:
- Custom class: MiniBatchGradientDescent
- Scikit-learn: Custom implementation using batched inputs.

