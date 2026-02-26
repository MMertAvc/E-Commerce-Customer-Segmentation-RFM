# 🛒 E-Commerce Customer Segmentation using K-Means Clustering

## 📋 Project Summary

This project applies unsupervised machine learning to segment an e-commerce company's customer base. By analyzing purchasing behaviors based on **Frequency (number of orders)** and **Monetary Value (total spend)**, the project groups customers into distinct actionable clusters using the **K-Means algorithm**.

## 🎯 Key Objectives

- **Behavioral Analysis:** To understand customer purchasing patterns and identify the most valuable customer groups.
- **Optimal Clustering:** To determine the ideal number of customer segments by calculating and analyzing the **Silhouette Score**.
- **Targeted Marketing:** To provide actionable data segments that allow marketing teams to create personalized campaigns for different customer profiles.

## 🛠️ Technical Approach

- **Data Preprocessing:** Filtered out invalid transactions (e.g., negative subtotals, zero quantities) and aggregated raw order data at the unique customer level using `Pandas`.
- **Feature Engineering:** Extracted Frequency and Monetary metrics to build the foundational RFM-style matrix. Applied `StandardScaler` to normalize the data, ensuring the clustering algorithm weights all features equally.
- **Machine Learning:** Implemented K-Means clustering from `Scikit-Learn`. Evaluated cluster quality using the Silhouette Method and visualized the customer segments using `Matplotlib`.

## 💼 Business Value

Customer segmentation is crucial for maximizing ROI in marketing. Instead of using a "one-size-fits-all" approach, this model allows businesses to identify their "Whales" (high spend, high frequency) and "One-Time Buyers." This data-driven approach enables highly targeted retention, upselling strategies, and efficient budget allocation.
