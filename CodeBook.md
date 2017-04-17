### CodeBook:
for Accelerometer Data set to analyse smartphone accelerometer. 
## Project Description
Raw data were collected from a zip downloadable file at 
"https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"

Notes on the original raw data Raw data is separated in 2 data sets. One for training and one for testing. 
Each data set is formed by 3 different files, with information regarding the subjects of the study, the experiments labels, 
and the data itself respectively.

## Creating Tidy Datafile
Guide to create tidy dataset is done in run_analysis.R

## Cleaning of the data The script has different steps for cleaning the data:

Load and merge the train and data sets
Extract mean and standard deviation for each measurement
Use human readable activity names to name the different experiments
Label the data set
Obtain averages for each measurement
Write the tidy data set to an output file More detailed description can be found in the README.md file
##Description of the variables in the tiny.txt file Main features of the tidy data set:

Dimensions of the dataset: 180 rows x 81 columns
Units: all variables are normalised to a -1 to 1 range.
## Variable:	Type:	Values
user:	Integer:	0 to 30
activity:	Character:	WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING

tbodyaccmeanx:	Numeric:	-1 to 1

tbodyaccmeany:	Numeric:	-1 to 1

tbodyaccmeanz:	Numeric:	-1 to 1

tgravityaccmeanx:	Numeric:	-1 to 1

tgravityaccmeany:	Numeric:	-1 to 1

tgravityaccmeanz:	Numeric:	-1 to 1

tbodyaccjerkmeanx:	Numeric:	-1 to 1

tbodyaccjerkmeany:	Numeric:	-1 to 1

tbodyaccjerkmeanz:	Numeric:	-1 to 1

tbodygyromeanx:	Numeric:	-1 to 1

tbodygyromeany:	Numeric:	-1 to 1

tbodygyromeanz:	Numeric:	-1 to 1

tbodygyrojerkmeanx:	Numeric:	-1 to 1

tbodygyrojerkmeany:	Numeric:	-1 to 1

tbodygyrojerkmeanz:	Numeric:	-1 to 1

tbodyaccmagmean:	Numeric:	-1 to 1

tgravityaccmagmean:	Numeric:	-1 to 1

tbodyaccjerkmagmean:	Numeric:	-1 to 1

tbodygyromagmean:	Numeric	-1 to 1

tbodygyrojerkmagmean	Numeric	-1 to 1

fbodyaccmeanx	Numeric	-1 to 1

fbodyaccmeany	Numeric	-1 to 1

fbodyaccmeanz	Numeric	-1 to 1

fbodyaccmeanfreqx	Numeric	-1 to 1

fbodyaccmeanfreqy	Numeric	-1 to 1

fbodyaccmeanfreqz	Numeric	-1 to 1

fbodyaccjerkmeanx	Numeric	-1 to 1

fbodyaccjerkmeany	Numeric	-1 to 1

fbodyaccjerkmeanz	Numeric	-1 to 1

fbodyaccjerkmeanfreqx	Numeric	-1 to 1

fbodyaccjerkmeanfreqy	Numeric	-1 to 1

fbodyaccjerkmeanfreqz	Numeric	-1 to 1

fbodygyromeanx	Numeric	-1 to 1

fbodygyromeany	Numeric	-1 to 1

fbodygyromeanz	Numeric	-1 to 1

fbodygyromeanfreqx	Numeric	-1 to 1

fbodygyromeanfreqy	Numeric	-1 to 1

fbodygyromeanfreqz	Numeric	-1 to 1

fbodyaccmagmean	Numeric	-1 to 1

fbodyaccmagmeanfreq	Numeric	-1 to 1

fbodybodyaccjerkmagmean	Numeric	-1 to 1

fbodybodyaccjerkmagmeanfreq	Numeric	-1 to 1

fbodybodygyromagmean	Numeric	-1 to 1

fbodybodygyromagmeanfreq	Numeric	-1 to 1

fbodybodygyrojerkmagmean	Numeric	-1 to 1

fbodybodygyrojerkmagmeanfreq	Numeric	-1 to 1

tbodyaccstdx	Numeric	-1 to 1

tbodyaccstdy	Numeric	-1 to 1

tbodyaccstdz	Numeric	-1 to 1

tgravityaccstdx	Numeric	-1 to 1

tgravityaccstdy	Numeric	-1 to 1

tgravityaccstdz	Numeric	-1 to 1

tbodyaccjerkstdx	Numeric	-1 to 1

tbodyaccjerkstdy	Numeric	-1 to 1

tbodyaccjerkstdz	Numeric	-1 to 1

tbodygyrostdx	Numeric	-1 to 1

tbodygyrostdy	Numeric	-1 to 1

tbodygyrostdz	Numeric	-1 to 1

tbodygyrojerkstdx	Numeric	-1 to 1

tbodygyrojerkstdy	Numeric	-1 to 1

tbodygyrojerkstdz	Numeric	-1 to 1

tbodyaccmagstd	Numeric	-1 to 1

tgravityaccmagstd	Numeric	-1 to 1

tbodyaccjerkmagstd	Numeric	-1 to 1

tbodygyromagstd	Numeric	-1 to 1

tbodygyrojerkmagstd	Numeric	-1 to 1

fbodyaccstdx	Numeric	-1 to 1

fbodyaccstdy	Numeric	-1 to 1

fbodyaccstdz	Numeric	-1 to 1

fbodyaccjerkstdx	Numeric	-1 to 1

fbodyaccjerkstdy	Numeric	-1 to 1

fbodyaccjerkstdz	Numeric	-1 to 1

fbodygyrostdx	Numeric	-1 to 1

fbodygyrostdy	Numeric	-1 to 1

fbodygyrostdz	Numeric	-1 to 1

fbodyaccmagstd	Numeric	-1 to 1

fbodybodyaccjerkmagstd	Numeric	-1 to 1

fbodybodygyromagstd	Numeric	-1 to 1

fbodybodygyrojerkmagstd	Numeric	-1 to 1
