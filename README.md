# The Power of the Plots

## Pymaceuticals

### Files
  * mouse_metadata.csv: raw data that includes basic information about each mouse
    * located in data
  * Study_resuls.csv: raw data that includes information of the trial 
    * located in data
  * pymaceuticals.ipynb: The coding language used in Visual Studio to complete analysis
  
 ### Coding/Analysis Procedures
  #### Data Cleaning
  * Check the data  for any mouse ID with duplicate time points and remove any data associated with that mouse ID.
  #### Summary Statistics Table 
  * For each drug:
      * mean
      * median
      * variance
      * standard deviation
      * SEM of the tumor volume for each drug regimen

  #### Bar Plot
  * Make two charts using the following:
    * 1. Panda's DataFrame.plot()
    * 2. Matplotlib's pyplot
    
  #### Pie Plot
  * Make two charts using the following:
    * 1. Panda's DataFrame.plot()
    * 2. Matplotlib's pyplot
  
  #### Quartiles, Outliers and Boxplots
  * Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin
  * Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
  * Boxplot
    * Plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
    * All four box plots should be within the same figure

  #### Line plot
  * Select a mouse that was treated with Capomulin (I used 'r157')
  * Generate a line plot of tumor volume vs. time point for that mouse.

  #### Scatter plot
  * Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

  #### Correaltion Coefficient & linear regression
  * Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment
  * Plot the linear regression model on top of the previous scatter plot.

  #### Observations and inferences
  * Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data.
  * Observations at the top of notebook.
