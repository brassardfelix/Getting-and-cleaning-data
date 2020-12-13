# Getting-and-cleaning-data
This is the course project for the Getting and Cleaning Data Coursera course.

run_analysis.R is an R script that does the following things:

- Downloads the dataset from web only if it does not exist in the working directory alrealdy.
- Reads the train and test datasets before merging them into measurements, activity and subject,   respectively.
- Loads the data feature, activity info and extracts columns named 'mean'(-mean) and 'standard'(-std). The column names are also changed to descriptive. (-mean -> Mean, -std -> Std, and symbols like -, (, )) are removed.
- Extracts data by selected columns (from step 3), and merges measurements, activity and subject data. Also, replace activity column to it's name by refering activity label.
- Generates a tidy dataset that shows the average of each variable for each subject and each activity. The tidy dataset is shown in the file tidy_dataset.txt
