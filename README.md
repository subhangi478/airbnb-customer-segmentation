# airbnb-customer-segmentation
Customer segmentation analysis on Airbnb NYC 2019 data using K-Means clustering to generate actionable pricing and marketing insights.

📊 Customer Segmentation Analysis – Airbnb NYC 2019
📌 Project Overview

This project performs customer (listing) segmentation analysis on the Airbnb New York City 2019 dataset using K-Means clustering.
The goal is to group Airbnb listings based on pricing, availability, and review behavior to generate actionable business insights for pricing and marketing strategies.

🎯 Objectives

Analyze Airbnb listing data to understand host and customer behavior

Segment listings into distinct groups using clustering algorithms

Identify premium, popular, and underperforming listings

Provide data-driven business recommendations

🛠 Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Platform: Google Colab

Version Control: GitHub

📂 Dataset

Name: Airbnb New York City 2019

Rows: ~49,000 listings

Key Features Used:

price

number_of_reviews

reviews_per_month

availability_365

neighbourhood_group

🔍 Project Workflow
1️⃣ Data Loading

Loaded CSV dataset using Pandas

Inspected shape, columns, and data types

2️⃣ Data Cleaning

Removed irrelevant columns (id, name, host_name, last_review)

Handled missing values (reviews_per_month)

Removed extreme price outliers

Encoded categorical variables where required

3️⃣ Exploratory Data Analysis (EDA)

Statistical summaries

Distribution analysis

Outlier detection

4️⃣ Feature Selection & Scaling

Selected numeric features relevant for clustering

Standardized data using StandardScaler

5️⃣ Clustering (K-Means)

Used Elbow Method to determine optimal number of clusters

Applied K-Means clustering to segment listings

Assigned cluster labels to each listing

6️⃣ Visualization

Scatter plots to visualize cluster separation

Color-coded clusters for interpretability

7️⃣ Cluster Analysis

Calculated mean values for each cluster

Interpreted cluster characteristics

📈 Cluster Insights
Cluster	Key Characteristics	Interpretation
0	Low price, high availability	Budget / low-engagement listings
1	High price, low availability	Premium listings
2	Moderate price, high reviews	Popular & trusted listings
3	Low reviews, low availability	Underperforming listings
💡 Business Recommendations

📌 Promote Cluster 0 listings with discounts and visibility boosts

💎 Maintain premium pricing for Cluster 1 listings

⭐ Reward loyalty and visibility for Cluster 2 listings

🔧 Improve listing quality and marketing for Cluster 3

📁 Repository Structure
airbnb-customer-segmentation/
│
├── data/
│   └── AB_NYC_2019.csv
│
├── notebooks/
│   └── airbnb_customer_segmentation.ipynb
│
├── images/
│   └── cluster_visualization.png
│
├── README.md
├── requirements.txt

🚀 Results & Learnings

Gained hands-on experience with clustering algorithms

Learned how to handle real-world messy datasets

Developed strong EDA and data preprocessing skills

Converted analysis into business-oriented insights

📌 Future Enhancements

Try advanced clustering algorithms (DBSCAN, Hierarchical Clustering)

Add geographical clustering using latitude & longitude

Build a dashboard using Power BI or Tableau

Convert into an ML-based recommendation system

📬 Contact

Name: Subhangi Panigrahi
Field: Data Analytics | Machine Learning
LinkedIn / GitHub: (add your links here)
