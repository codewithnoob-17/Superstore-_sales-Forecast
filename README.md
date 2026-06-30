# SuperStore Sales Dashboard (Power BI)

An interactive Power BI dashboard analyzing sales, profit, and forecasting trends for a retail "SuperStore" dataset, covering regional performance, category breakdowns, shipping behavior, and a 15-day sales forecast.

## 📊 Overview

This project visualizes key business metrics from the SuperStore dataset across two report pages:

1. **Sales Dashboard** – A high-level overview of sales, quantity, profit, and shipping performance.
2. **Sales Forecast (15 Days)** – A forecasting view projecting near-term sales trends, along with a state-wise sales breakdown.

## 🖥️ Dashboard Pages

### 1. Sales Dashboard
- **KPI Cards:** Total Sales (1.6M), Quantity (22.3K), Profit (175K), Avg. Ship Days (4)
- **Region Filter:** Central, East, South, West
- **Sales by Payment Mode:** Cards, COD, Online
- **Sales by Region:** Donut chart breakdown
- **Sales by Segment:** Consumer, Corporate, Home Office
- **Monthly Sales by YoY:** 2019 vs 2020 trend comparison
- **Monthly Profit by YoY:** 2019 vs 2020 trend comparison
- **Sales by Ship Mode:** Standard, Second Class, First Class, Same Day
- **Sales by Category & Sub-Category:** Technology, Furniture, Office Supplies; Phones, Chairs, Binders, Storage
- **Profit and Sales by State:** Geo map visualization across North America

### 2. Sales Forecast – 15 Days
- **Sales Forecast Line Chart:** Historical trend from Jan 2019 to Jan 2021 with a forecasted projection band
- **Zoomed Forecast View:** Daily forecast detail (Oct 2020 – Jan 2021) with a date range slider
- **Sales by State:** Top 10 states ranked by sales (California, New York, Texas, etc.)

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** – Report design and data modeling
- **DAX** – Calculated measures and KPIs
- **Power BI Forecasting** – Built-in analytics for the 15-day sales forecast
- **Data Visualization** – Cards, donut charts, line/area charts, bar charts, and geo maps
- **Interactive Filtering** – Slicers for region and time period

## 📁 Repository Contents

```
├── SuperStore_Sales_Dashboard.pbix   # Power BI report file
├── images/                           # Dashboard screenshots
└── README.md
```

## 🚀 How to Use

1. Clone or download this repository.
2. Open `SuperStore_Sales_Dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Refresh the data source if connected to a live dataset, or explore using the embedded sample data.
4. Use the slicers (Region, Date Range) to interact with the visuals.

## 📌 Key Insights

- Standard shipping accounts for the largest share of sales (0.91M).
- California leads all states in sales, followed by New York and Texas.
- Technology is the top-performing category, with Phones as the leading sub-category.
- COD is the most used payment mode at 43%, followed by Online (35%) and Cards (22%).

## 📷 Screenshots

```markdown
<img width="891" height="499" alt="snapshot1" src="https://github.com/user-attachments/assets/5b91bcf0-b62f-4b55-a7c1-5854144de5ce" />
<img width="887" height="498" alt="snapshoot2" src="https://github.com/user-attachments/assets/97f34b98-cca4-4ddd-acbe-41af7b508c6e" />


## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
