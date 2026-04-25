SmartCart Customer Segmentation:

This project focuses on identifying distinct customer segments for "SmartCart" using unsupervised machine learning. By analyzing purchasing behavior and demographic data, we can help the business tailor marketing strategies and improve customer retention.

Persona Identification: Detailed breakdown of "Big Spenders," "Frugal Consumers," and "Target Segments."

Project Overview:

The goal is to group customers based on similarities in their data (e.g., spending habits, age, or income). 
This is achieved through clustering algorithms to reveal patterns that aren't immediately obvious.


Machine Learning Approach:


K-Means Clustering: Efficiently partitions $N$ observations into $K$ clusters where each observation belongs to the cluster with the nearest mean.
Agglomerative (Hierarchical) Clustering: A bottom-up approach that builds a tree of clusters (dendrogram) to understand nested relationships in customer behavior.

3D Projection:Since customer behavior is multi-dimensional,
we use 3D scatter plots to view clusters across three primary axes simultaneously.

Key Steps:


Exploratory Data Analysis (EDA): Visualizing distributions and correlations.
Data Preprocessing: Handling missing values and scaling features.
Clustering: Using the Elbow Method to find the optimal number of clusters ($K$).
Analysis: Interpreting the characteristics of each customer segment.


Tech Stack:


Language: Python

Libraries: * pandas & numpy for data manipulation.

matplotlib & seaborn for data visualization.

scikit-learn for K-Means Clustering and data scaling.


Insights:


Identified specific "High Value" segments (High Income, High Spending).

Discovered "Target" segments (Low Income, High Spending) for credit-based promotions.

Compared the efficiency and cluster shapes between K-Means and Hierarchical methods.
