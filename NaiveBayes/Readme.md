# Naive Bayes Classifier
The naive bayes algorithms are a family of algorithms based on the Bayesian Probability theory. These are classifier algorithms used to solve classification problems.
- The key reason they are named Naive is due to their assumption that all atrribute pairs are independant of each other.
- This implies that all attributes contribute to the prediction to be made.
- The naive bayes algorithm is used for classification because they are very fast and can manage highly dimensional data. This is because they work with text classification where every word becomes an attribute due to the assumption of independance.
- Naive bayes gives the probability of of an attribute belonging to a class as an output.
 The Naive bayes algorithm works with the dataset by divind it into **Feature Matrix** and **Response Vector**. The feature mtrix consists of all the row vectors (rows) of the given dataset while the response vector has the prediction or the result classes of the classification performed.<br>
 The Naive Bayes algorithm takes a few assumptions before proceeding withthe processing. These assumptions are :<br>
 - All attributes are independant
 - Continuous features are normally distributions.
 - Discrete features are multinomial distributions.
 - Features are equally important.
 - There is no missing data in the provided dataset.
 There are three types of Bayesian Classifiers:
 1. Gaussian Naive Bayes
 2. Multinomial Naive Bayes
 3. Bernoulli Naive Bayes