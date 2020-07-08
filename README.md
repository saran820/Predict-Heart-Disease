# Predict-Heart-Disease
The above ML model is used to detect if the patient has a heart disease.

It is a Binary Classification Problem, however, the data is a highly imbalanced data, i.e the presence of heart disease is not there in nearly 85% of the data.

A simple model on the data will give high accuracy, but the number of undetected cases will be very high which is unwanted. Hence we use two techniques in an attempt to solve the above problem.

1. Random Under Sampling
In this, we bring down the number of majority class to the same number as that of the minority class, thus creating a balanced dataset. However, this leads to a data loss and hence less data for the model to work on.

2. Synthetic Minority Over Sampling(SMOTE):
In this,we create synthetic points from the minority class in order to reach an equal balance between the minority and majority class. SMOTE picks the distance between the closest neighbors of the minority class, in between these distances it creates synthetic points. In this more information is retained as opposed to Random Under Sampling.
