# Laptop Sales Performance Dashboard - 2008

An interactive dashboard created in Tableau to analyze and visualize key trends, geographic insights, and performance metrics from a UK-based laptop retail chain's 2008 sales data.

### ➡️ [View the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/LaptopSalesPerformanceDashboard/FinalDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---


## 🎯 Project Overview

This project was a group exercise to explore a complex dataset and design a single-screen dashboard for a retail company's management. The goal was to distill nearly 300,000 sales transactions from 2008 into a clear, interactive, and self-explanatory summary of business performance. The dashboard focuses on answering key questions related to sales over time, product configuration, price points, and geographic distribution.

## 📊 Key Insights & Findings

The dashboard reveals several key insights into the company's performance:

1.  **Sales Momentum:** There were significant sales spikes in late August and mid-December, likely corresponding to back-to-school and holiday shopping seasons.
2.  **Top-Selling Configurations:** Laptops with **15" screens**, **2GB of RAM**, and **2.4GHz processors** were the most significant drivers of revenue. These features represent the "sweet spot" for the 2008 market.
3.  **Optimal Price Point:** The majority of sales and revenue are generated from laptops priced between **£450 and £550**, indicating strong consumer demand in this mid-range bracket.
4.  **Geographic Concentration:** Sales are heavily concentrated in the **greater London area**, suggesting this is the primary market. There is a clear opportunity for targeted marketing in this region or expansion into other areas.
5.  **Value Proposition:** The "Value-for-Money" scatter plot shows that while some higher-priced models have higher performance scores, many average-priced laptops offer comparable performance, making them a better value for customers.

## 📈 Dashboard Components

The final dashboard is composed of several worksheets, each designed to answer a specific business question.

| Visualization | Purpose |
| :--- | :--- |
| **Sales Over Time** | A line chart showing daily revenue for 2008, with a trend line to illustrate overall growth. |
| **What features drive the sale?** | A treemap that visualizes total revenue broken down by key hardware features (Screen Size, RAM, CPU Speed). The size and color of each rectangle represent its revenue contribution. |
| **Sales Range** | A histogram showing the distribution of sales volume and total sales revenue across different price buckets. |
| **Value-for-Money Map** | A scatter plot that maps each laptop configuration by its retail price and performance score, helping to identify high-value products. |
| **Where Are Our Sales?** | A geographic map filled by postal code, showing the density of sales across the UK. |
| **Screen Size, RAM, CPU** | A series of bar charts that provide a quick look at the total sales for different screen sizes, RAM amounts, and processor speeds. |

**Interactivity:** The dashboard is highly interactive. Users can click on different hardware features in the treemap or bar charts to filter the entire dashboard, allowing management to dynamically explore how specific configurations performed across different price points and locations.

## 💾 Data Source & Preparation

The analysis is based on two CSV files:
* `LaptopSalesData.csv`: Contains transactional data for ~300,000 laptop sales in 2008, including date, configuration ID, and customer/store postcodes.
* `LaptopConfigurations.csv`: Contains hardware details for each laptop configuration model.

**Data Preparation:**
* The two datasets were **joined** in Tableau on the "Configuration" field to link sales transactions with their corresponding hardware specifications.
* The geographic locale in Tableau was set to the **United Kingdom** to correctly interpret and map the British postcodes.

## 🛠️ How to View

* **Live Dashboard:** The best way to experience the project is through the interactive version on **[Tableau Public](https://public.tableau.com/views/LaptopSalesPerformanceDashboard/FinalDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**.
* **Local File:** You can also download the `Laptop_Sales_Performance.twbx` packaged workbook file from this repository and open it using Tableau Desktop or the free [Tableau Reader](Laptop_Sales_Performance.twbx).
