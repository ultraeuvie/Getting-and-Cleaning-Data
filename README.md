# Getting and Cleaning Data - Programming Course Project

This is the course project for the Getting and Cleaning Data of Coursera's Data Science Specialization.
The R script, `run_analysis.R`, signifies the following procedures:

1. Download the dataset if it does not already exist in the working directory
2. Load the activity plus feature info
3. Loads the training and test datasets together, keeping only those columns which
   result a mean/standard deviation
4. Loads the activity and subject data for each dataset and merge those
   columns with the dataset
5. Merges the training and the test sets to create one data set.
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the mean values of each
   variable for each subject and activity pair.

The final result is shown in the file `tidy.txt`.
