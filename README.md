# Machine Learning

## Supervised Learning

### Regression

1. [Linear regression](regression/linear-regression.ipynb)
2. [Poisson regression](regression/poisson-regression.ipynb)
3. [LASSO regression](regression/lasso-regression.ipynb)
4. [Ridge regression](regression/ridge-regression.ipynb)
5. [Polynomial regression](regression/polynomial-regression.ipynb)

### Classification

7. [Logistic regression](classification/logistic-regression.ipynb)
8. [Naive Bayes](classification/naive-bayes.ipynb)
9. [Decision tree](classification/decision-tree.ipynb)
10. [Random forest](classification/random-forest.ipynb)
11. Adaboost
12. [SVM](classification/svm.ipynb)
13. [kNN](classification/knn.ipynb)

### Clustering

13. [k-means](clustering/k-means.ipynb)
14. [k-medoids](clustering/k-medoids.ipynb)
15. [Heirarchical clustering](clustering/heirarchical-clustering.ipynb)
16. MCL
17. [DBSCAN](clustering/dbscan.ipynb)
18. Affinity propagation
19. Fuzzy c-means

### Dimensional reduction

20. [PCA](dimensional-reduction/pca.ipynb)
21. LDA
22. [MDS](dimensional-reduction/mds.ipynb)
23. t-SNE
24. [Non-negative matrix factorization](dimensional-reduction/nmf.ipynb)
25. Probablistic PCA
26. Kernel PCA
27. ICA
28. [UMAP](dimensional-reduction/umap.ipynb)
29. Diffusion map

### Validation

30. [K-fold cross validation](k-fold-cross-validation.ipynb)

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
