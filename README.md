
# Customer Segmentation Using K-Means Clustering

## Overview
This project utilizes K-Means clustering to segment credit card customers based on their demographic and behavioral attributes. The clustering is performed to identify distinct customer groups, providing valuable insights for personalized marketing strategies.

## Features
- **Clustering**: Customers segmented into groups based on features such as:
  - Customer Age
  - Credit Limit
  - Total Transaction Amount
  - Average Utilization Ratio
- **Visualizations**: Detailed visualizations include scatter plots, bar plots, box plots, and pair plots to analyze clusters.

## Dataset
The dataset is sourced from the Kaggle dataset [Predicting Credit Card Customer Attrition with Machine Learning](https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m).

## Steps to Reproduce
1. **Setup KaggleHub**:
   - Install KaggleHub:
     ```bash
     pip install kagglehub
     ```
   - Authenticate using your Kaggle API key.
2. **Run the Script**:
   - Ensure all required libraries are installed:
     ```bash
     pip install pandas scikit-learn matplotlib seaborn kagglehub
     ```
   - Execute the script to perform clustering and generate visualizations.
3. **Explore Results**:
   - Clustered data is saved as `bank_customer_segmentation.csv` in the KaggleHub directory.

## Visualizations
### Scatter Plot: Avg Utilization Ratio vs. Total Transaction Amount
Displays the clustering results to analyze patterns in utilization and transaction behavior.

### Bar Plot: Average Total Transaction Amount per Cluster
Shows the average spending for each cluster.

### Box Plot: Credit Limit Distribution per Cluster
Analyzes credit limits within clusters.

### Pair Plot: Relationships Between Key Features by Cluster
Explores interactions among features across clusters.

## Technologies Used
- **Programming**: Python
- **Libraries**: Pandas, Scikit-learn, Matplotlib, Seaborn
- **Clustering Algorithm**: K-Means

## Output
Clustered data and visualizations are generated as outputs to help understand customer segments.

---

