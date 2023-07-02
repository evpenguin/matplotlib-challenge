# matplotlib-challenge

The code for this challenge is contained in Jupyter Notebook 'pymaceuticals_challenge.ipynb' located in the main branch. 
It follows the structure of the starter code given, located in 'pymaceuticals_starter.ipnyb'. 

This code analyses some drug trial data on mice. 
We first cleaned the data by searching for and removing mice with duplicate entries.
We then calculated some basic summary stats for each drug, focusing on tumor volume. I calculated these individually and using the .agg method. 
We visualised the number of data points taken for each drug. We did this twice, with pandas and matplotlib.
We then looked at the distribution of male vs female mice in a pie chart, again using both pandas and matplotlib.
After this, we focused in on four treatments. We calculated quartile and outlier stats for the average tumor volume for each mouse on each drug, and then presented this in boxplots. 
We then visualised the tumor volume over the course of the treatment for a single mouse using a line graph. 
We also looked at whether there was a correlation bewteen mouse weight and average tumor volume. We looked at this in a scatterplot, then calculated the Pearson correlation coefficient. Finally, we redrew the scatterplot with a linear regression line. 
