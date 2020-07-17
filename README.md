# Intended for coursework submission

This repository is created by Eian Vick Hon for submission of the Week 4 assignment of Getting and Cleaning Data course. The repository contains instruction to cleaning and tidying the UCI HAR data provided.

## Data

The data used is UCI's machine learning repository, it contains physical activity data of users wearing smartphone on their wrists. Link to download the data:  http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

## Files

### Code Book
A code book in txt file format that describes the variables, the data, and any transformations or work that I performed to clean up the data.

### run_analysis.R
A script file that details the exact steps and codes I have used to clean up the data, it follows the sequence shown on the coursework page. It
1. Merges the training and the test sets.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to rename the activities in the data.
4. Labels the dataset using descriptive variable names.
5. From the data produced in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Q5Data.txt
A data file in txt format following the fifth instruction given by the assignment.
