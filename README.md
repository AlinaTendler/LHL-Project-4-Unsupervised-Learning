

## Project Overview
This project applies unsupervised learning techniques to segment wholesale customers based on their annual spending across various product categories. By identifying distinct customer groups, the business can tailor marketing strategies, optimize inventory, and enhance customer satisfaction.
## Dataset
The dataset contains annual spending (in monetary units) on diverse product categories for clients of a wholesale distributor.
## Project Description:
### Data Preprocessing:

1. Load the dataset.
2. Handle missing values.
3. Detect and remove outliers using the IQR method.
4. Normalize the data using StandardScaler.

### KMeans Clustering:

1. Determine the optimal number of clusters using the Elbow method.
2. Apply KMeans clustering.
3. Visualize the clusters.

### Hierarchical Clustering:

1. Compute linkage matrix.
2. Plot dendrogram to determine the number of clusters.
3. Apply Agglomerative Clustering.

### Principal Component Analysis (PCA):

1. Reduce dimensionality for visualization.
2. Plot the clusters in the PCA-reduced space.

## Results

### Optimal Clusters: 3

### Segmentation:

Segment	Characteristics
1. High spending on fresh products
2. High spending on detergents and paper goods
3. Moderate spending across all categories


## Business Insights

### Segment 1: High-Volume Fresh Product Buyers

Profile: These customers consistently purchase large quantities of fresh products.

#### Strategic Actions:

- Customized Offerings: Develop tailored product bundles focusing on fresh goods.

- Loyalty Programs: Implement rewards programs to encourage repeat purchases.

- Efficient Delivery: Enhance delivery schedules to ensure freshness and reliability.

### Segment 2: High-Volume Detergents and Paper Product Buyers

Profile: This group predominantly purchases detergents and paper products.

#### Strategic Actions:

- Bulk Discounts: Offer volume-based pricing to incentivize larger orders.

- Subscription Models: Introduce recurring order options for consistent supply.

- Targeted Marketing: Create campaigns highlighting the benefits of bulk purchasing.

### Segment 3: Diverse Product Purchasers

Profile: These customers have moderate spending across various product categories.

Strategic Actions:

- Flexible Bundling: Allow customization of product bundles to cater to varied needs.

- Cross-Selling Opportunities: Identify and promote complementary products.

- Feedback Mechanisms: Implement systems to gather customer feedback for continuous improvement.