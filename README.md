# 🪑 Furniture Profit Dashboard (Python + Tableau)

## 🎯 Objective
Analyze profitability issues in the Furniture category of the Superstore dataset using Python for data preprocessing and Tableau for business intelligence visualization.

## 📊 Key Insights
- **High Sales, Low Profit**: Furniture sales are strong, but profitability is low, especially for categories like *Bookcases* and *Tables*.
- **Regional Disparity**: The *West* region leads in sales but has suboptimal profit margins.
- **Customer Segments**: *Consumer* segment dominates sales, but *Corporate* yields better profit margins.
- **Shipping Efficiency**: *Standard Class* shipping shows the highest loss margin compared to other shipping modes.
- **Discount Threshold**: Orders with a discount over 30% frequently result in negative profit.

## 🧹 Data Processing
Performed using Python (Pandas, Seaborn):
- Cleaned and converted date columns
- Extracted year/month for trend analysis
- Aggregated profit, sales, and discount metrics by region, category, shipping mode, etc.

## 📈 Visualizations
7 key charts created with Tableau:
1. **Sales vs. Profit by Sub-Category**
2. **Monthly Profit Trend**
3. **Profitability by Region**
4. **Profit by Customer Segment**
5. **Delivery Timeliness vs. Profit**
6. **Shipping Mode Impact**
7. **Discount vs. Profit Scatter**

All visualizations are integrated into one interactive dashboard layout.

## 📎 Snapshot
![Dashboard Preview](./dashboard.png)

## 🧰 Tools Used
- **Python**: Pandas, Seaborn, Matplotlib
- **Tableau Public**: Dashboard design and interactivity

## 📝 Folder Structure

```
furniture-profit-dashboard/
├── README.md
├── superstore_analysis.py
├── superstore_cleaned.csv
├── dashboard.png
└── figures/
    ├── sales_profit_subcat.png
    ├── monthly_profit_trend.png
    ├── region_profit.png
    ├── customer_segment_profit.png
    ├── shipping_efficiency.png
    ├── ship_mode_loss.png
    └── discount_vs_profit.png
```

## 🚀 Author
Shiyu Cai | [LinkedIn](https://www.linkedin.com/in/shiyucaisierra/)
