# Data-Science-Assignment-eCommerce-Transactions-Dataset-Zeotap

## Project Overview
This project involves analyzing an eCommerce Transactions dataset comprising three files:

- **Customers.csv**: Information about customers.
- **Products.csv**: Details of products.
- **Transactions.csv**: Records of transactions.
  
Your tasks include performing exploratory data analysis (EDA), building predictive models, and deriving actionable insights. This assignment will test your skills in data analysis, machine learning, and business insights.

---
## Dataset Description
1. Customers.csv
CustomerID: Unique identifier for each customer.
CustomerName: Name of the customer.
Region: Continent where the customer resides.
SignupDate: Date when the customer signed up.

3. Products.csv
ProductID: Unique identifier for each product.
ProductName: Name of the product.
Category: Product category.
Price: Product price in USD.

5. Transactions.csv
TransactionID: Unique identifier for each transaction.
CustomerID: ID of the customer who made the transaction.
ProductID: ID of the product sold.
TransactionDate: Date of the transaction.
Quantity: Quantity of the product purchased.
TotalValue: Total value of the transaction.

---
## Assignment Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
Perform EDA on the provided dataset.
Derive at least 5 business insights from the EDA in short point-wise sentences (maximum 100 words per insight).
Deliverables:

A Jupyter Notebook/Python script containing your EDA code.
A PDF report summarizing your business insights (maximum 500 words).

### Task 2: Lookalike Model
Build a Lookalike Model to recommend 3 similar customers for each input customer based on their profile and transaction history. The model should:

Use both customer and product information.
Assign a similarity score to each recommended customer.
Deliverables:

A file named Lookalike.csv with a mapping: CustomerID → List[CustomerID, SimilarityScore] for the first 20 customers (CustomerID: C0001 to C0020).
A Jupyter Notebook/Python script explaining the model's logic.


### Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques, combining:

Profile information from Customers.csv.
Transaction data from Transactions.csv.
Requirements:

Use a clustering algorithm of your choice (2 to 10 clusters).
Calculate clustering metrics, including the DB Index.
Visualize the clusters using relevant plots.
Deliverables:

A report on clustering results, including:
Number of clusters formed.
DB Index value.
Other relevant metrics.
A Jupyter Notebook/Python script for clustering.

---



## How to Run the Code
Clone or download the repository containing this dataset and scripts.
Install the required Python libraries (pandas, numpy, matplotlib, scikit-learn, etc.).
Run the Jupyter Notebooks provided for each task.


---
![image](https://github.com/user-attachments/assets/d76fc258-2a8b-4315-92fd-d3391f496faa)

![image](https://github.com/user-attachments/assets/cb15523d-0537-4e25-8768-240f0c46ab50)

![image](https://github.com/user-attachments/assets/c553a331-a962-48cd-912b-8abd63bac87a)

![image](https://github.com/user-attachments/assets/5306b337-bc98-4f2a-8a6c-ce32edafb4d1)

![image](https://github.com/user-attachments/assets/f3104ab1-be30-457f-9b9e-5997aeb8dde8)

![image](https://github.com/user-attachments/assets/87d84d6b-173f-454d-bc76-d7d4d5b16d72)

![image](https://github.com/user-attachments/assets/347d5e16-6ef6-4eec-85d4-6ff3b5a90f19)

![image](https://github.com/user-attachments/assets/f0dafc29-52c7-46e5-8b33-3e515c79d36c)

![image](https://github.com/user-attachments/assets/59c74ff8-8065-4406-af75-4d16fed67efc)



















