# 🛒 E-commerce Data Analysis

## 📌 Project Overview
This project analyzes e-commerce sales data using **Python** and **Pandas**.  
The dataset consists of **4–5 different tables** (Customers, Orders, Order Details, Products, Payments) which were merged together to generate meaningful business insights.

---

## 📂 Dataset Details
- **Customers** → Customer IDs, names, and demographic details  
- **Orders** → Order IDs, customer IDs, order dates  
- **Order Details** → Product IDs, order quantities, and prices  
- **Products** → Product names, categories, and unit prices  
- **Payments** → Payment and amount

---

## 🛠 Steps Performed
1. Loaded all datasets into Pandas DataFrames.
2. Merged datasets using `pd.merge()` on common keys (`customer_id`, `order_id`, `product_id`).

---

## 🔍 Insights Generated
1. Top Selling Product By Quantity
2. Top 10 Order By Total Amount
3. Top 10 customers By Payment
4. Revenue By Region
5. Revenue By Category
---

## 📊 Visualizations Used
- **Bar Chart** – Top customers by revenue  
- **Bar Chart** – Most ordered products  
- **Line Chart** – Monthly sales trend  
- **Pie Chart** – Sales share by product category  

---

## 🛠 Tools & Libraries
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
git clone https://github.com/KhushhalSharma/Data-Analysis-Python-project.git 
- Downloads/Data-Analysis-Python-project
- pip install pandas matplotlib seaborn jupyter
- jupyter notebook




