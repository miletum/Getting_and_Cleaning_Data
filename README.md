# Getting and Cleaning Data Course Project

## Introduction

The [Human Activity Recognition Using Smartphone Dataset](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) contains data collected from a group of 30 Samsung Galaxy S smartphone's accelerometers.  In this project, the dataset is prepared and cleaned up to allow for later analysis.

## Files

The dataset includes the following files:

* 'README.md'

* 'CodeBook.md': The CodeBook describes the variables, the data, and any transformations or work that has been performed to clean up the data.

* 'run_analysis.R': The R script takes in the unzipped data files and produces 2 tidy datasets that could be used for further analysis.  The first dataset is stored in the variable `data`, and it contains all measurements captured for each subject and activity.  The second dataset is stored in the variable `meanData`, and it contains the average of each measurement for each activity and subject.

* 'meanData.txt': This file contains the dataset `meanData` generated by the R script: 'run_analysis.R'.  It can be read into R using the following R code: `read.table("meanData.txt", header=TRUE)`.