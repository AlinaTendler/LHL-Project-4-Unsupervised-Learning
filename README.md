

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

#### Optimal Clusters: 4

Customer Segments (k=4)

#### Segment 0: Traditional Food Buyers

- High spending on Fresh and Frozen items
- Likely represents restaurants, caterers, or food service businesses

#### Segment 1: Convenience Product Buyers

- High spending on Milk, Grocery, and Detergents_Paper
- Likely cafés, convenience stores, or institutional buyers

#### Segment 2: Moderate General Buyers

- Moderate spending across all product categories
- Represents occasional or general-purpose customers

#### Segment 3: Premium and Specialty Buyers

- High spending on Fresh and Delicatessen
- Likely boutique stores, gourmet restaurants, or niche retailers

## Business insights

### Segment 0: Traditional Food Buyers
- Cold Chain Optimization: Ensure reliable storage and delivery of perishables
- Bulk Fresh Deals: Offer volume discounts on fresh and frozen goods
- Inventory Tools: Provide stock management tools for spoilable inventory

### Segment 1: Convenience Product Buyers
-  Subscription Options: Auto-refill common goods like groceries and cleaning supplies
- Cross-Selling: Bundle grocery and detergent products for higher order value
- Loyalty Programs: Reward repeat purchases from high-frequency customers

### Segment 2: Moderate General Buyers
- Starter Packs: Offer smaller, flexible product bundles
- Referral Incentives: Reward existing clients for bringing in new ones
- Usage Education: Promote product benefits through guides and marketing

### Segment 3: Premium and Specialty Buyers
- Premium Product Line: Market artisanal or high-end grocery options
- Custom Orders: Allow special requests and smaller batch deliveries
- Dedicated Support: Assign personal reps or support lines for VIP clients