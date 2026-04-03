# Hospitality Data Analysis 

This project focuses on analyzing hotel booking data to generate meaningful business insights and improve decision-making.

# Objective

The main goal is to explore booking patterns, occupancy trends, and revenue performance across different properties, cities, and room categories.

# Key Analysis Areas
1. Property & Booking Analysis
Identified unique property IDs across hotel bookings
Calculated total bookings per property
Detected cases where bookings exceeded property capacity
Highlighted properties with the highest accommodation capacity
# Data Cleaning
Handling Invalid Data
Removed records where the number of guests was less than zero, as these represent data errors
Missing Values
Observed a large number of null values in ratings
Instead of filling or removing them, retained these records to avoid bias in analysis
#  Outlier Detection (Revenue)
Focused analysis on RT4 (Presidential Suite) rooms since they have higher pricing
Used statistical method:
Mean + 3 × Standard Deviation
Conclusion:
No significant outliers were found in revenue data
#  Data Transformation
Created a new column: Occupancy Percentage (occ_pct)
Converted occupancy into percentage format for better interpretation
# Insights & Analysis
Room Category Insights
Calculated average occupancy rate for each room type
Mapped room categories like:
Standard
Premium
Elite
City-Level Insights
Compared average occupancy rate across cities
Analyzed average rating per city
Time-Based Analysis
Compared weekday vs weekend occupancy trends
Added August month data to extend analysis
Generated month-wise revenue trends
Revenue Analysis
Calculated revenue per city
Compared revenue by hotel type
Visualized revenue share by booking platform (pie chart)
# Key Takeaways
Occupancy trends vary significantly by room type and city
Weekend bookings may show different patterns compared to weekdays
Revenue distribution depends heavily on room category and platform
Data cleaning plays a crucial role in ensuring accurate insights
