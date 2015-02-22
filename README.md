# Getting_Cleaning_Data_Project

How `run_analysis.R` implements the above steps:

Checks if the file exists, otherwise it downloads;

Checks if the file has already been extracted to the directory;

Load both test and train data;

Load the features and activity labels;

Extract the mean and standard deviation column names and data;

Process the data;

Merge and creates data set: 

The result is saved as "./tidy-UCI-HAR-dataset-AVG.txt", a 180x68 data table (181 with column name), where as before, the first column contains subject IDs, the second column contains activity names (see below), and then the averages for each of the 66 attributes are in columns 3...68. There are 30 subjects and 6 activities, thus 180 rows in this data set with averages.
