# Project #1
This repository includes the files for Project #1

## Raw Data
 - [Raw Data](AirQuality_Daily_StudentVersion.csv)

## Project Code
 - [Project Code](https://github.com/tyler-potthoff/Project-1/blob/main/Project%201%20Final%20Draft.ipynb)

## Prompts
 1. What are the 5 locations in Nebraska with the highest mean and median concentrations of VOC, PM 2.5 and PM 10.0?
 2. On what days did the maximum values occur and where did this maximums occur?
 3. Does humidity and temperature have a noticeable effect on air quality?
 4. Have there been any Air Quality Index (AQI) health risks (unhealthy for sensitive populations) at any of the locations in the dataset for PM 2.5 and PM 10 based on the EPA’s AQI ratings?
 5. Does the sensor altitude have an impact on the air quality values?

## Solution
### Step 1
 - All data is grouped by sensor name
 - The data is run through statistics of mean, median, max, and min
 - The locations with the top five worst mean and median are found for PM2.5, PM10, and VOC

### Step 2
 - The data is set from highest to lowest for the three variables
 - It's sorted into a table with categories: date, sensor name, and the max variable shown

### Step 3
 - Equations are made to separate the temperature and humidity into different sections to better differentiate the data
 - The data is set from highest to lowest for each variable
 - It's sorted into a table with categories: sensor name, temperature level, humidity level, and the max variables

### Step 4
 - The data is cut to only unhealthy events from the data for PM2.5 and PM10
 - It's then sorted into a table with categories: sensor name, PM2.5, PM10, and the date

### Step 5
 - An equation is made to separate the altitude into high, medium, and low
 - It's sorted into a table with categories: sensor name, altitude, and the max variable shown

## Results
### Step 1
 - PM2.5 and PM10 both have the same locations for the top five worst mean and median
 - VOC shares the sensor ELVPHD Norfolk HD 4, but none of the same for the other four

### Step 2
 - It is found that from a three day stretch in Broken Bow, from February 18th through February 20th, recorded the max for PM2.5, PM10
 - After research, I found out that it was a super cold stretch of days that didn't have much 
