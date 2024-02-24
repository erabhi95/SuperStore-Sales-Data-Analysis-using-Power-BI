# SuperStore Sales Data Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [KPIs Considered](#kpis-considered)
- [Data Cleaning](#data-cleaning)
- [Data Transformation](data-transformation)
- [Data Visualisation](#data-visualisation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview
This is a data analysis project that aims to provide insights into the sales performance of a SuperStore. By analyzing various aspects of the sales data , we seek to identify trends, gain a deeper understanding of the data and make data-driven recommendations to enhance the store's performance in terms of growth, efficiency and customer satisfaction.
Also, we seek to leverage the historic data to forecast the sales values for next 15 days.

**Final Report**

![Final Dashboard](https://github.com/erabhi95/SuperStore-Sales-Data-Analysis-using-Power-BI/assets/159037337/3ab05a47-b4bc-4e3f-bd4e-068419bab4ac)

**Sales Forecast**

![Sales Forecast](https://github.com/erabhi95/SuperStore-Sales-Data-Analysis-using-Power-BI/assets/159037337/440414ce-bca5-49e6-9c3b-190abaf56541)

### Data Sources
The primary dataset used for this analysis are the 'SuperStore Sales dataset' excel data , containing detailed information about the sales made by the store.

### Tools
Microsoft Power BI

### KPIs Considered
- Sales Amount
- Profit Amount
- Order Count
- Category
- Sub-Category
- Ship Mode
- Region
- Segment
- Payment Mode
- State
    
### Data Cleaning
1. Data loading and inspection.
2. Checking for correct data type and formating.
3. Removing blank rows and duplicates from the data.

### Data Transformation
1. Created new columns and measures using DAX queries to get more insights out of the available data which are further used during dashboard creation.
   
### Data Visualisation
1. Created an interactive dashboard using sales data that gives information about the sales trends as per user's choice.
2. Performed forecasting for next 15 days based on the historic data using Power BI.

### Exploratory Data Analysis
EDA is performed on the Sales data to answer some key questions, such as:
- What is the sales distribution as per different categories and sub-categories of products?
- What is the sales distribution as per different modes of shipping opted by the customers based on the delivery urgency?
- What is the sales distribution across different regions of United States?
- What is the sales distribution across various Segments depending upon usecase?
- What is the sales distribution across the diiferent modes of payment?
- What is the sales and profit distribution throughtout the year across months?

  
### Results
- Majority sales comes from the **Western & Eastern states(~60%)**.
- In west, **California** is the majorily contributing state with **more than 60% of total sales and more than 70% of total profit**.
- In east, **New York** is the majorily contributing state with **more than 40% of total sales and more than 75% of total profit**.
- Normal **Consumers** are the majority contributors to the **sales(~50%) and profit(~45%)** followed by **Corporates** with **sales(~30%) and profit(~30%)**.
- Majority sales happen via **COD and Online payment modes**.
- In **2019, October has the highest profit** despite average annual sales.
- In **2020, March has the highest profit** despite December having highest sales.
- In terms of Category, **Office Supplies and Technology contribute to majority sales(~70%) and profit(~95%)**.
- Top 5 Sub-categories of products in terms of sales are Phones, Chairs, Binders, Storage and Accessories.
- **Standard Class** is the most preferred Shipment Mode **contributing to majority sales(~60%) and profits(~55%)**.
- **Next 15 days sales** values has been forecasted with **confidence interval of 95%** depicts the sales values ranging between **2.2K to 9.4K** vales.

### Recommendations
Inorder to improve “SuperStore” Sales & Profits :
- **California in west and New York in east US should be analysed** specifically to look what's driving the higher sales in these states and the same should be used to revive sales in the Northern and Southern states of the country.
- In terms of payment modes, major spending should be done in **maintaining the Online & Cash On Delivery customers like more cash back schemes,sales offs on transactions** etc can be given.
- **Year end (specially December) is witnessing higher sales, so more offers should be rolled off** during that period of the year. Also, further analysis should be done to generate more profit from the increased sales during that period.
- **Office Supplies & Technologies inventories should always be maintained** properly as they the majority contributors to sales and profits. Also more schemes should be provided to their buyers. In addition to this, **feeback form can be rolled out to the customers of 'Furniture' to see their pain point** and plan further strategies accordingly.
- Since more customers are using **Shipment mode as Standard Class**, if possible, **try to reduce the delivery time period** which is currently 6 days.
- **As per the forecasted values, stocks should be maintained in advance** specially for demanding item categories like Office Supplies & Technologies.

