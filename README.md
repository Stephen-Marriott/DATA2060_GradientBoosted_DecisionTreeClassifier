# DATA2060_GradientBoosted_DecisionTreeClassifier

Gradient boosting is an ensemble learning technique, which sequentially combines many weak learners into a single strong learner. Fundamentally, each individual weak learner corrects upon the predictions made by the previous iteration. 

In this final project for DATA2060, we implemented a gradient-boosted decision tree binary classifier from scratch, and directly compared it to the implementation built into scikit learn, using the Hastie dataset. The underlying weak learner was a decision tree regressor, also built from scratch.

## Main Packages:
    - Python: 3.12.4
    - numpy: 1.26.4
    - matplotlib: 3.8.4
    - scikit-learn: 1.4.2