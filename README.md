# Electric_Vehicle_Analysis
### Overview
 This project analyzes pizza sales data using **Excel** and **SQL**. It includes data cleaning, creating pivot tables and dashboards in Excel, and performing SQL queries to analyze KPIs and Trends. The goal is to identify top-selling pizzas, uncover sales trends, and optimize sales strategies.
### 📚Table of Contents:
1. [Overview](#overview)
2. [Data Sources](#data-sources)
3. [Tools Used](#tools-used)
4. [Problem Statement](#problem-statement)
5. [Data Cleaning and Processing](#data-cleaning-and-processing)
6. [SQL Queries for Data Analysis](#sql-queries-for-data-analysis)
7. [Process](#process)
8. [Result and Findings](#result-and-findings)
9. [Recommendations](#recommendations)
10. [Conclusion](#conclusion)
### 🗂️ Data Sources <a name="data-sources"></a> 
- The dataset used for this analysis is the "Pizza_Sales_Data.csv" file, containing detailed information.
- You can download the dataset from the following link: [Pizza_Sales_Data.csv](https://github.com/Lohitha45/pizza-sales-analysis/blob/main/Pizza_Sales_Data%20.csv)
### 🛠️Tools Used <a name="tools-used"></a>
 - **Excel**: For data cleaning, analysis, and initial visualizations.
 - **SQL Server**: For querying and analyzing the dataset.

### ❓Problem Statement
 - ####  KPIs Requirement:

   ##### 1. Total Vehicles:
   - Understand the overall landscape of electric vehicles, encompassing both BEVs and PHEVs, to assess the market's size and growth.
   ##### 2. Average Electric Range:
   - Determine the average electric range of the electric vehicles in the dataset to gauge the technological advancements and efficiency of the EVs.
   ##### 3. Total BEV Vehicles and % of Total BEV Vehicles:
   - Identify and analyze the total number of Battery Electric Vehicles (BEVs) in the dataset.
   - Calculate the percentage of BEVs relative to the total number of electric vehicles, providing insights into the dominance of fully electric models.
   ##### 4. Total PHEV Vehicles and % of Total PHEV Vehicles:
   - Identify and analyze the total number of Plug-in Hybrid Electric Vehicles (PHEVs) in the dataset.
   - Calculate the percentage of PHEVs relative to the total number of electric vehicles, offering insights into the market share of plug-in hybrid models.
  
- #### Charts Requirement:

  ##### 1. Total Vehicles by Model Year (From 2010 Onwards):
  - Visualization: Line/ Area Chart
  - Description: This chart will illustrate the distribution of electric vehicles over the years, starting from 2010, providing insights into the growth pattern and adoption trends.
  ##### 2. Total Vehicles by State:
  - Visualization: Map Chart 
  - Description: This chart will showcase the geographical distribution of electric vehicles across different states, allowing for the identification of regions with higher adoption rates.
  ##### 3. Top 10 Total Vehicles by Make:
  - Visualization: Bar Chart 
  - Description: Highlight the top 10 electric vehicle manufacturers based on the total number of vehicles, providing insights into the market dominance of specific brands.
  ##### 4. Total Vehicles by CAFV Eligibility:
  - Visualization: Pie Chart or Donut Chart
  - Description: Illustrate the proportion of electric vehicles that are eligible for Clean Alternative Fuel Vehicle (CAFV) incentives, aiding in understanding the impact of incentives on vehicle adoption.
  ##### 5. Top 10 Total Vehicles by Model:
  - Visualization: Tree map
  - Description: Highlight the top 10 electric vehicle models based on the total number of vehicles, offering insights into consumer preferences and popular models in the market.

### 🧹Data Cleaning and Processing
1. **Removed duplicates** using Excel's built-in tool.
2. **Handled missing values** by filling blanks.
3. **Corrected formatting** issues, including text errors.
4. **Standardized data** to ensure consistency.

### 📂Process
1. Data Cleaning and Processing
2. Made sure data is consistent and clean with respect to data type, data format and values used.
3. Created pivot tables according to the questions asked.
4. Merge all pivot tables into one dashboard.
### 📊Result and Findings <a name="result-and-findings"></a>
![Screenshot (184)](https://github.com/Lohitha45/pizza-sales-analysis/blob/main/Screenshot%20(184).png)
### 🧐Key Findings
#### 1. Busiest Days and Times
- **Days**: Orders are highest on weekends, particularly on **Friday** and **Saturday evenings**.
- **Times**: Peak order times are between **12:00–1:00 PM** and **4:00–8:00 PM**.

#### 2. Category Performance
- The **Classic** category leads in both total orders and sales revenue.

#### 3. Size Contribution
- **Large-sized pizzas** generate the maximum revenue and contribute the most to total sales.

#### 4. Best Sellers
- **Classic Deluxe** and **Chicken Pizza** are the top-performing products, driving both orders and revenue.

#### 5. Worst Performer
- The **Brie Carre** has the lowest orders and revenue, ranking at the bottom in performance.

---
### 📈Recommendations <a name="recommendations"></a> 

1. **Boost Weekend and Evening Sales**  
   - Increase promotional offers or special deals during weekends and peak evening hours.

2. **Capitalize on Popular Products**  
   - Introduce combo offers or discounts on **Classic** and **Large-size pizzas** to maintain their popularity and increase revenue.

3. **Address Underperforming Products**  
   - Rethink the strategy for the **Brie Carre** by either marketing it differently or replacing it with a new flavor to cater to customer preferences.

4. **Enhance Operations During Peak Hours**  
   - Optimize staffing and operations during peak times (**12:00–1:00 PM** and **4:00–8:00 PM**) to handle higher order volumes effectivel
### Conclusion 
The pizza sales analysis reveals that weekends and evenings see the highest order volumes, with Classic and Large-sized pizzas leading in revenue. To boost sales, promotional offers during peak times should be introduced. The Brie Carre pizza underperforms and could benefit from better marketing or replacement. Optimizing staffing during peak hours will improve service efficiency. Continuous monitoring of seasonal factors and customer preferences will help adjust strategies for sustained growth.
