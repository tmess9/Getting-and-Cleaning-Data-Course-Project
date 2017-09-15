# GettingandCleaning Data - Final Course Project

Final course project for Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does:

1) Downloads the dataset if it doesn't already exist.
2) Load the activity and feature info
3) Loads both the training and test datasets, and keeps only those columns which
   reflect a mean or standard deviation
4) Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
5) Merges the 2 datasets
6) Converts the `activity` and `subject` columns into factors
7) Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.
8) Viola

Results are stored in `tidy.txt`
