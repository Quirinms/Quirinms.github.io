

# Benchmarking Cluster Analysis Methods 

The following 27 Clustering algorithms will be evaluated here on sevel datasets of the Fundamental Clustering Problem Suite (FCPS) and additional high-dimensional data sets. The project is finished and the research is published in [[Thrun/Ultsch, 2020]](#1). 
 

100 trials per algorithm and data set are calculated. All datasets have uniquely unambiguously defined class labels defined by domain experts or artificially. The error rate is defined as 1-Accuracy (Eq. 3.1 on p. 29 [Thrun, 2018]) was is used as a sum over all true positive labeled data points by the clustering algorithm. The best of all permutation of labels of the clustering algorithm regarding the accuracy was chosen in every trial, because the labels are arbitrarily defined by the algorithms. The following clustering algorithms are used:


* Batch Self-Organizing Map (batchSOM) Clustering [Wehrens/Buydens, 2007]
* ADP Clustering (Clustering by fast search and find of density peaks) [Rodriguez/Laio, 2014]
* Affinity Propagation (AP) Clustering [Frey/Dueck, 2007]
* Databionic swarm (DBS) [Thrun, M. C., 2018] 
* DBscan [Ester et al., 1996]
* Fuzzy Clustering (Fanny) [Rousseeuw/Kaufman, 1990] 
* Markov Clustering [Van Dongen, 2000]
* Model-based Clustering (Mixture of Gaussians - MoG) [Fraley/Raftery, 2002, 2006]
* Spectral Clustering [Ng et al., 2002]
* Quality clustering (QT) clustering) [Heyer et al., 1999; Scharl/Leisch, 2006]
* Self-organizing Tree Algorithm (SOTA) [Herrero et al., 2001]
* Large Application Clustering (CLARA) Rousseeuw/Kaufman, 1990]




## References
<a id="1">[Thrun/Ultsch, 2020]</a> 
Thrun, M. C., & Ultsch, A.: Using Projection-Based Clustering to Find Distance- and Density-Based Clusters in High-Dimensional Data,
Journal of Classification, Springer, 2020.

