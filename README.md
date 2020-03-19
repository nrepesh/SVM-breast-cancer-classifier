# SVM-breast-cancer-classifier

Predict a classification- Cancer benign or maligant using a dataset from ScikitLearn 

I used Pandas for data analysis and Matplotlib/seaborn for data visualization.

Cleaned data and fitted a support vector machine model and used it to classify cancer. Finally, I evaluated the results using an evaluation matrix.

Udemy course - Python for Data Science and Machine Learning Bootcamp

This idea of creating a 'grid' of parameters and just trying out all the possible combinations is called a Gridsearch, this method is common enough that Scikit-learn has this functionality built in with GridSearchCV! The CV stands for cross-validation.

GridSearchCV takes a dictionary that describes the parameters that should be tried and a model to train. The grid of parameters is defined as a dictionary, where the keys are the parameters and the values are the settings to be tested. higher the number, the more verbose (verbose just means the text output describing the process).
