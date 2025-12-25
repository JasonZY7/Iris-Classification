# Iris Species Classification

## Analysis

1. Which model is better and why?
Logistic Regression achieved 96.67% accuracy and Decision Tree achieved 93.33% accuracy. Logistic Regression is the better choice not only because of its higher accuracy, but also because it provides probabilistic outputs, has lower variance, and generalizes more reliably to new data, whereas Decision Trees tend to overfit by memorizing training patterns.

3. Which class is most often confused and why?
Versicolor and virginica are most often confused. Logistic Regression misclassified  one versicolor as virginica, while Decision Tree made two errors that one in each direction between these classes. This happens because these two species have significant overlap in all measurements, particularly in petal length and width (1.0-1.8 cm vs. 1.4-2.5 cm), while setosa is completely separable with much smaller petals.

5. One realistic idea to improve results:
Adding engineered features such as petal_area (petal length × petal width) could capture non-linear relationships between measurements that may help distinguish versicolor from virginica, hence improve the results.
