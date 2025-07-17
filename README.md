# SCT_ML_02
Customer segmentation is a powerful technique to group customers with similar behaviors or characteristics. In this project, KMeans clustering is used to segment retail customers based on their annual income and spending score. By identifying distinct customer groups, businesses can tailor their marketing and sales strategies more effectively.

## Dataset

- **Source:** Mall Customer Dataset (commonly found on Kaggle)
- **Sample Features:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## Project Workflow

1. **Importing Libraries:**  
   Essential libraries for data manipulation, visualization, and clustering (pandas, numpy, matplotlib, seaborn, scikit-learn).

2. **Loading Data:**  
   Read customer data from `Mall_Customers.csv`.

3. **Exploratory Data Analysis (EDA):**
   - View first few rows and dataset shape.
   - Check for missing values and data types.

4. **Feature Selection:**  
   Select `Annual Income (k$)` and `Spending Score (1-100)` as features for clustering.

5. **Choosing the Number of Clusters:**  
   Use the Within-Cluster Sum of Squares (WCSS) and the Elbow Method to determine the optimal number of clusters (typically 5).

6. **KMeans Clustering:**  
   Train the KMeans model and assign cluster labels to customers.

7. **Visualization:**  
   Plot the Elbow graph and visualize the resulting clusters.

## Key Features

- Clean and documented end-to-end segmentation workflow
- Optimal cluster selection using the Elbow Method
- Easy-to-follow code for beginners and intermediate data scientists
- Insightful visualizations for better understanding of segments
