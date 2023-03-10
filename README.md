# Challenge Problem 4

## Deadline: March 3, 2023 by midnight

Note: While high-level discussion is allowed and encouraged for the challenge problems, these problems should be completed and submitted individually.

### Description

Explore various Naive Bayes Algorithms in the given Colab notebook. Then, answer the following questions.

### Part 1: Gaussian Naive Bayes

1.   Give 1-2 sentence description of the distribution assumed in this algorithm.

Gaussian Naive Bayes follows a Guassian distribution pattern. This algorithm also supports continuous valued features.
Source : https://iq.opengenus.org/gaussian-naive-bayes/ 

2.   Provide your observations on the performance of this algorithm on the wine data (comparisons with other algorithms below are encouraged).

 Compared to the other algorithms Guassian Naive Bayes is the most accurate at just over 94%. Additionally, when compared to the other algorithms the precision score is the highest too. The f1-score of this algorithm is overall the highest.

### Part 2: Multinomial Naive Bayes

1.   Give 1-2 sentence description of the distribution assumed in this algorithm.

The Multinomial Naive Bayes algorithm is based on the Naive Bayes algorithm but is used for multinomially distributed data. This distribution utilizes vectors for each class.
Source: https://scikit-learn.org/stable/modules/naive_bayes.html

2.   Provide your observations on the performance of this algorithm on the wine data (comparisons with bayes algorithms below are encouraged).

Based on the performance analysis the performance of this algorithm is not as good as the Guassian Naive Bayes algorithm. The accuracy of this algorithm is much lower and the precision has a wide variety between 59%-92%.

### Part 3: Complement Naive Bayes

1.   Give 1-2 sentence description of the distribution assumed in this algorithm.

The Complement Naive Bayes algorithm goes a step further than the Multinomial Naive Bayes algorithm with the ability to adapt to imbalanced data sets.
Source: https://scikit-learn.org/stable/modules/naive_bayes.html

2.   Provide your observations on the performance of this algorithm on the wine data (comparisons with bayes algorithms below are encouraged).

Based on the confusion matrix of this algorithm compared to the other algorithms this came up with relatively more false postives. The accuracy was also not the greatest and seems to go down as these algorithms get further from the original Guassian Naive Bayes algorithm. 

### Part 4: Bernoulli Naive Bayes

1.   Give 1-2 sentence description of the distribution assumed in this algorithm.

This algorithm uses the naive Bayes training and classification techniques but assumes the data to be binary-valued and distributes it according to multivariate Bernoulli distributions.
Source: https://scikit-learn.org/stable/modules/naive_bayes.html

2.   Provide your observations on the performance of this algorithm on the wine data (comparisons with bayes algorithms below are encouraged).

This Bernoulli Naive Bayes algorithm has the lowest scores out of all the algorithms we have looked at so far. The confusion matrix shows that it was wrong more times than it was right. The accuracy is very low at 44% and the f1-score is the lowest we have seen. 
