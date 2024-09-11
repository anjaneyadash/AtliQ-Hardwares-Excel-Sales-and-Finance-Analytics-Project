# AtliQ-Hardware-Excel-Sales-and-Finance-Analytics-Project
The goal is to create a detailed sales and financial report analyzing AtliQ Hardware's market performance for 2019, 2020, and 2021, providing key insights to support informed decision-making.

🎯 **Objective**

AtliQ Hardware is a retail company which offers a range of hardware products like PCs, keyboards, printers, and more. Serving clients such as Croma, Amazon, Best Buy, and Flipkart, the company aims to leverage data from files containing over 1.5 million records to generate comprehensive sales and financial reports, as requested by AtliQ's business users.

➡️**Steps Taken to Create This Report**

**1 - ETL (Extract, Transform, Load)**

     ✅Loaded all the provided CSV files into Power Query.
     ✅Ensured there were no missing values.
     ✅Verified that all dimension tables contained a unique column.
     ✅Removed duplicate values.
     ✅Corrected all spelling errors.
     ✅Finally, loaded the files into a Data Model.

**2 - Data Modelling**
         
     ✅Connected all the tables using the star schema method.
     ✅Created a new table, dim_date, in Power Query with separate columns for date, month, and year.
     ✅Added a new column for AtliQ Hardware's fiscal year, which runs from September to August.
     ✅Connected the dim_date table with the other tables.

**3 - Pivot Table and Power Pivot**
        
     ✅Integrated the data model with a Pivot Table for quick data analysis.
     ✅Utilized Power Pivot to create new measures and columns.
     ✅Employed Power Query for seamless data transformation and connectivity.

**4 - DAX (Data Analysis Expression) measures **

     ✅Created over 10 new measures, including Net Sales for each year, Gross Margin, GM%, and COGS.
     ✅Used formulas like CALCULATE, SUM, and DIVIDE.
     ✅Created new columns with functions like RELATED, CALCULATE, and FORMAT.
     ✅Extracted quarterly months by adding four months to the calendar year for the fiscal year perspective.

**5 - Formatting and Report Design**

    ✅Applied conditional formatting to enhance data presentation.
    ✅Set rules for formatting numbers and text.
    ✅Highlighted important data.
    ✅Identified trends in the data.
    ✅Improved overall data readability for more effective analysis.

**Sales Report Insights:**

    📈Reviewed customer sales and growth percentages over the years in the Customer Performance Report.
    🎯Analyzed market performance against sales targets in the Market Performance and Sales Targets Comparison.

**Finance Report Insights:**

    📊Assessed financial performance across various time frames in the Profit and Loss (P&L) Reports by fiscal year and month.
    💹Derived market-based insights to benchmark P&L reports for comparative analysis by markets.

