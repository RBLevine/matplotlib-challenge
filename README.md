# matplotlib-challenge

This repository includes the following:
	
Pymaceuticals (folder):
	data (folder):
		Mouse_metadata (Microsoft Excel Comma Separated Values File): This file contains data on the mice
			used in this study. It contains Mouse ID, Drug Regimen, Sex, Age (in months), and Weight (g)
			for each mouse in the study.
		Study_results (Microsoft Excel Comma Separated Values File): This file contains data on the results
			of the study. It contains Mouse ID, Timepoint, Tumor Volume (mm3), and Metastatic Sites
			information for each mouse at each timepoint.
	pymaceuticals_starter.ipynb (IPYNB File): This file is the Jupyter Notebook file that contains all of the
		analysis for the study. In this, information from the two data files are combined in a dataframe and
		cleaned. Statistics are ran, providing the mean, median, variance, standard deviation, and SEM of the
		tumor volume for each drug regimen. Bar plots are created to visualize the number of total mice for
		each drug regimen. A pie chart is created to visualize the number of female and male mice in total in
		the study. Final tumor volume for mice in drug regimens Capomulin, Ramicane, Infubinol, and Ceftamin
		is retrieved and displayed in a box plot. A mouse from the Capomulin regimen is selected and the tumor
		volume is charted in a line plot to show the tumor shrinkage over the course of the study. Lastly, a
		scatter plot and linear regression model is created based on the tumor volume and weight of mice in 
		the Capomulin regimen.
HW INSTRUCTIONS (MD File): This contains quick access to the hw information and instructions for this assignment.
