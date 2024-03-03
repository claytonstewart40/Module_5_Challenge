# Module_5_Challenge
Module 5 Challenge
Got help from a tutor.  Location is pymaceuticals_starter-Copy1.ipynb.

Background
Joining Pymaceuticals, Inc., a burgeoning pharmaceutical company focusing on anti-cancer medications, involves diving into the latest research on squamous cell carcinoma (SCC), a common form of skin cancer. In a pivotal animal study involving 249 mice with SCC tumors, various drug regimens were administered, including Pymaceuticals' promising drug, Capomulin. The study, spanning 45 days, aimed to monitor tumor development and evaluate Capomulin's efficacy relative to other treatments.

Objective
The executive team has tasked you, as a senior data analyst, with analyzing the study's data to generate comprehensive tables and figures for the technical report, alongside providing a concise summary of the findings.

Getting Started
Files
Module 5 Challenge Files: Essential for initiating the analysis.

Data Preparation
Data Merge: Combine mouse_metadata and study_results DataFrames.
Data Cleaning: Identify and remove data for any mouse with duplicate time points, ensuring a clean dataset for analysis.
Unique Mice: Verify and display the count of unique mice IDs post-cleaning.

Analysis Tasks
Generate Summary Statistics
Summary DataFrame: Include mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.

Visualization
Bar Charts: Create two identical bar charts using both Pandas and Matplotlib to display the number of data points for each drug regimen.
Pie Charts: Generate two identical pie charts, again using Pandas and Matplotlib, to illustrate the gender distribution of the study mice.
Quartiles, Outliers, and Box Plot
Final Tumor Volume: Calculate for each mouse across Capomulin, Ramicane, Infubinol, and Ceftamin regimens.
Quartiles and IQR: Determine potential outliers across the four treatment regimens.
Box Plot Visualization: Use Matplotlib to create box plots for the final tumor volume of mice in each treatment group, highlighting outliers.

Additional Analysis

Line and Scatter Plots: Create a line plot of tumor volume over time for a mouse treated with Capomulin and a scatter plot of mouse weight versus average tumor volume for the Capomulin regimen.
Correlation and Regression: Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.



Conclusion
This README outlines the scope and objectives of the Pymaceuticals study analysis assignment. Through careful data preparation, statistical analysis, and visualization, this assignment aims to elucidate the effectiveness of various drug regimens in treating SCC, with a particular focus on Pymaceuticals' Capomulin, thereby informing future pharmaceutical developments and strategies.

Three observations: 
1.  Capomulin and Ramicane were the most effective medications to decrease the tumor voume size in mice.
2.  Looking at the line plot of tumor volume vs time point for a single mouse treated with Capomulin, it appears as though
   the medication starts to kick in in 20 days.  After that point, is when the tumor size starts to decrease, in that singular
mouse's case at least, it decreased by about 20% within two weeks, and then there was another increase in tumor size again.  This may indicate the need for a change in dosage or another strategy to continue to decrease the size of the tumor.
3.  There was a statistically significant positive correlation between the mouse's weight and the average tumor volume (.84),
   this would perhaps indicate that a diet with a caloric deficit, should be compounded with the medication regimen
 to decrease the size of the tumor sites.  
