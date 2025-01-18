# European Bank Customer Churn Analysis using Excel and Power BI
**PROJECT OBJECTIVE**

This project is undertaken to provide a detailed analysis of customer demographics, behaviors, and churn patterns of 10,000 customers at a European bank. The project will identify key churn predictors, examine regional differences in account behavior, and segment customers for targeted retention and marketing strategies.

**DESCRIPTION OF THE DATASET**

The dataset used for this project was downloaded from [Maven Analytics](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=bank), and contains account information for 10,000 customers at a European bank, including details on their credit score, balance, products, and whether they have churned. The original CSV file had a single table with 13 columns of partly clean data. The CSV file was first converted to an Excel file before importing into Power BI for transformation. 


**TOOLS AND TECHNOLOGIES USED**

**Excel:** Data cleaning and preliminary analysis.

**Power BI:** Data transformation, modelling, and visualization.

**Data Cleaning (Excel)**

As the dataset was already clean and almost ready for use, the major actions taken in Excel was Changing the values under 3 columns (HasCrCard, IsActiveMember, and Exited) to "Yes" and "No"

**Data Transformation (Power BI)**

This was the major tool used for this project. After the dataset was imported into Power BI, data transformations were performed. Four calculated columns were added to the table, and data type changes were made to three columns.

I used DAX to achieve the calculated measures and columns (e.g., Churn Rate, Total Customers, Average Account Balance, Oldest/Youngest Age, Age Group, Salary Group, Credit Score Group, etc).

**DATA VISUALIZATIONS AND DASHBOARDS**

The project has been visualized on a single dashboard with the following visual components for easy navigation and adequate understanding, and ultimately to draw key insights from the analysis to aid business decision making going forward;

* Bar charts for trend analysis.

* Pie chart for categorical breakdown by gender (male and female).

* Cards for metrics (Total customers, Oldest age, Oldest age, Average account balance, Churn rate, and Churned Customers).

* Filters and slicers for interactivity

* Tables for comparative analysis

* Reset button to return back to default after interactive analysis.

**INSIGHTS**

Some Key Insights from this project's data visualization are summarized below:

* **OVERVIEW**: The general overview of the data shows the project is based on 10,000 customers of the bank from across France, Germany and Spain, out of which 2,037 customers have churned and the churn rate is 20.37%. The oldest customer is 92 years, while the youngest is 18 years. The average account balance is €76,490.
The gender distribution shows that 54.57% of the customers are male, while 45.43% are female. Geographically, a greater percentage of the customers are from France, followed by Germany and Spain respectively.
The age distribution visual shows that a greater number of the customers are between the age 26 -55, with the leading age group being 36 - 45.
The bank equally have more customers who are high salary earners between €100,001 - €200,000, and the customer salary group visual shows that the number of customers increased as the salary goes higher.
![Overview](https://github.com/user-attachments/assets/69c1d779-c69f-46b2-8f4e-d49adcb82501)


* **KEY FINDINGS**: Here are some of the key findings deduced from navigating the visuals using the slicers

  1. France is where most of the customers are. 50.14% of the bank's customers are from France, and 810 of them have churned.
  2. Germany, with 25% of the total customers has the highest number of churners at 814.
  3. 24.77% of the customers are from Spain, and Spain has the least number of churners at 413.
  4. 54.57% of the customers are male and 45.43% are female.
  5. Of the 10,000 customers of the bank, only 5,151 of them are active with France still leading with 50% of the active customers.
  6. Spain surprisingly, has more active customers than Germany, and also has the least number of churners among the 3 countries.
  7. 55.66% of the active customers are male while 44.34% are female.
  8. 70% of the active customers are between the age of 26 - 45 years.
  9. Over 50% of the active customers are earning €100k and above.
      
![Active Customers](https://github.com/user-attachments/assets/81410e41-9119-41fc-91bf-aff07a5c0b40)
