# Lab 5 — Clustering YouTube Comments

## Objective
Apply unsupervised learning techniques (K-Means and DBSCAN) to discover hidden patterns in cleaned YouTube comments using TF-IDF vectorization and PCA visualization.

## Dataset
- Source: `cleaned_comments.csv` (from Lab 2)
- Text column: `cleaned_tokens`

## Methods
- TF-IDF vectorization (max_features=2000)
- K-Means clustering with elbow method
- DBSCAN clustering with parameter testing
- PCA for 2D visualization

## Deliverables
- Jupyter Notebook: `notebooks/CSE477_Lab5_Comments_Clustering.ipynb`
- Lab Report (PDF): `reports/Lab_5_Report.pdf`

## Key Insight
K-Means produced interpretable thematic clusters, while DBSCAN identified sparse noise patterns due to short-text characteristics.
