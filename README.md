# Flight Delay Analysis – Exploratory Data Analysis (EDA)

Author

Umesh Chandra

# Project Type

Data Analysis / Exploratory Data Analysis (EDA)

#Tools Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Dataset

# Flight Delay Dataset containing 4,821 flight records and 18 operational features.

# Project Overview

Air transportation plays a critical role in modern travel and logistics. Flight delays can cause passenger dissatisfaction, operational inefficiencies, and financial losses for airlines. This project aims to analyze flight delay patterns and identify the major factors contributing to delays.

Through Exploratory Data Analysis (EDA), we investigate departure delays, arrival delays, airport performance, weather impact, and airline operational efficiency.

# Problem Statement

Flight delays are a common challenge in the aviation industry. Understanding the causes behind these delays is essential for improving operational efficiency and customer satisfaction.

# Key Questions

What factors contribute most to flight delays?
Does departure delay influence arrival delay?
How significant is the impact of weather conditions?
Which airports experience higher delay frequencies?
How do operational factors affect airline performance?

# Objectives

 Analyze flight delay patterns

 Identify factors affecting delays

 Study the relationship between departure and arrival delays

 Evaluate weather-related disruptions

 Compare airport operational performance

 Generate actionable insights for improving flight schedules

# Dataset Information

Metric	Value
Records	4,821
Features	18
Missing Values	0
Duplicate Records Removed	8
Average Departure Delay	22 Minutes
Average Arrival Delay	19 Minutes
Data Quality Check
No missing values found.
Duplicate records removed successfully.
Dataset ready for analysis.

# Hypothesis
H1: Departure Delay Impacts Arrival Delay

Flights departing late are likely to arrive late.

H2: Weather Conditions Increase Delays

Severe weather contributes significantly to operational disruptions.

H3: Airport Traffic Influences Delays

Busy airports experience higher delay frequencies.

# Key Visualizations

## Departure Delay Distribution

![Departure Delay](Departure%20delay.png)

### Insight
Most flights experience small delays while a few flights show extremely high delays.

# Arrival Delay Distribution

![Arrival Delay](Arrival%20delay.png)

# Insight
Majority of flights arrive near schedule.
Few flights experience severe delays.
Presence of outliers indicates operational disruptions.

# Flight Distance Distribution

![Flight Distance](Flight%20distance.png)

# Insight
Most flights are short-to-medium haul.
Long-distance flights are comparatively fewer.
Distribution shows right skewness.

# Weather Delay Impact

![Weather Delay](Weather%20delay.png)

# Insight

Most flights are unaffected by weather.
Severe weather creates large delays for a small number of flights.

# Correlation Heatmap 

![Correlation Heatmap](Correlation%20heatmap.png

# Most Important Finding

Strong positive correlation exists between:

Departure Delay
Arrival Delay

This indicates that flights departing late generally arrive late as well.

# Professional Visualization Recommendation

For portfolio projects, include these three graphs only:

1. Departure Delay Distribution

Shows overall delay pattern.

2. Origin Airport vs Cancelled Flights

Compares airport operational performance.

3. Correlation Heatmap

Highlights relationships among all variables.

These provide maximum business insight while keeping the report professional.

# Major Findings

# Flight Delay Patterns

Departure and arrival delays are strongly related.
Delays vary throughout the week.
Most delays are relatively small.

# Airport Performance

Some airports handle significantly more flights.
Certain airports show higher delay frequencies.

# Weather Effects
Weather delays affect fewer flights.
When weather disruptions occur, delays become substantial.

# Airline Operations

Carrier-related issues contribute to flight delays.
Operational efficiency differs across airlines.

# Business Recommendations

# For Airlines

Improve departure schedule management.
Monitor flights with high departure delays.

# For Airports

Reduce congestion during peak hours.
Optimize runway and gate allocation.

# For Operations Teams

Develop contingency plans for adverse weather.
Improve coordination between airports and carriers.

# Conclusion

This Flight Delay Analysis project successfully explored operational factors influencing airline performance. The study revealed that departure delay is the strongest predictor of arrival delay, while weather and carrier-related issues contribute significantly to extreme delay cases.

The findings can help airlines and airport authorities improve scheduling efficiency, reduce delays, and enhance passenger satisfaction.
