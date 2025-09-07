# Customer Segmentation for Telecom Users

## Project Description

This project moves beyond traditional churn prediction to perform a deeper analysis of a telecom company's customer base using **Agglomerative Hierarchical Clustering**. The goal is to segment customers into distinct groups based on service usage, contract details, and spending patterns. These segments can help drive targeted marketing campaigns, personalize customer experiences, and develop proactive retention strategies.

Key customer personas identified include:
- High-Value Loyalists
- Budget-Conscious Subscribers
- At-Risk Newcomers

## Dataset

The analysis is based on the **Telco Customer Churn** dataset, which includes information about 7,043 customers from a fictional telecommunications company. The dataset contains 33 features categorized into:

- **Customer Demographics**
- **Service Usage & Subscriptions**
- **Account & Financial Information**
- **Churn Value / Churn Label**

## Notebook Structure

1. **Data Loading and Exploration**
   - Load the dataset and display basic information (shape, data types, summary statistics).

2. **Data Preprocessing**
   - Handle missing values, encode categorical variables, and scale numerical features.

3. **Linear Regression**
   - Initial predictive modeling to understand relationships between features and target variables.

4. **Agglomerative Hierarchical Clustering**
   - Apply clustering to segment customers.
   - Visualize clusters using dendrograms and scatter plots.

5. **Cluster Analysis**
   - Interpret and label clusters based on feature importance.
   - Extract actionable insights for business strategies.

6. **Visualization**
   - Use plots to compare clusters and their characteristics.


## Usage
1. Upload the dataset Telco_customer_churn.xlsx to the appropriate directory (e.g., /content/ in Google Colab).

2. Run the notebook cells sequentially to perform:

   - Data loading and inspection

   - Preprocessing

   - Modeling (Linear Regression and Clustering)

   - Visualization and interpretation

## Results
The clustering model identifies distinct customer segments, each with unique behaviors and characteristics. These insights can be used to tailor marketing efforts and improve customer retention.
