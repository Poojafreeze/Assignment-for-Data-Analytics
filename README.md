# Food Ordering Data Analysis

The primary objective is to identify trends, uncover key business insights, and provide actionable recommendations based on customer preferences and behaviors.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Key Insights](#key-insights)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Code Features](#code-features)
- [Results](#results)
- [Recommendations](#recommendations)
  

### Project Overview

The project focuses on analyzing data from food orders, cooking sessions, and user demographics to understand patterns in customer behavior. Key analyses include the most popular dishes, order distribution by age group, and geographical ordering trends. These insights are valuable for businesses to enhance their marketing strategies and operational planning.

### Data Sources

The primary datasets used in this analysis are:

- UserDetails.csv: Contains user demographic information such as age, location, and registration details.
- CookingSessions.csv: Includes details of cooking sessions like session duration, ratings, and dishes prepared.
- OrderDetails.csv: Provides order-related data such as dish names, order statuses, amounts, and timestamps.

### Tools

The following tools and libraries were used for data analysis and visualization:
- Python: For data cleaning, manipulation, and visualization using the following libraries:
 - Pandas: Data manipulation and analysis.
 - NumPy: Numerical computations.
 - Matplotlib and Seaborn: Data visualization.
- Excel: For initial exploration and validation of data.

### Key Insights

Top 10 Most Ordered Dishes
- Insight: Dishes like "Grilled Chicken" and "Spaghetti" are highly popular, indicating a strong preference for fast food.
- Actionable Recommendation: Promote these dishes with combo offers or discounts to increase sales.
Orders by Age Group
- Insight: The 25-34 age group places the highest number of orders, followed by the 35-44 group.
- Actionable Recommendation: Focus marketing efforts on younger demographics through social media and digital campaigns.
Orders by Location
- Insight: Urban areas with high population density show the most significant order volume.
- Actionable Recommendation: Expand delivery services and increase marketing budgets in these regions.
Distribution of Orders by Age Group
- Insight: A significant percentage of orders come from middle-aged adults, emphasizing the need to cater to this demographic.
- Actionable Recommendation: Design loyalty programs and age-specific promotions.

### Exploratory Data Analysis

Key EDA questions addressed:
 - What are the most ordered dishes?
 - Which age groups place the most orders?
 - What are the geographical trends in orders?
 - How does the distribution of orders vary by age group?
EDA was conducted to clean the data, identify trends, and visualize patterns. Various charts, such as bar plots, pie charts, and heatmaps, were used to convey insights effectively.
   
### Code Features

This project demonstrates several interesting coding techniques:
-Data Merging: Combined multiple datasets using Pandas for a holistic analysis.

 ```
final_data = pd.merge(order_data, session_data, on='Order ID', how='inner')
 ```
### Results

The analysis results are summarized as follows:

- Top 10 Most Ordered Dishes
 - Popular dishes like "Pizza" and "Burger" dominate the orders, reflecting a strong preference for fast food items among customers.
Orders by Age Group
 - The majority of orders come from the 25-34 age group, followed closely by the 35-44 age group, highlighting the importance of targeting these demographics.
Orders by Location
 - High-order volumes are observed in urban and densely populated areas, suggesting the need to focus marketing and service expansion efforts in these regions.
Distribution of Orders by Age Group
 - Customers aged 26-50 drive the majority of sales, making them the key demographic for targeted campaigns and loyalty programs.

### Recommendations

Summary of Recommendations:
- Focus on fast food dishes by promoting top sellers.
- Design targeted marketing campaigns for the 25-34 age group.
- Expand delivery services in high-demand urban areas.
- Introduce age-specific loyalty programs to boost customer retention.

  
 

