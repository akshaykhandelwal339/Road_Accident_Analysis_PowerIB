Overview
This project focuses on analyzing car crash data using SQL queries and visualizing the results using Power BI. The dataset contains information about various aspects of car crashes, including crash dates, weather conditions, road conditions, and more. By extracting insights from this dataset using SQL queries, we aim to create meaningful visualizations using Power BI to better understand patterns and trends in car crashes.


Project Steps
Database Setup:

The project starts by creating a database table named crashes to store the car crash data. The SQL commands provided in the code are used to create the table and load data from a CSV file into it.

Data Cleaning:

SQL queries are used to clean and transform the data within the crashes table. Date values are formatted consistently, and columns are modified to appropriate data types.

Data Analysis:

SQL queries are executed to gather insights from the car crash data. Key analyses performed include:

Total counts of recorded crashes in the dataset.
Earliest and latest dates of recorded crashes.
Number of crashes reported per year.
Monthly crash counts for 2017 and 2018, with percentage change.
Creating New Dataset:

A new dataset named crash_new is created by filtering the original data to include only records from the years 2018 to 2022.

Exporting Data:

The cleaned and transformed data is exported to CSV files (crash_new.csv and crash_new2.csv) using SQL queries.

Power BI Visualization:

The exported CSV files are imported into Power BI for visualization. The Power BI application is used to create charts, graphs, and dashboards to showcase the insights gained from the SQL analysis. Various visualizations can be created to represent crash trends, correlations, and patterns.
Total Crashes Overview
The project begins with an overview of the total number of crashes in the dataset.
Injuries Fatal: 698
Injuries Incapacitated: 12,000
Total Crashes: 545,848
Lighting Condition Analysis
A pie chart showcases the distribution of crashes based on lighting conditions.
First Crash Type Breakdown
A bar chart displays the distribution of crashes based on the first crash type.
Primary Cause Insights
A bar chart provides insights into the primary causes of crashes.
Top causes include "disregarding traffic signal," "failing to reduce speed," and more.
Road Defect Analysis
A bar chart shows the distribution of crashes based on road defects.
Weather Condition Breakdown
A bar chart displays the distribution of crashes based on weather conditions.
Total Crashes by Primary Cause
A stacked bar chart illustrates the total number of crashes, further divided by primary cause.
Time Series Analysis
Line charts depict the trends of total crashes over the years, quarters, months, and days of the week.
Street-wise Crash Analysis
A bar chart showcases the total crashes based on street names.
Injuries Fatal by Street Name
A bar chart illustrates the distribution of fatal injuries based on street names.
Day of Week Analysis
A heatmap displays the distribution of crashes based on years and days of the week.
Street Direction Analysis
A heatmap showcases the distribution of crashes based on years and street directions.
Monthly Crash Distribution
A heatmap displays the distribution of crashes based on years and months.
Report Type Analysis
A bar chart shows the distribution of crashes based on report types.

Use Power BI to create various visualizations such as:

Time Series Analysis: Plot the number of crashes over time to identify trends and patterns.
Yearly Crash Counts: Create a bar chart showing the number of crashes reported per year.
Monthly Analysis: Visualize monthly crash counts and percentage changes between years.
Geospatial Analysis: Use maps to display crash locations and hotspots.
Correlation Matrix: Explore correlations between factors like weather conditions, road conditions, and crash severity.

Conclusion
By combining SQL analysis with Power BI visualization, this project provides valuable insights into car crash data. The project showcases the potential of using SQL queries to clean and analyze data before creating compelling visualizations using Power BI. These insights can be used for making informed decisions related to road safety and accident prevention.
This Power BI project successfully transforms car crash data into meaningful insights through interactive visualizations. By exploring patterns, trends, and key metrics, the project provides valuable information that can contribute to informed decisions regarding road safety and accident prevention.


