Pymaceuticals, Inc. - Anti-Cancer Medication Study
Objective: To evaluate the performance of Pymaceuticals' drug of interest, Capomulin, in comparison to other treatment regimens. We are looking at data from a pharmaceutical company that works with anti-cancer medication. We will looking at how the different types of anti-cancer medication will affect mice, and the tumour volume on the mice.

In this study, 249 mice with squamous cell carcinoma (SCC) tumors were subjected to various drug regimens. Over 45 days, the development of tumors was observed and measured. The primary objective of this study was to evaluate the performance of Pymaceuticals' drug of interest, Capomulin, in comparison to other treatment regimens.

Instructions
Please open the file called: main.ipynb in the matplotlib-challenge/Pymaceuticals and run the code.

Project Tasks
The project tasks are divided into several steps, each contributing to a comprehensive analysis of the study results. Here's a breakdown of what I've done.

1. Prepare the Data
Import the required packages and load the data.
Merge the mouse_metadata and study_results DataFrames into a single DataFrame.
Identify unique mouse IDs and check for duplicate time points.
Create a cleaned DataFrame with duplicate data removed.

2. Generate Summary Statistics
Create a DataFrame of summary statistics for each drug regimen.
Calculate and display the mean, median, variance, standard deviation, and SEM of tumor volume for each regimen.

3. Create Bar Charts and Pie Charts
Create two identical bar charts displaying the total number of rows (Mouse ID/Timepoints) for each drug regimen.
Create two identical pie charts showing the distribution of female versus male mice in the study.

4. Calculate Quartiles, Find Outliers, and Create a Box Plot
Isolate the final tumor volume for each mouse in four promising treatment regimens (Capomulin, Ramicane, Infubinol, Ceftamin).
Calculate quartiles and the interquartile range (IQR) to identify potential outliers.
Generate a box plot displaying the final tumor volume distribution for each treatment regimen, highlighting potential outliers.

5. Create a Line Plot and a Scatter Plot
Select a single mouse treated with Capomulin and create a line plot of tumor volume versus time point for that mouse.
Generate a scatter plot showing mouse weight versus the average observed tumor volume for the entire Capomulin treatment group.

6. Calculate Correlation and Regression
Calculate the correlation coefficient and perform linear regression analysis between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
Plot the linear regression model on top of the scatter plot.
Getting Started
To begin your analysis, download the project files and open the Jupyter Notebook provided. Follow the step-by-step instructions within the notebook to complete each task. Feel free to explore different methods and libraries to achieve the desired results.

Conclusion
This project offers a unique opportunity to delve into the world of pharmaceutical data analysis, providing valuable insights into the effectiveness of anti-cancer medications. By the end of this analysis, you'll have generated essential tables, charts, and statistical summaries that will contribute to the technical report on the clinical study. Your efforts will help Pymaceuticals, Inc. make informed decisions regarding its drug development efforts. Good luck with your analysis! 📊🐭🔬

Calculate Correlation and Regression
Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.

Plot the linear regression model on top of the previous scatter plot.
