# Phishing
Phishing ML
I have performed the following steps with Pandas, Numpy, Matplot lib, sklearn
Read the file and displayed its columns.
Calculated basic statistics of the data (count, mean, std, etc), did exploratory analysis and described my observations.
Resampled the imbalanced dataset by oversampling the positive cases-SMOTe.
Selected columns that will probably be important to predict Phishing.
Created training and testing sets (using 70% of the data for the training and reminder for testing) Built 9 different machine learning models to predict malicious/legitamate: 
Logistic Regression - 92.56% Accuracy
MLP Classification - 95.98% Accuracy
Random Forest Classification - 95.39% Accuracy
Decision Tree Classification - 96.66% Accuracy
Gradient Boosting Classification - 94.46% Accuracy
Hyperparameter tuned the RandomForestClassification - 95.77% and GradientBoostingClassification - 95.21%.
Evaluated each model (f1 score, Accuracy, Precision ,Recall and Confusion Matrix) and plotted a graph for the false positive rate and true positive rate for each model.
Ensembled the four best models using Stacking technique to further increase the accuracy of the model and achieved an accuracy score of 96.17%
Concluded that Ensembling all the four most important models, with DT Classification leading the way, has resulted in a very high accuracy score.
