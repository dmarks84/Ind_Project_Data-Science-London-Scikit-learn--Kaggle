## Ind_Project_Data-Science-London-Scikit-learn--Kaggle
    
## Screenshot
![screenshot](https://github.com/dmarks84/Ind_Project_Data-Science-London-Scikit-learn--Kaggle/blob/main/london_screenshot.png?raw=true)

## Summary
I worked on the Data Science London data set for the Data Science London + Scikit-learn competition.  The dataset provided 40 features that we used to predict a binary classification.  I performed basic exploratory data analysis before creating a combination of pipelines.  Each pipeline incorporated one of three scalers-- StandardScalar, MinMaxScaler, or MaxAbsScaler-- as well as Principal Component Analysis and then a classifier model/estimator.  I used GridSearchCV to determine the best parameters for each unique model type, and iterated through each to determine the best model on the validation data (a subset of the training data provided).  

## Results
### Model Selected
There as some variation as several models produced very similar results.  For the submission, the best version was a Multilayer Perceptron Classifier with default parameters, and PCA utilizing 40 components with MinMax Scaler to start. On other runs, a Support Vector Classifier with C equal to 10 and gamma equal to 1 come out on top. That classifier version used the MinMaxScaler and PCA utilized 40 components. 

### Scores
The best score on the training set was as high as 1.0 and for most models about 0.8, with a few above 0.9.  On the validation set, the best scores were between 0.89-0.90 as well. Not fantastic but it's not bad in either case.

## Skills (Developed & Applied)
Programming, Python, Statistics, Numpy, Pandas, Matplotlib, Scikit-learn, Dataframes, Data Modeling, EDA, Data Visualization, Data Reporting, Classification, Supervised ML, Cross Validation, Grid search
