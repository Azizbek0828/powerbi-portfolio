# 🛒 E-commerce Sales Analysis

A one-page dashboard analysing an online store's orders across Indian states and cities — sales, profit, quantity and payment behaviour.

![E-commerce Sales Analysis](images/dashboard.png)

## 🎯 Business questions

- How much do we sell, and how profitable is it?
- Which **cities and states** bring the most sales — and where do we lose money?
- Which **categories** and **payment methods** do customers prefer?

## 📈 Key metrics

| Metric | Value |
|---|---|
| Total sales | **₹438K** |
| Total profit | **₹36.96K** |
| Profit margin | **8.44%** |
| Orders | **500** |
| Units sold | **5,615** |
| Avg order value | **₹0.88K** |
| Avg quantity per order | **11.23** |

## 💡 Insights

- **Indore** (₹63.7K) and **Mumbai** (₹58.9K) are the top cities by sales, followed by Pune, Mathura and Bhopal.
- Profit is spread fairly evenly across categories: **Clothing 36.1%**, **Electronics 35.6%**, **Furniture 28.3%**.
- **Clothing** accounts for about half of all orders, but not half of profit — high volume, lower value per order.
- **COD** is the most used payment method (≈36% of orders), showing a strong preference for paying on delivery.
- The large number of **loss-making order lines** (248 vs 384 profitable) points to discounting or pricing issues worth investigating.

## ⚙️ Features

- **KPI cards** — profit margin, average order value, average quantity, profitable vs loss-making orders
- **Trend sparklines** — sales, profit, quantity and orders over time
- **Breakdowns** — top 5 cities, profit by category, profit by state, orders by category and payment mode
- **Slicers** — month, day, state / city, category
- **Order details table** — order-level drill-through with conditional formatting on profit

## 🧮 Key DAX measures

Total Amount · Total Profit · Total Quantity · Total Orders · Profit Margin % · Avg Order Value · Avg Quantity per Order · Profitable / Loss-making orders

## 🛠 Tools

Power BI Desktop · DAX · Power Query

## 📂 Files

- `ecommerce-sales-analysis.pbix` — Power BI report
- `images/` — screenshots
