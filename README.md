# Pymaceuticals: matplotlib-challenge

Pymaceuticals Inc. specializes in anti-cancer pharmaceuticals and has begun screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In their most recent animal study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

This script: 

1. Checks the data for any mouse ID with duplicate time points and removes any data associated with duplicate mouse IDs.

2. Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

3. Generates a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

4. Generates a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

5. Calculates the final tumor volume of each mouse across four of the most promising treatment regimens, as well as the quartiles and IQR, and then quantitatively determines if there are any potential outliers across all four treatment regimens.

6. Using Matplotlib, generates a box and whisker plot of the final tumor volume for all four treatment regimens and highlights any potential outliers in the plot by changing their color and style.

7. Selects a mouse that was treated with Capomulin and generates a line plot of tumor volume vs. time point for that mouse.

8. Generates a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

9. Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plots the linear regression model on top of the previous scatter plot.

The notebook also includes three observations made from the data. 
