gettingandcleaningdata
======================

Data: Collected measurements from accelerometers from the Samsung Galaxy S smartphone. 

Included testing & training set of measurements, text description of variables (features) corresponding numeric participant (subjects), and numeric lable of activity.

Included Files:

Code Book: Describes resulting output variables, their data types and how they were derived.

runAnalysis.R: Code used in R to pull in training/testing sets and merge them with corresponding subject and activity text files. Subset aggregated file (including both testing and training) for the columns with measurements including mean or standard deviation. calculate averages by subject/activity.

Goals: merge the testing and training set including subject and activity data.  Subset metrics of observations for mean and standard deviation.  Aggregate on subject and activity and calculate mean of the subset.
