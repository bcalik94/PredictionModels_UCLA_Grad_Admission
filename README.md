# PredictionModels_UCLA_Grad_Admission

In this practical, as the aim of creating prediction models through predictors, I’ve found a dataset created by UCLA Graduate Admission. This dataset was built for the purpose of helping students in shortlisting universities with their profiles. The dataset contains several parameters during the application for graduate programs. The parameters include:

GRE Scores (out of 340)
TOEFL Scores (out of 120)
University Rating (out of 5)
State of Purpose Strength(out of 5)
Letter of Recommendation Strength (out of 5)
Research Experience (Either 0 or 1)
Chance of Admit (Ranging from 0 to 1)
Since the outcome probability was provided by dataset as “Chance of Admit”,to predict whether the student can get accepted or not, I’ve created another parameter as “Accepted” that the students who have more than 75% chance of admission, it will be assumed as accepted (1), and the students who have less than 75% chance of admission, will be assumed as not accepted(0).

In the assignment, there will be three different prediction/classification models created with the k-nearest neighbors algorithm, logistic regression, and linear discriminant analysis. The prediction outcomes will be compared by confusion matrixes to find out which model would be most accurate for our prediction. Since we have 400 observations, I’ve decided to split the dataset into a training set by 80% and test set 20%. After executing the models, through the confusion matrix analysis, even though I’ve found that their accuracy results are slightly close to each other,Linear Discriminant Analysis has slightly better prediction results with 90% accuracy where KNN has 81% and LR has 85% accuracy rate.
