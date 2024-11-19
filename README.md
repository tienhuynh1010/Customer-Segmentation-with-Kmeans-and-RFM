This repository contains a project that uses K-Means Clustering and RFM (Recency, Frequency, Monetary) Analysis to segment customers for better targeting and personalization in marketing strategies. The goal is to identify customer groups with similar behaviors and optimize business decision-making.

Features:
RFM Analysis:
Recency: Time since the last purchase.
Frequency: Total number of purchases.
Monetary: Total monetary value of purchases.
K-Means Clustering:
Groups customers into clusters based on their RFM scores.
Visualizes clusters to identify patterns and insights.
Customer Profiling:
Labels clusters to define actionable customer segments (e.g., "Loyal Customers," "Churn Risk," "Big Spenders").

Applications:
Tailor marketing campaigns for specific customer segments.
Design loyalty programs targeting high-value customers.
Predict customer churn and improve retention strategies.

Workflow:
Data Preprocessing: Clean and prepare transactional data for RFM calculations.
RFM Scoring: Assign scores to customers based on RFM values.
Clustering with K-Means: Use RFM scores as features for clustering.
Visualization & Insights: Plot clusters and interpret customer behavior.

Technologies Used:
Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, PySpark
Clustering Algorithms: K-Means for segmentation
Data Visualization: To analyze cluster distribution and customer profiles
