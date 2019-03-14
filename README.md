# Leaf-Classification

This project was done as part of the Data Mining and Mahchine Learning course at Utah State University. We were to pick a public dataset and run appropriate analyses on it. I picked a [dataset](https://archive.ics.uci.edu/ml/datasets/Leaf#) about leaf classification from the UCI data repository. The data set is a set of 16 features of the leaves of 30 different plant species. The features were extracted from digital images of each leaf specimen. The original data set contains data for 40 species with both simple and complex leaves, but here I only used those with simple leaves. I tried to find the best classifier for leaf species.

Since this was an intro course into machine learning and the objective was to pick the best classifier, I used a bunch of different classifiers including, Discriminant Analysis, k-Nearest Neighbors with between 7 and 2 neighbors, classification trees, and random forests. I used SAS for everything except the random forests, which I did in R.

In the end, the best classifier I found was k-Nearest Neighbors with 2 neighbors. I will include the final write-up I did explaining the results from the other methods.


Data Citation:
'Evaluation of Features for Leaf Discrimination', Pedro F.B. Silva, Andre R.S. Marcal, Rubim M. Almeida da Silva (2013). Springer Lecture Notes in Computer Science, Vol. 7950, 197-204.
