NAME : Mohit Singh Rautela

Domain : DATA ANALYTICS

Duration : JULY 5th, 2024 to AUGUST 5th, 2024

Company :  CODTECH IT SOLUTIONS 

ID : CT08DS4126

Mentor :  Neela Santhosh Kumar 


Overview Of The Project 

Objective

The objective of this project is to perform customer segmentation and analysis on a retail dataset to identify distinct customer segments based on their purchasing behavior and demographic characteristics. By segmenting customers into distinct groups, businesses can tailor marketing strategies, improve customer service, and optimize product offerings to better meet the needs of different customer segments.

Key Activities

Data Loading and Preprocessing:

Data Loading: Imported the retail dataset using pandas.
Categorical Encoding: Converted categorical variables (e.g., Genre) into numerical values using LabelEncoder.
Feature Scaling: Standardized the features to have a mean of 0 and a standard deviation of 1 using StandardScaler.
Clustering with K-means:

Optimal Clusters Determination:
Elbow Method: Used to find the optimal number of clusters by plotting the Sum of Squared Errors (SSE).
Silhouette Score: Evaluated different cluster numbers based on silhouette scores to determine the best clustering configuration.
K-means Clustering: Applied the K-means algorithm to segment customers into clusters.
Clustering with DBSCAN:

DBSCAN Clustering: Applied the DBSCAN algorithm to identify clusters based on density. Adjusted parameters such as eps and min_samples to optimize clustering results.
Analysis and Visualization:

Cluster Analysis: Analyzed the characteristics of each cluster to understand the profiles of different customer segments.
Visualization: Created scatter plots to visualize the clusters in terms of key features like Annual Income and Spending Score.
Technologies Used
Python: Programming language for data analysis and modeling.
pandas: Data manipulation and analysis.
numpy: Numerical operations.
scikit-learn: Clustering algorithms (K-means and DBSCAN) and evaluation metrics.
matplotlib: Plotting and visualization.
seaborn: Enhanced visualization and plotting.


Key Insights

Customer Segmentation:

K-means Clustering: Revealed distinct groups of customers with similar purchasing behaviors and demographic characteristics. These clusters can help in targeted marketing and personalized customer experiences.
DBSCAN Clustering: Identified clusters based on density and detected outliers that do not fit into any cluster. This can help in identifying niche customer segments and anomalies.
Cluster Characteristics:

Income and Spending Patterns: Insights into how different income levels and spending scores influence customer segmentation. For instance, high-income customers may show different spending patterns compared to low-income customers.
Demographic Trends: Understanding how age and gender influence spending behavior and segmentation.

Contribution

Feel free to open issues or submit pull requests if you have suggestions or improvements. For major changes, please open an issue first to discuss what you would like to change.


License

This project is licensed under the MIT License - see the LICENSE file for details.


Acknowledgments

The dataset is sourced from the Mall Customers Dataset.
Special thanks to the creators of the libraries and tools used in this analysis.


#OUTPUT
![Screenshot 2024-07-24 163002](https://github.com/user-attachments/assets/801f042c-eadc-4b60-82d5-ad74e0edae29)

![Screenshot 2024-07-24 163014](https://github.com/user-attachments/assets/e340df77-392f-4b7a-8298-bec9d4e94120)

![Screenshot 2024-07-24 163058](https://github.com/user-attachments/assets/f95261a5-f03a-4d15-b3c3-ff0f68fd0821)

![Screenshot 2024-07-24 163142](https://github.com/user-attachments/assets/4340dbf0-b78a-439a-abaf-3a6a97411e43)


