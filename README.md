# Customer Segmentation — Unsupervised Learning

An unsupervised customer segmentation pipeline using clustering algorithms to identify customer groups for targeted marketing. This project demonstrates clustering, feature scaling, and cluster evaluation techniques.

## Overview

This project covers:
- **Feature Scaling & Preprocessing**: Standardisation of customer features
- **Optimal Cluster Selection**: Elbow method and silhouette analysis
- **Clustering Algorithms**: KMeans and DBSCAN implementations
- **Cluster Evaluation**: Silhouette scores, Calinski-Harabasz index
- **Visualisation**: 2D/3D cluster visualisation for insights

## Dataset

**E-commerce Customer Behaviour Dataset**
- Customer demographics (age, income, location)
- Purchase behaviour (frequency, value, product categories)
- Engagement metrics (site visits, reviews, ratings)
- Binary target: customer segments for marketing campaigns

## Tech Stack

- **Python 3.8+**
- **scikit-learn**: Clustering algorithms and metrics
- **pandas**: Data manipulation
- **numpy**: Numerical operations
- **matplotlib & seaborn**: Cluster visualisation

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<username>/customer-segmentation.git
cd customer-segmentation
pip install -r requirements.txt
```

## Usage

Open and run the notebook:

```bash
jupyter notebook notebooks/customer_segmentation.ipynb
```

The notebook demonstrates the complete segmentation workflow, from data preparation through cluster interpretation.

## Results

The project provides:
- Optimal number of clusters via elbow method
- Silhouette and Calinski-Harabasz evaluation scores
- Customer segment profiles and characteristics
- Visualisations for business insights

## Applications

Use these customer segments for:
- Targeted marketing campaigns
- Personalised product recommendations
- Customer retention strategies
- Resource allocation

## License

MIT License — feel free to use this project for learning and reference.
