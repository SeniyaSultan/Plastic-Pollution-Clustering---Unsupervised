# Plastic Pollution Clustering Analysis

## Overview
This project performs an unsupervised learning analysis on plastic pollution data from various countries. The goal is to identify clusters of countries with similar plastic pollution characteristics using geographic and pollution-related features.

## Dataset
The dataset includes metrics such as:
- Country or Administrative Area
- Area (km²)
- Coast length (km)
- Rainfall (mm/year)
- Mismanaged Plastic Waste (MPW) in metric tons/year
- Estimated Plastic entering the Ocean (M[E]) in metric tons/year

## Objectives
- Clean and preprocess the data by removing formatting artifacts (e.g., apostrophes, commas) and converting data to numeric.
- Scale features to standardize the range for clustering.
- Apply KMeans clustering to group countries based on plastic pollution metrics.
- Optionally compare clustering results with supervised classification labels.
- Identify the key features that drive the cluster formation.

## Methodology
1. **Data Cleaning**: Remove non-numeric characters, handle missing values.
2. **Feature Selection**: Use relevant features that reflect geographic and pollution factors.
3. **Feature Scaling**: Standardize features using `StandardScaler`.
4. **Clustering**: Use KMeans algorithm to create clusters.
5. **Analysis**: Compare clusters to known pollution categories (if available) and analyze feature importance.

## Usage
- Run the notebook/script in an environment with Python and the required libraries installed (`pandas`, `scikit-learn`, etc.).
- Modify the file path or data source as necessary.
- Follow the notebook cells to preprocess data, run clustering, and analyze results.

## Libraries Used
- pandas
- numpy
- scikit-learn

## Results
- Countries are grouped into clusters representing different levels or types of plastic pollution contribution.
- Insights into the most influential features driving the clusters.

## Author
Seniya Sultan 



