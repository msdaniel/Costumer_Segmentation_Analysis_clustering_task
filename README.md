# Costumer_Segmentation_Analysis_clustering_task

# Customer Segmentation Analysis on Wholesale Customer Dataset Using K-Means and Gaussian Mixture Clustering Algorithms

## 1. Introduction

Customer Segmentation analysis is a technique for categorizing subdivisions of a market into discrete customer groups that share similar characteristics. This report explores the application of machine learning clustering algorithms, specifically K-Means and Gaussian Mixture, to identify different groups of customers with similar spending behavior.

### 1.1 Motivation

Understanding customer segments is crucial for businesses to tailor their marketing strategies, personalize customer experiences, and optimize resource allocation.

### 1.2 Methodology

The clustering machine learning analysis in this report focuses on finding natural clusters in the customer wholesale dataset based on the principle that items within the same cluster must be similar to each other.

## 2. Datasets

The project utilizes the customer wholesale dataset publicly available on the [UCI Machine Learning Repository] https://archive.ics.uci.edu/dataset/292/wholesale+customers . The dataset consists of 440 rows representing customer annual spending in monetary units across eight columns. These columns include 'Channel', 'Region', and six other columns as product names, each representing annual spending on specific products.

### 2.1 Data Details

- All columns in the original dataset are numerical.
- The 'Channel' and 'Region' columns are of nominal scale of measurement.
- No missing values are present, and there are no duplicated rows of customer spending.
- The 'Channel' column has two unique values: Retail and Horeca (Hotel, Restaurant, and Cafe) with value counts of 142 and 298, respectively.

## 3. Implementation

The clustering analysis is implemented using K-Means and Gaussian Mixture clustering algorithms. The code and detailed analysis can be found in the corresponding code file.

### 3.1 Dependencies

Ensure you have the following dependencies installed before running the code:

- Python 3.x
- Pandas
- Scikit-learn
