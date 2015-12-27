# Getting-and-Cleaning-Data
This Script will install the rPackages data.table and reshpe2 if not installed already
Load: activity labels for test and train data
Load and process X_test & y_test data.
Extract only the measurements on the mean and standard deviation for each measurement.
Load and process X_train & y_train data.
Extract only the measurements on the mean and standard deviation for each measurement.
Load activity data
Bind data
Merge test and train data

Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.
