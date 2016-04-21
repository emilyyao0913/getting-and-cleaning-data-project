Getting and Cleaning Data: Course Project

This repository contains my work for the Coursera course "Getting and Cleaning data" final project.

The purpose of this project is to demonstrate my ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

I created a script called run_analysis.R which will merge the test and training sets together. 

The R script, run_analysis.R, does the following:

Download the dataset 
Load the activity and feature information
Loads both the training and test datasets
Extracts only the measurements on the mean and standard deviation for each measurement.
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.


The CodeBook.md file talked about the variables and measurements I included in the analysis. 









