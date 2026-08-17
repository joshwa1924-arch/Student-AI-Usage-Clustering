# Student AI Assistant Usage Clustering

## Overview

This project analyses student interactions with AI assistants and identifies different usage patterns using unsupervised machine learning.

The study uses Hierarchical Clustering and K-Means Clustering to discover natural groups of students based on their AI usage behaviour.

## Objective

The main objective is to identify different types of AI assistant users based on:

- Session duration
- Number of prompts
- AI assistance level
- Task type
- Satisfaction rating

## Methodology

The project follows these steps:

1. Data Cleaning
2. Missing Value Handling
3. Categorical Encoding
4. Feature Selection
5. Feature Scaling
6. Hierarchical Clustering
7. Dendrogram Analysis
8. Elbow Method
9. Silhouette Score Analysis
10. K-Means Clustering
11. PCA Visualization
12. Cluster Profiling

## Models Used

- Hierarchical Clustering
- K-Means Clustering

## Results

The analysis identified three meaningful student behaviour groups.

### Cluster 0 – Support-Seekers

Students who rely heavily on AI assistance and report high satisfaction.

### Cluster 1 – Deep Explorers

Students who spend more time with the AI assistant, ask more prompts and interact deeply with the system.

### Cluster 2 – Light Users

Students who use the AI assistant less frequently, require less assistance and report lower satisfaction.

## Key Findings

The dendrogram and Elbow Method suggested 3 clusters. Although the Silhouette Score was highest for k = 2, k = 3 was selected because it provided more meaningful behavioural segmentation while maintaining an acceptable silhouette score.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Hierarchical Clustering
- K-Means
- PCA

## Conclusion

The project demonstrates how unsupervised learning can be used to identify hidden patterns in student AI assistant usage when predefined labels are not available.
