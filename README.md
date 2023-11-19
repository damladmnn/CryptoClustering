
# CryptoClustering

CryptoClustering is a project that utilizes Python and unsupervised learning techniques, specifically K-Means clustering and Principal Component Analysis (PCA), to predict and analyze the impact of 24-hour or 7-day price changes on cryptocurrencies.

## Project Overview

The project involves the following key steps:

1. **Data Loading and Preparation**: Loading cryptocurrency market data from a CSV file and preparing the data for analysis.

2. **Feature Scaling**: Normalizing the data using the StandardScaler module from scikit-learn to ensure consistent scaling across features.

3. **Original Data Clustering**: Applying K-Means clustering to the original scaled data to identify clusters of cryptocurrencies based on price change patterns.

4. **PCA and Clustering**: Utilizing Principal Component Analysis (PCA) to reduce the dimensionality of the data and applying K-Means clustering to the PCA-transformed data.

5. **Visualizations and Analysis**: Creating visualizations, including elbow curves and scatter plots, to analyze and compare clustering results between the original data and PCA data.

## Files and Structure

- `Crypto_Clustering.ipynb`: Jupyter Notebook containing the Python code for the project.
- `crypto_market_data.csv`: CSV file with cryptocurrency market data.

## Instructions

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Run the Jupyter Notebook**: Open and run the `Crypto_Clustering.ipynb` Jupyter Notebook to execute the code and perform the analysis.

3. **Explore Results**: Examine the visualizations and analysis results provided in the notebook to understand the clustering of cryptocurrencies.

## Dependencies

Ensure you have the following Python libraries installed:

- pandas
- hvplot
- scikit-learn

Install dependencies using:

```bash
pip install pandas hvplot scikit-learn
