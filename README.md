# Matplotlib Homework - The Power of Plots

## Background

Based on the study that involves screening for potential treatments for squamous cell carcinoma (SCC), 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of the study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 
My task was to generate all of the tables and figures needed for the technical report of the study and a top-level summary of the study results.

## Process

Tasks included the following:

* Checking the data for any mouse ID with duplicate time points and removing any data associated with that mouse ID.

* Using cleaned data to generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generating a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

 * Generating a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

 * Calculating the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculating the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib to generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

 * Selecting a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generating a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

* Calculating the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotting the linear regression model on top of the previous scatter plot.

* Writing at least three observations or inferences that can be made from the data. These observations were included at the top of notebook.