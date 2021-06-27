# Detection-of-Modified-Nucleotide-Clusters-in-Nanopore-Sequenced-RNA-Reads
### Master Thesis at the Laboratory for Bioinformatics and Computational Biology, Faculty of Electrical Engineering and Computing, University of Zagreb

### Abstract
The main goal of this thesis was to detect groups of modified nucleotides in RNA reads obtained by third generation sequencers. Reads obtained by third-generation sequencers often contain a large amount of noise. In this work, detailed analyzes of the data were performed in order to try to remove the noise and so that the data could be better understood. The related work achieved in the area of this problem is shown. Clustering was performed by various methods such as K-means, Graph Spectral Clustering and Non-negative matrix factorization. Clustering methods were tested on simulated datasets as well as on real datasets. The results are presented in tables and graphs.

## Explanation of notebooks:

- Simulated data: generating simulated data
- Kmeans: PCA and elbow method for detecting the number of clusters and Kmeans algorithm
- Non-negative matrix factorization: implementation of NMF algorithm with several iterations
- Kalman_filter: performing Kalman filter on ligand and nonligand data
- Detection_of_significant_positions: obtaining significant positions for reducing noise in data
- Graph_spectral_clustering: performing graph spectral clustering on read representations obtained with Detection_of_significant_positions
- Kmeans_with_significant_positions: PCA, elbow method and Kmeans algorithm for read reperesentations obtained with Detection_of_significant_positions

