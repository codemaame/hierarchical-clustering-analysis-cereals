# Cereal Hierarchical Clustering Analysis

This project applies hierarchical clustering to a dataset of 77 breakfast cereals to identify groups with similar nutritional profiles. The goal is to explore the structure of the data and to identify a cluster of “healthy” cereals that could be used for school menu planning.

## Dataset

- **Cereals.csv** contains nutritional information, display shelf, and consumer ratings for breakfast cereals.
- Categorical variables were removed and numeric features were scaled before clustering.

## Methods

- Hierarchical clustering using **Euclidean distance**
- Comparison of **single linkage** and **complete linkage** dendrograms
- Selection of a cutoff distance to determine the number of clusters
- Computation of **cluster centroids** (cluster profiles)
- Identification of the cluster representing the healthiest cereals based on nutrition variables (e.g., calories, sugar, fat, fiber, protein)

## Files in this Repository

- `Hierarchical_Clustering_Cereals.ipynb` — Jupyter notebook with the full analysis  
- `Cereals.csv` — Dataset used in the analysis  

## How to Run

1. Open the notebook `Hierarchical_Clustering_Cereals.ipynb` in Jupyter or Google Colab.
2. Make sure `Cereals.csv` is in the same directory.
3. Run the notebook from top to bottom to reproduce the analysis and results.

## Key Outcome

The analysis identifies distinct clusters of cereals and selects a “healthiest” cluster based on nutritional profiles. It also examines cluster sizes and discusses practical constraints, such as covering multiple school days with a limited number of healthy options.
