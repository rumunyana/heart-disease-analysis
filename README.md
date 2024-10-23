# Heart-disease-analysis

## Project Overview

This project analyzes medical records to identify patients at high risk of developing heart disease using various unsupervised learning techniques. The analysis uses the UCI Heart Disease dataset containing 303 patient records with 14 attributes.

## Dataset Description

The dataset includes key medical attributes:

Age
Sex
Chest pain type
Blood pressure
Serum cholesterol
Target variable (presence/absence of heart disease)

## Analysis Pipeline

## Data Preprocessing

Dataset loaded and cleaned for missing values
Features scaled using StandardScaler
Categorical variables encoded appropriately

## Clustering Techniques Applied

K-means clustering with elbow method optimization
Hierarchical clustering with dendrogram analysis
DBSCAN clustering with parameter tuning
Gaussian Mixture Models (GMM)

## Dimensionality Reduction and Visualization

PCA implementation for feature reduction
t-SNE visualization of cluster patterns
Visual analysis of cluster formations

## Performance Evaluation
# Metrics Used
Silhouette Score
Davies-Bouldin Index

## Best Performing Algorithm

K-means clustering emerged as the most effective algorithm due to:

Higher silhouette score
Better cluster separation
More interpretable results
Computational efficiency

## Key Findings

Distinct patient groups identified based on medical attributes
Strong correlation between chest pain type and heart disease risk
Age and blood pressure showed significant clustering patterns

## Dependencies

Python 3.x
scikit-learn
pandas
numpy
matplotlib
seaborn

## Usage Instructions

Install required dependencies
Load the dataset
Run the Jupyter notebook
Analyze results and visualizations

## Future Improvements

Feature engineering for better cluster separation
Implementation of additional clustering algorithms
Integration of supervised learning techniques
Real-time prediction system development
