# matplotlib-challenge

## Background

In an animal study using 249 mice with SCC tumor growths the mice were treated with a variety of different drug regimens. Over 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

The executive team has asked for a top level summary fo the study results which should consist of all tables adn figures needed for a techincal report.

## Data

- Check for duplicated data by 'Mouse ID' and 'Timepoints'. Remove any data associated with that mouse (exclude them from the study overall).
- Generate a summary of stats table per drug regimen
    - Mean
    - Median
    - Variance
    - Standard Deviation
    - SEM (sum of the error means)
- Generate bar plot displaying the number of total mice per drug regimen
- Generate pie plot displaying the number of female or male mice
- Calculate final tumor volume of each mouse across the four most promising treaments: Capomulin, ramicane, Infubinol, and Ceftamin
    - Quartiles
    - IQR
    - Outliers from stats across all tumor volumes of promising treaments
- Generate box and whisker plot of final tumor volume for all four treament regimens
    - Quartiles per regimen
    - IQR per regimen
    - Outliers per regimen & highlight with different color

- Select a mouse treated with Camopulin and generate a line plot of the tumor volume vs. time point for that specific mouse
- Generate a scatter plot of mouse weight vs. avg tumor volume for Capomulin treament regimen
- Calculate correlation coefficient and linear regression model between mouse weight and avg tumor volume for Capomulin treament. Plot the linear regression model on top of the previous scatter plot.

## Analysis

Looking at all figures and tables include at least 3 observations or inferences that can be made from the data and include this at the top of the notebook.

1. Neither gender nor mice population size per drug regimen group affected the results. There were between 24-25 mice per study and it was a 49% to 51% split between females and males.
2. Of the four most promising drug regimens [Capomulin, Ceftamin, Infubinol, Ramicane] Capomulin and Ramicane performed similarly to one another, while Ceftamin and Infubinol performed similarly to one another. Both Capomulin and Ramicane resulted in lower tumor volumes on average than Ceftamin and Infubinol. Out of the whole group there were no outliers when analyzed collectively and Infubinol only had one outlier when analyzed individually.
3. Using mouse g288’s results, Capomulin demonstrated a reduction in the tumor volume overall. There seemed to be a brief increase, then drop, brief increase, then drop that trended through the study.
4. When comparing weight to tumor volume we saw a moderate positive correlation between the two with a factor of 0.53.
