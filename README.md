# Adventure_Cycles_Analysis

## Project Overview
This project illustrates information from a global manufacturing company called Adventure Works Cycles*, by creating a dashboard to track KPIs, compare regional performance, analyze product-level trends, and forecast and identify high-value customers. Using Power BI, the raw data was connected and transformed, a relational model was built, calculated columns were created using DAX measures and a fully interactive report was designed with bookmarks and links to tie all the pages together.


## Resources
- Data source: `AdventureWorks_Calendar.csv`, `AdventureWorks_Customers.csv`, `AdventureWorks_Product_Categories.csv`, `AdventureWorks_Product_Subcategories.csv`, `AdventureWorks_Products.csv`, `AdventureWorks_Returns.csv`, `AdventureWorks_Territories.csv`, `AdventureWorks_Sales_2015.csv`, `AdventureWorks_Sales_2016.csv`, `AdventureWorks_Sales_2017.csv`   
- Software: `Power BI`
- Power BI Public Dashboard: 
 
## Results

### Relational Model

After loading and connecting all of the source data into Power BI a **Relational Model** was created so that all tables were related, and which enabled the sales data to be associated with any of the lookup tables.

![image](https://user-images.githubusercontent.com/91766276/159355510-709b5a52-9668-47a3-9e92-36fd573d52a2.png)

### DAX Calculations

These are some examples of DAX calculations that were created for this report. By using these functions and many more, calculated columns and measures were added to the model, allowing the creation of new important analysis to enhance the visualization of this project.

![image](https://user-images.githubusercontent.com/91766276/159356940-2752e3aa-edc0-4917-9cf2-d7fdd8c343b6.png)

![image](https://user-images.githubusercontent.com/91766276/159357080-75ca8e9e-85bc-476d-8439-755dc6566d8a.png)

![image](https://user-images.githubusercontent.com/91766276/159357218-9963c524-d646-4314-8fe7-baf613f0ed12.png)

![image](https://user-images.githubusercontent.com/91766276/159357380-e0216ca0-cccc-41a7-8057-3edee2846ff2.png)

### Visualization

The Executive Summary allows the client to break down the data and explore information by categories, product subcategories, it illustrates the core business KPIs (revenue, order volume and returns for current month). Also, it provides a snapshot of the most ordered products and the top revenue driving products. Finally, it allows the user to filter down the entire report by specific sales regions and it also includes a `Drill Through` functionality.

![image](https://user-images.githubusercontent.com/91766276/159361057-f4325f1e-8dab-4d42-9922-310ea06398e7.png)

#### How to interact with the report

As mentioned before the report is fully interactive. You can click on any continent, category or even subcategory and it will filter the entire page. 
In this example the report was filtered by **Country = Europe**, **Category = Bike** and using the **dates filter slicer** to show only information for the year 2017. Taking a close look to the subcategory table, the items that are related to the **Bike** category are highlighted, and the map is showing Europe only, further more the user can go deeper and click on any country to filter all the information.

![image](https://user-images.githubusercontent.com/91766276/159361598-fe438655-17b9-4c45-b0e1-bdee860450a9.png)


The `Drill Through` functionality allows the user to dive deeper into specific product performance. To access this function, the user will have to right-click on any specific product select Drill through -> Product Detail as shown in this picture:

![image](https://user-images.githubusercontent.com/91766276/159363322-cc1a2a0d-f7a8-4f7a-86a5-31ab015fa985.png)

This functionality takes the user to a new page that only shows product details for the desired product. Here, the user can find new insights like forecast, current month sales, orders and returns vs. target, impact of pricing adjustment on the company's profit. 

![image](https://user-images.githubusercontent.com/91766276/159363557-3aa3d87e-c55c-4278-8157-efda8143bcbd.png)

The pricing adjustment can be used to compare the company's profit by changing the product's price. On this picture, a price adjustment of 10% was selected and the graph illustrates it by creating a new line to compare Actual Profit vs. price change scenario. Additionally, there is a `Multi-Row Card` that shows what would be the adjusted price by incrementing it.

![image](https://user-images.githubusercontent.com/91766276/159363870-4e91b39f-52c0-4e9a-b09a-6fce44dc9e9e.png)

The final page of the report provides a view of all customers information, to analyze top revenue driving customers, different breakdowns by demographics like gender, income level and occupation. It also illustrates orders by age, top customers, and top line metrics.

![image](https://user-images.githubusercontent.com/91766276/159366216-06674271-5287-4416-ac1e-6b98517d193d.png)

