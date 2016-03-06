CODEBOOK

Data Source

Orginal data source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Files used:

test/subject_test.txt
test/X_test.txt
test/y_test.txt
train/subject_train.txt
train/X_train.txt
train/y_train.txt

Variable data from:

Activiy  (Values) : “Y_train.txt” and “Y_test.txt”
Activity (labels) : “activity_labels.txt”
Subject  (Values) : “subject_train.txt” and subject_test.txt"
Features (Values) : “X_train.txt” and “X_test.txt”
Features (Names)  : “features.txt”

Descriptive variable names:

prefix t is replaced by time
Acc is replaced by Accelerometer
Gyro is replaced by Gyroscope
prefix f is replaced by frequency
Mag is replaced by Magnitude
BodyBody is replaced by Body

Library (plyr) used to create tidy data set

tidy_data.txt: Dataset with all the average measures for each subject and activity type (180 observations/68 variables).