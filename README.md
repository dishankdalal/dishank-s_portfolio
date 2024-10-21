# Dishank's Portfolio

# World Life Expectancy Project
This project focused on cleaning and refining a life expectancy dataset for accurate analysis. Key steps included:

Duplicate Removal: Detected and removed duplicate entries using ROW_NUMBER() and GROUP BY on country-year combinations, ensuring unique records.

Handling Missing Status: Filled blank "Status" values (Developed/Developing) by inferring data from existing rows, using SQL joins to update records consistently.

Filling Life Expectancy Gaps: Interpolated missing life expectancy values by averaging data from adjacent years and updating missing fields accordingly.

# Life Expectancy Analysis
In this project, I conducted a comprehensive analysis of global life expectancy trends using a dataset from the World Health Organization. Key insights include:

1) Life Expectancy Improvement: I identified countries with significant increases in life expectancy over time, calculating the minimum and maximum values for each country to assess their progress.

2) Temporal Trends: I examined the average life expectancy for each year, revealing a consistent upward trend, indicating improvements in health outcomes over the decades.

3) GDP Correlation: The analysis explored the relationship between GDP and life expectancy, showing that lower GDP often correlates with lower life expectancy. I categorized countries based on GDP levels and compared life expectancy averages.

4) Development Status Impact: I investigated how a country’s development status (developed vs. developing) affects average life expectancy, providing insights into health disparities.

5) BMI Influence: I analyzed the correlation between average Body Mass Index (BMI) and life expectancy in developed countries, highlighting trends that suggest lower BMI can relate to lower life expectancy.

6) Rolling Mortality Totals: I computed the rolling total of adult mortality over a 15-year span for each country, offering a deeper view of mortality trends and their potential impacts on life expectancy.

## This analysis utilizes advanced SQL queries to extract meaningful patterns and correlations, contributing to a better understanding of global health dynamics.
