# World Population 1980-2020

### Project Overview

This project presents a comprehensive analysis of world population trends from 1980 to 2020 using Excel and Power BI. The primary goal was to explore population growth patterns, compare countries' populations over time, and visualize insights using interactive dashboards. The analysis focuses on population size, growth rates, and population density in different regions among others, helping to identify critical demographic shifts.

![world population pic](https://github.com/user-attachments/assets/1cf02cde-0e3c-4370-9c6c-daab8f618faf)


### Tools 

- Microsoft Excel: Data cleaning, transformation, and preliminary analysis.
- Power BI: Data modelling, visualization, and reporting.

### Data Sources
The dataset used for this project is contains historical population data from 1980 to 2020, including:

- Population Value: Total population of each country.
- Land Area: Area of each country in square kilometers.
- Country Names: List of countries globally.
- Date Table: Includes columns for year, month, and month number to support time-based analysis among many others.

### Methodology

- Data Cleaning and Preparation (Excel)
1. Imported the world population dataset into Excel.
2. Verified the integrity of data and removed duplicates.
3. Handled missing values by either imputing or removing based on the context.
4. Ensured proper data formatting, particularly for population values and years.

- Data Modeling (Power BI)

1. Imported the data from Excel into Power BI and further cleaned and normalize the data.
2. Created a Date Table to structure time-based analysis, with columns for the Date, year, month, and month number.
3. Created relationships between the Date Table, the Consolidated World Population Table, YearLookUp Table, Country Code, and Country_Land Areas Table to enable time intelligence functions.
4. Consolidated the data by unpivoting other columns and joining the Datasets together.
5. Added calculated columns density (population/land area) to enrich the analysis.
6. Added Power BI Scroller to show the world population in 1980 and also to enhance the analysis.
7. Added a customized list of country TopoJSON file for Shape Map.
8. Used customized Shape Map to show World Population in 2020. 

### Exploratory Data Analysis (EDA)
In this phase, I explored the dataset to uncover patterns and trends in the world population between 1980 and 2020. The key questions I asked and insights discovered during EDA include:
1.	Show the geographical representation of the world population in 2020?
2.	Which country has the highest population in 2020 and what is the Population value
3.	 Which country has the lowest population in 2020 and what is the population value?
4.	 What is the world population in 2020 and previous year population?
5.	 What is the world population in 1980?
6.	Show the countries with population of 200 million and above?
7.	What are the top 10 most populated countries in the world?
8.	Show the population of each country in 1980?
9.	What is the annual population growth rate?
10.	What is the population density from 1980 to 2020?




### Key Finding
- Population Growth Trends: From 1980 to 2020, the global population increased significantly from 3.99 billion in 1980 to 7.63 in 2020, with notable growth in countries such as China, India, and the United States.
- Top 10 Populated Countries: China and India consistently ranked as the most populated nations, while countries like Nigeria showed rapid growth in Africa.
- Population Density: Countries like Bangladesh and the Netherlands exhibited high population density due to limited land areas.
- Regional Shifts: While growth rate has been slowing in recent decades (1.09% in 2020), Africa and Asia saw the most significant increase in population growth due to higher fertility rates, while growth rates in Europe remained relatively stable or declined in some countries lower birth rates or aging population.

### Recommendations
- Sustainable Development: Countries experiencing rapid population growth, particularly in developing regions like Africa, need to prioritize sustainable resource management and control the birth rate to ensure economic stability.

- Urban Planning: Regions with high population density like the Bangladesh and the Netherlands should focus on efficient urban planning and infrastructure development to accommodate growing populations.

- Policy Formulation: Governments should use demographic trends to inform policies related to healthcare, education, and employment to ensure their populations thrive.
