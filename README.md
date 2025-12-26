What Are Boosting Algorithms and What Do They Do?

Boosting is an ensemble learning approach where models are built sequentially — and each new model focuses on improving the errors made by previous ones.

Rather than training trees independently (like Random Forest), boosting:

emphasizes misclassified samples

reduces bias stage-by-stage

improves generalization through controlled learning

The module focused on three core boosting methods:

🔹 AdaBoost (Adaptive Boosting)
Reweights misclassified samples so later learners focus on harder cases.

🔹 Gradient Boosting
Builds trees by minimizing a loss function using gradient descent.

🔹 XGBoost (Extreme Gradient Boosting)
An optimized and regularized version of Gradient Boosting with:

faster training

better handling of overfitting

improved performance on tabular data

Each algorithm revealed different trade-offs in learning speed, bias-variance behavior, and robustness.

✔ Advantages of Boosting

Delivers strong predictive accuracy

Handles complex non-linear relationships

Reduces bias while maintaining controlled variance

Performs well on structured/tabular datasets

Works across both classification and regression tasks

✘ Disadvantages of Boosting

Can overfit without proper regularization

Requires careful tuning of learning rate & estimators

More computationally expensive than simpler models

Less interpretable than shallow trees
