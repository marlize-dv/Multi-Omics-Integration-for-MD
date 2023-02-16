# Multi-omics integration for gene prioritization to improve the understanding of mitochondrial diseases

This is the notebook for my research project for M2 of MSc Data Science and Artificial Intelligence at the Université Côte d'Azur.

## Abstract

With the recent breakthroughs in sequencing technologies, more omics data are becoming available.
Some studies have been done on integrating different omics data to identify responsible genes.
The problem with most omics integration techniques is that when the different omics data are combined, the interactions between genes are lost.
A study using a Graph Convolution Network (GCN) showed promising results to solve this problem in an oncological application.
However, mitochondrial diseases remain neglected when it comes to multi-omics studies.
This is due to the various challenges posed by this application, which include the availability of data, the curse of dimensionality that is inherently present in omics data, and the heterogeneity of the data.
A simplistic GCN has been implemented on mitochondrial disease omics data to classify genes as pathogenic or non-pathogenic.
The model obtained an average accuracy of 83\%, and the state-of-the-art GCN obtained 89\%.
These results show that CGNs are promising methods that can be used for multi-omics integration for gene prioritization in mitochondrial diseases.
