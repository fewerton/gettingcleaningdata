# Getting and cleaning data

Coursera peer-graded Assignment: Getting and Cleaning Data Course Project
Week 4

## Getting and cleaning data project

The purpose of this project is to demonstrate  ability to collect, work with, and clean a data set. 

The goal is to prepare tidy data that can be used for later analysis. 

Submission requires: 

1) a tidy data set as described below 
2) a link to a Github repository with your script for performing the analysis  
3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. 
4) a README.md file

This repo explains how the script works and how data sets are connected.

Here are the "raw" data for the project:

 https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  

### R Script 
filename: run_analysis.R

The R script called **run_analysis.R** does the following: 

1) Merges the training and the test sets to create one data set.
2) Extracts only the measurements on the mean and standard deviation for each measurement. 
3) Uses descriptive activity names to name the activities in the data set
4) Appropriately labels the data set with descriptive variable names. 
5) From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Tidy data set
filename: independented_tidy_data_step5.txt

This is an independent tidy data set with the average of each variable for each activity and each subject, and it is the final data set result from running the script run_analysis.R


