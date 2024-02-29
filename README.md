# Games-dataframe-analysis
The project aims to analyze a dataset related to video games, seeking insights from various perspectives. The following steps are taken in the analysis:

1. Data Wrangling:
-Import necessary libraries (pandas, numpy, matplotlib, seaborn, plotly).
-Read the dataset ('games.csv') into a Pandas DataFrame.
-Identify and note corrections to be made, including handling missing values and correcting data types.
-Convert column names to snake_case.
-Fill null values in specific columns with appropriate values.
-Add a new column 'total_sales' by summing sales from different regions.

2. Data Analysis:
-Explore the number of games released in different years and assess their significance over time.
-Identify the platform with the highest revenue and analyze its revenue trends over the years.
-Explore platforms that used to be popular but are no longer so.
-Analyze the time it takes for old platforms to disappear and new platforms to appear.
-Explore the sales trends of top platforms and identify how they have evolved over time.
-Examine the correlation between critic/user scores and total sales on a specific platform (PlayStation 2).
-Compare the revenue of games on PlayStation 2 to their revenue on other platforms.
-Analyze the profitability of different game genres.

4. Regional Analysis:
-Identify the top 5 profitable platforms in each region (North America, Europe, Japan).
-Explore the top 5 profitable genres on the top 5 platforms in each region.
-Analyze how ESRB ratings affect sales in different regions.
-The analysis provides insights into gaming trends, platform popularity, genre profitability, and the impact of ESRB ratings on sales in different regions. Visualizations, such as bar charts and scatter -plots, are used to present the findings.
