# TidyData Codebook

Accelerometer data collected with the Samsung Galaxy smartphone
----------------------------------------------------------------

The variables selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

The set of variables that were estimated from these signals are: 

mean(): Mean value
std(): Standard deviation

Experiment Details
---------------------------------
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 

Entry Description
## [column number] [variable code]
### [variable descrition]
values: [range of values]

## 1 subject
### Identification number of volunteers aged between 19-48 years.
values: 1-30

## 2 activity
### experimental activity performed by volunteer wearing a smartphone (Samsung Galaxy S II) on the waist.
values: 
1 WALKING 
2 WALKING_UPSTAIRS
3 WALKING_DOWNSTAIRS
4 SITTING
5 STANDING
6 LAYING

## 3-5 tBodyAccMeanXYZ
### Mean calculated for accelerometer signals from body captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 6-8 tBodyAccStdXYZ
### Standard deviation calcuated for accelerometer signals from body captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 9-11 tGravityAccMeanXYZ
### Mean calculated for accelerometer signals from gravity captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 12-14 tGravityAccStdXYZ
### Standard deviation for accelerometer signals from gravity captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 15-17 tBodyAccJerkMeanXYZ
### Mean for accelerometer signals during linear body acceleration captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 18-20 tBodyAccJerkStdXYZ
### Standard deviation for accelerometer signals during linear body acceleration captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 21-23 tBodyGyroMeanXYZ
### Mean for gyroscope signals from body captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 24-26 tBodyGyroStdXYZ
### Standard deviation for gyroscope signals from body captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 27-29 tBodyGyroJerkMeanXYZ
### Mean for gyroscope signals from body angular velocity captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 30-32 tBodyGyroJerkStdXYZ
### Standard deviation for gyroscope signals from body angular velocity captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 33 tBodyAccMagMean
### Mean for magnitude of accelerometer signals from body captured at constant rate.Measurement of signals made in units of g and normalized and bounded within [-1,1]. 
values: -1,1

## 34 tBodyAccMagStd
### Standard deviation for magnitude of accelerometer signals from body captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. 
values: -1,1

## 35 tGravityAccMagMean
### Mean for magnitude of accelerometer signals from gravity captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. 
values: -1,1

## 36 tGravityAccMagStd
### Standard deviation for magnitude of accelerometer signals from gravity captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1].
values: -1,1

## 37 tBodyAccJerkMagMean
### Mean for magnitude of accelerometer signals from during body linear acceleration captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1].
values: -1,1

## 38 tBodyAccJerkMagStd
### Standard deviation for magnitude of accelerometer signals during body linear acceleration captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1].
values: -1,1

## 39 tBodyGyroMagMean
### Mean for magnitude of gyroscope signals from body captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1].
values: -1,1

## 40 tBodyGyroMagStd
### Standard deviation for magnitude of gyroscope signals from body captured at constant rate.Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. 
values: -1,1

## 41 tBodyGyroJerkMagMean
### Mean for magnitude of gyroscope signals from body angular velocity captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. 
values: -1,1

## 42 tBodyGyroJerkMagStd
### Standard deviation for magnitude of gyroscope signals from body angular velocity captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1].
values: -1,1

## 43-45 fBodyAccMeanXYZ
### Mean for accelerometer frequency domain signals from body captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 46-48 fBodyAccStdXYZ
### Standard deviation for accelerometer frequency domain signals from body captured at constant rate.Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 49-51 fBodyAccJerkMeanXYZ
### Mean for accelerometer frequency domain signals from body linear acceleration captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 52-54 fBodyAccJerkStdXYZ
### Standard deviation for accelerometer frequency domain signals from body linear acceleration captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 55-57 fBodyGyroMeanXYZ
### Mean for gyroscope frequency domain signals from body captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 58-60 fBodyGyroStdXYZ
### Standard deviation for gyroscope frequency domain signals from body captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. '-XYZ' denotes 3-axial signals in the X, Y and Z directions.
values: -1,1

## 61 fBodyAccMagMean
### Mean for magnitude of accelerometer frequency domain signals from body captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1].
values: -1,1

## 62 fBodyAccMagStd
### Standard deviation for the magnitude of accelerometer frequency domain signals from body captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1].
values: -1,1

## 63 fBodyAccJerkMagMean
### Mean for magnitude of accelerometer frequency domain signals from body linear acceleration captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1].
values: -1,1

## 64 fBodyAccJerkMagStd
### Standard deviation for the magnitude of accelerometer frequency domain signals from body linear acceleration captured at constant rate. Measurement of signals made in units of g and normalized and bounded within [-1,1]. 
values: -1,1

## 65 fBodyGyroMagMean
### Mean for magnitude of gyroscope frequency domain signals from body captured at constant rate.Measurement of signals made in units of rad/s and normalized and bounded within [-1,1]. 
values: -1,1

## 66 fBodyGyroMagStd
### Standard deviation for the magnitude of gyroscope frequency domain signals from body captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1].
values: -1,1

## 67 fBodyGyroJerkMagMean
### Mean for magnitude of gyroscope frequency domain signals from body angular velocity captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1].
values: -1,1

## 68 fBodyGyroJerkMagStd
### Standard deviation for the magnitude of gyroscope frequency domain signals from body angular velocity captured at constant rate. Measurement of signals made in units of rad/s and normalized and bounded within [-1,1].
values: -1,1
