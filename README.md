# Pymaceuticals Matplotlib Challenge 

# Overview 
This is a technical report of a clinic animal study of 249 mice who were identified with SCC tumors. The mice received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

# Data Sources 
The data used was the complete data from the most recent animal study. The file names are "Mouse_metadata.csv" and "Study_results.csv". This data can be found in the "data" folder in the repository.  

# Technologies:
Python, Pandas, Matplotlib, Jupyter Notebook, 

# Analysis section 

- Capomulin and Ramicane report the smallest Final Tumor Volume (mm3)'s, indicating these are the most effective treatments (see Box Plot). 

- There is a high correlation between mouse weight and average tumor volume (0.84). Looking at the scatter plot with linear regression, we see a direct linear relationship between these two variables: as mouse weight increases, average tumor weight increases. 

- On the line plot of tumor volume vs. time point for a mouse treated with Capomulin, there is a slight growth in tumor volume between days 35 and 45. Longer time data would be useful here to look at the effects of Capomulin on tumor volume past day 45 to see if it would still be more effective than other treatments over the long run. 

# Figures

- Summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen
- Bar plot showing the total number of timepoints for all mice tested for each drug regimen
- Pie plot showing the distribution of female versus male mice
- Box plot that shows the distrubution of the tumor volume for each treatment group.
- Line plot of tumor volume vs. time point for a mouse treated with Capomulin
- Scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen
- Correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin regimen
