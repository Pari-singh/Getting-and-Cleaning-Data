# Accelerometer data analysis.
R script that analyze data gathered from smartphones accelerometers. Done as part of the Getting and Clening Data Coursera course.
## Getting and Cleaning the data:
1. Load the raw data from the working directory. Raw data is divided into train and test data sets.
2. Merge the training and the test sets to create one data set.
3. Load variable names from raw data separated file and assign them to the merged data
4. Extract only the measurements on the mean and standard deviation for each measurement.
1. Get variable names for the mean measurements
2. Get variable names for the standard deviation measurements
3. Subset data selecting columns that are among the previous variable names
5. Use descriptive activity names to name the activities in the data set.
  1. Load activity names from raw data separated file
  2. Cast activity variable to factor
 3. Level activity variable to the loaded activity names
6. Label the data set with descriptive variable names.
 1. Make variables names lower case
2. Remove any dot from variable names
7. Create an independent tidy data set with the average of each variable for each activity and each subject.
8. Write the tidy data set to an output file.
## Codebook
Dataset description is given in CodeBook
