# FMT
The objective of the Feature Selection and Model Tuning project is to optimize predictive model performance by selecting the most relevant features and fine-tuning model parameters. Utilizing techniques such as PCA and various hyperparameter optimization methods to  reduce overfitting, and improve generalization.


![image](https://github.com/user-attachments/assets/8dfa4c2f-b066-4a5a-91d4-f40d44fd66e5)


## Project Features
- Treating missing values and unexpected values with a suitable approach.
- Treatment of outliers.
- Understanding correlation between features and removing the mulaticollinear features
- Applying Feature redution techniques such as Principle Component Analysis(PCA).
- Balancing techniques(SMOTE).
- EDA and Evaluation metrics.

## Dataset

- Signal-dataset


https://www.kaggle.com/code/saurabhbagchi/fmst-semiconductor-manufacturing-project/input



## Tools and Techniques

- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- LogisiticRegression, SVM
- Bagging, boosting
- PCA, SMOTE, CorrelationMatrix and Cross_Validation Techniques.
## Analysis


### SemiConductor Pass/Fail Prediction.







- Comparing with all the models, Base Logistic Regression and tuned Logistic model using different c values are giving good recall, precision, f1_score and AUC_score.
- Accuracy for training set is 97% and testing set is 84.7%.
- According to the Recall_score KNN model is performing good but accuracies are very low.
- So, Logistic Regression model is giving good performance comparing with all other models we have build on the data.








