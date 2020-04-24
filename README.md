# Machine Learning

1. [Linear regression](01-linear-regression.ipynb)
2. [Logistic regression](02-logistic-regression.ipynb)
3. [Poisson regression](03-poisson-regression.ipynb)
4. [LASSO regression](04-lasso-regression.ipynb)
5. [Ridge regression](05-ridge-regression.ipynb)
6. [Naive Bayes](06-naive-bayes.ipynb)
7. [Decision tree](07-decision-tree.ipynb)
8. [Random forest](08-random-forest.ipynb)
9. Adaboost
10. [SVM](10-svm.ipynb)
11. kNN
12. [k-means](11-k-means.ipynb)
13. [k-medoids](12-k-medoids.ipynb)
14. [Heirarchical clustering](13-heirarchical-clustering.ipynb)
15. MCL
16. [DBSCAN](15-dbscan.ipynb)
17. Affinity propagation
18. Fuzzy c-means
19. [PCA](18-pca.ipynb)
20. IDA
21. [MDS](20-mds.ipynb)
22. [t-SNE](21-tsne.ipynb)
23. [Non-negative matrix factorization](22-nmf.ipynb)
24. Probablistic PCA
25. Kernel PCA
26. ICA
27. [UMAP](27-umap.ipynb)
28. [Diffusion map]()
29. [K-fold cross validation](26-k-fold-cross-validation.ipynb)
30. MLJ

## Packages

### Distributions

* Distributions.jl

### Regression

* Lasso.jl
    * Ridge regression
    * LASSO regression
    * ElasticNet
* LARS.jl
    * Least angle regression
    * L1-regularized linear regression
* Isotonic.jl
    * Linear PAVA (fastest)
    * Pooled PAVA (slower)
    * Active Set (slowest)

### Clustering

* Clustering.jl
    * K-means
    * K-medoids
    * Affinity Propagation
    * Density-based spatial clustering of applications with noise (DBSCAN)
    * Markov Clustering Algorithm (MCL)
    * Fuzzy C-Means Clustering
    * Hierarchical Clustering
        * Single Linkage
        * Average Linkage
        * Complete Linkage
        * Ward's Linkage

### Dimensional Reduction

* MultivariateStats.jl
    * Data Whitening
    * Principal Components Analysis (PCA)
    * Canonical Correlation Analysis (CCA)
    * Classical Multidimensional Scaling (MDS)
    * Linear Discriminant Analysis (LDA)
    * Multiclass LDA
    * Independent Component Analysis (ICA), FastICA
    * Probabilistic PCA
    * Factor Analysis
    * Kernel PCA
* NMF.jl
    * Lee & Seung's Multiplicative Update (for both MSE & Divergence objectives)
    * (Naive) Projected Alternate Least Squared
    * ALS Projected Gradient Methods
    * Random Initialization
    * NNDSVD Initialization
* TSne.jl
* UMAP.jl

### Kernel Density Estimtion

* KernelDensity.jl

### Time Series Analysis

* TimeSeries.jl
