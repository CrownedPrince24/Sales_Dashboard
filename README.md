# Operating Profit Analysis Dashboard

### Overview
This project presents an Excel dashboard that visualizes operating profit across multiple dimensions, providing insights into profitability trends by **Region**, **Product**, **Retailer**, and **Time**. The dashboard enables stakeholders to understand profit performance, identify high-performing categories, and make data-driven decisions.

### Contents
The Excel file in this repository includes the following key sheets:

- **Dashboard**: The main sheet where you’ll find interactive charts that display operating profit by different categories:
  - **Operating Profit by Region**: Visualizes which regions contribute the most to operating profit.
  - **Operating Profit by Product**: Shows profitability across various product categories, helping identify high-margin items.
  - **Operating Profit by Retailer**: Highlights which retailers generate the most profit, offering insights for partnerships and expansion.
  - **Operating Profit Over Time**: Analyzes trends in operating profit over months or years to reveal growth patterns.
  - **Operating Profit by Channel**: Reveals the operating orofit by channel distribution, enabling stake holders to know what channel is more proftable.
- **Raw Data**: Contains the raw data, including fields like First Name, Last Name	Title, Retailer,	Retailer ID,	Invoice Date,	Region,	State,	City,	Product,	Price per Unit,	Units Sold,	Total Sales,	Operating Profit,	Operating Margin	and Sales Method
- **Cleaned Data**: This is the sheet where all necessaring cleaning has been done, here I merged the First Name, Last Name and title to one single coumn as Full Name, I filled down the missing columns in the Retailer column using the fill option in teh excel power query, I converted the Invoice date data type from General to date, I also changed the data type of the Price per unit, Total Sales and Operating Profit to Currency format and indicated the currency with which the transaction was made, In conclusion I then converted teh Operating margin to percentage for easy assimilation by the user.
- **Pivot**: Supporting calculations and pivot tables used to generate the dashboard visuals. This sheet includes summaries and profit calculations for each category.

### Observations
Here are some key observations from the dashboard:

1. **Regional Profit Analysis**: In general, the Western region is more profitabe compared to others followed by the south and sout east region that are almost ties. 
2. **Product Profitability**: Men's Street Footwear has the highest Operating profit.
3. **Retailer Performance**: Kohl accounts for a significant share of operating profit, suggesting a strong partnership and customer loyalty.
4. **Customer Purchases**: Each customer made only a single purchase, with no repeat buyers in the dataset. This may suggest opportunities for customer retention strategies, as increasing repeat purchases could significantly impact future operating profit.
5. **Time-based Trends**: Operating profit spikes during August.
6. The KPI indicators indicate there are situation of no sales at all

### How to Use
1. **Download the Excel File**: Click on the Excel file in this repository and download it.
2. **Explore Each Chart**: On the **Dashboard** sheet, you’ll find visualizations showing operating profit across categories. You can click through each chart to gain different insights.
3. **View Raw Data**: Go to the **Data** sheet to explore the data that drives the analysis.
4. **Check Calculations**: For more detailed calculations, see the **Analysis** sheet, where you’ll find the supporting data for each chart.


### Technologies Used
- **Microsoft Excel** for data analysis and visualization.
