# Exploratory-Data-Analysis-and-Customer-Segmentation-for-eCommerce-Transactions
This repository contains the solution for an eCommerce transactions dataset analysis, which involves performing Exploratory Data Analysis (EDA), building a Lookalike Model, and conducting customer segmentation using clustering techniques.

## Overview

This project is an analysis of an eCommerce transactions dataset. The goal is to derive meaningful insights from customer and transaction data and build predictive models to enhance business strategies. The analysis includes:

1. **Exploratory Data Analysis (EDA)** - Understanding the dataset, identifying patterns, and deriving business insights.
2. **Lookalike Model** - Recommending similar customers based on profile and transaction history.
3. **Customer Segmentation** - Clustering customers based on their transaction behavior and profile to optimize marketing strategies.

## Steps Performed

1. **Exploratory Data Analysis (EDA)**:
   - Analyzed the dataset to uncover trends and patterns.
   - Derived key business insights to help improve customer targeting and sales strategies.

2. **Lookalike Model**:
   - Built a model that identifies similar customers based on their transaction behavior.
   - Recommended top 3 similar customers for each of the first 20 customers.

3. **Customer Segmentation**:
   - Applied KMeans clustering to segment customers into 4 groups based on their spending behavior and region.
   - Evaluated clustering quality using the Davies-Bouldin Index.

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`, `seaborn`: For data visualization.
- `scikit-learn`: For machine learning algorithms and clustering.
- `scipy`: For additional statistical methods.
