# SuperStore Data Analysis 📊

This project contains an exploratory data analysis (EDA) of a retail dataset using Python and Jupyter Notebook. The analysis is based on sales, profit, and customer behavior to extract meaningful business insights.

---

## 📁 Dataset
The dataset used in this notebook includes:
- Orders with fields like Order ID, Order Date, Ship Date, Customer ID, Segment, Category, Sub-Category, Sales, Profit, Quantity, Discount, and Region.

---

## 🔍 Objectives
- Analyze sales and profit by different dimensions (Year, Region, Category, Country, Product).
- Calculate key performance indicators such as:
  - Profit per item
  - Unit price
  - Delivery duration
- Create RFM metrics to segment customers.
- Identify top-performing regions, products, and categories.
- Visualize data trends using `matplotlib` and `plotly`.

---

## 🛠️ Tools and Libraries Used
- `pandas`: data manipulation
- `numpy`: numerical operations
- `matplotlib.pyplot`: static data visualization
- `plotly.express`: interactive charts
- `datetime`: working with dates

---

## 📈 Key Analyses Performed
- Total profit per region and year
- Product-wise and category-wise profitability
- Delivery time analysis
- Weekday ordering behavior
- Customer segmentation using RFM (Recency, Frequency, Monetary)
- Encoding techniques: One-Hot Encoding, Target Mean Encoding

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/superstore-analysis.git
   cd superstore-analysis
