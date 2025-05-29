# Zomato-Restaurant-Description:

This project involves the creation of an interactive Power BI dashboard using worldwide Zomato restaurant data. The goal is to extract actionable insights about global dining trends, city-level food culture, and restaurant performance.

# Objectives:
Analyze restaurant availability and ratings across countries and cities.
Visualize cuisine popularity and average pricing trends.
Track high-rated restaurants based on location and cuisine.
Provide insights into delivery services and online booking facilities.
Help users identify top restaurants by location, cuisine, and rating.

# Tools & Technologies:

Power BI Desktop
DAX (Data Analysis Expressions)
Power Query (for ETL)
Custom Visuals (Map, TreeMap, etc.)

# Power BI Features Used:

Slicers for Country, City, Cuisine
Map visuals for geographical insights
Card visualizations for KPIs (e.g. Avg Rating, Total Restaurants)

# Sample DAX:

Rating Category = 
SWITCH(
    TRUE(),
    'Zomato'[Aggregate Rating] >= 4.5, "Dark Green",
    'Zomato'[Aggregate Rating] >= 4.0, "Green",
    'Zomato'[Aggregate Rating] >= 3.5, "Yellow",
    'Zomato'[Aggregate Rating] >= 2.5, "Orange",
    'Zomato'[Aggregate Rating] >= 1.8, "Red",
    "White"
)

# Author:

Name - Pranay Sontakke

LinkedIn - www.linkedin.com/in/pranay-sontakke
