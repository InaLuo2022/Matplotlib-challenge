# Matplotlib-challenge
The purpose of this data analysis was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The data analysi include the following steps:
 -Prepare the data.
 -Generate summary statistics with bar charts and pie charts.
 -Calculate quartiles, find outliers, and create a box plot.
 -Create a line plot and a scatter plot.
 -Calculate correlation and regression.

Prepare the Data 
Merged original databases mouse_metadata and study_results and clean to get unique mice IDs related data.

Generate Summary Statistics
Create a DataFrame of summary statistics for each druge regimen with each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumour volume.

Create Bar Charts and Pie Charts
-Generate two bar charts in the Pandas DataFrame.plot() method and Matplotlib's pyplot methods individually to show the total number of time points for all mice tested for each drug regimen throughout the study.
-Generate two pie charts in DataFrame.plot() method and Matplotlib's pyplot methods to show the distribution of female versus male mice.

Calculate Quartiles, Find Outliers, and Create a Box Plot
-Calculate the final tumour volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
-Calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens.
-Determine outliers by using the upper and lower bounds, and then print the results.

Create a Line Plot and a Scatter Plot
-Select a mouse that was treated with Capomulin, and generate a line plot of tumour volume versus time point for that mouse.
-Generate a scatter plot of tumour volume versus mouse weight for the Capomulin treatment regimen.

Calculate Correlation and Regression
-Calculate the correlation coefficient and linear regression model between mouse weight and average tumour volume for the Capomulin treatment.
-Plot the linear regression model on top of the previous scatter plot.

