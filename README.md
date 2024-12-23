
# Customer Segmentation Using K-Means Clustering

## Overview
This project segments credit card customers into distinct clusters using K-Means clustering. By analyzing customer behavioral and financial attributes, the clustering process uncovers insights to aid personalized marketing and customer management.

## Features
- **Clustering**: Customers segmented based on:
  - Average Utilization Ratio
  - Total Transaction Amount
  - Credit Limit
  - Total Transaction Count
- **Visualizations**: Key insights visualized using scatter plots, bar charts, box plots, and pair plots.

## Dataset
The dataset is sourced from the Kaggle dataset [Predicting Credit Card Customer Attrition with Machine Learning](https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m).

## Observations from Clustering and Visualizations
1. **Scatter Plot (Avg Utilization Ratio vs. Total Transaction Amount)**:
   - Cluster 3 represents high-value customers with higher transaction amounts and balanced utilization ratios.
   - Cluster 1 exhibits moderate transaction activity but higher utilization ratios.

2. **Bar Plot (Average Total Transaction Amount per Cluster)**:
   - Cluster 3 leads in transaction amounts, making it a priority group for retention strategies.
   - Cluster 1 has relatively low transaction activity.

3. **Box Plot (Credit Limit Distribution per Cluster)**:
   - Cluster 3 shows significantly higher credit limits, highlighting premium customer status.
   - Cluster 0 and Cluster 1 have lower credit limits, suggesting a focus on cost-conscious customers.

4. **Pair Plot (Relationships Among Key Features by Cluster)**:
   - Distinct feature groupings highlight cluster differentiation, particularly for `Credit Limit` and `Total Transaction Amount`.

## Technologies Used
- **Programming**: Python
- **Libraries**: Pandas, Scikit-learn, Matplotlib, Seaborn
- **Clustering Algorithm**: K-Means

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
   - Execute the Python script to segment customers and generate visualizations.
3. **Explore Results**:
   - Review the clustered data saved as `bank_customer_segmentation.csv`.

## Conclusion
The project successfully identified actionable customer segments. By targeting high-value clusters (Cluster 3) and improving engagement for low-value clusters (Cluster 1), businesses can optimize customer retention and profitability.

---

For questions or suggestions, feel free to reach out.

Happy analyzing! 🎉
