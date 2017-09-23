# Getting-and-Cleaning-Data-Course-Project

An R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set.


Extracts only the measurements on the mean and standard deviation for each measurement.


Uses descriptive activity names to name the activities in the data set


Appropriately labels the data set with descriptive variable names subject, Activity_ID, and Activity_Label


Creates a second, independent tidy data set with the average of each variable for each activity and each subject

To run the script

Download the data source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) and put into a folder on your local drive. 


You'll have a UCI HAR Dataset folder.


Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory.


Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.
