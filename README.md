# Clustering Evaluation Project

## Overview
This project aims to evaluate the performance of different clustering algorithms on a dataset of wholesale customer data. The dataset contains information on the annual spending of various customers on different product categories.

## Objective
The main objectives of this project are as follows:
- To assess the effectiveness of different preprocessing techniques on clustering performance.
- To compare the performance of different clustering algorithms in grouping similar customers together.
- To determine the optimal number of clusters for each algorithm.

## Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository. It contains the following features:
- Fresh: annual spending on fresh products
- Milk: annual spending on milk products
- Grocery: annual spending on grocery products
- Frozen: annual spending on frozen products
- Detergents_Paper: annual spending on detergents and paper products
- Delicassen: annual spending on delicatessen products

## Preprocessing Techniques
The following preprocessing techniques are applied to the dataset before clustering:
- Normalization (MinMaxScaler)
- Standardization (StandardScaler)
- Robust Scaling (RobustScaler)
- PCA (Principal Component Analysis)
- Feature Selection (SelectKBest)
- Log Transformation
- Box-Cox Transformation
- Imputation

## Clustering Algorithms
The following clustering algorithms are evaluated in this project:
- KMeans
- Agglomerative Clustering
- DBSCAN

## Evaluation Metrics
The clustering performance is evaluated using the following metrics:
- Silhouette Score
- Calinski-Harabasz Index
- Davies-Bouldin Index

## Results
The results of the clustering evaluation are summarized in the following table:
