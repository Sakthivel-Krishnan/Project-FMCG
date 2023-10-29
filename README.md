# Project-FMCG
Data Analysis: Gain insights into customer behavior, product profitability, and order trends.
Interactive Dashboard: Easily navigate through data and customize your analysis.
Visualizations: Visualize data using charts and graphs to make informed decisions.
Data Sources
Orders: Contains information about orders, including Order ID, Order date, Customer ID, and Product ID.
Customers: Provides details about customers, such as Customer ID, Customer Name, Email, Phone Number, and more.
Products: Includes information on coffee products, including coffee type, Roast type, size, unit price, and profit.
Data Transformations
In the process of preparing the data for analysis, the following transformations were applied:

Customer Data Integration: Customer Name, Email, and Country were added to the Orders worksheet using the XLOOKUP function, matching on the Customer ID column.
Product Data Integration: Coffee Type, Roast Type, Size, and Unit price were filled in from the Products worksheet using the INDEX and MATCH functions.
Sales Calculation: The Sales column was calculated by multiplying the Unit Price and Quantity from the Orders worksheet.
Coffee Type and Roast Type Abbreviations: Abbreviations in the Coffee Type and Roast Type columns were expanded using the IF function.
Pivot Tables
To create meaningful graphs and filters for the dashboard, the following Pivot Tables were built:

Total Sales Pivot Table

Technologies and Functions Used
Microsoft Excel: Used for data processing, analysis, visualization, and dashboard creation.
XLOOKUP: Used to search for specific information (such as Customer Name, Email, and Country) based on the Customer ID and populate these details in the respective columns, enhancing the dataset for analysis.
Usage
Navigate through the different worksheets (Orders, Customers, and Products) to explore the data. Utilize the Pivot Tables to create graphs and apply filters for deeper insights. Interact with the dashboard to analyze sales data, customer behavior, and product performance. Refer to the visualizations and data to make informed decisions.

Results/Insights
Identify sales trends for different coffee types over time.
Analyze the impact of loyalty cards on customer spending.
Discover the top-performing countries and customers.
Gain insights into product preferences and profitability.
Use filters to customize your analysis and uncover actionable insights.
