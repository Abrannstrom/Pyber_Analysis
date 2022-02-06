# Pyber_Analysis

## Project Overview
I've been given the following tasks to complete by V. Isualize of Elections on ride-sharing data by city type.

1. A ride-sharing summary DataFrame by city type
2. A multiple-line chart of total fares for each city type
2. A written report for the PyBer analysis (README.md)

## Resources
- Data Source: city_data.csv, ride_data.csv
- Sodtware: Python 3.7.6, Visual Studio Code, 1.38.1

## Summary
Deliverable 1 Requirements:

- The total number of rides for each city type is retrieved.
- The total number of drivers for each city type is retrieved.
- The sum of the fares for each city type is retrieved.
- The average fare per ride for each city type is calculated.
- The average fare per driver for each city type is calculated.
- A PyBer summary DataFrame is created.
- The PyBer summary DataFrame is formatted as shown in the example.

Result: 
![image](https://user-images.githubusercontent.com/63436684/152704542-16957e50-0bdc-4de7-a24b-91bf656a53de.png)

Deliverable 2 Requirements:

- A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
- A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
- A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.
- A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
- An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

Result: 
![image](https://user-images.githubusercontent.com/63436684/152704600-c335b8c5-3725-4447-9175-d03ece9ce68a.png)


