# Mall-Customer-Segmentation-Data

This project applies unsupervised machine learning techniques to segment customers of a mall based on demographic and behavioral data. Customer segmentation enables businesses to identify distinct groups of customers, understand their spending behavior, and tailor marketing strategies accordingly.

The dataset used consists of 200 customers with features including age, gender, annual income, and spending score. Since no labeled outcomes exist, clustering algorithms were employed to discover inherent patterns in the data.

## Dataset

- Source: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial
- Features:
  - CustomerID: Unique identifier
  - Gender: Male/Female
  - Age: Years
  - Annual Income (k$): Estimated yearly income in thousands USD
  - Spending Score (1-100): Mall-assigned spending behavior score

## Problem Statement

Identify natural customer segments in the mall dataset using unsupervised learning methods. These segments can help tailor marketing efforts, loyalty programs, and product placement.

## Methods

- Exploratory Data Analysis (EDA): Visualized distributions, correlations, and checked for missing values and outliers.
- Feature Scaling: StandardScaler applied to numerical features for fair distance-based clustering.
- Models Used:
  - KMeans Clustering (k=5 chosen via Elbow Method)
  - Agglomerative Hierarchical Clustering (Ward linkage)
  - Principal Component Analysis (PCA) for visualization

## Results

- Both KMeans and Hierarchical Clustering produced meaningful clusters.
- Silhouette Score for KMeans was 0.408, indicating good cluster separation.
- Clusters reflected distinct customer groups differing in age, income, and spending patterns.

## Business Implications

- Target high-spending customers with premium offers.
- Engage low-spending, high-income customers with incentives.
- Design age-specific marketing campaigns.

## How to Run

1. Clone the repository.
2. Ensure you have Python 3.x installed along with required packages: pandas, numpy, matplotlib, seaborn, scikit-learn.
3. Run the Jupyter Notebook Unsupervised Algorithms in Machine Learning Final Project.ipynb to reproduce analysis and results.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Author

Nushin Anwar

## References

- [Mall Customers Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- Scikit-learn Documentation: https://scikit-learn.org/stable/
- McKinsey & Company. (2021). The Value of Personalization at Scale.
- Lecture Notes: Unsupervised Machine Learning (Course Material)

