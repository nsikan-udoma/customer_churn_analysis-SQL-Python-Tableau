# Customer Churn Analysis Using SQL, Python and Tableau

![Cropped - Customer Churn Dashboard](https://user-images.githubusercontent.com/24312721/224085369-e520eb0f-3e8e-4168-9993-53af01f0ea90.png)

<p align="center">
<em> Customer Churn Dashboard (Tableau) - See link to Dashboard at the bottom of this page </em> 
  </p>
  
  <br>
  
Dollar Bank Customer Churn Analysis using SQL + Python + Tableau:  An end-to-end project that involved exploratory analysis with SQL, a deep-dive EDA using Python, and building an interactive dashboard with Tableau to present meaningful business insights for the bank. 

Overall, the bank had a churn rate of 16%, meaning that 16% of customers stopped using the bank's credit card services in the given time period. Customer churn varied significantly by age, with the highest churn rates among customers in their 40's and 50's.
Customers with higher income earnings tended to have lower churn rates, while those with lower income earnings were more likely to churn. Most customers across all income categories owned blue credit cards, with the female blue credit card holders earning less than $40k churning the most. Customers who had a higher number of transactions and spent higher amounts per transaction tended to have lower churn rates, suggesting that engagement and activity were important factors in retaining customers.

Established customers - those who had been with the bank for 25 to 36 months – churned the most, with a churn rate of 5% for females and 3.6% for males. Additionally, long-term customers (those with the bank for 37-48 months) had the second-highest churn rate in both female and male customers, with rates of 2.8% and 2.3%, respectively. These findings suggested that the bank needed more efforts in retaining its established and long-term customers in all income categories. Pareto analysis was used to identify the 20% (vital few) area of interest for each custom demographic customer segment. And Targeted marketing ad campaigns were recommended to effectively target members of the 20% vital few. Campaigns included: Rewards and incentives e.g sign-up bonuses, or cash back rewards on purchases made with their credit cards. Another recommendation was partnering with fitness brands and offering discounts on gym memberships or workout gears to credit card customers of the bank.


SQL queries were used to explore and understand the data, and joining all 3 datasets was critical in answering research questions to generate valuable insights for the business. Python deep-dive analysis took this a step further by drilling down into the data to understand the different variables, their datatypes, summary statistics, checking for outliers, and assessing both data quality and tidiness issues that required data cleaning. Performing a distribution analysis for each variable identified unique values and variables that showed potential in providing useful business insights. A cross-correlation analysis helped to check for the relationship between variables and identify variables of interests that can help solve the business problem at hand; which is the ultimate question for the bank - "Why are customers churning?" See link below.

[Link to Python Notebook](Supporting%20Files/notebook.ipynb)


The Tableau dashboard highlighted the importance of understanding customer demographics, account information, and transaction behavior in predicting and preventing customer churn. Click the link below to use the dashboard.

[Link to Tableau Dashboard](https://public.tableau.com/app/profile/nsikan.udoma/viz/DollarBankCustomerChurnDashboard/CustomerChurnDashboard)
