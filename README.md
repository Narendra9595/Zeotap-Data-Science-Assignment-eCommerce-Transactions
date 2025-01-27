# Zeotap-Data-Science-Assignment-eCommerce-Transactions

# Customer Segmentation and Lookalike Model Project

This repository contains the deliverables for the **Customer Segmentation** and **Lookalike Model** project. The goal of this project is to analyze customer behavior using clustering techniques, develop a lookalike model for personalized recommendations, and provide actionable business insights.

## Project Overview
The project is divided into the following tasks:
1. **Exploratory Data Analysis (EDA)**:
   - Analyzed customer, transaction, and product data to uncover patterns and trends.
   - Created visualizations to support business insights.
2. **Lookalike Model**:
   - Built a model to recommend 3 similar customers for each target customer based on profile and transaction history.
3. **Customer Segmentation**:
   - Used clustering techniques to segment customers into distinct groups for targeted strategies.
   - Evaluated clusters using the Davies-Bouldin Index (DB Index).

## Repository Contents
- **`clustering_report.pdf`**: Summary report of clustering results and insights.
- **`EDA.ipynb`**: Jupyter notebook with exploratory data analysis.
- **`Lookalike_Model.ipynb`**: Notebook for the lookalike model and recommendations.
- **`Clustering.ipynb`**: Notebook for customer segmentation using clustering techniques.
- **`Customer_Clusters.csv`**: Clustering results with cluster assignments.
- **`Lookalike.csv`**: Lookalike recommendations for the first 20 customers.

## Clustering Results
### Metrics:
- **Davies-Bouldin Index (DB Index):** 0.85 (Good cluster separation and compactness).
- **Silhouette Score:** 0.38 (Moderate cluster quality).

### Number of Clusters:
- **4 Clusters**
  - **Cluster 0:** High spenders with frequent transactions.
  - **Cluster 1:** Low spenders with minimal transaction activity.
  - **Cluster 2:** Moderate spenders with steady transaction behavior.
  - **Cluster 3:** A mixed group with diverse spending patterns.
  - 
## How to Use
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/<Narendra9595>/<Zeotap-Data-Science-Assignment-eCommerce-Transactions>.git
