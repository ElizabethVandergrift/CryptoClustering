# CryptoClustering

## Overview

In this project, we use Python and unsupervised learning techniques to analyze and cluster cryptocurrencies based on their 24-hour and 7-day price changes. By applying clustering algorithms and Principal Component Analysis (PCA), we explore whether reducing the number of features impacts the clustering results.

## Project Structure

- **Crypto_Clustering.ipynb**: The main Jupyter Notebook containing all the code and analysis.
- **crypto_market_data.csv**: The dataset used for clustering the cryptocurrencies.
- **README.md**: This file, providing an overview and instructions for the project.

## Results
![Original Data Elbow Plot](https://github.com/user-attachments/assets/83eddb0e-5add-4c2a-aa82-670293429ee2)

![PCA Elbow Plot](https://github.com/user-attachments/assets/8c298e07-9878-4702-ae75-2b56bd5dc9c9)

![Original versus PCA Clusters Results](https://github.com/user-attachments/assets/faf25ae2-67c9-4283-9ce6-cc2b7ebca54f)

## Impact of Using Fewer Features in Clustering

When using fewer features (via PCA) to cluster the data: 

**Simplicity:** The clusters are more distinct and easier to interpret due to reduced dimensionality.

**Potential Loss of Information:** Some nuances in the data could be lost, leading to slightly different cluster boundaries or even misclassification.

**Computational Efficiency:** PCA reduces the complexity, making clustering faster and less resource-intensive.

**The visual comparison of clusters reflect these trade-offs, showing that the PCA-transformed data clusters overlap more but also have a few spread out clusters.**

### Prerequisites

To run this project, you'll need to have Python 3.x installed along with the following libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `hvPlot`
- `HoloViews`
- `matplotlib`

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn hvplot holoviews matplotlib
