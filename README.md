# ADMISSION-PREDICTION
This dataset was built with the purpose of helping students in shortlisting universities with their profiles and it contains several parameters that are considered important during the application for master programs.
The predicted output gives them a far idea about their chances for a particular university.
After analyzing the dataset, the linear regression remain the best model, there is a linear relationship between the target and most independent variables and I made sure some of the assumptions of linear regression were respected and the CGPA is the most important score to get admitted. 
For master program,most university requires students mostly international students to take some test like the GRE test which is a graduate entrance exam, the TOEFL test which is an english language skills and eventually the Cumulative Grade Point Average (CGPA) to evaluate the student's competence.
Having a good score in these tests enhance the chance of getting admitted.
However, this dataset's target the chance of getting admitted is ranged from 0 to 1, and transforming the target data and removing some outliers provide an amazing improvement in the model performance.
From the k-fold cross validation standard deviation result, this model perfom well but it can still perfom better maybe with other advanced model such as XGBOOST, Lasso and Ridge regression.

Thank you!
