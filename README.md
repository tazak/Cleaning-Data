# Cleaning-Data

# Steps required for creating the tidy data set.

1. Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive,
say /Users/tanweer/Data Science/Getting And Cleaning data/W-3/UCI HAR Dataset on your linux or mac machine.

2. Put run_analysis.R into /Users/tanweer/Coursera/Data Science/Getting And Cleaning data/W-3/UCI HAR Dataset

3. In RStudio: setwd("/Users/tanweer/Coursera/Data Science/Getting And Cleaning data/W-3/UCI HAR Dataset"), followed by: source("run_analysis.R")

4. Use data <- read.table("data_set_with_the_averages.txt") to read the data. 
It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows.
Note that the provided R script has no assumptions on numbers of records, only on locations of files.
