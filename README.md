# Ezerx-internship-works

This repository includes my works during 1st June 2020 to 31st August 2020 in EzeRx Health Tech Private Limited. Here I worked as a Data science intern. I worked with some Biomedical signals which they provided from a non invassive device, buitl by Ezerx Health tech Pvt. Ltd. 

# Dataset description

-- The Dataset contains 291 colums. Here 290 coloums are feature and 291th is labels which is continius value betwen 66000 to 88000.

-- Later I divide the labels in five categories using histrogram plot.

# Libraries:

1. Pandas -- for tabular dataset handeling

2. Numpy -- for array related works

3. Scipy -- for peak detection and gaussian smoothing

4. Scikit learn -- for different types of regression and classification machine learning models

5. Imblearn -- for reducing imbalanced class


# My work

Here I worked with some Bio medical signals.  I used some preprocessing stpes like abrupt Peak finding, removing noise by Gausiinan filtering (see notebook: name of the file)
Then using histrogram plots try to create some class.

At first I solved the given problem as a regression problem, later I solved the problem as a classification problem.

So, in regression problem, I tried to use diffrent regression algorithims like SVR,Random forest(Bagging), XGBOOST(Boosting).

Also the given dataset was very much imbalanced, so while solving classification problems I used Imblearn library's SMOTE algorithim to reduce imblance.
