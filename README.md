# Matplotlib-challenge

A Python script "5.pymaceuticals_starter.ipynb" is created to do screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In this skin cancer study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.



* The data for any mouse ID with duplicate time points is checked and any data associated with that mouse ID is removed.

* A summary statistics table is generated, consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* A bar plot is generated, showing  the number of total mice for each treatment regimen throughout the course of the study.

* A pie plot is generated, showing the distribution of female or male mice in the study.

* The final tumor volume of each mouse across four of the most promising treatment regimens is calculated: Capomulin, Ramicane, Infubinol, and Ceftamin. 
 
* The quartiles and IQR and quantitatively are calculated to determine if there are any potential outliers across all four treatment regimens.

* A box and whisker plot of the final tumor volume for all four treatment regimens are generated and any potential outliers in the plot are highlighted by changing their color and style.

* A mouse that was treated with Capomulin is selected and a line plot of time point versus tumor volume for that mouse is generated.

* A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen is generated.

* The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment are calculated. The linear regression model on top of the previous scatter plot is plotted.
