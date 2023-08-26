# Practicum_project_3
My third project from Practicum course

What was used in the project: Python, Jupyter notebook. Libraries: pandas, matplotlib, seaborn.

Project Description

I'm an analyst at Crankshaft List. Hundreds of free advertisements for used vehicles are published on our site every day. I need to study data collected over the last few years and determine which factors influence the price of a vehicle.

# Steps
1) Data preprocessing.
   - Identify and study missing values
   - Convert the data to the required types
2) Calculate and add to the table the following:
   - Day of the week, month, and year the ad was placed
   - The vehicle's age (in years) when the ad was placed
   - The vehicle's average mileage per year
3) Carry out exploratory data analysis, following the instructions below:
   - Study the following parameters: price, vehicle's age when the ad was placed, mileage, number of cylinders, and condition.
   - Determine the upper limits of outliers
   - Use the filtered data to plot new histograms
   - Study how many days advertisements were displayed
   - Analyze the number of ads and the average price for each type of vehicle
   - What factors impact the price most? Take each of the popular types you detected at the previous stage and study whether the price depends on age, mileage, condition, transmission type, and color
4) Overall conclusion.

# Description of the data
The data is stored in the file vehicles_us.csv

## Description of columns:
'price'

'model_year'

'model'

'condition'

'cylinders'

'fuel' — gas, diesel, etc.

'odometer' — the vehicle's mileage when the ad was published

'transmission'

'paint_color'

'is_4wd' — whether the vehicle has 4-wheel drive (Boolean type)

'date_posted' — the date the ad was published

'days_listed' — from publication to removal
