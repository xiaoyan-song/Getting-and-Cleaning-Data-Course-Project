# Getting-and-Cleaning-Data-Course-Project
 This repo explains how all of the scripts work and how they are connected.
 
Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, say C:\Users\l\Desktop\Coursera\

Put all related materials in the UCI HAR Dataset directory

Put run_analysis.R into C:/Users/l/Desktop/Coursera/UCI HAR Dataset

In RStudio: Set working directionary as "C:/Users/l/Desktop/Coursera/UCI HAR Dataset", followed by: source("run_analysis.R")

Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is a 181x68 table including the colnames.
