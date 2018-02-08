For each record in the dataset it is given:
1. The Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
2. Triaxial Angular velocity from the gyroscope.
3. A 561-feature vector with time and frequency domain variables.
4. Its activity label.
5. An identifier of the subject who carried out the experiment.

Activity Name
1. WALKING
2. WALKING_UPSTAIRS
3. WALKING_DOWNSTAIRS
4. SITTING
5. STANDING
6. LAYING

Data Set Information

The experiments employing the sensors have been carried out with a group of 30 volunteers within an age bracket of 19-48 years old.
Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) 
with each one wearing a smartphone (Samsung Galaxy S II) on their waist. 
Using its built-in sensors (accelerometer and gyroscope), data was captured from 3-axial linear acceleration and 3-axial angular velocity 
at a constant rate of 50 Hertz. The experiments have been video-recorded to label the data manually. 
The obtained dataset has been randomly partitioned to produce two sets:
1. 70% of the volunteers for generating the training data and 
2. 30% of the volunteers for the test data.

The accelerometer and gyroscope were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.
