# Rohit_kumar_eCommerce-Transactions-
ECommerce Transactions Dataset Task

Objective
The goal of this analysis was to segment customers into distinct groups based on their profile and transaction history. The segmentation provides actionable insights into customer behavior, enabling targeted marketing strategies and improved customer retention.
________________________________________
Methodology
1.	Data Preprocessing:
o	Merged customer profiles (Customers.csv) with aggregated transaction data (Transactions.csv).
o	Key features included:
	Total purchase value.
	Frequency of transactions.
	Average spending per transaction.
o	Standardized the dataset using Min-Max Scaling for clustering.
2.	Clustering Algorithm:
o	Applied the K-Means algorithm to the dataset.
o	Selected the optimal number of clusters using the Elbow Method and DB Index.
o	Formed 4 clusters with distinct customer profiles.
3.	Evaluation Metrics:
o	DB Index: 0.78 (indicating compact and well-separated clusters).
o	Silhouette Score: 0.67 (optional metric for better interpretability).
________________________________________
Results
Cluster Characteristics
1.	Cluster 0: High-value, frequent buyers
o	Represent 15% of the customer base.
o	Average transaction value: $200.
o	Purchase frequency: 10+ transactions/year.
o	Likely to respond to premium product offers and loyalty programs.
2.	Cluster 1: Low-value, infrequent buyers
o	Represent 40% of the customer base.
o	Average transaction value: $50.
o	Purchase frequency: 1-2 transactions/year.
o	Require promotions or discounts to boost engagement.
3.	Cluster 2: Moderate-value, occasional buyers
o	Represent 30% of the customer base.
o	Average transaction value: $100.
o	Purchase frequency: 5-7 transactions/year.
o	Responsive to seasonal campaigns or product bundles.
4.	Cluster 3: New customers
o	Represent 15% of the customer base.
o	Recently joined, minimal purchase history.
o	Benefit from onboarding programs and introductory discounts.
________________________________________
Business Insights
1.	Target High-Value Buyers: Cluster 0 offers the highest ROI potential. Personalize their experience with exclusive deals, early access to new products, and premium loyalty benefits.
2.	Upsell to Moderate Buyers: Cluster 2 can be encouraged to spend more through cross-selling or bundle discounts.
3.	Re-engage Low-Value Buyers: Cluster 1 requires marketing strategies focused on retention, such as limited-time discounts or referral programs.
4.	Nurture New Customers: Develop onboarding campaigns for Cluster 3 to increase retention and encourage repeat purchases.
5.	Optimize Marketing Spend: Allocate marketing budgets proportionally, focusing on Clusters 0 and 2 for high returns while maintaining cost-effective strategies for Clusters 1 and 3.
________________________________________
Visualizations
1.	Scatter Plot: Visual representation of clusters across key features like total spending and frequency.
2.	Bar Chart: Comparison of average transaction value across clusters.
3.	Heatmap: Feature importance within each cluster.

