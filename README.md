Read Me

This repository contains the following files:

    README.md: provides an overview of the data set and how it was created
    tidy_data.txt: contains the data set
    CodeBook.md: describes the contents of the data set
    run_analysis.R: the R script that was used to create the data set as described below


Creating the data set:

    The R script run_analysis.R can be used to create the data set. It retrieves the source data set and transforms it to produce the final data set by implementing the following steps:

    Download and unzip source data if it doesn't exist.
    Read data.
    Merge the training and the test sets to create one data set.
    Extract only the measurements on the mean and standard deviation for each measurement.
    Use descriptive activity names to name the activities in the data set.
    Appropriately label the data set with descriptive variable names.
    Create a second, independent tidy set with the average of each variable for each activity and each subject.
    Write the data set to the tidy_data.txt file.