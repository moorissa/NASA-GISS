# NASA Goddard Institute for Space Studies, Fall 2017

* Intern: Moorissa Tjokro (moorissa.tjokro@columbia.edu)
* Advisor: Anastasia Romanou (anastasia.romanou@columbia.edu)


## Dataset
Dataset used for this research project is a clean version of `12-month Ocean Carbon States (OCS)` dataset, which can be found in the `Data` folder.

For further information: https://data.giss.nasa.gov/oceans/carbonstates/

## Research Questions

1. Can we explore other pattern recognition techniques, ie. clustering, for classifying ocean carbon regimes based on geophysical data such as pCO2 and SST?

2. Can we cluster regimes using more than two variables, in addition to pCO2 and SST?

## Methodology

## Part 1: 2-D Clustering

### Classification Input
![](Images/2d_input.png)

### 1. K-Means Clustering
![](Images/cluster_kmeans.png)

### 2. Agglomerative / Hierarchical Clustering
![](Images/cluster_agglo.png)

### 3. Expectation-Maximization (EM) Clustering
![](Images/cluster_em.png)

## Part 2: 3-D Clustering

### Classification Input
![](Images/3d_input.png)

### 1. Per-bin Classification
![](Images/class_perbin.png)

### 2. All-bins classification
![](Images/class_allbins.png)

### 3. Scatterplots as an alternative to histograms
![](Images/3d_scatter.png)
