# Customer-Segmentation-Analysis
Customer Segmentation project using K-Means clustering to group customers based on purchasing behavior and identify high-value segments.

# 🧠 Customer Segmentation Analysis

## 📌 Project Overview

This project focuses on segmenting customers into distinct groups based on their purchasing behavior using **K-Means Clustering**. The goal is to identify patterns and categorize customers into meaningful segments such as high-value, regular, and low-value customers.

---

## 📂 Dataset

* Dataset used: *(mention your dataset name, e.g., retail_sales_dataset.csv)*
* Key columns include:

  * Customer ID
  * Transaction ID
  * Total Amount
  * Product / Purchase details

---

## ⚙️ Workflow

### 🔹 Data Cleaning

* Removed duplicates
* Handled missing values
* Standardized column formats

### 🔹 Feature Engineering

Created customer-level features:

* **Total Spend** → Total money spent by each customer
* **Frequency** → Number of purchases
* **Average Value** → Average purchase amount

---

### 🔹 Feature Scaling

* Applied **StandardScaler** to normalize data
* Important for distance-based algorithms like K-Means

---

### 🔹 Model Building (K-Means)

* Used **K-Means clustering algorithm**
* Determined optimal clusters using **Elbow Method**
* Assigned cluster labels to each customer

---

### 🔹 Cluster Analysis

* Interpreted each cluster based on:

  * Spending behavior
  * Purchase frequency
* Labeled segments such as:

  * High Value Customers 💰
  * Regular Customers 🔁
  * Low Value Customers 📉

---

### 🔹 Visualization

* Scatter plots for cluster distribution
* Elbow graph for optimal K
* Cluster-wise comparisons

---

## 📊 Key Insights

* Identified most valuable customer group
* Found customers with high frequency but low spending
* Enabled targeted marketing strategies

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🚀 Conclusion

Customer segmentation helps businesses understand their customers better and design personalized strategies. This project demonstrates how clustering techniques can be used to group customers effectively.

---

## 📎 Author

Sauravee Palaskar
