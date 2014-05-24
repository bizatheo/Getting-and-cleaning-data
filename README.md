Getting-and-cleaning-data
=========================

The data analysed here was obtained from the following link
( https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip )

    Then downloaded on my  local drive, C:\Users\gettingandcleaningdata
    The next stage was to unzip the data, and set a working directory in my R.

    run_analysis.R is an R source code used to make the data preparation 

    
    Assumptions

    The training and test data are available in in my one folder (in which i set my working directory for the R session.
    For each of these data sets:
    Measurements are present in X_<dataset>.txt file
    Subject information is present in subject_<dataset>.txt file
    Activity codes are present in y_<dataset>.txt file
    All activity codes and their labels are in a file named activity_labels.txt.
    Names of all measurements taken are present in file features.txt ordered and indexed as they appear in the X_<dataset>.txt files.
    All columns representing means contain ...mean in them.
    All columns representing standard deviations contain ...std in them.
   

