# Matplotlib Project: &nbsp;The Power of Plots

## Background

What good is data without a good plot to tell the story?

So, let's apply Python and Matplotlib to a real-world situation and dataset:

![Laboratory](Images/Laboratory.jpg)

Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, specializes in anti-cancer pharmaceuticals. &nbsp;In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

We have been given access to the complete data from their most recent animal study. &nbsp;In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. &nbsp;Over the course of 45 days, tumor development was observed and measured. &nbsp;The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. &nbsp;We have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. &nbsp;The executive team also has asked for a top-level summary of the study results.

## Steps

Our tasks were the following:

* Before beginning the analysis, checked the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID.

* Used the cleaned data for the remaining steps.

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

  * **NOTE:** These plots should look identical.

* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

  * **NOTE:** These plots should look identical.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: &nbsp;Capomulin, Ramicane, Infubinol, and Ceftamin. &nbsp;Calculated the quartiles and IQR and quantitatively determined if there were any potential outliers across all four treatment regimens.

* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.

* Selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

* Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. &nbsp;Plotted the linear regression model on top of the previous scatter plot.

* Looked across all previously generated figures and tables, and wrote at least three observations or inferences that can be made from the data. &nbsp;Included these observations at the top of the notebook.
