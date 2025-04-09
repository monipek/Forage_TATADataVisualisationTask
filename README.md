# TATA Data Visualization: Empowering Business with Effective Insights Task

## Project Overview
As part of The Forage's TATA Data Visualization Virtual Experience Program, I completed a task focused on transforming raw sales data into actionable business insights using Tableau. The goal was to analyse an online retail dataset, by cleaning it, and creating visualisations that would guide the CEO and CMO in making expansion decisions.

## Data Cleaning & Preparation
Before any analysis could begin, I performed data quality checks to ensure the dataset was reliable. This involved:
- Filtering out invalid entries, such as negative quantities (returns), zero/negative unit prices (input errors) as well as nulls in the customer id column.
- Standardising country names (e.g., renaming "EIRE" to "Ireland") to avoid inconsistencies in geographic analysis.
  
## Visualisation

[click here to access the Tableau Dashboard](https://public.tableau.com/app/profile/monika.pekosz3314/viz/ForageTATADataVisualisationTask/Dashboard1)

The project required building four different visualisations in Tableau, each addressing a specific business question:

### 1. Monthly Revenue Trends (2011)
Business Question:

The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

Visualisation and Insights:
- A line chart showing revenue fluctuations throughout 2011.
- Identified seasonal peaks (e.g., November's £1.2M high, possibly due to Black Friday) and troughs (January's post-holiday slump).
- Insight: Recommending increased inventory and promotions ahead of Q4 to maximize holiday sales.

![image](https://github.com/user-attachments/assets/c3d720fe-bc75-4eb4-9185-6ac5988a988e)


### 2. Top 10 Revenue-Generating Countries (Excluding UK)
Business Question:

The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

Visualisation and Insights:
- A bar chart ranking countries by revenue and units sold.
- Highlighted top markets: Netherlands (£285K), Ireland (£266K), and Germany (£229K).
- Insight: Prioritising marketing and logistics investments in these high-performing regions.

![image](https://github.com/user-attachments/assets/826633c7-c9bd-4cbf-8bb0-df3962775dd3)


### 3. Top 10 Customers by Revenue

Business Question:

The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

Visualisation and Insights:
- A sorted bar chart displaying the highest-spending customers. When you hover on a bar you can see the country of given customer.
- Revealed that the top 3 customers contributed 18% of the total revenue.
- Insight: Implementing loyalty programs to retain these high-value clients.

![image](https://github.com/user-attachments/assets/12c5ad6c-da47-4c68-b70d-17e27b757b59)


### 4. Global Demand Heatmap

Business Question:

The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.

Visualisation and Insights:
- A color-coded world map visualising revenue concentration with labels of revenue in each country.
- Classified markets by colour, showing clearly where demand is the highest and lowest.
- Insight: Exploring localised fulfilment centres in top demand countries to reduce shipping costs.

![image](https://github.com/user-attachments/assets/80e3c1e1-df70-48a1-81e8-4c3a302ed215)


## Conclusion
This project was a good opportunity to apply real-world data analysis techniques in a business context. By cleaning, visualizing, and interpreting sales data, I helped uncover growth opportunities and operational efficiencies for a hypothetical retail expansion strategy.

---

**Tools Used**: Excel, Tableau
