# NovaBanc Loan Performance & Risk Analytics Dashboard

## Leveraging Power BI to Analyze Loan Portfolio Performance, Branch Profitability, and Credit Risk Across Africa

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/tim-gouw-KigTvXqetXA-unsplash.jpg?raw=true)


***Disclaimer⚠️:*** All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual mention. All info are dummy and design to demonstrate my capabilities of using PowerBI to perform advance analysis


## INTRODUCTION

For this case study, I analyzed data from Deskify's Office Supply, a fictional U.S. company specializing in office supplies, technology/computer accessories, 
and furniture. Serving both individual consumers and businesses with a diverse product portfolio, the company provided an ideal dataset for exploring sales performance. 
Using Power BI, I uncovered actionable insights to support data-driven decision-making around customer behavior, product performance, and overall business growth.



## PROBLEM STATEMENT
The organization currently depends on Excel for compiling, analyzing, and reporting its monthly sales and transaction data. It has become increasingly cumbersome and time-consuming due
to the complexity of the data and the high volume of transactions processed each month. Reporting process involves manual data entry, consolidation from multiple sources which introduces 
errors and inconsistencies.


## AIM OF THE PROJECT
- To build a data model using Deskify OfficeSupply Co.’s sales and transaction reporting by using Power BI. This solution will
centralize data sources and streamline data cleaning. By reducing manual processes, the project will improve reporting accuracy and efficiency.

- Build an interactive dashboards that will enable faster, data-driven decisions.
  


## METHODOLOGY 

Before building visuals, I had to clean and model the data to ensure the insights were reliable.

### Step 1: Data Cleaning & Preparation

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/data%20clean%20-%20deskify.JPG?raw=true)


### Step 2: Modelling & DAX

The data modeling for this project follows a clean Star Schema configuration, where the central Fact Table (Orders) links out to primary Dimension Tables (Orders, Customers, Location, Products, and a programmatic Calendar Table) through unique system identifiers.

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/deskify%20data%20model.JPG?raw=true)


I wrote DAX measures for:

- **Total Revenue**
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/TR-deskify.JPG?raw=true)


- **Total profit**
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/TP-deskify.JPG?raw=true)


- **Total Orders**
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/TO-deskify.JPG?raw=true)


- **Total Customers**
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/TC-deskify.JPG?raw=true)


- **Profit Margin**
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/PM-deskify.JPG?raw=true)


To support robust time-series calculations across the complete 2009–2012 matrix, a custom, standalone time dimension was generated directly inside the Power BI data model using DAX.


![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/calenderdim.JPG?raw=true)





## Step3: DASHBOARD REVIEW

The dashboard provides a comprehensive analysis of product and customer profitability over a four-year period, from 2009 to 2012. It incorporates interactive parameters 
that allow users to filter and view performance data for a specific year, enabling focused analysis and comparison of sales trends across different time frames.

1️⃣ **Product Insights**

Key KPIs, Total Profit by Product Category, Total Orders by Ship Mode, Top 10 Best Performing States by Profit, Total Profit by Product Name, and Total Profit by Month.

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/Product%20Analysis.JPG?raw=true)



2️⃣ **Customer Insights**

Key KPIs, Profitability by Customer Segment, Profitability by Product Sub-Category, Profitability by Customer, Profitability by Region 
and Customer Segment.

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/Customer%20Analysis.JPG?raw=true)



## KEY INSIGHTS

### **Revenue & Profitability**

Deskify generated **$14.74M in revenue** and **$1.52M in profit**, resulting in a **10.33% profit margin**. The business operates on a high-volume, low-margin model, making cost efficiency and operational optimization critical to profitability.

### **Product Performance**

* **Office Supplies** is the primary profit driver, contributing **64.7% ($985K)** of total profit.
* Top-performing sub-categories include **Binders ($260K)** and **Paper ($242K)**.
* **Technology** contributes only **13.5% ($206K)** of profit despite its strategic importance.
* **Copiers** are the only loss-making sub-category, generating **-$16K** in profit.

### **Customer Segments**

* The **Corporate** segment delivers the highest profit contribution (**$530K**), followed by **Home Office ($390K)**.
* A small group of high-value customers contributes a disproportionately large share of total profits, highlighting opportunities for customer retention and account management strategies.

### **Seasonal Trends**

Profitability demonstrates strong seasonality:

* Peak performance occurs in **September ($167K)** and **October ($177K)**.
* **August ($81K)** is the weakest month, indicating a significant seasonal slowdown that may require targeted promotional activity.

### **Regional Performance**

* **Northwest Territories** is the strongest-performing region, generating approximately **$569K** in profit.
* **Quebec ($14K)** and **Yukon ($6K)** show substantially lower profitability, suggesting opportunities for market expansion or operational review.

### **Shipping & Fulfillment**

* **Regular Air** accounts for **74% of all shipments**, making it the dominant fulfillment method.
* Heavy reliance on air freight may be limiting overall profitability due to higher transportation costs.

## RECOMMENDATIONS

* Review pricing, supplier agreements, and sales strategies for the **Copiers** category to eliminate losses.
* Develop targeted campaigns and promotions to address the **August profitability decline**.
* Optimize shipping operations by reducing dependence on costly air freight where possible.
* Introduce a **VIP loyalty program** for high-value customers and corporate accounts to improve retention.
* Increase investment in high-performing regions while reassessing strategies in underperforming markets.
* Leverage the strong demand for Office Supplies to cross-sell Technology products and improve category profitability.

## BUSINESS IMPACT

This analysis identified key profitability drivers, underperforming product lines, seasonal trends, customer concentration risks, and regional growth opportunities, providing actionable insights to support data-driven business decisions.

