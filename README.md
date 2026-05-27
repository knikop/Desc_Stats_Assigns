# Desc_Stats_Assigns
## 420-972-VA --- Assignments for Descriptive Statistics for Data Science 


#### Assignment 1: Customer Satisfaction Survey Analysis
This project involves acting as a Data Analyst to process and analyze a dataset containing 200 customer satisfaction survey results. The primary goal is to use Excel to clean, manage, and perform descriptive statistical analysis on variables such as age, gender, satisfaction scores, and time spent on the company website.

The initial phase focuses on data cleaning and standardization within a dedicated "Cleaned_Data" worksheet. Key tasks include standardizing country names, removing rows with missing or invalid data, converting text to proper case, and implementing Data Validation to ensure satisfaction scores remain within a 1–10 range. A legend table is also required to define each variable type for clarity.

Once the data is cleaned, the project moves into Descriptive Statistics, where various Excel formulas are used to calculate central tendency and dispersion. Specific metrics computed include the mean, median, and mode for age, as well as the standard deviation and variance for satisfaction scores. Additionally, the analysis calculates the percentage of female respondents and site usage extremes.

The final segment involves filtering and visual formatting to highlight key business insights. The data is filtered to isolate "High Satisfaction" customers (scores ≥ 8) from specific regions like the USA or UK. Conditional formatting is then applied to visually flag low satisfaction scores and high time-on-site values, while professional table styles and frozen headers ensure the final report is readable and well-organized.

#### Assignment 2: Sales Performance Data Analysis
This assignment focuses on analyzing a tab-delimited sales dataset to evaluate regional performance, salesperson productivity, and product trends. The dataset includes detailed transaction records with columns for Date, Region, Salesperson, Product Category, Units Sold, Revenue, Profit Margin, and Customer Rating.

A critical component of this project is the Data Cleaning and Importing process, which must be documented in a summary worksheet. This involves handling duplicate elimination, fixing invalid values that fall outside expected ranges, and managing missing data. Special attention is paid to technical formatting issues, such as removing extra tabs and spaces that may interfere with the data import.

The analysis phase requires calculating specific business Totals and Calculated Cells. This includes determining the total units sold, identifying the top-performing product category, and calculating the total profit for specific individuals based on revenue and profit margins. Analysts also calculate targeted metrics, such as total revenue for specific categories like "Clothing" within the North region.

Finally, the project emphasizes Data Visualization to communicate insights effectively. It requires the creation of at least five different chart types—such as Histograms, Scatter Plots, and Box & Whisker Plots—to visualize distribution, relationships, and regional revenue trends. Each chart must include a professional title, labeled axes, and a brief interpretation describing the specific insights revealed by the data.

#### Assignment 3: SQL Database and Amazon Sales Analysis
This project transitions data analysis into SQL database environments (such as SQLite or PostgreSQL) to handle larger, more complex datasets. The primary dataset used is the Amazon Sales Dataset, which contains product listings, discounted pricing, user ratings, and review details. Alternatively, a custom CSV with at least 500 rows and multiple numerical columns may be used.

The technical workflow begins with Data Loading and Basic Exploration. This includes creating a new database, importing the CSV as a table, and executing metadata queries to verify row counts and column types. This stage ensures the data is correctly structured and ready for deep querying.

The core of the assignment involves writing SQL queries for Descriptive Statistics. Queries are developed to calculate the count, minimum, maximum, average, median, and standard deviation for numerical columns like "discounted_price" or "rating". Furthermore, Grouped Statistics are used to aggregate these metrics by categorical variables, such as calculating the average rating or total count per product category.

The final tasks involve Filtering and Conditional Queries to extract specific performance tiers. This includes identifying rows where values exceed the overall average and retrieving the top and bottom 10 values for specific numerical columns. The final submission is a comprehensive package including the SQLite database and a document containing all SQL statements and their corresponding output results.

#### Key Skills:

1. Data Cleaning and Preprocessing
   - Data Standardization: Cleaning and standardizing categorical data, such as converting text to proper case and unifying inconsistent country names (e.g., "usa" to "USA").
   - Integrity Management: Identifying and removing rows with missing or invalid data, and performing duplicate elimination.
   - Data Validation: Implementing constraints to ensure data entry accuracy, such as restricting satisfaction scores to a specific 1–10 range.
   - File Importing & Formatting: Importing various file formats (CSV, Tab-delimited TXT) into analytical environments and fixing technical formatting issues like extra tabs or spaces.

2. Statistical Analysis
   - Descriptive Statistics: Calculating measures of central tendency (Mean, Median, Mode) and measures of dispersion (Standard Deviation, Variance, Range) using both Excel formulas and SQL queries.
   - Grouped Aggregations: Performing segmented analysis to find averages, counts, and extremes (min/max) based on specific categories like product type or gender.
   - Metric Development: Calculating custom business KPIs, such as profit margins, total revenue for specific regional sub-sections, and percentage-based distributions.

3. SQL & Database Management
   - Relational Database Operations: Creating databases, importing tables from external datasets, and verifying data structure through metadata queries.
   - Advanced Querying: Writing complex SQL statements to filter data based on conditional logic (e.g., retrieving records that exceed an overall average).
   - Data Ranking: Using SQL to isolate top and bottom performance tiers through ordering and limit-based queries.

4. Data Visualization
   - Advanced Charting: Creating a diverse range of visualizations, including Histograms, Scatter Plots, Box & Whisker Plots, and TreeMaps, to reveal distributions, trends, and relationships.
   - Conditional Formatting: Using visual cues (e.g., color-coding) to highlight critical values, such as low satisfaction scores or high engagement times.
   - Insight Interpretation: Summarizing complex data findings into brief, actionable interpretations that describe what a visualization reveals about the business.

5. Tools & Technologies
   - Microsoft Excel: This was the primary tool for cleaning, managing, and analyzing datasets in the first two assignments.
      Specifically used for:
         - Advanced Formulas: Using functions like AVERAGE, MEDIAN, STDEV.S, COUNTIF, and COUNTA for statistical calculations.
         - Data Validation & Cleaning: Implementing rules to ensure data integrity and manually cleaning tab-delimited text files for import.
         - Worksheet Management: Organizing complex projects into multiple functional tabs such as Raw_Data, Cleaned_Data, Statistics, and Totals.

   - SQL Engines: Proficiency in systems such as SQLite, PostgreSQL, or MySQL for data exploration and descriptive statistics.
   
