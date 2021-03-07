

# Matplotlib Homework - The Power of Plots
# Meriane Franco


## Background

In this assignment, 2 files were used to generate charts and stat outputs using pandas, matplotlib and scipy.

The data gave insights related to different drug regimen on reducing tumor size in mice in different timepoints.

## Cleaning the data

A mouse that got duplicated measurements was removed from the data analysis.
The clean data was used in the further steps.

## Data Analysis


* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen was generated.

* Bar plots using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study was plotted.

* A pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study was presented.

* The final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin was calculated. The quartiles, IQR and outliers across all four treatment regimens were displayed using MatplotLib. Outliers are highlighted in red.

* A mouse that was treated with Capomulin was selected and a line plot of tumor volume vs. time point for that mouse was generated.

* A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen was provided.

* The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment was calculated. The linear regression model was ploted on top of the previous scatter plot.

* Some observations from the data are commented in the beginning of the notebook.

