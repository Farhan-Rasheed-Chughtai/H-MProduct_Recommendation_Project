Overview :

This project aimed to perform exploratory data analysis (EDA), customer segmentation, and build a robust product recommendation system for H&M using publicly available data from Kaggle.

The dataset included three main components:

Articles dataset: Information on over 100,000 products.
Customers dataset: Demographic and behavioral data on over 1.3 million customers.
Transactions dataset: 30 million purchase records showing online and in-store purchases.

Key Objectives & Methodologies:

EDA & Insights:

Identified popular product categories (e.g., dresses, trousers).
Analyzed sales trends, demographics, and purchase behavior.
Found that ~70% of sales occurred online, suggesting a focus on digital channels.

Customer Segmentation:

Used feature engineering to augment customer data (e.g., total spend, category preferences).
Applied PCA for dimensionality reduction and K-Means clustering to group customers into 4 distinct clusters.
Determined high-value customers (Cluster 3) and tailored marketing insights for each cluster.

Market Basket Analysis (MBA):

Applied Apriori algorithm to uncover product associations.
Identified product pairs frequently bought together, although the effectiveness was limited by dataset size.

Recommendation System:

Collaborative Filtering: Implemented user-user and user-item similarity approaches, including matrix factorization (SVD) for personalized recommendations.
Content-Based Filtering: Engineered product features using TF-IDF and GloVe embeddings; recommended items based on similarity.
Hybrid Approach: Combined collaborative and content-based recommendations to balance personalization, diversity, and scalability.
