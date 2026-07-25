# Credit-Fraud-Detection-Corrected
OVERVIEW:
This project focuses on detecting frudulent credit card transaction using machine learning. since fraudulent transactins are very rare compared to legitimate ones, the dataset is highly imblanced. to adres this, SMOTE (Synthentic Minority Over-Scalling Technique) was used to balanced the traing data before building the models.

Three diffrent machine learnig models wher trained nad evaluated: Logistics Regression, Radom Forest and XGBoost. Theor performance was compared using evaluation metrics such as pression, recall and f1-score to dtermine the most sutable model for fraud detection.

PROJECT OBJECTIVE:
The goal of this project is buildind a machine leartning modelthat can accurately identiofy fraudulent transactions while redusing false alarms the projrct aslo campare multiple classification algorithims to determine which performs best on an imbalanced dataset.

DATASET:
The dataset conatims credit card transactions records labbel as either:
0-Legitamte transactions
1-frudulent transaction
Because fraud caseses make onkly small portion of the dataset, balancing the data was an important step before training tyhe model 

TECHNOLOGY USED
Python
Pandas
NUmpy
Matplotlib
Scikit-learn
Imbalacd learn (SMOTE)
XGBoost

WORKFLOW:
Loaded and explored the dataset.
Checked fir missing values and understood the data structure.
Performnce exploratory datA analysis.
Split the dataset into training and testing set.
Appply SMOTE tyo balance tye traing data.
Trained three machine learning models: Logistics Rregression, Random Forest, XGBoost 
Evaluated each model using: Accuracy, Precission, Recall, F1-score, Confussion matrix, ROC Curve and AUC Score
Compared the result of the selected best performing model

RESULT:
The three models produced difficult result when evalutated on the dataset

Logistic Resgression archive high recall but had a low f1-score beacuse it produced many false positvie
XGBoost better overal but did not out pr=erform Random Forest
Random Forest archived the best balance betwen precission and recall, resulting the highest f1-score amog the three models.
Based on this three result, Random FOrest was selected as the final model for this project.

CONCLUSION:
This project demoostrates how machine learing can be used to detect fraudlent credit card transactions. Handling class imbalance with SMOTE significantly improved model performance, and comparing mukltiple algorithims made it possible to selct the most possible to select the most effective model. Random Forest provided the strobgest overall performance and was choosen as the final model. 

FUTURE IMPROVEMENT:
True model hyperparameters to improve performance
Experiment wioth addition ensemble models.
Deploy the model as aweb aplication
Test the model on a newer trasaction data.

Author
EXCELLENT CHUKWU
Mchine Learning Egineer
