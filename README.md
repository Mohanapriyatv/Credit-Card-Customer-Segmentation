# Credit Card Customer Segmentation

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)

## Project Overview
This project aims to develop a customer segmentation model to define marketing strategies for credit card holders. By analyzing customer behavior, we can segment customers into distinct groups to tailor marketing efforts more effectively.

## Dataset
The dataset used in this project summarizes the usage behavior of about 9000 active credit card holders over the last 6 months. It includes 18 behavioral variables, such as:

- **CUST_ID:** Identification of Credit Card holder (Categorical)
- **BALANCE:** Balance amount left in their account to make purchases
- **BALANCE_FREQUENCY:** How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- **PURCHASES:** Amount of purchases made from account
- **ONEOFF_PURCHASES:** Maximum purchase amount done in one-go
- **INSTALLMENTS_PURCHASES:** Amount of purchase done in installment
- **CASH_ADVANCE:** Cash in advance given by the user
- **PURCHASES_FREQUENCY:** How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
- **ONEOFFPURCHASESFREQUENCY:** How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
- **PURCHASESINSTALLMENTSFREQUENCY:** How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- **CASHADVANCEFREQUENCY:** How frequently the cash in advance being paid
- **CASHADVANCETRX:** Number of Transactions made with "Cash in Advanced"
- **PURCHASES_TRX:** Number of purchase transactions made
- **CREDIT_LIMIT:** Limit of Credit Card for user
- **PAYMENTS:** Amount of Payment done by user
- **MINIMUM_PAYMENTS:** Minimum amount of payments made by user
- **PRCFULLPAYMENT:** Percent of full payment paid by user
- **TENURE:** Tenure of credit card service for user

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install these dependencies using the following command:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Credit-Card-Customer-Segmentation.git
   cd Credit-Card-Customer-Segmentation
   ```

2. Place the dataset in the `data` directory.

3. Run the Jupyter notebook to explore the data and build the segmentation model:
   ```bash
   jupyter notebook Customer_Segmentation.ipynb
   ```

## Modeling
The project involves the following steps:
1. **Data Preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Exploratory Data Analysis (EDA):** Visualizing data distributions and relationships between features.
3. **Feature Engineering:** Creating new features and aggregating existing ones to enhance model performance.
4. **Clustering:** Applying clustering algorithms to segment customers, including:
   - K-Means Clustering
   - Hierarchical Clustering
   - DBSCAN

5. **Model Evaluation:** Evaluating clustering results using metrics such as silhouette score and visual inspection of clusters.

## Results
The results of the clustering models, including performance metrics and visualizations, are documented in the Jupyter notebook. The final customer segments can be used to inform targeted marketing strategies.

