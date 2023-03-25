# Mid_Bootcamp_Project

### FIRST PROJECT

    * Albert Lleida Estival
    * Iron Hack, March - 2023



# Modeling Future Fire Damage in Catalonia: 
## A Linear Regression Model Using Temperature, Rainfall, and Forest Growth Data



#### Overview

Over the last years, larger and more virulent forest fires have occurred not only in the Mediterranean basin, but also in many areas around the world like California, Chile… What do they seem to have in common? Their greater capacity to destroy large areas.

As temperatures keep rising year by year and longer droughts dry the land, in Catalonia there is an additional problem: 64% of its territory it’s covered by forest lands and this ratio keeps increasing annually, especially due to the economical depreciation of the agricultural sector.

Hence, we can say that forests in Catalonia are fully charged with fuel for future wildfires.

After looking for data of fires in Catalonia since 1999, I attempted to build a Linear Regression model to predict the amount of hectares that are likely to be affected by future fires in the region and I also explored the relationship between their damage scope and the following features:

* Average Annual temperatures (celsius)
* Average Annual Rainfall (mm)
* Use of Land (forest / agriculture / urban / no vegetation)

##### All information has been imported from many of the tables included in:

    * https://www.idescat.cat/indicadors/?id=aec&n=15177&lang=en  (“Environment and Territory” sub-folders)


For public institutions, such a model would facilitate the decision-making in forest control, as long as predicting the areas affected by fires would allow them to estimate and compare the costs of prevention versus recovery strategies.




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

    Tableau (Presentation link: https://public.tableau.com/app/profile/albert1030/viz/Mid-Project_16795179049110/Mid-Project?publish=yes)


