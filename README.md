# Mid_Bootcamp_Project

### FIRST PROJECT

    * Albert Lleida Estival
    * Iron Hack, March - 2023



# Modeling Future Fire Damage in Catalonia: 
## A Linear Regression Model Using Temperature, Rainfall, and Forest Growth Data



#### Overview

Over the past few years, larger and more destructive forest fires have occurred not only in the Mediterranean basin but also in many areas around the world, such as California and Chile. What do they have in common? Their ability to destroy vast areas.

As temperatures continue to rise each year and longer droughts dry out the land, Catalonia faces an additional problem: 64% of its territory is covered by forest lands, and this ratio is increasing annually, particularly due to the economic decline of the agricultural sector.

Thus, we can say that the forests in Catalonia are fully loaded with fuel for future wildfires.


After gathering data on fires in Catalonia since 1999, I attempted to build a linear regression model to predict the number of hectares likely to be affected by future fires in the region. I also explored the relationship between the damage scope and the following features:

- Average annual temperatures (in Celsius)
- Average annual rainfall (in millimeters)
- Land use (forest/agriculture/urban/no vegetation)

All information has been imported from various tables included in the "Environment" and "Territory" subfolders of:

https://www.idescat.cat/indicadors/?id=aec&n=15177&lang=en.

For public institutions, such a model would facilitate decision-making in forest control. Predicting the areas affected by fires would allow them to estimate and compare the costs of prevention versus recovery strategies.




#### In this project:

#### Used:

    * Python
    * Jupyter Notebook
    * MySQL
    * Tableau
    * Linear Regression model (Confusion Matrix, X-y split, Train-Test split, MinMaxScaler, OneHotEncoding, Linear Regression, Error metrics)


#### Index:

     1. Importing dataframes
     2. Cleaning data
     3. Saving individual cleaned dataframes to 'csv' files.
     4. Reshaping and Merging
     5. Exporting/Importing tables from Jupyter Notebook to MySQL.
     
     6. Exploratory Data Analysis (both Jupyter Notebook and Tableau)
     7. Subset data for linear regression and Correlation Matrix.
     8. Linear Regression model, predictions and error metrics score (R2, RMSE, MSE and MAE).
     9. General results

    Tableau (Presentation link: https://public.tableau.com/app/profile/albert1030/viz/Mid-Project_16795179049110/Mid-Project?publish=yes )


