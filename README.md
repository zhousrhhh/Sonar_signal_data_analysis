# Sonar Signal Data Analysis
In this [project](code.ipynb), I conduct analysis with Python for sonar signal data collected after they are bounced off two kinds of objects (underwater). The objects are either rocks or mines and the sonar signals are sent at 60 different frequencies. The value returned is then recorded. The goal of the exercise is to build a model that can figure out whether an object is a rock or a mine.

1. A logistic regression model is built and tuned. 
2. Metrics (precision, recall, accuracy, area under the ROC curve (AUC), average precision) of the model are calculated for comparison and intepretation. 
3. Cross validation model is run to test the model. 
