# Kannada MNIST
## by Thu Pham


## Dataset

>  Kannada is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers and is written using the Kannada script.
>  In this project, I will develop a classifier that will be used to predict which of the 10 digits is being written

## Important Findings

- In the 1st part, I use the Random Forest Classifier, which is a set of decision trees from randomly selected subset of training set. It aggregates the votes from different decision trees to decide the final class of the test object. The algorithm that uses all variables returns the accuracy of 92% on the test set.
- In the 2nd part, I execute principal components analysis (PCA) on the combined training and test set data together, generating principal components that represent 95 percent of the variability in the explanatory variables. The number of principal components is 239. The Random Forest with PCA returns the accuracy of 89% on the test set.
- In the 3rd part, I execute PCA on only the training set as the 2nd part has a major flaw of using both training and test set. The new number of principal components is 237. The Random Forest with PCA returns the accuracy of 88% on the test set.
- In the last part, I use the K-Means, which is an iterative algorithm that tries to partition the dataset into K pre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. The K-Means returns the accuracy of 76% on the test set.


## Credits

Kaggle (https://www.kaggle.com/c/Kannada-MNIST)
