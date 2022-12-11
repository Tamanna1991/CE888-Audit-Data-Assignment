# Audit-Risk-Classification
This project is CE888 Reassessment Winter 2022 Assignment

The goal of this project building a classification model that can predict the fraudulent firm on the basis the present and historical risk factors. 

Link: https://archive.ics.uci.edu/ml/datasets/Audit+Data

The code of this project is collabed in one jupyter notebook, where it consits of different functions to perform a particular functionality.
1. Feature Selection: Find correlated features, and remove multi collinear features from the data set.
2. Modelling: StratifiedKfold function, Evaluation function(accuracy, confusion matrix, precision etc.), finetune_prediction(Hyper parameter tuning, training with best parameters, and evaluation on train and test predictions). 

get_results function: This is a menu driven function which uses the function made in Modelling part and create result according to the chosen choice.
