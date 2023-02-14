# HyperionDev-DS-Final_Capstone_PCA_Clustering
This is the final capstone of the HyperionDev Data Science bootcamp programme. This final project was on the application of Unsupervised Machine Learning (Clustering) techniques on a US arrest dataset containing three major crimes of Murder, Assault, and Rape per a thousand residents with their Urban population in percentage during a statistic done in 1973 for each of the 50 states in the US.

### Description
The project used the application of two clustering techniques; Hierarchical also known as Agglomerative clustering and K-means clustering to analyze the USArrest dataset in the grouping of states according to the degree of crime (either high crime zone or low crime zone). 

This project is important because it shows how to look at a problem in a simplified form especially when there are a lot of features in a dataset thereby making it difficult to manually check and select the most impactful features that are required for further analysis. This is why a reduction analysis was introduced in the process. Although the dataset used did not have a lot of columns (only five), it was only for demonstration of the process of feature reduction.

Before the clustering models was applied on the dataset, a technique used for feature reduction, Principal Component Analysis (PCA) was applied to reduce the features to two instead of the initial four to ease the process of the machine learning application. The two selected features that showed the most positive impact on the dataset after the PCA and other exploratory analysis was carried out was ‘Murder’ and ‘Assault’. These two features were further explored using the two selected clustering techniques, and the results gotten from their analysis was a representation of the full dataset.  

## Table of Contents

- [Dataset](#Dataset)
- [Goals of Analysis](#Goals of Analysis)
- [Installation](#installation)
- [Testing](#testing)
- [Deployment](#deployment)
- [System Architecture](#system-architecture)
- [System Requirements Specification](#system-requirements-specification)
- [Security](#security)
- [Wireframes](#wireframes)
- [Usage](#usage)
- [Credits](#credits)

## Dataset

The USArrest.csv dataset contains statistics, in arrest per 100,000 residents for assault, murder and rape in each of the 50 US States in 1973. The percentage of the population living in urban areas is also given.

## Goals of Analysis
**The aim of the Analysis are as follows:**

- To explore the dataset in order to gain insights on the relationships between the features of the dataset and draw inferences.
- To investigate the impact of each individual feature in the dataset using PCA to understand it's impact and to decide if it should be dropped or be used for further analysis.
- Apply two major Unsupervised Machine Learning methods/ Clustering technigues (Agglomerative and K-means) on the selected features to give a clearer picture of the crime rates in the states using the most effective parameters and group them according to crime zones; high or low.
- Finally, compare the two Clustering methods used to see their similarities and differences.
