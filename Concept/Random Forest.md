- 출처 : https://scikit-learn.org/stable/auto_examples/inspection/plot_permutation_importance.html?fbclid=IwAR1bPn1xldrpum8FWZEte0M7wPi9kE3BuFjSsyG9B4jSS5Th4oBkujEenNc
- the impurity-based feature importance of random forests suffers from being computed on statistics derived from the training dataset: the importances can be high even for features that are not predictive of the target variable, as long as the model has the capacity to use them to overfit.