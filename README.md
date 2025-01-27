# Data Science Assignment: eCommerce Transactions Dataset

This repository contains the solution for the Data Science assignment involving exploratory data analysis (EDA), a lookalike model, and customer segmentation using an eCommerce Transactions dataset. The assignment demonstrates practical skills in data analysis, machine learning, and deriving actionable business insights.

---

## Dataset Description
The dataset consists of three files:
1. **Customers.csv**:
   - CustomerID: Unique identifier for each customer.
   - CustomerName: Name of the customer.
   - Region: Continent where the customer resides.
   - SignupDate: Date when the customer signed up.

2. **Products.csv**:
   - ProductID: Unique identifier for each product.
   - ProductName: Name of the product.
   - Category: Product category.
   - Price: Product price in USD.

3. **Transactions.csv**:
   - TransactionID: Unique identifier for each transaction.
   - CustomerID: ID of the customer who made the transaction.
   - ProductID: ID of the product sold.
   - TransactionDate: Date of the transaction.
   - Quantity: Quantity of the product purchased.
   - TotalValue: Total value of the transaction.

---

## Tasks Completed

### **Task 1: Exploratory Data Analysis (EDA) and Business Insights**
- Performed EDA to explore the dataset and derive insights.
- Key insights include:
  - Revenue by region.
  - Top products by quantity sold.
  - Seasonal trends in revenue.
  - High-value customers.
  - Revenue contribution by product categories.
- Deliverables:
  - A Jupyter Notebook containing EDA code.
  - A PDF report summarizing business insights (maximum 500 words).

### **Task 2: Lookalike Model**
- Built a lookalike model to recommend 3 similar customers for each user.
- Used features from customer profiles and transaction history.
- Generated similarity scores using cosine similarity.
- Deliverables:
  - Jupyter Notebook with model code.
  - A CSV file (`Lookalike.csv`) containing recommendations for customers C0001 to C0020.

### **Task 3: Customer Segmentation / Clustering**
- Performed customer segmentation using clustering techniques (KMeans).
- Combined customer and transaction data to create meaningful features.
- Evaluated clusters using the Davies-Bouldin Index.
- Visualized clusters in 2D using PCA.
- Deliverables:
  - Jupyter Notebook with clustering code.
  - A CSV file (`Clustering.csv`) containing customer cluster assignments.

---

## Contact
For any queries or suggestions, please reach out to:
- **Name**: Boopalamani J
- **Email**: boopalamani2003@gmail.com
