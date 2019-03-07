# projectML
NYCDSA: Machine Learning Project (Housing in Ames, IA)

This Python machine learning project is the work of the "Bench Initiative" group from the winter 2019 cohort of the NYC Data Science Academy. Our members are: 
 - Eric Adlard
 - Ryan Essner & 
 - Sabbir Mohammed

It revolves around the kaggle.com competition on Advanced Regression Techniques, found here:
<https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data>

This repository holds our work notebooks(code) and files. Here is a brief workflow explaining the file and folder structure:

  A) The "house-prices-advanced-regression-techniques" folder initially contains the raw train and test data sets from kaggle.com.
  Inside it are a few additional files(.csv) used by our group to organize our work.
  
  B) The "1. Training set overview" Jupyter notebook shows our brief, initial exploration of the training data.

  C) The "2. Imputation and Feature Engineering" notebook holds our code where we handled missingness (in both the test and train sets)     
  and how we updated the features to be analyzed. It outputs the .csv(s) used for modeling, into the "data" folder.

  D) The "3. Feature Reduced data set" notebook holds similar code to the imputation notebook, but instead it outputs .csv files of the 
  reduced data sets into the "data" folder as well.

  E) Finally, the remaining notebooks (#4 and #5) carry out regression modeling done on the final, prepared data sets from the "data"
  folder, and outputs formatted csv(s) for submission into the kaggle.com competition to the "kaggle_submissions" folder.
  
  Our group's presentation on our efforts can be found in the following link:
  <https://docs.google.com/presentation/d/1WkYu03gJjzGtiChRyQkntf2fqkcEbRGYk1MqyaaalYw/edit?usp=sharing>
  
  
Thank you for visiting our repository!
