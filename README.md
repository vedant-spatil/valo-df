# Valorant Esports Players & Teams Analysis
### Data Cleaning • EDA • Earnings Analysis • K-Means Clustering • PCA Visualization

This project analyzes top Valorant esports players and teams, focusing on performance metrics, earnings, and competitive tier distribution. It applies K-Means clustering and Principal Component Analysis (PCA) to uncover meaningful patterns in player performance.

---

## Features

### 1. Dataset Loading & Preparation
- Loads `players_df` and `teams_df` from the Valorant esports dataset.
- Cleans currency fields by removing commas and converting them to integers.
- Performs null checks and dataset validation.

### 2. Exploratory Data Analysis (EDA)
- Generates summary statistics for players and teams.
- Produces visualizations such as:
  - Players vs Earnings
  - Teams vs Earnings

### 3. Feature Engineering
Features used for clustering:
- Gold  
- Silver  
- Bronze  
- S Tier  
- Earnings  

Data is standardized using `StandardScaler`.

### 4. K-Means Clustering
- Groups players into four clusters.
- Computes per-cluster averages for selected features.
- Implements a scoring system combining medal counts and normalized earnings.

### 5. PCA for Visualization
- Reduces dataset to two principal components.
- Creates a scatter plot showing cluster separation.
- Applies cluster labels for easier interpretation.

---

## Tech Stack

- Python 3
- NumPy, Pandas
- Matplotlib, Seaborn
- scikit-learn (StandardScaler, KMeans, PCA)

---
