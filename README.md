Getting and Cleaning Data: Course Project
=========================================

Introduction
------------
The code contained in this repository was written for  project for Coursera's Getting and Cleaning Data Course.

This script works with the Human Activity Recognition Using Smartphones Dataset. The original dataset and its description can be found here:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

About the script and the tidy dataset
-------------------------------------
I created a script called run_analysis.R which will merge the test and training sets together.
Prerequisites for this script:

1. the UCI HAR Dataset must be extracted and..
2. the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.


About the raw data
------------------

The features (561 of them) are unlabeled and can be found in the x_test.txt. 
The activity labels are in the y_test.txt file.
The test subjects are in the subject_test.txt file.

The same holds for the training set.


Result tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.



