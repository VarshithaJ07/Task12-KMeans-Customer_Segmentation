
# Customer Segmentation using K-Means Clustering

##  Overview
This task focuses on customer segmentation using the K-Means clustering algorithm.  
K-Means is an unsupervised machine learning technique used to group customers based on similar characteristics.  
The objective of this project is to segment mall customers based on their Annual Income and Spending Score.

## Dataset
Dataset Name: Mall Customer Segmentation Dataset  
Source: Kaggle  

The dataset contains the following columns:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

Note: There is no target variable because K-Means is an unsupervised learning algorithm.

## Algorithm Used
K-Means Clustering

K-Means works by grouping data points into K clusters such that the distance between data points and their respective cluster centers is minimized.

## Steps Followed
1. Imported required Python libraries  
2. Loaded and explored the dataset  
3. Selected relevant features for clustering  
4. Scaled features using StandardScaler  
5. Applied the Elbow Method to find the optimal number of clusters  
6. Trained the K-Means model  
7. Assigned cluster labels to customers  
8. Visualized the clusters  
9. Saved the final segmented dataset  

## Elbow Method
The Elbow Method is used to determine the optimal number of clusters (K).  
K values from 1 to 10 are tested and inertia values are calculated.  
The value of K at which inertia decreases sharply is selected as the optimal K.

## Results
The optimal number of clusters selected is K = 5.  
Each customer is assigned a cluster label representing their segment.

## Cluster Interpretation
Cluster 0: Average income, average spending customers  
Cluster 1: High income, high spending customers (Target customers)  
Cluster 2: Low income, high spending customers  
Cluster 3: High income, low spending customers  
Cluster 4: Low income, low spending customers  

## Output
The final dataset is saved as:
segmented_customers.csv

## Technologies Used
Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Scikit-learn  

## Conclusion
This task demonstrates how K-Means clustering can be used to identify meaningful customer segments.  
The results can help businesses understand customer behavior and improve marketing strategies.

 
