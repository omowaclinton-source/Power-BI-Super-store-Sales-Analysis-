**Superstore Sales Analysis**

This project is a Power BI analysis of the Superstore dataset. I built the dashboard to get a clearer view of sales, profit, orders, customers, products, and sales trends over time. The main goal was to take a raw dataset and turn it into something that is easy to explore and useful for understanding business performance.



**Technologies Used**

Microsoft Power BI

Power BI was the main tool used for the project. I used it to build the data model, create the dashboard, develop the visualizations, and bring the analysis together in one place.

**Power Query**

I used Power Query to prepare the dataset before building the dashboard. This included checking the data, correcting data types, dealing with missing values, removing duplicates, and making the columns easier to work with.

DAX

I used DAX to create the calculations and measures needed for the dashboard. These measures were used for things such as total sales, total profit, total orders, average order value, shipping cost, and profit margin.

What the Dashboard Shows

The dashboard gives a quick overview of the overall performance of the business and also makes it possible to look more closely at individual products and sales trends.

**Overall Performance**

The main KPIs show total sales, total profit, total orders, total customers, average order value, total shipping cost, and profit margin.

Sales Trends

I looked at sales across the available years and months to see how performance changed over time. The yearly view makes it easier to compare overall performance, while the monthly view gives a closer look at how sales moved throughout the year.

Product Performance

The product analysis helped identify products with high sales and products making a strong contribution to profit. Looking at both measures together is useful because a product can have strong sales without necessarily generating the same level of profit.

Sales and Profit

The sales and profit comparison helped show how closely the two measures move together across products. It also made it easier to spot products that perform differently from the general pattern.

**My Process**

1. Getting the Data Ready

I started by importing the Superstore dataset into Power BI and reviewing the available columns and values.

2. Cleaning the Data

I used Power Query to prepare the data for analysis. I checked for missing values and duplicates, corrected data types, standardized formats, and made changes to columns where needed.

3. Building the Model

Once the data was ready, I worked on the data model and created the calculated measures needed for the analysis. I also checked that the fields were working correctly before using them in the visuals.

4. Building the Dashboard

I created KPI cards for the main business figures and added charts for yearly sales, monthly sales, product sales, product profit, and the relationship between sales and profit.

I kept the layout focused on the information that would be most useful when reviewing the performance of the business.

5. Reviewing the Results

After building the dashboard, I went through the results and checked the calculations and visuals. I compared the different views to make sure the trends and product results made sense.

**File Structure**

superstore_sales_analysis
|
|   data
|       Superstore_Data.csv
|
|   dashboards
|       Superstore_Sales_Dashboard.pbix
|
|   images
|       dashboard_preview.png
|
|   README.md
|   LICENSE

The data folder contains the dataset used for the analysis.

The dashboards folder contains the Power BI report file.

The images folder contains the dashboard screenshot used in this README.

The README file contains the project documentation.

**What I Learned**

This project gave me more practical experience working with Power BI from start to finish.

I became more comfortable with cleaning data in Power Query and creating measures with DAX. I also learned more about choosing the right visual for a particular question and arranging a dashboard so that the important information is easy to find.

One of the biggest things I took from the project was that creating a dashboard is not just about making charts. The visuals need to answer useful questions and make the data easier to understand.

**What I Would Improve**

There are several things I would like to add if I continued developing the project.

I would add more detailed analysis by region and category and create additional pages for customer and segment analysis. I would also explore more advanced DAX calculations and add forecasting to get an idea of how sales might develop in the future.

Another improvement would be connecting the report to a data source that can be refreshed regularly instead of relying on a static dataset.

**Common Issues I Came Across**

While working on the project, I had to pay attention to a few areas that can easily cause problems in Power BI.

Data types need to be correct before calculations are created. A number stored as text, for example, can cause unexpected results.

Missing values also need to be checked before analysis because they can affect calculations and visuals.

Relationships in the data model need to be set up correctly. If relationships or filtering behave unexpectedly, the results in the dashboard can also be affected.

DAX measures need to be checked carefully because a small mistake in a calculation or column reference can change the result.

I also learned that keeping the data model simple and removing columns that are not needed can help keep a report easier to manage.

**Final Thoughts**

This project was a practical way for me to put my Power BI skills into use. It helped me move from simply working with data to actually using it to answer business questions.

The final dashboard brings the main sales and profit information together in one place and gives a useful starting point for exploring the Superstore data.

If you have any feedback or suggestions for the project, I would be happy to hear them.
