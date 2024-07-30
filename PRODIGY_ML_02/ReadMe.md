# Prodigy Internship Task 2

This repository contains the implementation of a K-means clustering algorithm to group customers of a retail store based on their purchase history.

## Implementation

1. **Import Libraries**: Import necessary libraries.
2. **Load Data**: Read the dataset from a CSV file named `Mall_Customers.csv`.
3. **Inspect Data**: Print the columns, head, and info of the dataset to understand its structure and contents.
4. **Check Missing Values**: Identify and count any missing values in the dataset.
5. **Visualize Distribution**: Bar plot and histogram to visualize the distribution in the dataset.
6. **Analyze Annual Income by Age Group**: Calculate and plot the average annual income for each age group.
7. **Analyze Spending Score by Age Group**: Calculate and plot the average spending score for each age group.
8. **Drop Irrelevant Columns**: Remove columns that are not relevant to the clustering task.
9. **Visualize Pair Plot**: Created a pair plot to visualize relationships between features.
10. **Correlation Analysis**: Visualize the correlation matrix to understand relationships between features.
11. **Feature Selection**: Select features `Annual Income (k$)` and `Spending Score (1-100)` for clustering.
12. **Scale Features**: Normalize the selected features using `StandardScaler`.
13. **Elbow Method for Optimal Clusters**: Use the elbow method to determine the optimal number of clusters by plotting the within-cluster sum of squares (WCSS) for different values of k.
14. **Train K-Means Model**: Train a K-Means clustering model with the optimal number of clusters.
15. **Predict Clusters**: Predict cluster labels for the dataset and add them as a new column.
16. **Cluster Visualization**: Create a scatter plot to visualize the clusters and their centroids.

### Dataset Link

Dataset :- https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

