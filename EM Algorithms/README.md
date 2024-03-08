## Description 
This repository contains a step-by-step approach to implementing the Expectation-Maximisation algorithms for fitting KMeans clustering Gaussian mixture models(GMM). The motivation for this was to understand how a GMM model captures a wide variety of progression patterns and does not require a particular functional form and it's improvement from a Kmeans structure.

## Script contents
1. Kmeans algorithm implementation from scratch on the MNIST, FASHION MNIST and 20NG dataset using gini and purity index for cluster evaluation
2. Gaussian Mixture Models with 2 and 3 mixtures on gaussian2.txt and gaussian3.txt, which are randomly generated data and the goal was to retrieve weights, means and covariances associated with it given a random initial setup(the chicken and egg problem). 
3. A practical application of the EM algorithm to determine the biased and mixing probability of coin flips from coin_flips_outcomes.txt
