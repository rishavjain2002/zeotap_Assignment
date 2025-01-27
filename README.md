## **Dataset Description**

### **1. Customers.csv**

- **CustomerID**: Unique identifier for each customer.
- **CustomerName**: Name of the customer.
- **Region**: Continent where the customer resides.
- **SignupDate**: Date when the customer signed up.

### **2. Products.csv**

- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **Category**: Product category.
- **Price**: Product price in USD.

### **3. Transactions.csv**

- **TransactionID**: Unique identifier for each transaction.
- **CustomerID**: ID of the customer who made the transaction.
- **ProductID**: ID of the product sold.
- **TransactionDate**: Date of the transaction.
- **Quantity**: Quantity of the product purchased.
- **TotalValue**: Total value of the transaction.
- **Price**: Price of the product sold.

---

## **Assignment Tasks**

### **Task 1: Exploratory Data Analysis (EDA) and Business Insights**

1. Perform **exploratory data analysis (EDA)** on the provided dataset.
2. Derive at least **5 business insights** from the EDA.
    - Write these insights in short, point-wise sentences (maximum 100 words per insight).


---

### **Task 2: Lookalike Model**

Build a **Lookalike Model** that takes a user's information as input and recommends **3 similar customers** based on their profile and transaction history. The model should:
- Use both **customer and product information**.
- Assign a **similarity score** to each recommended customer.


---

### **Task 3: Customer Segmentation / Clustering**

Perform **Customer Segmentation** using clustering techniques. Use both:

- Profile information (from `Customers.csv`)
- Transaction information (from `Transactions.csv`).

#### **Requirements**

- Choose any clustering algorithm and any number of clusters between **2 and 10**.
- Calculate **clustering metrics**, including the **Davies-Bouldin Index (DB Index)** (this will be used for evaluation).
- Visualize your clusters using relevant plots.

