#Title
Association of Electronic Cigarette Use With Respiratory Complications Among U.S. Adults Aged 18 Years and Older: A 2022–2023 BRFSS Analysis
##Project Description
This repository includes BRFSS survey data from 2022 and 2023, along with the R markdown code used to analyze it.
This project assesses the association between e-cigarette use and respiratory complications in US adults 
over age 18 using BRFSS data from 2022-2023.
##Files Included
-`ADA final project RMD`: R script used to summarize and visualize the data
-`brfss_selected`: Cleaned version of the final dataset (22-23 combined)
-`ReadME.md`: This file
## What the code does 
-Reads in the BRFSS survey data from 2022 and 2023
-Combines the surveys from two years into one file
-Makes a new dataset with the variables of interest 
-Performs data cleaning (e.g., renaming columns, recoding varibles to recatagorize them, recoding to change the catagories label, filtering etc)
-Creates table 1 for summary statistics
-Generates a stacked bar plot to visualize respiratory complication outcomes by e-cigarette smoking status. 
-Performs binary logistic regression to obtain odd ratios and confidence intervals 
##How to run the code
1. Download or clone this repository to your computer 
2. Open `ADA final project RMD` in RStudio
3. Make sure your working directory is set to the folder where the files are
saved
4. Run the script
##Author
-Name:Arifa Nayab
-Course:PHCC.6009.03 Advanc Data Analysis 


