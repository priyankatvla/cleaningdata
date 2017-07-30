Tidied Data from the Human Activity Recognition Using Smartphones Dataset

The final data set can be found in the tidyMeans.txt file, which can be read into R with read.table("tidyMeans.txt", header = TRUE). A detailed description of the variables can be found in CodeBook.md. The basic naming convention is:
Mean{timeOrFreq}{measurement}{meanOrStd}{XYZ}
Where timeOrFreq is either Time or Frequency, indicating whether the measurement comes from the time or frequency domain, measurement is one of the original measurement features, meanOrStd is either Mean or StdDev, indicating whether the measurement was a mean or standard deviation variable, and XYZ is X, Y, or Z, indicating the axis along which the measurement was taken, or nothing, for magnitude measurements.