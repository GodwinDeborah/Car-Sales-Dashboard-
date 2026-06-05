# Car Sales Dashboard

## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Business Problem](#2-business-problem)
3. [Project Objectives](#3-project-objectives)
4. [Project Tools](#4-project-tools)
5. [Repository Structure](#5-repository-structure)
6. [Dataset Overview](#6-dataset-overview)
7. [Dashboard Overview](#7-dashboard-overview)
8. [Dashboard Screenshot](#8-dashboard-screenshot)
9. [Key Insights](#9-key-insights)
10. [Recommendations](#10-recommendations)
11. [Assumptions & Limitations](#11-assumptions--limitations)
12. [Future Enhancements](#12-future-enhancements)
13. [Author](#13-author)

## 1. Project Overview

The Car Sales Dashboard is a Tableau-based analytics project designed to explore vehicle sales performance across different manufacturers, dealer regions, vehicle categories, and customer segments. The dashboard consolidates key sales metrics and interactive visualizations to provide insights into revenue trends, sales volume, pricing performance, and customer preferences. By enabling users to analyze sales data from multiple perspectives, the dashboard supports a deeper understanding of performance patterns and business outcomes.

## 2. Business Problem

Vehicle sales data often exists across multiple dimensions, including manufacturers, dealer regions, vehicle categories, and customer segments. Without a centralized analytical view, identifying sales trends, customer preferences, and high-performing markets can be challenging. This dashboard addresses that challenge by consolidating key sales metrics and visualizations into a single interactive reporting solution.

## 3. Project Objectives

The objective of this project is to develop an interactive Tableau dashboard that provides a comprehensive view of vehicle sales performance. The dashboard is designed to analyze key sales metrics, including total sales, average selling price, and vehicles sold, while tracking year-over-year performance trends. It also enables the exploration of sales distribution across manufacturers, vehicle body styles, colors, and dealer regions, helping users identify patterns in customer preferences and sales activity. Through interactive visualizations and filtering capabilities, the dashboard supports the effective analysis and communication of sales insights.

## 4. Project Tools

* **Tableau** — Dashboard development, data visualization, and interactive reporting.
* **CSV Dataset** — Source data used for sales analysis, trend identification, and performance evaluation.
* **Git & GitHub** — Version control, project organization, and documentation management.

## 5. Repository Structure

```text
Car-Sales-Dashboard/
│
├── dashboard/
│   └── Car Sales Dashboard.twbx
│
├── data/
│   └── Car Sales Data.xlsx
│
├── docs/
│   ├── business-requirements.md
│   └── insights-report.md
│
├── images/
│   └── Car Sales Dashboard.jpg
│
├── LICENSE
└── README.md
```

## 6. Dataset Overview

The dataset contains vehicle sales transaction records and customer-related information used to analyze sales performance and purchasing trends. Key attributes include vehicle manufacturer, model, body style, transmission type, color, engine specifications, sales price, dealer region, and customer demographics. These fields support the exploration of revenue performance, customer preferences, and regional sales distribution.

## 7. Dashboard Overview

The dashboard consists of KPI cards, trend visualizations, comparative charts, and interactive filters that enable users to analyze vehicle sales performance from multiple perspectives. Users can monitor revenue growth, evaluate sales volume trends, compare manufacturer performance, assess regional sales distribution, and explore customer purchasing preferences through a single interactive interface.

## 8. Dashboard Screenshot
![Car Sales Dashboard](Images/car_sales_dashboard.jpg)

## 9. Key Insights
- YTD Total Sales reached $371.19M, with a 23.59% year-over-year increase.
- Vehicle sales volume grew by 24.75%, totaling 13.26K cars sold.
- SUVs generated the highest sales among all vehicle body styles.
- Pale White and Black vehicles accounted for the largest share of sales by color.
- Automatic transmission vehicles consistently outsold manual vehicles across all dealer regions.
- Sales performance varied across regions, with Austin recording the highest sales among the displayed dealer locations.
- Manufacturer contributions differed, with Chevrolet, Ford, and Dodge among the leading contributors to total sales.

## 10. Recommendations
- Increase inventory allocation for SUV models, as they generate the highest sales among all vehicle body styles.
- Prioritize stocking Pale White and Black vehicles to better align inventory with observed customer purchasing preferences.
- Expand the availability of automatic transmission vehicles, given their consistently stronger sales performance across dealer regions.
- Conduct further analysis of top-performing dealer regions to identify practices that may be replicated in lower-performing markets.
- Review sales strategies for lower-performing vehicle body styles to identify opportunities for improving market performance.
- Strengthen partnerships and promotional activities around high-performing manufacturers to capitalize on existing sales momentum.
- Analyze seasonal sales patterns to better align inventory planning and marketing campaigns with periods of increased demand.

## 11. Assumptions & Limitations

### Assumptions
- The dataset is assumed to be complete and sufficiently representative for sales performance analysis.
- Vehicle pricing and sales records are assumed to be accurate and free from significant data entry errors.
- Dealer regions are treated as independent sales locations for comparative analysis.
- Year-over-Year (YOY) metrics are calculated based on the data available within the dataset.

### Limitations
- The analysis is limited to the data provided and may not reflect real-world market conditions.
- External factors such as economic conditions, competitor activities, promotions, or seasonality are not included in the dataset.
- Customer behavior is analyzed using available demographic attributes only and may not capture all purchasing influences.
- Insights and recommendations are based solely on historical sales records and should not be interpreted as predictive outcomes.

## 12. Future Enhancements
- Incorporate profit and cost metrics to enable profitability analysis alongside sales performance.
- Add customer segmentation analysis to explore purchasing patterns across different demographic groups.
- Introduce forecasting models to estimate future sales trends and demand patterns.
- Expand regional analysis with geographic mapping visualizations for improved location-based insights.
- Include inventory and stock-level data to support inventory planning and vehicle demand analysis.
- Develop manufacturer and model-level performance dashboards for more detailed sales monitoring.
- Integrate real-time or automated data refresh capabilities to support ongoing business reporting.
- Add advanced drill-through functionality to enable deeper exploration of sales performance across regions, vehicle categories, and customer segments.

## 13. Author

**Godwin Deborah**  
Data Analyst

- LinkedIn: https://www.linkedin.com/in/godwin-deborah-163b10398/
- GitHub: https://github.com/GodwinDeborah
- Email: debbiegodwin001@gmail.com
