# K-Means Clustering on Wine Dataset
## Project Overview
This repository presents an implementation of **K-Means Clustering**, an unsupervised machine learning algorithm, applied to the **Wine dataset**. The project focuses on discovering inherent patterns and groupings within the dataset based on chemical properties of wines, without using class labels during training.

## Objectives

* Apply K-Means clustering to an unlabeled dataset
* Identify optimal number of clusters using the Elbow Method
* Analyze and visualize wine groupings based on feature similarity
* Understand the effectiveness of unsupervised learning techniques

## Dataset Description

The **Wine dataset** contains physicochemical attributes of wines, such as:
* Alcohol
* Malic acid
* Ash
* Flavanoids
* Color intensity
The dataset is commonly used for pattern recognition and clustering tasks in machine learning research.

## Methodology
1. Data loading and exploratory analysis
2. Feature scaling using StandardScaler
3. Determination of optimal clusters (Elbow Method)
4. Training the K-Means clustering model
5. Visualization of clusters and centroids
6. Interpretation of clustering results
   
## Results & Analysis
* The Elbow Method identifies an optimal number of clusters
* K-Means successfully groups wines with similar chemical compositions
* Visualizations demonstrate clear separation among clusters

## Technologies Used
* Python
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook
  
## Limitations
* K-Means requires predefining the number of clusters
* Sensitive to feature scaling and outliers
* Assumes spherical cluster shapes
 
## Conclusion
This project demonstrates the effectiveness of K-Means clustering in identifying meaningful patterns within multidimensional data. It serves as a strong foundational example of unsupervised learning applied to real-world datasets.

