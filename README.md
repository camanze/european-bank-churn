# European Bank Customer Churn Analysis using Excel and Power BI
**PROJECT OBJECTIVE**

This project aims to provide a comprehensive analysis of customer demographics, behaviours, and churn patterns for 10,000 customers at a European bank. The analysis identifies key predictors of customer churn, examines regional differences in account behaviour, and segments customers for targeted retention and marketing strategies.

**DATASET DESCRIPTION**

The dataset, sourced from [Maven Analytics](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=bank), includes account information for 10,000 customers at a European bank. It contains 13 columns detailing credit scores, balances, products, and churn status. The data was converted from a CSV format to an Excel file and imported into Power BI for transformation and visualization. 


**TOOLS AND TECHNOLOGIES USED**

**Excel:** Data cleaning and preliminary analysis.

**Power BI:** Data transformation, modelling, and visualization.

**DATA CLEANING AND TRANSFORMATION**

1. **Excel:**
   * Cleaned and reformatted values for the "HasCrCard," "IsActiveMember," and "Exited" columns to "Yes" and "No."
2. **Power BI:**
   * Added four calculated columns using DAX to create metrics such as Churn Rate, Total Customers, Average Account Balance, and segmented groups (Age, Salary, and Credit Score).
   * Transformed data types for three columns to ensure consistency.
   * Used DAX to achieve the calculated measures and columns (Churn Rate, Total Customers, Average Account Balance, Oldest/Youngest Age, Age Group, Salary Group, Credit Score Group, etc).

**DATA VISUALIZATIONS AND DASHBOARDS**

The project has been visualized on 2 dashboards with the first page being for general analysis, while the second page focused on the Churned Customers. The following visual components were utilized for easy navigation and adequate understanding, and ultimately to draw key insights from the analysis to aid business decision making going forward;

* Bar charts for trend analysis.

* Pie chart for categorical breakdown by gender (male and female).

* Cards for metrics (Total customers, Oldest age, Oldest age, Average account balance, Churn rate, and Churned Customers).

* Filters and slicers for interactivity

* Tables for comparative analysis

* Reset button to return back to default after interactive analysis.

For Interactive Power BI report, click [here]()


**KEY INSIGHTS**

Some Key Insights from this project's data visualization are summarized below:

* **OVERVIEW**: The general overview of the data shows the project is based on 10,000 customers of the bank from across France, Germany and Spain, out of which 2,037 customers have churned and the churn rate is 20.37%. The oldest customer is 92 years, while the youngest is 18 years. The average account balance is €76,490.
The gender distribution shows that 54.57% of the customers are male, while 45.43% are female. Geographically, a greater percentage of the customers are from France, followed by Germany and Spain respectively.
The age distribution visual shows that a greater number of the customers are between the age 26 -55, with the leading age group being 36 - 45.
The bank equally have more customers who are high salary earners between €100,001 - €200,000, and the customer salary group visual shows that the number of customers increased as the salary goes higher.
![Overview](https://github.com/user-attachments/assets/69c1d779-c69f-46b2-8f4e-d49adcb82501)


**KEY FINDINGS**: Here are some of the key findings deduced from navigating the visuals using the slicers;

**General:** 

  1. France is where most of the customers are. 50.14% of the bank's customers are from France, and 810 of them have churned.
  2. Germany, with 25% of the total customers has the highest number of churners at 814.
  3. 24.77% of the customers are from Spain, and Spain has the least number of churners at 413.
  4. 54.57% of the customers are male and 45.43% are female.

**Active Customers**

  1. Of the 10,000 customers of the bank, only 5,151 of them are active with France still leading with 50% of the active customers.
  2. Spain surprisingly, has more active customers than Germany, and also has the least number of churners among the 3 countries.
  3. 55.66% of the active customers are male while 44.34% are female.
  4. 70% of the active customers are between the age of 26 - 45 years.
  5. Over 50% of the active customers are earning €100k and above, and 1,873 of them have zero balance.
  6. Using the 'Number of Products' slicer, you can see that 2,563 of the customers use 1 product, 2,446 of them use 2 products, and the number dropped drastically to 113 for customers that use 3 products and 29 for those that use 4 products.
  7. 3,607 of the active customers have credit card, while 1,544 don't.
      
![Active Customers](https://github.com/user-attachments/assets/81410e41-9119-41fc-91bf-aff07a5c0b40)

**CHURNED CUSTOMERS**: 

For a deeper understanding, page 2 of the dashboard is dedicated to churned customers. Germany has a greater percentage of the churned customers, followed by France and Spain.
* By gender, 55.92% are female customers.
* Although the bank customers are more males than females, there are more female churned customers than the men.
* Customers between the ages of 36 - 55 make up more than 50% of the churners.
* Over 51% of the churners earn €100k and above.

![Churned Customers](https://github.com/user-attachments/assets/58b0556e-7f26-4dfb-8937-9990aecb9a55)


**KEY FINDINGS**: Below are some of the key findings from navigating the Churned Customers visuals with the slicers;
  * A whooping 1,302 of the Churned customers are Inactive. This represents 64% of the total churned customers, 55.68% of which are female.
  * Majority of these inactive churners are between the ages of 36 - 55 and earn €100k and above.
  * 1,409 of the 2,037 total churned customers used 1 product, 348 used 2 products, 220 used 3 products, and 60 used 4 products.
  * 1,424 of the churned customers have credit card and 613 don't.

![Inactive Churned customers](https://github.com/user-attachments/assets/9a12c7ca-b073-4d4b-91d2-6f8816c8ce9e)

    
**CONCLUSION**   
1. Churn is highest among customers in Germany, particularly females aged 36-55 earning over €100,000.
2. Customers using only one product or maintaining zero balances are more likely to churn.
3. Active customers are predominantly younger (26-45) and higher earners, emphasizing the importance of retaining this demographic.
4. France has the largest customer base but relatively lower churn rates compared to Germany.   


**RECOMMENDATIONS**

1. **Targeted Retention Strategies:**

* Implement loyalty programs for high-earning customers aged 36-55.

* Focus retention efforts on German customers, especially inactive ones.

2. **Product Engagement:**

* Offer incentives for customers to use multiple products (e.g., bundled services).

* Educate customers on the benefits of additional financial products.

3. **Customer Segmentation:**

* Develop personalized engagement strategies based on demographic and behavioral data.

4. **Regional Focus:**

* Address churn in Germany through localized campaigns.

* Leverage Spain’s active customer base to replicate best practices elsewhere.

5. **Monitor Inactive Accounts:**

* Regularly review and engage inactive customers to prevent churn.

By addressing these areas, the bank can reduce churn, enhance customer satisfaction, and improve overall profitability.
