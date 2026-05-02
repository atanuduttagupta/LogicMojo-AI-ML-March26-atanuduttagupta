# 🛒 End-to-End E-commerce Intelligence System  
### Building a Customer 360 Analytics Framework

---

## 📌 Business Problem

In e-commerce, data is spread across multiple tables like customers, orders, payments, products, and reviews.  
Because of this, it is difficult to get a complete view of the business.

In this project, I worked on:
- Combining multiple datasets into one
- Creating a Customer 360 view
- Understanding customer behavior and revenue
- Finding business problems and improvement areas

---

## 📂 Dataset Overview

### Core Tables
- customers.csv → Customer details
- orders.csv → Order lifecycle data
- order_items.csv → Product-level order details
- payments.csv → Payment information
- reviews.csv → Customer feedback

### Supporting Tables
- products.csv → Product information
- sellers.csv → Seller details
- category_translation.csv → Category mapping
- geolocation.csv → Location data

---

## ⚙️ Methodology

I followed a step-by-step approach to build this project:

- Loaded all datasets using Pandas. Checked structure using head(), info(), describe().
- Identified relationships using keys. Understood how tables are connected.
- Cleaned data by handling missing values and duplicates. Ensured consistency.
- Converted date columns into datetime format. Used it for time-based analysis.
- Merged all datasets step-by-step. Created a master dataset (df_master).
- Created features like total order value and delivery time. Also calculated number of items per order.
- Built customer-level metrics like purchase frequency. Calculated average order value.
- Performed EDA to understand patterns. Focused on customers, revenue, and delivery.
- Created visualizations using matplotlib and seaborn. Made charts simple and clear.
- Derived insights and recommendations. Connected analysis with business decisions.

---

## 📊 Key Findings

- Customer demand is concentrated in a few states like SP and RJ. Demand is not evenly distributed.
- Sellers are also concentrated in limited regions. Some high-demand areas have low seller presence.
- Revenue follows a long-tail distribution. Most orders are low-value with few high-value outliers.
- Few product categories drive most of the revenue. Many categories have low contribution.
- Delivery delays impact customer satisfaction. Longer delivery time leads to lower ratings.

---

## 💡 Business Insights

- Revenue mainly comes from a few top categories. Business depends on these segments.
- Most orders are low-value. This shows a high-volume business model.
- Some states have high customers but low sellers. This creates supply-demand gaps.
- Delivery time has strong impact on ratings. Faster delivery improves satisfaction.
- Customers prefer certain payment methods. This shows clear behavior patterns.

---

## 🚀 Recommendations

- Focus on top-performing categories. Improve weak categories.
- Increase order value using combo offers. Encourage upselling.
- Add more sellers in high-demand regions. Balance supply and demand.
- Improve delivery speed. Reduce delays.
- Target high-value customers. Improve retention.
- Use payment data for better offers. Personalize experience.

---

## 📈 Visualizations

- Sales trend over time (line chart)
- Category-wise revenue (bar chart)
- Order value distribution (histogram)
- Outlier detection (box plot)
- Correlation analysis (heatmap)

---

## 🛠 Tech Stack

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```
Ecommerce_Intelligence_Project/
│
├── notebook.ipynb
├── README.md
├── dataset/
└── report.docx
```

---

## 🎯 Conclusion

In this project, I combined multiple datasets and created a single master dataset for analysis.  
This helped me understand customer behavior, revenue patterns, and operational challenges.

Overall, this project shows how data can be used to take better business decisions.

---

## 👤 Author

**Atanu Dutta Gupta**

---

## 📅 Created On
May 2026
