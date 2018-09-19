# Data Entry Analysis 

* Student: Kim Duong 
* Assignment: Data Entry Analysis 
* Due Date: 9/19/2018 

## Findings 

1. Missing data in certain column 
2. Columns are not placed in the order to make reading easier. For example, z values should not be placed in the second column and date should not be placed in the first column. Date should be listed in order rather than sectional for each species 
3. Some columns heading should label the measurement units. For example, whether the temperature is in Fahrenheit or Celsius 
4. One row is highlighted red but within the excel sheet which can cause some questions in Zoop file
5. One row has * as value which would make it hard to clean if using RStudio 
6. Analysis graph should not be placed in the dataset 
7. Inconsistent Naming Convention Problem - Heading column naming such as Cunni #/L can be confusion because the naming should be different rather than show the number of Cunni per length - perhaps state clearly like Density to combine three data file sets together 
8. Location – there is no column name for the location where measured values are taken 
9. Both zoop and zoop – temp-main files should be combined to avoid missing data between the dates 
10. Stating both species finding on the same row which makes data analysis in R be very complicated 



## Suggested Data Format 

**| Date | Species | Depth (m/ft) | Temp (F/C) | Density (units) | Colony Size | Chla | Location |  Z |** 

* Make sure to list Temp (F) or (C) 
* Make sure to state the units formula in the units - Density (units) 
* Make sure to state the units for depth in meter or feet 
* Not sure why Z value column is there but I just add in for extra information on the outcome spectrum analysis based on given datasets
