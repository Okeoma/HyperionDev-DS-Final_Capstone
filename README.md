# HyperionDev-DS-Final_Capstone_PCA_Clustering
This is the final capstone of the HyperionDev Data Science bootcamp programme. This final project was on the application of Unsupervised Machine Learning (Clustering) techniques on a US arrest dataset containing three major crimes of Murder, Assault, and Rape per a thousand residents with their Urban population in percentage during a statistic done in 1973 for each of the 50 states in the US.

### Description
The project used the application of two clustering techniques; Hierarchical also known as Agglomerative clustering and K-means clustering to analyze the USArrest dataset in the grouping of states according to the degree of crime (either high crime zone or low crime zone). 

This project is important because it shows how to look at a problem in a simplified form especially when there are a lot of features in a dataset thereby making it difficult to manually check and select the most impactful features that are required for further analysis. This is why a reduction analysis was introduced in the process. Although the dataset used did not have a lot of columns (only five), it was only for demonstration of the process of feature reduction.

Before the clustering models was applied on the dataset, a technique used for feature reduction, Principal Component Analysis (PCA) was applied to reduce the features to two instead of the initial four to ease the process of the machine learning application. The two selected features that showed the most positive impact on the dataset after the PCA and other exploratory analysis was carried out was ‘Murder’ and ‘Assault’. These two features were further explored using the two selected clustering techniques, and the results gotten from their analysis was a representation of the full dataset.  

