# SCT_ML_2
# Customer Segmentation using K-Means Clustering

This repository provides a Python implementation of K-Means clustering for segmenting retail store customers based on their purchase behavior. The algorithm groups customers into clusters using features such as Annual Income and Spending Score, enabling data-driven decision-making for marketing strategies.



## Features

- **Interactive Analysis**: Dynamically determine the optimal number of clusters using the Elbow Method.
- **Visualization**: Generates 2D scatter plots of clusters and centroids for intuitive understanding of customer segments.
- **Scalable**: Designed to handle datasets with multiple numerical features efficiently.



## Dataset

The dataset used for this implementation is `Mall_Customers.csv`, which contains the following attributes:

- `CustomerID`: Unique identifier for each customer.
- `Gender`: Gender of the customer.
- `Age`: Age of the customer.
- `Annual Income (k$)`: Annual income in thousands of dollars.
- `Spending Score (1-100)`: A score assigned based on spending behavior and purchasing patterns.



## Results

The script produces the following outputs:

1. **Clustered Data**:
   - The dataset with an additional column indicating the cluster each customer belongs to.

2. **Cluster Visualization**:
   - A scatter plot illustrating customer clusters and their centroids (for 2D features).

3. **Exported Data**:
   - Clustered data is saved as a CSV file (`Clustered_Customers.csv`) in the project directory.




## Acknowledgments

- The dataset is publicly available and used for educational purposes.
- Built using the `scikit-learn`, `matplotlib`, and `seaborn` libraries.


