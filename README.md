# SalesPrediction
E-commerce sales prediction using OLS regression

Introduction
About the Business:
Chown Market Place is an established player in the e-commerce industry. It serves its customers in
multiple locations, operating in 147 countries. The company sells products that are in 4 main categories
namely, Fashion, Electronics, Auto & Accessories, and Home & Furniture. As a result of their global
presence, our team is assuming that the company exercising dynamic pricing based on distinct
geographic locations.
Problems Statement: Stagnation of average growth rate in Sales
Indicators of the problem –
a) The average sales growth rate for the company over the year was 0.35% indicating stagnation (Figure 11 in
appendix).
b) Geographic performance discrepancies were identified, suggesting targeted expansion efforts in
underperforming regions such as Central Asia (Sri Lanka & Nepal), North Asia (Mongolia & Hong Kong), and
the Caribbean (excluding Cuba and the Dominican Republic).
 Team Chown | MMA 860 Report | CONFIDENTIAL
c) Products (such as "Curtains" and "Keyboards) performance discrepancies," which together accounted
for 2.43% of total orders, significantly impacted the overall sales due to their low average selling prices
(Curtains - $34 and Keyboard - $33) compared to the mean sales price of $156.43.

The dataset we are using is synthetic data that was pulled from Kaggle to mimic an E-commerce
company’s sales. There are two main components to the data set. The first is sales information such as
product type, shipping mode, and order Id. The second is customer information such as name, segment,
location, and market selection.
One assumption was made when interpreting this dataset as no description was provided, the value in the
‘sales’ column is total sales and not the sale price per product. This is because a common practice in
multinational business is to use dynamic pricing (different prices for different geographies) hence we see
that the total sale column shows the same amount for the distinct number of units sold.
We chose to do an OLS linear regression as sales is a continuous variable that we knew could be predicted
using the linear regression model. The building and testing of the model was entirely done in Python,
additionally, data exploration was also conducted in Python.
To demonstrate the relation among data more intuitively, we build a dashboard to help the management
team track sales performance and customer behavior while discovering potential business opportunities.
The data source comes from Excel and the dashboard will be built using Power BI. The dashboard consists
of four filters: date, discount, customer value group (high, medium, low), and high sales product(true and
false) to demonstrate the performance of different customer groups and products in each time series.
Maintain the consistency of the data (no change in data types and column names in Excel source) and
refresh data to ensure that the dashboard reflects the most up-to-date information for the management
team
