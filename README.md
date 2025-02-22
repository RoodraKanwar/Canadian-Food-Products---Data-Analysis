# Food Price Inflation Analysis (2017-2024)

## Overview

The rising costs of food products have been a significant concern in recent times. This project analyzes food price inflation in Canada using data from Statistics Canada, covering different provinces from 2017 to 2024. The dataset includes 110 products and their prices over this period.

## Data Processing and Analysis
The following steps were undertaken to clean, transform, and analyze the dataset:

1. Data Cleaning: Column names were updated to improve clarity and better reflect the dataset.

2.Data Transformation: The dataset was pivoted to allow price comparisons across years within a single row. Previously, the data was structured in a single column format.

3. Quarterly Averaging: To mitigate extreme price variations, the average prices for the first quarter (Jan, Feb, Mar) of 2017 and the last quarter (Oct, Nov, Dec) of 2024 were calculated. This adjustment helped balance fluctuations that might disrupt the findings.

4. Inflation Calculation: The price inflation was determined using the first and last quarter averages.

5. Red Meat Price Trends: A line chart was plotted to analyze red meat price trends across the four most populous provinces—Alberta, British Columbia, Ontario, and Quebec.

6. Top 5 Inflated Products: A ranking system was created, accompanied by a bar graph with a dropdown to select provinces. Olive oil was consistently among the top 5 most inflated products across all four provinces.

7. Provincial Inflation Analysis: The average inflation rate across all provinces was calculated based on the 110 products. Ontario exhibited the highest inflation, while Newfoundland had the lowest.

8. Geo-Visualization: Inflation rates were visualized on a Canadian map. Due to missing data, Yukon, Northwest Territories, and Nunavut remain unrepresented.

## Visualizations

1. Line chart: Displays red meat price trends across four key provinces.

2. Overlapping Dropdown Bar graph: Showcases the top 5 inflated products per province with an interactive dropdown.

3. GeoMap: Visual representation of inflation rates across Canada.

## Key Findings

1. Food prices have significantly increased from 2017 to 2024.

2. Olive oil showed consistent high inflation across all four key provinces.

3. Ontario had the highest average inflation rate. This makes sense as the province of Ontario has the highest population. Newfoundland had the lowest.
