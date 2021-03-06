The Human Activity Recognition Using Smartphones dataset has been modified as follows:

tidy_data.txt

The files train.txt and test.txt were combined. The activity labels from activity_labels.txt and the subject information from subject_train.txt and subject_test.txt were added to the combined data. Only the measurements on the mean and standard deviation for each reading were retained. The activity names were modified to be more descriptive by utilising and cleaning the feature names provided in features.txt.

Variables

The variable subject denotes the identity of the subject from whom the readings were taken.
The variable activity denotes the activity the subject was performing when the reading was taken.

The following signal readings are retained:

t_body_acc, t_gravity_acc, t_body_acc_jerk, t_body_gyro, t_body_gyro_jerk, t_body_acc_mag, t_bravity_acc_mag, t_body_acc_jerk_mag, t_body_gyro_mag, t_body_gyro_jerk_mag, f_body_acc, f_body_acc_jerk, f_body_gyro, f_body_acc_mag, f_body_acc_jerk_mag, f_body_gyro_mag, f_body_gyro_jerk_mag

From these readings, the mean and standarad deviation values are included in the dataset. These are denoted within the variable names as mean and std.
The prefix t denotes time, and the prefix f indicates frequency.
The suffixes X, Y and Z are used to denote signals in the X, Y and Z directions.

All values are normailed between -1 and 1.

tidy_average_data.txt

The modified dataset above was used to create this second data set containing the average of each reading for each activity and each subject.

Variables

The prefix average denotes that these readings have been averaged for each activity and each subject.

Files

The dataset includes the following files:

README.md

Codebook.md

run_analysis.R

tidy_data.txt
