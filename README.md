# Titanic Machine Learning Introduction
The following notebook walks through basic EDA and then deploys a machine learning model to correctly determine who survived the Titanic disaster. 

## Requirements
pandas,
matplotlib,
seaborn,
jupyter,
ydataprofiling,

## EDA
EDA for titanic survivor data. Variables that were found to be correlated with surviving were: sex, Pclass, SiBSp, Parch, in that order. A model was then created, trained and ran. The model was able to predict the survival of the test data set with 100% accuracy when comapred to the titanic manifest. 

![EDA](image.png)
![Train](train.png)

Report from ydataprofiling tool is [ydata profile report](report.html)

## Model 
Random Forest Classfier: n_estimators = 100, max depth = 5, random_state = 1

for results see: model_output_test.csv



![Output](output.png)





