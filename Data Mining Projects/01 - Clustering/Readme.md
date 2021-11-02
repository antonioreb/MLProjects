# Clustering Project

This project was made in the context of the Data Mining course (2020) of Lisbon University. 

The dataset to be analysed is medulloblastoma_genes.csv. It includes 76 samples of medulloblastoma (MB) with respective expression levels of 54.675 genes measured in children with ages between 3 and 16 years. Medulloblastoma is a malignant childhood brain tumour comprising four discrete subgroups.

In this project we will consider the labels of the samples included in the labels.csv file where samples are labelled as MB-CL or Other. In this case, we have 51 samples of classic medulloblastoma (MB-CL) and 25 other types (namely: 6 desmoplastic nodular, 17 anaplastic and 2 medullomyoblastoma).

The goal is to cluster the data with and without ground-truth and analyze the results to see if we're able to differentiate between the different groups.

This project has several phases:

1. Create dimensionaly reduced versions of the dataset using variance filtering and PCA
2. Cluster data using Partitional Clustering
   - explore different hyper-parameters
   - evaluate and compare results (Silhouette Score, etc..)
3. Cluster data using Hierarchical Clustering
4. Evaluate clustering results
      - with ground truth
      - without ground truth

5. Cluster using Density-based Clustering
6. Final Conclusions




