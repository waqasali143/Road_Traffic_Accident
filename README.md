# Road_Traffic_Accident<br>
### Road Traffic Severity Classification Prediction 
# <strong>Description: <br>
This dataset is collected from Addis Ababa Sub-city police departments for 
master's research work. The data set has been prepared from manual records of 
road trafic accidents of the year 2017-20. All the sensitive information has been 
excluded during data encoding and finally it has 32 features and 12316 instances 
of the accident. Then it is preprocessed and for identification of major causes of 
the accident by analyzing it using different machine learning classification 
algorithms. 
# Problem Statement: 
The target feature is Accident_severitywhich is a multi-class variable. The 
task is to classify this variable based on the other 31 features step-by-step by 
going through each day's task. Your metric for evaluation will be <i><strong>f1-score
<br>
# What is F1 score?<br>
F1 score is a machine learning evaluation metric that measures a model’s accuracy. It combines the precision and recall scores of a model.
<br>
## Training with different Model
<br>
1- XGBClassifier<br>
2- KNeighborsClassifier<br>
3- DecisionTreeClassifie<br>
4- ExtraTreeClassifier<br>
5- RandomForestClassifier<br>

<br>

# According to my observation, I got the best results with ExtraTreesClassifier and xgboost model showing the best result**<br>
### Model       

<strong>XGB =>    PrecisionScore = 0.930  AccScore = 0.929  f1_Score = 0.929

ExtraDT  =>   PrecisionScore = 0.938  AccScore = 0.937  f1_Score = 0.937
<br>
<br>
![Screenshot 2024-03-31 002608](https://github.com/waqasali143/Road_Traffic_Accident/assets/82609521/0775f6c9-cdda-40cd-8711-8555874501c4)
