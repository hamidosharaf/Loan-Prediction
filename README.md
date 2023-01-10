# Loan-Prediction
Hello there , it's my firts project of my Data Science internship at CodeClause.
The main task of the project is to build a machine learning model which is concerned of predicting whether or not a loan will get approved.
After doing some search for :
  * How does this industry work ?
  * What are the challenges it faces ?
  * What are the straregies used ?
i got a good understanding og the problem .
Now , it's time to get started to work on the problem , then i have used a dataset that is provided on kaggle datasets *"Dataset link attached below !"* and started to do some analysis and get some insights from these rare data , After analysing the dataset then i started to clean it and do some transformations to make it ready to be fed to machine learning model that is concerned to do the task .
*it's important to mention that There is an impalance in the column Loan_Status which is the target column of the dataset with ratio 3:1*
After data preprocessing i have decided to train various types of machine learning models which are :
  * LogisticRegression model.
  * SVC model.
  * KNeighborsClassifier model.
  * DecisionTreeClassifier model.
  * RandomForestClassifier model.
After training the models they performed somehow poorly cause of impalance in the dataset target , so that i tried to solve this problem by using a resampler , the next step after resampling is to retrain the five models with the new dataset and that what i have done .
The best best model of these five models was the **RandomForestClassifier** , so that i fine tunned it's parameters using RandomizedSearchCV to find the best parameters and retrained it with the best parameters.
the resulted model scored  **92% accuracy** with **F1 Score 0.93** which is satisfying .




    
## Attachmnets 
  * Notebook of the project. 
  * A copy of the trained model.

## Languages 
  * Python

## Acknowledgements

 - [Notebook link](https://www.kaggle.com/hamidosharaf/loan-prediction/)
 - [Dataset link ](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

