# NovaBanc Loan Performance & Risk Analytics Dashboard

## Leveraging Power BI to Analyze Loan Portfolio Performance, Branch Profitability, and Credit Risk Across Africa

![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/bank%20image.png?raw=true)


***Disclaimer⚠️:*** All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual mention. All info are dummy and design to demonstrate my capabilities of using PowerBI to perform advance analysis


## PROJECT OVERVIEW

NovaBanc is a fictional pan-African commercial bank operating across multiple African countries, offering a wide range of financial products including Education Loans, SME Loans, Corporate Loans, Consumer Loans, Auto Loans, and Trade Finance.

As the bank continues expanding its lending operations, executive management requires a centralized reporting solution capable of monitoring loan growth, branch profitability, customer activity, and credit risk in real time.

This project demonstrates how Power BI can transform fragmented financial datasets into interactive business intelligence dashboards that support strategic lending decisions and operational excellence.



## PROBLEM STATEMENT

NovaBanc currently relies on manually prepared reports from multiple departments to monitor lending operations and financial performance.

This reporting process presents several operational challenges:

Portfolio Visibility

Management lacks a centralized view of loan disbursement performance across branches, countries, and loan products.

Credit Risk Monitoring

High-default loan products cannot easily be identified, making proactive risk management difficult.

Branch Performance Evaluation

Executives have limited visibility into which branches generate the highest revenue, profitability, and loan volumes.

Financial Reporting

Revenue, costs, and net income reporting require extensive manual consolidation, increasing reporting time and reducing accuracy.


## AIM OF THE PROJECT

* To design and develop an interactive Power BI dashboard using NovaBanc's existing retail banking data model and DAX measures. This solution will transform complex lending and financial data into intuitive visual reports, enabling stakeholders to monitor loan portfolio performance, branch productivity, profitability, and credit risk from a centralized dashboard.

* To create dynamic, interactive dashboards that provide real-time visibility into key banking KPIs, lending trends, branch performance, and financial metrics, empowering management to make faster, data-driven decisions through self-service analytics.

  


## METHODOLOGY 

Before building visuals, I had to clean and model the data to ensure the insights were reliable.

### Step 1: Data Cleaning & Preparation

![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Data%20Cleaning.JPG?raw=true)


### Step 2: Modelling & DAX

The data modeling for this project follows a clean Star Schema configuration, where the central Fact Table  links out to primary Dimension Tables (officer_dim, department_dim, branch_dim, customer_dim, and a programmatic Calendar Table) through unique system identifiers.

![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Data%20Model.JPG?raw=true)


I wrote DAX measures for:

- **Total Principal Disbursed**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Total%20Principal%20Disbursed%201.JPG?raw=true)


- **Total Loans Disbursed**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Total%20Loans%20Disbursed%202.JPG?raw=true)


- **Total Customers**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Total%20Customers%203.JPG?raw=true)


- **Average Loan Amount**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Average%20Loan%20Amount%204.JPG?raw=true)


- **Average Tenor (Months)**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Average%20Tenor%205.JPG?raw=true)


- **Total Revenue**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Total%20Revenue%206.JPG?raw=true)


- **Total Net Income**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Total%20Net%20Income%207.JPG?raw=true)


- **Net Profit Margin**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Net%20Profit%20Margin%208.JPG?raw=true)


- **Total Defaulted Loans**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Total%20Defaulted%20Loans%209.JPG?raw=true)


- **Default Rate (%)**
  
![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/Default%20Rate%209.JPG?raw=true)




To support robust time-series calculations across the complete 2009–2012 matrix, a custom, standalone time dimension was generated directly inside the Power BI data model using DAX.


![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/assets/calendar%20Dim.JPG?raw=true)





## Step3: DASHBOARD REVIEW

The dashboard delivers an end-to-end view of NovaBanc's lending operations by combining loan portfolio analytics with financial and risk performance metrics. Interactive slicers allow users to filter results by country, loan status, and year, making it easy to compare lending trends, monitor branch performance, and evaluate portfolio risk over time.

1️⃣ **Loan Performance & Portfolio**


![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/Loan%20Performance%20&%20Portfolio%20Dashboard.JPG?raw=true)



2️⃣ **Risk & Financial Performace**


![image](https://github.com/joel-adusei/Retail-Banking-Performance-Analysis--PowerBI-Case-Study/blob/main/Risk%20&%20Financial%20Performance%20Dashboard.JPG?raw=true)



## KEY INSIGHTS

- Loan Portfolio Performance

NovaBanc successfully disbursed approximately ₦25 Billion across 2,000 loans, serving 300 customers with an average loan amount of ₦12 Million and an average repayment period of 29 months.

- Lending Trends

Loan disbursement remained relatively stable throughout the year, with noticeable increases during March–April and August, indicating periods of stronger lending demand.

- Product Performance

Education Loans, Scholarship Loans, and SME Business Loans represent the strongest-performing products, reflecting sustained demand for educational financing and business expansion capital.

- Financial Performance

NovaBanc generated approximately:

₦12 Billion Total Revenue
₦4 Billion Net Income
30.14% Net Profit Margin

These figures indicate healthy profitability supported by effective cost management and diversified lending operations.

- Credit Risk

The overall portfolio records a 24.15% Default Rate, highlighting the need for stronger credit monitoring and risk mitigation strategies.

Salary Advance, Student Loans, and Mortgage Loans exhibit the highest default exposure and should be prioritized for enhanced credit assessment.

Branch Performance

Branches such as Accra Main, Cairo Branch, and Abuja Central consistently deliver strong financial performance, while other branches present opportunities for operational improvement and targeted growth initiatives.

## RECOMMENDATIONS

* Review pricing, supplier agreements, and sales strategies for the **Copiers** category to eliminate losses.
* Develop targeted campaigns and promotions to address the **August profitability decline**.
* Optimize shipping operations by reducing dependence on costly air freight where possible.
* Introduce a **VIP loyalty program** for high-value customers and corporate accounts to improve retention.
* Increase investment in high-performing regions while reassessing strategies in underperforming markets.
* Leverage the strong demand for Office Supplies to cross-sell Technology products and improve category profitability.

## BUSINESS IMPACT

This analysis identified key profitability drivers, underperforming product lines, seasonal trends, customer concentration risks, and regional growth opportunities, providing actionable insights to support data-driven business decisions.

